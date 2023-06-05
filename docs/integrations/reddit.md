# Reddit

>[Reddit](www.reddit.com) is an American social news aggregation, content rating, and discussion website.

## Installation and Setup

First, you need to install a python package.

```bash
pip install praw
```

Make a [Reddit Application](https://www.reddit.com/prefs/apps/) and initialize the loader with with your Reddit API credentials.

## Document Loader

See a [usage example](../modules/indexes/document_loaders/examples/reddit.ipynb).


```python
from langchain.document_loaders import RedditPostsLoader
```