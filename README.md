# Apache-Log-Spam-Analyzer
See read me file for description
The College uses Google's Site Search Service, also known as Google Custom Search Engine, as part of how it delivers search results on its own website.
Google only allows for 10000 total hits every day.  These are not unique hits, so if someone searches 10000 times for the word "the" we will run out.
While the College does cache search results, these garbage results are often "just unique enough," that is, they might have one letter or number changed, to run up that count.
We have run out of searches because of this.
The objective of this project is to gain an understanding of just how serious this issue is. We are going to analyze a section of the Apache httpd log file to see just how long it will take to bring down the search if the invalid results are not filtered.
This file is stored at https://appserv3.montgomerycollege.edu/cmsc-206/sample_www_error_log.txt
