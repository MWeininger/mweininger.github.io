# File and Directory Overview

- _data/navigation.yml: Relevant for navigation bar at the top of the website, and indicates which page-source is found where
- _pages: contains an md file for every page of the website. Currently only news.
- _posts: Not relevant
- _site: html that is actually displayed, created automatically by jekyll from the sources
- assets: Put pictures and pdfs here.
- _config.yml: Side bar and some page info is in here.
- index.md: Landing page, doubles as about. Explicitly contains the info about side bar in the header
- rest: don't touch.

# How to Push New Changes

1. Modify site content (likely _pages/news.md, index.md, or _config.yml)
2. Push
There is no need to locally build.