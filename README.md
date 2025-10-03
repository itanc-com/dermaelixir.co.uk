# dermaelixir.co.uk
dermaelixir.co.uk website



## RUN the website

```
hugo server

```

Includes content marked as draf & future-dated content.
```
hugo server -D -F

```

Run on a custom port (default is 1313)
```
hugo server --port 1314
```

Rebuild all the content on every change if disabled fast render
```
hugo server --disableFastRender
```

Disable Cache
```
hugo server --noCache
```


Ensure you're always seeing the latest changes without any caching interference
```
hugo server --noCache --disableFastRender 
```

Ignore any cached data and clean public & rebuild all the content 
```
hugo server --ignoreCache --disableFastRender  --cleanDestinationDir
```

Delete Cache
```
rm -rf .hugo_cache
```
