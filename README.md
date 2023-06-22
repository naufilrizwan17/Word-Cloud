# Word-Cloud
This project dives deep into the complex Python functions and operations regarding the formation of word cloud. 
As you might be aware about the libraries I have imported:
  1) WordCloud: https://pypi.org/project/wordcloud/
  2) Matplotlib: https://matplotlib.org/stable/index.html
  3) Pandas: https://pandas.pydata.org/
  4) stopwords: https://www.geeksforgeeks.org/removing-stop-words-nltk-python/
All of these websites comprehensively describe each and every useful library. WordCloud can be pretty helpful as it is the best way to visualize text data in different fonds using Python. Similarly, matploltlib can be used to construct virtually anything from line graphs to bar graphs, arrays, and even 3d shapes. At the same time, pandas is very helpful for manipulating all sorts of different data values and help in dealing with them.
Then after importing all these libraries, I opened a random .txt file which can easily be found online and read every line of its contents.
Stopwords are those English words that are of no value i.e they do not change the meaning of the sentence if removed.
![stopwords](https://github.com/naufilrizwan17/Word-Cloud/assets/108338824/c46ddf28-31c6-484e-ba6b-ea6233e4289b)
After adding some other stopwords into the imported stopwords library, I convert every word into a string and then end then splitting them.
Next every token was converted into a lowercase after which I added the required info for the wordcloud like height, background color etc.
This generated the wordcloud so to give it the final image we had to dispay it by giving it figsize etc and then show ing it.
