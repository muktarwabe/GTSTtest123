

 
 Types of hackers 

## Black HAT  hackers 
- the most evil and bad peoples in the cyberspace 
# White HAT hackers 
 The helping and good peoples
# Gray HAT hackers
-individual who sometimes act ethically and othet times engage in questionable or illegal activities 


## types of hackers based on skill

### newbie / Noob
- don’t have any knowledge about hacking 

## Script kiddie
- A script kiddie , skiddie,Kiddie, or skid is a relatively unskilled individual who uses scripts or programs developed by others, primarily for malicious purposes 
-

# why hack happens ?
- ATTACKS= MOTIVE(GOAL) + METHOD + VULNERABILITY 
- MOTIVE:- information theft, manipulating data, Financial loss, Revenge, Ransom, Damaging reputation. 

# Elements of information security 
1 CIA triad  
![[image.jpg]]






# today class topic 

## what is kernel 
- kernel is a code/program that used to meet your software and hardware and allocate some resources.

![[image 1.jpg]]
# history of linux
- in 1969 a team led by computer scientist ken thompson and dennis ritchie created the first version of UNIX on a PDP-7 minicomputer,
- Which was chosen mainly because of thompsons familiarity the system from his hobby work on it
- But it wasn’t cheap and open source 
- 
![[image 2.jpg]]![[image 3.jpg]]

# what is shell?
![[image 4.jpg]]
# types of shell 
![[image 5.jpg]]

# what is OS-operating system??

![[image 6.jpg]]

# kernel

![[image 7.jpg]]

# desktop environment 

![[image 8.jpg]]


# types of desktop environment on linux
A mate

![[image 9.jpg]]

B gnome

![[image 10.jpg]]

c KDE plasma

![[image 11.jpg]]


# D XFCE 


![[image 12.jpg]]

# Which desktop environment is best ?

![[image 13.jpg]]

# windows manager 
I3- window manager 

![[image 14.jpg]]


# why linux ?
Most used


![[image 15.jpg]]

# most hacking tools

![[image 16.jpg]]


# most secured 

![[image 17.jpg]]


# linux distributions/distro

- distro is modified linux kernel,type of operating systems with different 

  - 1 Linux kernel
  - 2 packages (GNU)

![[image 18.jpg]]

# so many distros

![[image 19.jpg]]![[image 20.jpg]]

![[image 21.jpg]]

![[image 22.jpg]]


![[image 23.jpg]]

Type of vertualization 
Type 1
![[image 24.jpg]]

# type 2

![[image 25.jpg]]

![[image 26.jpg]]


![[image 27.jpg]]

Homework 

![[image 28.jpg]]


MARKDOWN SHORT CUT

![[image 29.jpg]]


# linux comand


## Echo

SYNOPSIS
echo ( string)


# Description 

Echo command in linux is used to display line of text/string that are passed as an urgument.
![[image 30.jpg]]
# OUTPUT RESIRECTING

![[image 31.jpg]]

#  foldera harawa text wojjiin  uummuuf command kana fayyadamna

Echo “my name is muktar” >muktar.text

# ![[image 32.jpg]]folder dura jiru keessatti text barreessuuf command nu fayyadu

Echo “my name is Muktar” >> maqa folder keessatti galchuu barbaannuu


## cat /head/tail/less comands

SYNOPSIS 
- cat[[file]]
- Head[[file]]
- Tail[[file]]
- Less [[file]]

Description 
- All are used to show the content of a file 
- Head and tail will display the 10 lines of the file
![[image 33.jpg]]cat ka nufaayyadu file keessa waan jiru nuu muldhisuuf nufayyada
Head file gubbaa jiru hanga wohii nuu mudhisa
Tail ka jalaa qofa nuu muldhisa
Less akkasuma

# touch commands

SYNOPSIS 
touch [file1 ] (file 2) (file3 )

#### discrimination 

Create any kind of files with the name you gave it. With empty inside
File maqaa barbaanneen create nuuf godhu garu kaa waan takka of keessaa hin qabne
![[image 34.jpg]]
# mkdir/make directory

