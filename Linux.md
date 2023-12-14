# LINUX ASSIGNMENT   


 ## 1.How to make a directory
**mkdir** - The mkdir command is used to create a new directory (folder) in a file system. You can use the mkdir command in a terminal or command prompt on various operating systems.

  **Syntax:  mkdir directory_name**
  **mkdir tusha**     
  **Output-**     
 tusha@tusha:~$ mkdir tusha
 tusha@tusha:~$ ls
 bak  	Desktop  	Downloads                 	ldap1.sh        	ldap.sh   organisation.ldif   rm 	Templates            	Videos
 Coding   Dictionary   farmer_suicide_in_India.md	LDAP_Document.md	ldif  	Pictures        	run	tusha
 config   Document 	farmer_suicide_in_India.pdf  'Ldap explanation'   logs  	Public          	snap   tusha.txt
 db   	Documents	group.ldif                	LDAP.md         	Music 	PycharmProjects 	ssca  'Untitled Document 111'
tusha@tusha:~$



  
 ->  mkdir : It is used to create a directory.
       mk : make ,     dir - directory
 ->  tusha : it is the name of folder.
 ->  ls: This is the command to list files and directories.

Remove a directory
rmdir -The rmdir command is used to remove empty directories.
          Syntax:  rmdir directory_name
          rmdir tusha         
          Output- 
           tusha@tusha:~$ mkdir tusha
tusha@tusha:~$ ls
 bak      Desktop      farmer_suicide_in_India.md    LDAP_Document.md    ldif                Pictures          run         test.txt
 Coding   Dictionary   farmer_suicide_in_India.pdf  'Ldap explanation'   logs                Public            snap        tusha
 config   Documents    group.ldif                    LDAP.md             Music               PycharmProjects   ssca       'Untitled Document 111'
 db       Downloads    ldap1.sh                      ldap.sh             organisation.ldif   rm                Templates   Videos
tusha@tusha:~$ rmdir tusha
tusha@tusha:~$ ls
 bak      Desktop      farmer_suicide_in_India.md    LDAP_Document.md    ldif                Pictures          run         test.txt
 Coding   Dictionary   farmer_suicide_in_India.pdf  'Ldap explanation'   logs                Public            snap       'Untitled Document 111'
 config   Documents    group.ldif                    LDAP.md             Music               PycharmProjects   ssca        Videos
 db       Downloads    ldap1.sh                      ldap.sh             organisation.ldif   rm                Templates
tusha@tusha:~$ 


           ->  rmdir : It is used to remove an empty directory.
                 rm : remove   , dir - directory
           ->    tusha : it is the name of folder.

 
           rmdir can only remove directories that are empty. If a directory contains any files or subdirectories, the command will not work, and you'll need to use the rm command with the -r (recursive) option to remove non-empty directories.
Syntax-
rm -r my_directory
rm -r tusha
Output-
tusha@tusha:~/tusha$ touch file1.txt file2.txt file3.txt
tusha@tusha:~/tusha$ cd ..
tusha@tusha:~$ rm -r tusha
tusha@tusha:~$ ls
 bak  	Desktop  	Downloads                 	ldap1.sh        	ldap.sh   organisation.ldif   rm 	Templates
 Coding   Dictionary   farmer_suicide_in_India.md	LDAP_Document.md	ldif  	Pictures        	run   'Untitled Document 111'
 config   Document 	farmer_suicide_in_India.pdf  'Ldap explanation'   logs  	Public          	snap   Videos
 db   	Documents	group.ldif                	LDAP.md         	Music 	PycharmProjects 	ssca
tusha@tusha:~$

             mkdir : It is used to create a directory.
             tusha : it is the name of folder.
             cd :  change directory.
             test:  create directory inside the tusha directory.
             cd .. :The cd .. command is used to change the current working directory to its parent directory. The .. represents the parent directory, so executing cd .. moves you up one level in the directory structure.
             
