# PorcoBot
This little guy let you know if you should leave work early (or not). 

## Requirements

+ [`cloudscraper`](https://pypi.org/project/cloudscraper/); The website we're crawling denies any request from... `requests`, this package circumvents it.
+ [`BeautifulSoup`](https://pypi.org/project/beautifulsoup4/) for the actual scraping.

### Services/timers files

This is a plus for - at least mine - [Arch Linux](https://archlinux.org/).  
PorcoBot itself will output to STDOUT, these systemd files will notify you using your notification daemon (I use [Dunst](https://dunst-project.org/)).

## Usage

1. Clone this repository
2. Install the requirements (**#TODO** `requirements.txt`)
3. Make `porcobot` executable (`chmod` it)
4. (Optional) Create an alias on your `.bashrc` / `.zshrc`, whatever your shell use it

## More to come

PorcoBot is only aware of football matches so far. The idea is to make it notify about other events at Allianz Park (i.e shows).
