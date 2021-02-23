# Instagram Followers Scraper

## Overview
This is python script to scrape instagram followers.

## Requirement
Python 3.6+

## Installation

### Download

```
$ git clone https://github.com/Eagle19243/instagram-followers-scraper.git
```

### Install chromedriver

```
$ wget https://chromedriver.storage.googleapis.com/2.41/chromedriver_linux64.zip
$ unzip chromedriver_linux64.zip
$ sudo mv chromedriver /usr/bin/chromedriver
$ sudo chown root:root /usr/bin/chromedriver
$ sudo chmod +x /usr/bin/chromedriver
```

### Virtual Environment
Create and populate development virtualenv.

```
$ virtualenv ~/venv/instagram-followers-scraper
$ . ~/venv/instagram-followers-scraper/bin/activate
$ pip install -r requirements.txt
```

## Run

```
$ python script.py

Enter your instagram username: xxx
Enter your instagram password: xxx
Enter an instagram account's username to scrape it's followers: xxx
```
