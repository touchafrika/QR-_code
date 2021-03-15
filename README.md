Task1: basic task

1.type in ls and press enter. What do you see? What does this mean?
recruit@recruit-M:~$ ls
 cd                    myapp                      Templates
 create                node_modules               thabo
 Desktop               package-lock.json         'The Takeover 2.0'
 Dockerchallenges      Pictures                   todo-api
 Documents             Public                     Videos
 Downloads             reactApp                  'VirtualBox VMs'
 exercise.md           README.md                  websportfolioLN
 git-basic-exercises  'semitone GUI'              wordpress
 memory-game-master    string-calculator-master   workspace.cd
 Music                 tech-department
>>It shows list of files content.
>>It means all files with the specified directory are shown.

2.type in pwd and press enter. What do you see? What does this mean?
   recruit@recruit-M:~$ pwd 
   /home/recruit
  >>It shows the current directory which is working
  >>It shows you where you are at the moment 

3.Make a new directory called workspace then cd into your new directory
   >mkdir workspace

4.type in ls and press enter. What do you see? What does this mean?
>>shows you the list  of files in directory(workspace has been created and appears on the list).
>> It mean the mkdir workspace command has been executed.

5.Make a new file called README.md (you can use the touchcommand to do this)
 recruit@recruit-M:~/workspace$ touch README.md
recruit@recruit-M:~/workspace$ ls
README.md

>>mkdir  README.md

6.Make a copy of README.md, name your copy CHANGELOG.md
recruit@recruit-M:~/workspace$ cp README.md CHANGELOG.md
recruit@recruit-M:~/workspace$ ls
CHANGELOG.md  README.md
  

Task 2: Absolute & Relative Paths

1.recruit@recruit-M:~/workspace$ mv exercise.md /tmp
recruit@recruit-M:~/workspace$ cd
recruit@recruit-M:~$ rmdir /tmp/exercise.md
recruit@recruit-M:~$ 


Task 3: Cat Commands

1.recruit@recruit-M:~$ cat > umuzi.md
I make money  
recruit@recruit-M:~$ cat > recruit.md 
I will marry a striperrecruit@recruit-M:~$ cat > cohort.md 
sell it
recruit@recruit-M:~$ cat umuzi.md recruit.md cohort.md
I make money 
I will marry a striper
sell it
>> creating file, writing info and concatenation done

2. recruit@recruit-M:~$ cat umuzi.md recruit.md cohort.md > summary.md
>> created a summary file.

3. recruit@recruit-M:~$ echo "THE END" >> summary.md
recruit@recruit-M:~$ cat summary.md
I make money 
I will marry a stripersell it
THE END
>> Added “THE END” to the summary

Task 4:The Locate Command 

1.recruit@recruit-M:~$ locate umuzi
/home/recruit/.local/share/Trash/files/Memory/img/umuzi.png
/home/recruit/memory-game-master/umuzi.png
/home/recruit/tech-department/content/5-misc/make-umuzi-better-full.md
/home/recruit/tech-department/content/5-misc/make-umuzi-better-short.md
/home/recruit/tech-department/static/images/umuzi.png

2. recruit@recruit-M:~$ locate umuzi > search_results.md


Task 5: The Locate Command Cont....
1. recruit@recruit-M:~/Desktop$ cd ...
recruit@recruit-M:~/Documents$ touch pad.md
recruit@recruit-M:~/Documents$ ls
pad.md

recruit@recruit-M:~/Documents$ cd
recruit@recruit-M:~$ cd Desktop
recruit@recruit-M:~/Desktop$ mkdir work
>>Create a file within a directory and add a file named “pad.md”

2.recruit@recruit-M:~/Desktop$ cd Desktop
   recruit@recruit-M:~/Desktop$ mkdir work
>> change the directory to “Desktop” , create a folder and call it “work”
 
3. recruit@recruit-M:~/Desktop$ cp ~/Documents/pad.md 
   recruit@recruit-M:~/Desktop$ mv pad.md pad_copy.md
>>copy pad.md” to the currently working directory as “pad_copy.md”

4. recruit@recruit-M:~/Desktop$ locate updatedb
>>update the database used by locate by running locate “updatedb”.

5. recruit@recruit-M:~/Desktop$  cd -
>>change the working directory to the previous branch using “cd -”

6. recruit@recruit-M:~/Desktop$ locate pad_copy.md
>>Use “locate” to find “pad_copy.md”

Task 6: Find Commands

1. recruit@recruit-M:~/Desktop$ find -name *.pdf

2. recruit@recruit-M:~/Desktop$ locate *.pdf >> files.md

3.recruit@recruit-M:~/Desktop$ find . -maxdepth 1 -print

TASK 7:

1. recruit@recruit-M:~/Desktop$ nano my_bio.med
 
2. Used “Ctrl” , pressed “X” and pressed “Enter” to exit the edit section

3. recruit@recruit-M:~/Desktop$ mkdir my_files