SYNOPSIS 
- mkdir {folder name1} {folder name2}
- Mkdir -p folder1/folder2/folder3

Discription
- create folder with the name you gave it
- Don’t forget to Add the”” when you are using folders with space between them

Folder harawa oomnee folder harawa keessatti folder biraa umuu yoo barbaanne
Command kana fayyadamna

Mkdir -p muktar/ omer 

# ![[image 35.jpg]]![[image 36.jpg]]rm/remove comands
Synopsis 
Rm {file1} {file2} {file3}
Description 
Remove file

Rm  command file balleessuuf nu fayyaduudha
![[image 37.jpg]]
…

- rm -r  > maqaa folder keessa seenee ka balleessuu barbannu itti barreessina
-  rm -i file osoo hin balleessin fura eyyama akka nugaafu yoo barbaanneef fayyadamna
- rm -f  eeyyama malee file akka balleessinuuf nugargaara

# ![[image 38.jpg]]cp/mv copy,move 

# ![[image 39.jpg]]home work

![[image 40.jpg]]

# grep - global search for regular expression 

- grep {options} pattern {files}

- the grep filter searches a file for a particular pattern of characters and displays all lines that contain that pattern 
The pattern that is searched in the file is referred tonas the regular expression ( grep stands for global search for regular expression and print out)

grep ka fayyadamnu file barbaannu file keessaa barbaannee garaa ittiin argannuudha

Fakkenyaaf jecha my jedhu file keessa yoo search godhuu barbaanne  grep “my” jennee maqaa file keessaa search godhuu barbaanne san itti barreessina 
Fakkeenyaaf grep “my” muktar.text


##### ![[image 41.jpg]]grep -i “search” file 
- jecha barbaannu san qubee guddaa fi xiqqaan ka jiru search godhee lachuu akka nuu baasuuf itti fayyadamna
- case insensitive 

 grep -c “search “ file name
 Jechi search goonu sun yeroo meeqa akka jiru baayyina isaa nuuf baasa

Grep -l “search” * file nuti search goonu folder kam fa’a keessa akka jiru foldaroota nuu baasa
![[image 44.jpg]]


Grep -r “search “ folder name
Kuni folder biraa keessa jechi nuti barbaannu keessa soquuf nu gargaara

grep -v ‘term’ file name
Jechi nuti barbaannu sun yoo hin jiraannee akka jiruuf akka hin jirre nuu hima

grep -n “term” file 
File nuti barbaannu lakkofsa inni irra jiru nuuf baasa
![[image 42.jpg]]grep -o “my” file name
Kuni jech nuti barbaannu qofa display nuuf godha

![[image 43.jpg]]

![[image 45.jpg]]
# wc - word count 

Synopsis 
Wc {option} file 

Description 
-  it is used to find out number of lines,word count, byte and characters count in the files specified in the file arguments.
- kuni kan nu gargaaru file keessa wonti nu barbaannu sun line meeqa akka qabu size isaa hagam akka tahe qubee meeqa akka qabu adda nuu baasee nutti hima

![[image 46.jpg]]
wc -l  line meeqa akka qabu nuu baasa
wc -w qubee meeqa akka qabu nuu baasa
wc -c size hagam akka tahe nuu baasa

# multiple commands executions 

-  you can run / execute multiple commands in 1 line
- Using 3 methods 
     - And(&&)
     - Or(ll)
     - Pipeing(l)
 # ![[image 47.jpg]]or 
![[image 48.jpg]]
Pipeing (i)

![[image 49.jpg]]
# sed /stream editor 


# ![[image 50.jpg]]awk command 

# ![[image 51.jpg]]Day 4 school

# Topics


- linux file hierarchy 
- VIM
- NANO
- LINUX USER MANAGEMENT 


# Linux file Hierarchy 

- linux /UNIX have a special file system than windows 
- File system is a directory structure that the OS uses.

### system files 

