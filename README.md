# Unix Comamnd Helper List
	
### Find in Unix file
find . -type f -name “*.*” -exec grep -il “YOUR TEXT” {} \;

### Count number of files in unix directory
find .//. ! -name . -print | grep -c //

