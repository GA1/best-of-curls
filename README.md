# List of handy curls in all flavors:

simple get:
```
curl https://www.knguyenvan.com
```

time a get curl:
```
time https://curl www.knguyenvan.com
```

get with details (verbose)
```
curl -v https://www.knguyenvan.com
```

get with headers only 
```
curl -I https://www.knguyenvan.com
```


get with headers only 2
```
curl -sSL -D - www.knguyenvan.org -o /dev/null
```

post with body
```
curl -H "Content-type: application/json" -X POST -d '{"some_param":"some_value"}' https://www.knguyenvan.com
```

