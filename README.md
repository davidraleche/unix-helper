# Unix Command Helper List
	
### Find in Unix file
```
find . -type f -name "*.*" -exec grep -il "YOUR TEXT" {} \;
```

### Count number of files in unix directory
```
find .//. ! -name . -print | grep -c //
```

### Cat
```
cat file.php
```


### tail
```
tail -n 20 xxx.php
tail -f
```

### Memory space
```
df

du -skh .

```

