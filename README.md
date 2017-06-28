# List of handy curls in all flavors:

simple get:
```
curl www.knguyenvan.com
```

get with details (verbose)
```
curl -v www.knguyenvan.com
```

get with headers only 
```
curl -I www.knguyenvan.com
```

post with body
```
curl -X POST -d '{"some_param":"some_value"}' www.knguyenvan.com
```