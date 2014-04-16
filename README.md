

Setup
=================
1. git clone https://github.com/cfreder2/twitter_sentiment

2. Download and run pycurl-7.19.3.1.win-amd64-py2.7.exe for windows.  On mac run: pip install pycurl
     - http://www.lfd.uci.edu/~gohlke/pythonlibs/#pycurl

3. pip install oauth2

4. pip install certifi

5. pip install unirest


There are two files
--------------------
*twitter_stream.py* - polls the twitter stream for a given "track".  by default it's find tweets that mention dogs or cats.   There is a flag you can flip to write to file in addition to printing to the screen.

*add_sentiment.py* - calls a sentiment anlysis api and appends the sentiment score to a new csv file.

Compatable with python 2.7.X