Make a copy of a file
cp: The cp command is used to copy files or directories.
Syntax:cp source(filename/directory name) destination
cp test.txt Downloads/
Output-
 tusha@tusha:~$ touch test.txt
tusha@tusha:~$ ls
 bak  	Desktop  	Downloads                 	ldap1.sh        	ldap.sh   organisation.ldif   rm 	Templates
 Coding   Dictionary   farmer_suicide_in_India.md	LDAP_Document.md	ldif  	Pictures        	run	test.txt
 config   Document 	farmer_suicide_in_India.pdf  'Ldap explanation'   logs  	Public          	snap  'Untitled Document 111'
 db   	Documents	group.ldif                	LDAP.md         	Music 	PycharmProjects 	ssca   Videos
tusha@tusha:~$ cp test.txt Downloads/
tusha@tusha:~$ cd Downloads/
tusha@tusha:~/Downloads$ ls
 ApacheDirectoryStudio      	google-chrome-stable_current_amd64-1.deb   image.png                   	'Screenshot from 2023-11-15 16-14-21.png'
 apache-tomcat-10.1.16.tar.gz   google-chrome-stable_current_amd64-2.deb   node-v20.10.0-linux-x64.tar.xz   test.txt
 BCD                        	google-chrome-stable_current_amd64.deb 	README.pdf
tusha@tusha:~/Downloads$ cd ..
tusha@tusha:~$ ls
 bak  	Desktop  	Downloads                 	ldap1.sh        	ldap.sh   organisation.ldif   rm 	Templates
 Coding   Dictionary   farmer_suicide_in_India.md	LDAP_Document.md	ldif  	Pictures        	run	test.txt
 config   Document 	farmer_suicide_in_India.pdf  'Ldap explanation'   logs  	Public          	snap  'Untitled Document 111'
 db   	Documents	group.ldif                	LDAP.md         	Music 	PycharmProjects 	ssca   Videos
tusha@tusha:~$


           -> source: The file or directory you want to copy.
->destination: The location where you want to copy the source.
-> cp: it is used to copy commands.
->test.txt: it is a filename.
Move or rename a file
mv:To move or rename a file in a Linux operating system, you can use the mv command. The mv command is versatile and can be used to both move and rename files.
Syntax: mv filename destination
mv test Downloads/
Output-
tusha@tusha:~$ ls
 bak  	Desktop  	Downloads                 	ldap1.sh        	ldap.sh   organisation.ldif   rm 	Templates            	Videos
 Coding   Dictionary   farmer_suicide_in_India.md	LDAP_Document.md	ldif  	Pictures        	run	test
 config   Document 	farmer_suicide_in_India.pdf  'Ldap explanation'   logs  	Public          	snap   tusha
 db   	Documents	group.ldif                	LDAP.md         	Music 	PycharmProjects 	ssca  'Untitled Document 111'
tusha@tusha:~$ mv test Downloads/
tusha@tusha:~$ ls
 bak  	Desktop  	Downloads                 	ldap1.sh        	ldap.sh   organisation.ldif   rm 	Templates
 Coding   Dictionary   farmer_suicide_in_India.md	LDAP_Document.md	ldif  	Pictures        	run	tusha
 config   Document 	farmer_suicide_in_India.pdf  'Ldap explanation'   logs  	Public          	snap  'Untitled Document 111'
 db   	Documents	group.ldif                	LDAP.md         	Music 	PycharmProjects 	ssca   Videos
tusha@tusha:~$ cd Downloads/
tusha@tusha:~/Downloads$ ls
 ApacheDirectoryStudio      	google-chrome-stable_current_amd64-1.deb   image.png                   	'Screenshot from 2023-11-15 16-14-21.png'
 apache-tomcat-10.1.16.tar.gz   google-chrome-stable_current_amd64-2.deb   node-v20.10.0-linux-x64.tar.xz   test
 BCD                        	google-chrome-stable_current_amd64.deb 	README.pdf
tusha@tusha:~/Downloads$

-> mv: it is used to move commands.
->test: it is a filename.
->Downloads/: it is a destination

