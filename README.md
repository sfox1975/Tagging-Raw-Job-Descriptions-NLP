# Tagging-Raw-Job-Descriptions-NLP
Using natural language processing (NLP) to tag raw job descriptions

## Summary
This project was completed as a Hackerrank.com machine learning contest, sponsored by Indeed.com. The objective was to develop a machine learning algorithm capable of accurately tagging job descriptions with combinations of the following 12 tags:
* part-time-job
* full-time-job
* hourly-wage
* salary
* associate-needed
* bs-degree-needed
* ms-or-phd-needed
* licence-needed
* 1-year-experience-needed
* 2-4-years-experience-needed
* 5-plus-years-experience-needed
* supervising-job

This contest was a first for me on two fronts:
1. first online coding contest entered
2. first time building an NLP model

I really enjoyed participating, and only wish I'd discovered the contest sooner (I found it with less than a day to go). I finished 127th out of 248 entries, based on F1-score. I will aim to do much better on my next contest!

## Other Documents
* data.zip - contains the two raw data files (test.tsv and train.tsv)
* Fox_Stephen_Indeed-HackerRank.ipynb - Python notebook file containing the algorithm code
* Fox_Stephen_Indeed-HackerRank.pdf - Very brief (1 page) report with key highlights about the coding process

## Running the file
The code was developed in the ‘Indeed-HackerRank.ipynb’ Jupiter notebook. To launch the file, make sure a Python package is installed and then type the following from the appropriate directory:

`jupiter notebook Indeed-HackerRank.ipynb`

You will need to have the ‘train.tsv’ and ‘test.tsv’ data files saved in the same working directory as the notebook. They have been uploaded as a zip file.

You can work through the steps in the code by pressing the ‘play’ button. Once the final step executes, a ‘tags.tsv’ file will be written as output. 

One final step is needed before testing the output (I unfortunately ran out of time to automate this step): Open the ‘tags.tsv’ file in a text editor and do a ‘find-and-replace’, searching for all instances of ‘“”’ and replacing them with blanks (‘’). The ‘tags.tsv’ file is then ready for testing against the Indeed / HackerRank.com scoring system.
