# anastasiatan.github.io
Here's some common_used commonds on mac terminal:

--------
1. ls 
	ls 				list all files/folders on current location
    	ls -a 				list all content on current location includes extension filename and hidden files/folder
	ls -l 				list all file/folder details on current location
	ls -t				list the last time modified file and its directory
	ls -alt				the combine of command -a&-t&-l

--------
2. pwd
	pwd				check current location's direcotry

--------
3. cd	
	cd foldername			enter the folder which named foldername
	cd ..				back to previous entered folder

--------
4. mkdir
	mkdir foldername		create a folder named foldername

--------
5. touch 
	touch filename.extension	create a file "filename.extension"

--------
6. cp
	cp index/text.html html/			copy text.html under directory index to directory html
	cp index/text.html index/text2.html html/	copy text.html and text2.html to html folder
	cp index/t*.html html/				copy all t* files to html folder

--------
7. mv
	mv index/text.html html/        		move text.html under directory index to directory html
        mv index/text.html index/text2.html html/       move text.html and text2.html to html folder
        mv index/t*.html html/          		move all t* files to html folder

--------
8. rm 
	rm index.html			delete file index.html	
	rm -r index/			delete all files under index

--------
9. echo 
	echo "aaa"			echo string
	echo "aaa">aaa.txt		create aaa.txt and write words "aaa"

--------
10. cat
	cat aaa.txt			print aaa.txt
	cat aaa.txt>world.txt		world.txt's content will be instead by aaa.txt's content
	cat aaa.txt>>world.txt		world.txt's content will be added in aaa.txt's content


