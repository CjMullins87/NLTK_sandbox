
# NLTK Work

Just using NLTK to review about 30+ data science job descriptions from LinkedIn that are local to me. 

End goal is to find insight into what's useful for optimizing my personal resume.

### Progress so far:  Frequency Distribution

Successfully imported `.txt` file of accumulated job postings. Split text by word, then used NLTK's `stopwords` to clean up English plumbing. No stemming/tokenization yet beyond breaking down to initial words. From there, was able to clean up text a bit more by removing non-informative words such as "*" and the break symbol "--------".

Building a frequency distribution from that data so far looks like this:

![Frequency Distribution](/images/freq_dist.png)
