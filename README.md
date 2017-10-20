Scrape Cron
===========

Use Travis CI cron to trigger scrape jobs periodically.

![Trigger status](https://travis-ci.org/OpenUpSA/scrape-cron.svg?branch=master)

Updating environment variables
------------------------------

API Key

```
travis encrypt SCRAPINGHUB_API_KEY="the key" --add
```

Spider list

```
travis encrypt SCRAPINGHUB_SPIDER1="gpw" --add
```

And it's probably good to delete the old ones from .travis.yml