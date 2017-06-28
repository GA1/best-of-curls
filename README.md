# List of handy curls in all flavors:

simple get:
```
curl www.knguyenvan.com
```

time a get curl:
```
time curl www.knguyenvan.com
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
curl -H "Content-type: application/json" -X POST -d '{"some_param":"some_value"}' www.knguyenvan.com
```