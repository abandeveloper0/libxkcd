# libxkcd

libxkcd is an API wrapper to fetch, search or download [xkcd](http://www.xkcd.com/) comics (with *partial* support to what-if articles). Written in **Python** *2.7.12*

## Features : 
+ Search comics and what-if articles.
+ Download comics to specific folder.
+ Parse what-if articles' illustrations.

## Sample code : 
```python
>>> import libxkcd.net
>>> random = libxkcd.comic.random_comic()
>>> print random.Title
Apple Jacks
>>> print random.ID
38
>>> libxkcd.net.download_comic(random)
38, Apple Jacks.
True
```

## Dependencies : 
+ [requests](http://docs.python-requests.org/en/master/) module.
+ [Beautiful Soup 4](https://pypi.python.org/pypi/beautifulsoup4).
