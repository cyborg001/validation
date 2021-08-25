build : 
	hugo -D > /dev/null 2>&1

.PHONY: clean
clean :
	rm -rf ./dist/ > /dev/null 2>&1

post : 
	hugo new posts/$(POST_NAME).md 
	echo '---' | \
	echo 'title: "$(POST_TITLE)"' | \
      	echo 'date: 2010-03=26T08:47:11+01:00' | \
	echo 'draft: false' | \
	echo '---' > $(POST_NAME).md > /dev/null 2>&1	
      