Rename a file:
Syntax- mv oldfile.txt newfile.txt
mv tusha.txt test.txt
Output-
tusha@tusha:~$ touch tusha.txt
tusha@tusha:~$ ls
 bak  	Desktop  	Downloads                 	ldap1.sh        	ldap.sh   organisation.ldif   rm 	Templates
 Coding   Dictionary   farmer_suicide_in_India.md	LDAP_Document.md	ldif  	Pictures        	run	tusha.txt
 config   Document 	farmer_suicide_in_India.pdf  'Ldap explanation'   logs  	Public          	snap  'Untitled Document 111'
 db   	Documents	group.ldif                	LDAP.md         	Music 	PycharmProjects 	ssca   Videos
tusha@tusha:~$ mv tusha.txt test.txt
tusha@tusha:~$ ls
 bak  	Desktop  	Downloads                 	ldap1.sh        	ldap.sh   organisation.ldif   rm 	Templates
 Coding   Dictionary   farmer_suicide_in_India.md	LDAP_Document.md	ldif  	Pictures        	run	test.txt
 config   Document 	farmer_suicide_in_India.pdf  'Ldap explanation'   logs  	Public          	snap  'Untitled Document 111'
 db   	Documents	group.ldif                	LDAP.md         	Music 	PycharmProjects 	ssca   Videos
tusha@tusha:~$

-> mv:In this place we have used this command to remove filename.
->tusha.txt: it is an old filename.
->test.txt: it is an New filename.


Create an empty file
         touch :-The touch command is used to create empty files and update   access and modification timestamps on existing files. You can use the touch command in a terminal or command prompt.
 Syntax: touch filename
 touch tusha.txt
 Output-
tusha@tusha:~$ touch tusha.txt
tusha@tusha:~$ ls
 bak  	Desktop  	Downloads                 	ldap1.sh        	ldap.sh   organisation.ldif   rm 	Templates
 Coding   Dictionary   farmer_suicide_in_India.md	LDAP_Document.md	ldif  	Pictures        	run	tusha.txt
config   Document 	farmer_suicide_in_India.pdf  'Ldap explanation'   logs Public          	snap  'Untitled Document 111'
db   	Documents	group.ldif                	LDAP.md         	Music 	PycharmProjects 	ssca   Videos
tusha@tusha:~$


 ->touch:it is used to create an empty file command.
-> tusha.txt:It is a filename.

    
Remove multiple files with a single command
 rm-To remove multiple files with a single command in a Unix-like operating system.
Syntax: rm filename
rm file1.txt file2.txt file3.txt

-> rm: it is a remove command.
->file1.txt file2.txt file3.txt: it is a file name.
   
Remove content from the folder without removing folder
rm -r:To remove the contents of a folder without removing the folder itself, you can use the rm command with the -r (recursive) option.
Syntax: rm -r filename
rm -r file1.txt file2.txt file3.txt
Output-
tusha@tusha:~$ mkdir tusha
tusha@tusha:~$ cd tusha/
tusha@tusha:~/tusha$ touch file1.txt file2.txt file3.txt
tusha@tusha:~/tusha$ ls
file1.txt  file2.txt  file3.txt
tusha@tusha:~/tusha$ rm -r file1.txt file2.txt file3.txt
tusha@tusha:~/tusha$ ls
tusha@tusha:~/tusha$


-> rm: it is a remove command.
->file1.txt file2.txt file3.txt: it is a file name.
->-r : it is a recursive option.

Create multiple folder(a-z) with a single command
         mkdir-To create multiple folders (a-z) using a single command, you can use a loop in a shell or command prompt.
      Syntax: mkdir {a..z}
     This command uses brace expansion to create folders named from "a" to   "z". Each letter is separated by two dots. After running this command, you should have folders named a, b, c, ..., z in your current directory.


 -> mkdir : It is used to create a directory.
       mk : make ,     dir - directory
->{a..z} :it is the name of folder.
