---
title: Scraping Congressional Financial Disclosure Forms
excerpt_separator: "<!--more-->"
---

In a perfect world, it would be easy to where our congresspeople put their money. That way it would be easy to see whether an elected official was charged with regulating an industry where their own bank account could be affected.

But we do not live in a perfect world! Representatives and senators, as well as anyone running for these offices, submit annual Financial Disclosure Forms, as well as supplimentary disclosures for large trades and a few other events. And while the forms are publicly available, the data is tied up in unindexed PDF's (for the House) and unindexed HTML (for the Senate). The format of these forms changed from year to year, and many of the forms were filled out by hand. (In 2019!)

[Sludge](https://readsludge.com/) is a non-partisan site dedicated to investigating money in politics. They wanted the Financial Disclosure information, but they didn't want to take the time to go over every form manually. So they asked me to scrape, clean, and parse the forms into something manageable. [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/), [Selenium](https://selenium-python.readthedocs.io/), [PDFPlumber](https://github.com/jsvine/pdfplumber) and [PDFQuery](https://github.com/jcushman/pdfquery) made it possible.

### Selected Articles

My work allowed Sludge reporters to run and bolster dozens of stories about congressional conflicts of interest. Links to a few are below.

- [Revealed: how US senators invest in firms they are supposed to regulate](https://www.theguardian.com/us-news/2019/sep/19/us-senators-investments-conflict-of-interest)

- [Reps Who Will Question Zuckerberg Own Stock In Facebook](https://readsludge.com/2019/10/22/reps-who-will-question-zuckerberg-own-stock-in-facebook/)

- [Leader of Centrist Climate Caucus Has Millions Invested in Oil and Gas Companies](https://readsludge.com/2019/06/20/leader-of-centrist-climate-caucus-has-millions-invested-in-oil-and-gas-companies/)
- [Presidential Candidate Who Attacked Medicare for All is Invested in Health Care Companies](https://readsludge.com/2019/06/04/presidential-candidate-who-attacked-medicare-for-all-is-invested-in-health-care-companies/)
- [Reps Questioning Megabank CEOs Own Stock in Their Companies](https://readsludge.com/2019/04/10/reps-questioning-megabank-ceos-own-stock-in-their-companies/)