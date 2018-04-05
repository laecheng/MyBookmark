# Bookmark Server

 *bookmark server* or URL-shortening service,
MyBookmark is similar to `TinyURL.com` or `goo.gl`, but with no persistent storage.

This server will accept a URL and a short name, check that the URL actually
works (returns an HTTP 200), then store it in a Python dictionary.


# Environment
  - **Python** with version 3.6.4
  - Follow this [guidance](https://www.python.org/about/gettingstarted/) to install Python on your operating system.

# How to Run
  ```
  $ git clone git@github.com:laecheng/MyBookmark.git bookmark
  $ cd bookmark
  $ python BookmarkServer.py
  ```
