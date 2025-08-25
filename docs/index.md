#bloomberg-fec 1.0.0

##About
This app allows for importing and searching expenditures, independent expenditures and contributions from electronic FEC filings. It was originally forked from a NYT [project](https://github.com/newsdev/nyt-fec) and relies on the NYT's [fec2json](https://github.com/newsdev/fec2json) library.

**Why not just use the FEC website?**
The FEC website has been substantially improved, but it still lacks several main features.

- It takes several days for itemizations to be processed, so it is impossible to search transactions right away
- There are some search fields that do not exist in the FEC bulk data, such as street addresses
- We want to be able to do more with independent expenditure summing and categorizing
- We want to be able to add additional data, such as our own donor ids

If you don't really need to deploy and maintain your own standalone campaign finance infrastructure, you can use tools developed by the FEC including their [site](https://www.fec.gov/data/), their [API](https://api.open.fec.gov/developers/) or their [bulk data](https://www.fec.gov/data/browse-data/?tab=bulk-data). Or use ProPublica's [site](https://projects.propublica.org/itemizer/) or [API](https://www.propublica.org/datastore/api/campaign-finance-api).
