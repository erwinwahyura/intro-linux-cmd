# What is Linux
Linux is considered a Unix-like operating system which basically means that Linux derives heavy inspiration from Unix without actually conforming to be a full Unix operating system. macOS and FreeBSD would be two more examples of a Unix-like operating system.

# Why Linux
So why Linux over other operating systems?

First, it's free. Anyone can use Linux to do anything without paying anyone a dime. This is useful for college students who don't have any money but it's also critical for large businesses running thousands or tens-of-thousands of servers. It can save them millions of dollars to not have to pay for an operating system.

It's very well maintained. Because Linux is such a popular operating system, it has a lot of eyes on it. Engineers from all over the world and all over the industry are constantly contributing fixes and new features to Linux, both on their own free time and during the course of their jobs.

# Distros
There are so, so, so many distros of Linux. They all do different things well and some of them are very specialized in what sorts of things they can accomplish but the most common people use for daily basis is `Ubuntu`.

other distros linux:
- Debian
- Mint
- Red Hat
- Alpine
- Kali
- CentOS
- Backtrack

# Run Linux
There are a lot of way to run linux

## Command Line
```
Command		What it does
pwd		   show me where I am in the file system (initially, this will be your home directory)

ls		   list my files

ls -a		list even more of my files (including those that start with a period)

ls -al		list my files with lots of details (including dates, file sizes and permissions)

who		   show me who is logged in (don’t be disappointed if it’s only you)

date		remind me what day today is (shows the time too)

ps		   list my running processes (might just be your shell and the “ps” command)
```

```
Command		What it does

cd /tmp		move to another directory (in this case, /tmp)

ls		    list files in that location

cd		    go back home (with no arguments, cd always takes you back to your home directory)

cat .bashrc	display the contents of a file (in this case, .bashrc)

history		show your recent commands

echo hello	say “hello” to yourself

cal		    show a calendar for the current month

```

```
Command				What it does
echo “echo hello” > tryme	create a new file and put the words “echo hello” into it

chmod 700 tryme		make the new file executable
tryme				run the new file (it should run the command it contains and display “hello”)

ps aux				show all running processes

ps aux | grep $USER	show all running processes, but limit the output to lines containing your username

echo $USER			display your username using an environment variable

whoami				display your username with a command
who | wc -l	
```

## Wrap-Up
Once you get used to the basic commands, you can explore other commands and try your hand at writing scripts. You might find that Linux is a lot more powerful and nice to use than you ever imagined.