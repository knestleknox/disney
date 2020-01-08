# disney
Disney fraudulent reviews analysis

I miscalculated how much time I'd have (especially promising to do this new years break) to do this.
I wasn't going to prioritize validating myself to a bunch of people on the internet over spending time with my family and whatnot so to be honest
I didn't get to this analysis at all until today (Tue 7.).

I'll be going more in depth when I have time over the coming weeks if anyone wants to keep track but I've uploaded about 1-2 hours of work.
So that includes scraping the data from google docs and some basic EDA.

Some things I want to do:

* Compare name frequencies to that of an expected american population (to check for repeated names as the OP of the video claimed).
* Get an average cosine similarity for each review group (we would expect this average to be higher for 5 star reviews assuming they're fradulent).
* Run some stats tests against basic features of 5-star reviews and other-stars. To, for instance, statistically show that the word counts in both groups are likely from differnt distributions (and thus supporting a fraud claim).
* Do some time-series analysis (if I can get access to time data more granular than the day). If OP suspects that Disney is publishing reviews to keep a minimum score of 86%, then we should be able to see some evidence of that in the time series data.
* And many more...

Anyway, so far, I haven't seen *damning* evidence of fraud. But there are definetly some anomalies in the review data.
For instance, I have uncovered that 5-star reviews *do* use less unique language. However, we can't rule out the possibility
that people who are satisfied are succinct and people who are not (1,2,3-star reviewers) are more verbose about their gripes. 

I'll pick this back up over the next couple of days so stay tuned.