- system files are files used by the system software OS
- Windows system files appear under the local C
- Linux  system files appear under the root directory (/)

# file structure in detail 

1)  /(root)
     - every single file and directory starts from the root directory 
     - The only root user has the right to write under this directory 
     - /root is the root user’s home directory which is not the same as /
     -
 ![[image 52.jpg]]we can’t command cd root
 Because we don’t have permission 
To bypass we can use cd su root

2 bin- binary executable 
   - essential command binaries thet need to be available in single-user mode:for all users
Examples 


![[image 53.jpg]]3 /boot-Boot loader files

  - Kernel initrd,vmlinux,grub files are located under /boot
-

Exm


4 /dev-essential device files

 These include terminal devices, usb or



5 /etc-et cetera

Contains configuration files required by all program
This also contains startup and shutdown shell scripts used to start/stop individual programs 

Example 
/etc/hosts, etc/password


![[image 54.jpg]]6 /home-home directory 

  Home directories for all users to store ther personal file
Example 
/home/muktar , /home/muktar



![[image 55.jpg]]7 /lib-libraries essential for the binaries in /bin&/sbin

   Library filenames are either id* or lib*.so.*

Example id-2.11.1.so
Libncourse


![[image 57.jpg]
![[image 56.jpg]]8 /media


![[IMG_3820.jpeg]]
9 /mnt- temporarily mounted file

 Temporarily mount directoty where sysadmins can mount file system 


10 /opt-optional application software packages 

Contains add-on application from individual vendors 
Add-on applications should be installed under either/opt/ or /opt/sub-directory

Bakk software keenna taa’u


![[image 59.jpg]]

![[image 58.jpg]]
11 /sbin essential system binaries 

Bakka file command taa’u

Just like /bin 

![[image 60.jpg]]12 /tmp temporarly files



![[image 61.jpg]]13  /usr user utility 



![[image 62.jpg]]

# text editor 

- programs that used for text processing 
- linux command line text editor 
     -  vim
     - Nano
     - Emacs
     - Neovim
- linux
- 

![[image 63.jpg]]

# Vim



# ![[image 64.jpg]]
How to open vim


![[image 65.jpg]]

Command mode

![[image 66.jpg]]
![[image 67.jpg]]
![[image 68.jpg]]
![[image 69.jpg]]
![[image 70.jpg]]
![[image 71.jpg]]

![[image 72.jpg]]

# visual mode


![[image 73.jpg]]commands in visual mode

![[image 74.jpg]]

# day 5 class

### NANO 

 The GNU nano text editor is a user
 

![[image 75.jpg]]

### Starting nano


![[image 76.jpg]]

Nano keys


![[image 77.jpg]]

..
## linux user management 
- on computer systems 
- Every users have group
- User have their own file&application
- To know 
- Those users 
- On Linux there is 2 kinds users
       -  root id=0
       - Normal user id start with 1-999
The root user have the power  to do everything on Linux 
But if users want to have a root acces they add SUDO in front of the command 

         Sudo your command 
     -  SUDO= superuser do used to bypass permission denied 


# How to create users



![[image 80.jpg]]






![[image 79.jpg]]

To see user password 
Cat etc/shadow


# day 5 class

### On today’s class

- further on user management 
- Linux file ownership + permissions 
- Software installation 

![[image 81.jpg]]

# Some advanced user commands 

![[image 82.jpg]]
### How to change passwords


![[image 83.jpg]]

# How to create passwords 

![[image 84.jpg]]
# To change user id

![[image 85.jpg]]
![[image 86.jpg]]

# To change group id

![[image 87.jpg]]
# To delete user

![[image 88.jpg]]
To change user on terminal

![[image 89.jpg]]

To create folder in anather user


![[image 90.jpg]]

![[image 91.jpg]]
# To change shell


![[image 92.jpg]]

![[image 93.jpg]]
# Some advanced group commands 


![[image 94.jpg]]
# To remove user from group 

![[IMG_4229.png]]

# Sudoers file

![[image 95.jpg]]
# Linux file permission 

![[image 97.jpg]]

![[image 96.jpg]]

# Ownership 


![[image 98.jpg]]
# Permission 

![[image 99.jpg]]

![[image 100.jpg]]

![[image 101.jpg]]

# Chmod commands

![[image 102.jpg]]


![[image 103.jpg]]
![[image 104.jpg]]

# Day 5 part 2 class

## Special file permissions 




![[image 105.jpg]]


![[image 106.jpg]]
# Package installation on linux 


- ON Linux to install software you use package managers.

    Example apt,pacman,pkg

- we will use debian package manager 
- On debian the package manager is called’APT’ also there is called ‘ dpkg’ 
- Package managers are a free-software user



![[image 107.jpg]]
# The repository 

![[image 108.jpg]]

 Advanced package tool APT
# advanced package tool

- sudo apt update 
- Sudo apt search (software name)
- Sudo apt install software name
- Sudo apt remove software 
- Sudo apt upgrade 
- Sudo purge software 
 
![[image 109.jpg]]

# Package dependencies 

- A software can be built based on another program called ‘modules’
- So a program to work properly the dependencies have to be installed successfully 
- Those packages manager installe the software +dependencies
-


![[image 110.jpg]]


### Example 

![[image 111.jpg]]

![[image 112.jpg]]

Common Linux repository errors

![[image 113.jpg]]

# Dpkg/debian package manager

- Dpkg is an offline package managing



![[image 114.jpg]]

# Flatpak

![[image 115.jpg]]
# How to use flatpak

![[image 116.jpg]]

# day 6 class

### today topics
- script installation 
- Help on linux
- Linux services 
- Symbolic linking
- Alias
- Tmux
- Wget
- Find



![[image 117.jpg]]
# script instructions 

File linux irra hin jirta git hub irraa akka itti download godhanuudha

- some hacking tools are developed by some peoples and those people make it open-source, that means we can get those scripts 
- So we can download and use it for this purpose git have a feature called ‘CLONE’
- Syntax 
-

Example 

![[image 119.jpg]]





![[image 118.jpg]]

# Script modules

- scripts are made with scripting languages(programming ) like python,bash,go,roby…

Example 

1 python: to install python modules we use -> pip install< module name>
 For requirements file -> pip install -r requirements.txt
 2 Go: to install go modules -> go install < module name>
 3 Ruby: to install ruby modules -> gem install < module name>

![[image 120.jpg]]

# python installation 



![[image 121.jpg]]

# go package installation 



![[image 122.jpg]]

# if you need help on linux about commands

You can use 
- man ( manual )
     - this 
![[image 123.jpg]]

# Help

-  help 
      - some commands help option 
  Example 
- Your command -h
- Your command-help
- Your command—help
- 

![[image 124.jpg]]

Class work

![[image 125.jpg]]


# linux processes and services 



-  terms 
      -  processes: running instances of programs 
      -when you execute a program like opening a text editor , running a command or starting a web browser Linux loads that program into memory and starts is as process 
      - services : background programs that start automatically or manually often for system tasks( also known as daemons )
      -A service that runs to gather any change on the system or to count time runs on background 
  To get the process running 
- Ps ( options)
More commands 
- ps -> for process running on my shell
- Ps -A -> view all running process
- Ps -u username-> view user process 


![[image 126.jpg]]

# managing process 

To stop process 
- kill { option } [ PID ]
- killall [ program name ]

More on kill
- kill -19 PID : to stop the process 
- Kill -18 PID : to resume the process we stopped 
- Kill -9 PID : to stop process immediately 
-

PID proces id
PPID parent process id



![[image 127.jpg]]

-  this is a time taking an not realtime 
- For realtime we have the tool called “top” imstalled on linux by default 
- But to make this fun we will use “htop” it is colorful and more enhanced!
- 

![[image 128.jpg]]

# foreground/background



![[image 129.jpg]]

# Managing services 

Example command 
Sudo systemctl start apache2


![[image 130.jpg]]



# Null device


![[image 131.jpg]]

# Symbolic linking 

- symbolic linking is same as windows shortcut 
- 

![[image 132.jpg]]
Symbolic linking examples 


![[image 133.jpg]]


# Alias 

-  used to give a name to some bunch of commands 
- Example: if I wanted to name is -la ‘rex so any time i want to get output of is -la i just type rex

Example commands 
-  alias rex =‘ls -la 

![[image 135.jpg]]
![[image 134.jpg]]

# Tmux - terminal multiplexer


- tmux is used to classify our terminal work
- You can install it using apt. On kali it is built-in then to start it just type ‘tmux’
- 
![[image 136.jpg]]

![[image 137.jpg]]
![[image 138.jpg]]



# Wget

- is a tool used yo download files from websites/servers
      *wget [ optional] [link

![[image 139.jpg]]
# Find

- On terminal if you want to search for files/folders/music/videos
- It is very essential tool
- Syntax 
       - find [search path ] [ optionals ( search word )
       - More commands 
          - find/ -name “linux”
          - Find/ home-perm 777
          - Find -type f | find -type d
          - Find / -type f -perm /4000
          - 
![[image 140.jpg]]


Home work

![[image 141.jpg]]

# today topics day 7


![[image 145.jpg]]
![[image 142.jpg]]


# What is programming language 


![[image 143.jpg]]

# What is program

- A program is an *algorithm* expressed in a programming language 
- An algorithm is a detailed sequence of actions to perform to accomplish some task Named after an Iranian mathematical Al-khwarizmi
- Technically, an algorithm must reach a result after a finite number of steps 
- With those steps programs do a 

![[image 144.jpg]]

# Algorithm example 


![[image 146.jpg]]
# Pseudo code



#### Example for pseudo code 

#Begin
      Prompt user for usename
      

![[image 147.jpg]]

# Example 2 

#Begin 
      DISPLAY “Enter the first number:”
      INPUT number1
      DISPLAY “Enter the second number:”
      INPUT number 2
      Result =number1 + number2
      Display “the result is” result 
#End

  
![[image 148.jpg]]
### Advanced 

![[image 149.jpg]]

#### Evolution of I/O { input/Output }

- Early im the history of computing, programs were submitted on #punch_cards_with_all_the_data they required and executed together with other programs that used the same libraries. Output was to a #line_printer 
- Later developments introduced interactive processing which allowed the user to provide data while the program was running. This normally take place in A Question & Answer format.
- 
![[image 150.jpg]]

# Generation of computers 



![[image 151.jpg]]

# Types of programming languages 

![[image 152.jpg]]
# A) Low level programming language 


![[image 153.jpg]]

![[image 154.jpg]]

![[image 155.jpg]]

# What is python programming?
![[image 156.jpg]]

# History of Python 

![[image 157.jpg]]

# Uses of python 

![[image 158.jpg]]

# Day 7 P2 class 

#### Today topics 

Python 
1 output and comments 
2 variables and Data type 


### Output and comments 
- on python to display output we use keyword’print’
- Syntax: print ( object=“ , sep “, end=“)
- You can use the term “display “ for pseudo code 

Example 
Print( ‘python is powerful’ )
Output: python is powerful

Print with end white space 
Print (‘good morning’ ,end=‘ :’)
Print (‘ it’s rainy today’)

\n-new line
\t -tap space

![[image 159.jpg]]

# Comments
- this are a simple notes written on our codes those can help as to remember the function of the code or to make it simple for peoples to understand our code.
- Comments won’t be executed.
- Syntax: # this is comment line 

![[image 160.jpg]]


# Python keyboard 

Keywords are predefined, reserved words used in python programming that have special meanings to the computer.


![[image 161.jpg]]


![[image 162.jpg]]

# Variables 
- variables are a value holders/container/
- They store data 
- We give some value to some word.
- Example: number=10  => from jow on my python program knows the value of number is 10
- The process of giving value to word is called variable declaration 
- The word that holds the data is called identifier
- We can print value of variables by giving the identifier 
- Yo can use the term “declared” for pseudo code


gtst 
![[image 163.jpg]]


![[image 164.jpg]]

# Data types 
- 
![[image 165.jpg]]


![[image 166.jpg]]


![[image 167.jpg]]

![[image 168.jpg]]
![[image 169.jpg]]

![[image 170.jpg]]

# Day 8 class topics

- indexinf and slicing { start,stop,step }
- 

![[image 171.jpg]]


# Indexing 

-  on lists, we habe seen about index numbers 

Languages = ( `python ` `swift `c++`)
               |.                  |.           |
Indeex ———-   0                    1         2

- calling text by index also works for strings&tuples


![[image 172.jpg]]

calling text by index also works for strings&tuples

Name = (‘hello’ , 23,22 )
 Print (name [2])
#output : 22

Name = ‘nathan’
Print (name [2])
#output : t

![[image 173.jpg]]


# Slicing 

-  in python it is possible to acces section of items from the list using slicing operator’:’ , not just a single item.
- syntax:
      - Mylist [start : stop :step ]
-  slicing is indexing syntax that extracts a portion from a list. If a is a list, then a[m:n] returns the portion os a:
     - string with position m
     - Up to but not including n
     - Negative indexing can also be used 
 - it is more applicable for strings.
-

Example 

Name = ‘no 1 is Nathan’
print (name [8 :14 : 1 ])
#output : Nathan

![[image 174.jpg]]


![[image 175.jpg]]


# User input handling 

- on python there are 2 types of inputs
-     -  by input function 
     -by Argument 
1) by input functions,
      - syntax: var = input (“text you like to display:”)
      - Will accept the input and store on variable
Example 
name =input (“what is your name?\n name: “)
Print(f”hello {name} !”)
#output : what is your name ?
        Name: ‘Nathan Hailu’
         Hello Nathan Hailu !
         
![[image 176.jpg]]

![[image 177.jpg]]





# Class Agust 17


![[IMG_5652.jpeg]]


![[IMG_5653.jpeg]]




![[IMG_5655.jpeg]]







![[IMG_5671.jpeg]]




![[IMG_5656.jpeg]]






![[IMG_5660.jpeg]]




![[IMG_5669.jpeg]]




![[IMG_5671 1.jpeg]]





# Day 8 class


Topics

# If-else conditions 



![[image 178.jpg]]

# If statement

![[image 179.jpg]]


![[image 180.jpg]]



![[image 181.jpg]]



# Breaks 


In Python, the break statement is used to exit a loop immediately before it has finished running all its iterations.

  

Here are the main uses of break:

  

  

  

  

🔹 1. Stop a loop when a condition is met

  

for num in range(1, 10):

    if num == 5:

        break   # exit loop when num is 5

    print(num)

👉 Output:

1

2

3

4

  

  

  

  

🔹 2. Exit an infinite loop

  

while True:  

    user_input = input("Enter 'q' to quit: ")  

    if user_input == 'q':  

        break   # stops the infinite loop

  

  

  

  

🔹 3. Search and stop when item found

  

numbers = [2, 4, 6, 8, 10]

  

for n in numbers:

    if n == 6:

        print("Found 6!")

        break   # stop searching once found

  

  

  

  

🔹 4. With 

else

 in loops

  

  

Python allows else with loops. The else block runs only if the loop finishes normally (not stopped by break).

for i in range(5):

    if i == 3:

        break

else:

    print("Loop finished without break")  

  

print("Done")

👉 Here, the else won’t run because the loop was broken.

  

  

  

⚡ In summary:

  

- break ends the loop immediately.
- Useful for early exit, infinite loops, and searching tasks.

  

  

Would you like me to also explain the difference between break, continue, and pass in Python?

# Day 9 class



#### Class topics 

- Functions, recursion 
- Lambda —- Map/filter
- OOP&POP
- Class & objects 
- User-built modules 



# Functions


