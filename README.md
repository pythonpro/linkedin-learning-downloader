# LinkedIn Learning Downloader

#### Based on [mclmza's linkedin-learning-downloader](https://github.com/mclmza/linkedin-learning-downloader)

Asynchronous scraping tool to fetch LinkedIn-learning's courses videos.

Dependencies:
- Python 3.6
- aiohttp
- lxml

#### Info

Please use this script for your own purposes.

This script was written for educational usage only.

Make sure your LinkedIn account is **NOT** protected with 2FA

#### Usage
> pip3 install -r requirements.txt

Edit config.py file (username, password and courses slugs)  

```Course's slug can be obtained using its url
e.g:
COURSE URL: https://www.linkedin.com/learning/python-advanced-design-pattern
->
SLUG: python-advanced-design-pattern
```

> python3 linkedin_learning.py

#### TODO

 - Add Description
 - Use argparser
 - Fetch courses from bookmarks
