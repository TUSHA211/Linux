 **LINUX ASSIGNMENT1**   
<hr>



### 1. How to make a directory

**mkdir -** The mkdir command is used to create a new directory (folder) in a file system. You can use the mkdir command in a terminal or command prompt on various operating systems.

 **Syntax:**  **mkdir directory_name**

 **mkdir tusha**     

 **Output-**     

 tusha\@tusha:\~$ mkdir tusha

 tusha\@tusha:\~$ ls

 bak  Desktop  Downloads                 ldap1.sh        ldap.sh   organisation.ldif   rm Templates            Videos

 Coding   Dictionary   farmer\_suicide\_in\_India.md LDAP\_Document.md ldif  Pictures        run tusha

 config   Document farmer\_suicide\_in\_India.pdf  'Ldap explanation'   logs  Public          snap   tusha.txt

 db   Documents group.ldif                LDAP.md         Music PycharmProjects ssca  'Untitled Document 111'

tusha\@tusha:\~$


  ****![](https://lh7-us.googleusercontent.com/QYCh-AFDwiiUdxQIGSXONd3hU44VlT-cxspYBGXaD5XbIGrkdsG0X5qm1eVaBuH9pRb41RY4OHST5nH82iERamaHKGGjMpY9tl_MjCn_ISPVyd1BzQY2qUcvsrRmxWTj1iTlsf4Qatja_Jr6njk0rXI)****

 **->mkdir :** It is used to create a directory.

 **mk** : make ,     **dir** - directory

 **->  tusha :** it is the name of folder.

 **->  ls:** This is the command to list files and directories.

### 2.Remove a directory

**rmdir-** The rmdir command is used to remove empty directories.

 **Syntax:rmdir directory\_name**

 **rmdir tusha**         

 **Output-** 



![](https://lh7-us.googleusercontent.com/khC8ssS_PaGvy0rvvLwPW_G2njDizRL9V4yXQosz90aenlnOIUrD1min-d7ZlaVd-618xpBW_E3AF8HBHB-xJjeIyFMSMDf5YSIdBe0Ip0BTj1MCPGgzQdFnH_w4c_LFiQEULTpMKvZrgpAfi54wcnU)

 **->rmdir:** It is used to remove an empty directory.

 **rm:** remove   , **dir:** directory

**->tusha :** it is the name of folder.

 **rmdir** can only remove directories that are empty. If a directory contains any files or subdirectories, the command will not work, and you'll need to use the **rm** command with the **-r (recursive)** option to remove non-empty directories.

**Syntax:-rm -r my_directory**

**rm -r tusha**

**Output-**

tusha\@tusha:\~/tusha$ touch file1.txt file2.txt file3.txt

tusha\@tusha:\~/tusha$ cd ..

tusha\@tusha:\~$ rm -r tusha

tusha\@tusha:\~$ ls

 bak  Desktop  Downloads                 ldap1.sh        ldap.sh   organisation.ldif   rm Templates

 Coding   Dictionary   farmer\_suicide\_in\_India.md LDAP\_Document.md ldif  Pictures        run   'Untitled Document 111'

 config   Document farmer\_suicide\_in\_India.pdf  'Ldap explanation'   logs  Public          snap   Videos

 db   Documents group.ldif                LDAP.md         Music PycharmProjects ssca

tusha\@tusha:\~$

![](https://lh7-us.googleusercontent.com/sRA2FFgCKDq38PUpbi7vQeLXWT4_tfQmPMLVK5M2yV3qYmVqCxSxyRaiOmnbAQxhyiNG9UCrEFMM_kWp8zfiC0pHYzrl5bxc4gI0bVMTvZxrS8cfwfZ8wvUW5owSTyCq_FZlOYuhXSwpBbpqFL8CUm0)

  **->mkdir:** It is used to create a directory.

  **->tusha:** it is the name of folder.

  **->cd:** change directory.

  **->test:**  create directory inside the tusha directory.

  **->cd ..** :The **cd ..** command is used to change the current working directory to its parent directory. The **..** represents the parent directory, so executing **cd ..** moves you up one level in the directory structure.

             

 ### 3. Make a copy of a file

**cp:** The **cp** command is used to copy files or directories.

**Syntax**:**cp source(filename/directory name) destination**

**cp test.txt Downloads/**

**Output-**

 tusha\@tusha:\~$ touch test.txt

 tusha\@tusha:\~$ ls

 bak  Desktop  Downloads                 ldap1.sh        ldap.sh   organisation.ldif   rm Templates

 Coding   Dictionary   farmer\_suicide\_in\_India.md LDAP\_Document.md ldif  Pictures        run test.txt

 config   Document farmer\_suicide\_in\_India.pdf  'Ldap explanation'   logs  Public          snap  'Untitled Document 111'

 db   Documents group.ldif                LDAP.md         Music PycharmProjects ssca   Videos

tusha\@tusha:\~$ cp test.txt Downloads/

tusha\@tusha:\~$ cd Downloads/

tusha\@tusha:\~/Downloads$ ls

 ApacheDirectoryStudio      google-chrome-stable\_current\_amd64-1.deb   image.png                   'Screenshot from 2023-11-15 16-14-21.png'

 apache-tomcat-10.1.16.tar.gz   google-chrome-stable\_current\_amd64-2.deb   node-v20.10.0-linux-x64.tar.xz   test.txt

 BCD                        google-chrome-stable\_current\_amd64.deb README.pdf

tusha\@tusha:\~/Downloads$ cd ..

tusha\@tusha:\~$ ls

 bak  Desktop  Downloads                 ldap1.sh        ldap.sh   organisation.ldif   rm Templates

 Coding   Dictionary   farmer\_suicide\_in\_India.md LDAP\_Document.md ldif  Pictures        run test.txt

 config   Document farmer\_suicide\_in\_India.pdf  'Ldap explanation'   logs  Public          snap  'Untitled Document 111'

 db   Documents group.ldif                LDAP.md         Music PycharmProjects ssca   Videos

tusha\@tusha:\~$

![](https://lh7-us.googleusercontent.com/HjNLXJN5mPx2l_E1HKV49JSktYSEqulpopyxwAledv3b17rLT4b2TyJLE4fuPveyeXiEY2i3hxLB1SaDyZyCU_5CMQLSAy9hmb4XWo-_OKbhINxHjnV1MS70Kq3ut_V9-1hjrQNC0Wa072g3_Gq0jNM)

**-> source:** The file or directory you want to copy.

**->destination:** The location where you want to copy the source.

**-> cp**: it is used to copy commands.

**->test.txt:** it is a filename.

### 4. Move or rename a file

**mv:** To move or rename a file in a Linux operating system, you can use the **mv** command. The **mv** command is versatile and can be used to both move and rename files.

**Syntax: mv filename destination**

**mv test Downloads/**

**Output-**

**tusha\@tusha:\~$ ls**

 **bak  ****Desktop  ****Downloads                 ****ldap1.sh        ****ldap.sh   organisation.ldif   rm ****Templates            ****Videos**

 **Coding   Dictionary   farmer\_suicide\_in\_India.md ****LDAP\_Document.md ****ldif  ****Pictures        ****run ****test**

 **config   Document ****farmer\_suicide\_in\_India.pdf  'Ldap explanation'   logs  ****Public          ****snap   tusha**

 **db   ****Documents ****group.ldif                ****LDAP.md         ****Music ****PycharmProjects ****ssca  'Untitled Document 111'**

**tusha\@tusha:\~$ mv test Downloads/**

**tusha\@tusha:\~$ ls**

 **bak  ****Desktop  ****Downloads                 ****ldap1.sh        ****ldap.sh   organisation.ldif   rm ****Templates**

 **Coding   Dictionary   farmer\_suicide\_in\_India.md ****LDAP\_Document.md ****ldif  ****Pictures        ****run ****tusha**

 **config   Document ****farmer\_suicide\_in\_India.pdf  'Ldap explanation'   logs  ****Public          ****snap  'Untitled Document 111'**

 **db   ****Documents ****group.ldif                ****LDAP.md         ****Music ****PycharmProjects ****ssca   Videos**

**tusha\@tusha:\~$ cd Downloads/**

**tusha\@tusha:\~/Downloads$ ls**

 **ApacheDirectoryStudio      ****google-chrome-stable\_current\_amd64-1.deb   image.png                   ****'Screenshot from 2023-11-15 16-14-21.png'**

 **apache-tomcat-10.1.16.tar.gz   google-chrome-stable\_current\_amd64-2.deb   node-v20.10.0-linux-x64.tar.xz   test**

 **BCD                        ****google-chrome-stable\_current\_amd64.deb ****README.pdf**

**tusha\@tusha:\~/Downloads$**

****![](https://lh7-us.googleusercontent.com/BC05R8650KHCmelELE39u5PGXkPb5PkKnYvwt-RKsz8z9yqxULKibljf1Qot7ckDbQa6vsXAgXg-roI8XnBD-tvxrgKSoRY9QIBapnKsQj9s9bwWntsuPvoi53Gs7g3M3L0_Yb4Ws5se_cZksYo-TWU)****

**->mv**: it is used to move commands.

->**test:** it is a filename.

->**Downloads/:** it is a destination

 #### Rename a file:

**Syntax- mv oldfile.txt newfile.txt**

**mv tusha.txt test.txt**

**Output-**

tusha\@tusha:\~$ touch tusha.txt

tusha\@tusha:\~$ ls

 bak  Desktop  Downloads                 ldap1.sh        ldap.sh   organisation.ldif   rm Templates

 Coding   Dictionary   farmer\_suicide\_in\_India.md LDAP\_Document.md ldif  Pictures        run tusha.txt

 config   Document farmer\_suicide\_in\_India.pdf  'Ldap explanation'   logs  Public          snap  'Untitled Document 111'

 db   Documents group.ldif                LDAP.md         Music PycharmProjects ssca   Videos

tusha\@tusha:\~$ mv tusha.txt test.txt

tusha\@tusha:\~$ ls

 bak  Desktop  Downloads                 ldap1.sh        ldap.sh   organisation.ldif   rm Templates

 Coding   Dictionary   farmer\_suicide\_in\_India.md LDAP\_Document.md ldif  Pictures        run test.txt

 config   Document farmer\_suicide\_in\_India.pdf  'Ldap explanation'   logs  Public          snap  'Untitled Document 111'

 db   Documents group.ldif                LDAP.md         Music PycharmProjects ssca   Videos

tusha\@tusha:\~$

****![](https://lh7-us.googleusercontent.com/9BTrcJ66MNJtDkJHmImVRBfMA4ielcprkKPvG4dlRAEIKr0dRHuk392mJjSmaQ4h-oAp-4TLwhhi9-SrsDmCuN9XUhxeJmGAX9QXGsgqKQ-VEojKIroZPCEiNxmzIfEOIg-uV36BVGzDOBYzRIuUPkQ)****

**-> mv**:In this place we have used this command to remove filename.

->**tusha.txt:** it is an old filename.

->**test.txt:** it is an New filename.



 ### 5. Create an empty file

 **touch:** The touch command is used to create empty files and update   access and modification timestamps on existing files. You can use the touch command in a terminal or command prompt.

 **Syntax:touch filename**

 **touch tusha.txt**

 **Output-**

tusha\@tusha:\~$ touch tusha.txt

tusha\@tusha:\~$ ls

 bak  Desktop  Downloads                 ldap1.sh        ldap.sh   organisation.ldif   rm Templates

 Coding   Dictionary   farmer\_suicide\_in\_India.md LDAP\_Document.md ldif  Pictures        run tusha.txt

config   Document farmer\_suicide\_in\_India.pdf  'Ldap explanation'   logs Public          snap  'Untitled Document 111'

db   Documents group.ldif                LDAP.md         Music PycharmProjects ssca   Videos

tusha\@tusha:\~$

![](https://lh7-us.googleusercontent.com/CMrrymspFjl5OPajcX44H7-c1xfE_Adb-_QCpJQjuBWIUaxhLDiALPtdEq3VjKc899VAEB5RVNzK9GB3A1qCG52d4MR6pij6hw-Inw0Uy0Iee_GmExzgYCT392Y74xZJYdn2iLv1OkNUM3QMugF5J9k)

 **->touch:** it is used to create an empty file command.

**->tusha.txt:** It is a filename.

    

### 6.Remove multiple files with a single command

**rm-** To remove multiple files with a single command in a Unix-like operating system.

**Syntax: rm filename**

**rm file1.txt file2.txt file3.txt**

****![](https://lh7-us.googleusercontent.com/NJHf6ABHM-9jE29vhFU2bi6-CsN__Z9y3XCLgZUpYzWQoOt-o3PHoLPljyAhvTi15ppV498K8rBpTSHt3UzCQn2IYwsHk34GAibQoc54N771GoS5t6eMB8iWI18SViYL1IARu05Fh9_4AHX75pwAU7E)****

**-> rm:** it is a remove command**.**

**->file1.txt file2.txt file3.txt:** it is a file name.

   

 ### 7.Remove content from the folder without removing folder

**rm -r:** To remove the contents of a folder without removing the folder itself, you can use the **rm** command with the **-r (recursive)** option.

**Syntax: rm -r filename**

**rm -r file1.txt file2.txt file3.txt**

**Output-**

tusha\@tusha:\~$ mkdir tusha

tusha\@tusha:\~$ cd tusha/

tusha\@tusha:\~/tusha$ touch file1.txt file2.txt file3.txt

tusha\@tusha:\~/tusha$ ls

file1.txt  file2.txt  file3.txt

tusha\@tusha:\~/tusha$ rm -r file1.txt file2.txt file3.txt

tusha\@tusha:\~/tusha$ ls

tusha\@tusha:\~/tusha$

![](https://lh7-us.googleusercontent.com/9mgab5wNZobjJ6MTHb-Z60JQsEhBQ0HoJSlaffFgu_bAmwd9ZfCgEbdFd8ABd2jbCGJgfWSenUrPe-MKDDC6DNW0gfmolP73IgyN7LviuGSPyio-4pJmHzQjIMeW0T06wu6koQxpxVc2vTXFoMgo-fA)

**-> rm:** it is a remove command**.**

**->file1.txt file2.txt file3.txt:** it is a file name.

**->-r :** it is a recursive option.

### 8.Create multiple folder(a-z) with a single command

  **mkdir-** To create multiple folders (a-z) using a single command, you can use a loop in a shell or command prompt.

  **Syntax**: **mkdir {a..z}**

 This command uses brace expansion to create folders named from **"a" to   "z".** Each letter is separated by two dots. After running this command, you should have folders named **a, b, c, ..., z** in your current directory.

![](https://lh7-us.googleusercontent.com/k2P0TBh2O0yNnAAmhTyOHubprGzkK4uXxO7TEw69ofciMJ7R9sf4mfLZ2Kc2l52s3ZR0VwMl15ZVyDA0_Mm9HQCkO4UtTKbm4FKvss6pKRulcAwXRjYILaVkt6B6qUxmtkxm5jkG-Y_bv_IH8Eq8APM)

 **-> mkdir :** It is used to create a directory.

    **mk** : make ,     **dir** - directory

**->{a..z}:** it is the name of folder.

