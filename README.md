# Sphinx Search Releases Mirror

This repository is for the solo purpose of making a mirror for SphinxSearch releases, as they don't provide us with a simple CDN for downloading their releases and their servers don't have high bandwidth available for downloads.

This simply scraps their website with Github actions on a cron basis and copy the files into Github Releases.

The SphinxSearch license for versions 2.x is the plain old GPL, but their 3.x versions is (quoting their own homepage):

```
3.0 and up sources are currently only available under a delayed FOSS or commercial licenses for several reasons;
going back to regular plain old GPL is planned but timing is moot; so email us if you require the sources immediately.
```

You can see this here: http://sphinxsearch.com/downloads/#git
