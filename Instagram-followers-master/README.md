## Requirements

Before you can run **InstAnalytics.py**, you will need to install a few Python dependencies.

Note: Python 2.7.9 and later (on the python2 series), and Python 3.4 and later include pip by default, so you may have pip already. Otherwise, you can install [easy_install](https://pythonhosted.org/setuptools/easy_install.html) `sudo apt-get install python-setuptools` to install [pip](https://pypi.python.org/pypi/pip) `sudo easy_install pip`.

- [BeautifulSoup4](https://pypi.python.org/pypi/beautifulsoup4), for parsing html: `pip install BeautifulSoup4`
- [Selenium](http://www.seleniumhq.org/), for browser automation: `pip install Selenium`


## Configuration

Before you run **InstAnalytics.py**, edit the `users = ['yotta_life']` list to add as much as you want public Instagram accounts. It's that simple!

## JSON output example

```JSON

[
    {
        "username": "yotta_life", 
        "date": "2016-04-21", 
        "data": {
            "following": 231, 
            "followers": 649000, 
            "pLikesT": 2029474, 
            "posts": 608, 
            "photos": [
                {
                    "pId": "BEZLlc8sU_v", 
                    "pLikes": 4486, 
                    "pComments": 205
                }, 
                ...
                {
                    "pId": "uuhChFMU92", 
                    "pLikes": 282, 
                    "pComments": 19
                }
            ]
        }
    }
]
```
