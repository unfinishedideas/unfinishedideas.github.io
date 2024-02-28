---
layout: single
title:  "First post!"
---

# Welcome to my first post!

Just wanted to make a test post and see how **jekyll** interprets this.

> Writing markdown files for personal sites makes way more sense than making the thing out of HTML/CSS or React or something. *- some guy*

I want to see what [links](https://www.google.com) look like as well as images.

1. I assume
2. it will
3. look good

## Second header above this awesome screenshot

![Here is a test screenshot](/assets/img/wow.jpg)

```c++
int main
{
    // this is the best program ever
    int x = 9000;
    cout << "how does this code look? Is it over " << x << "?\n";
    return 0;
}
```

---

* At least I hope
* that it will
* look good

---

Ya like footnotes? [^1]

Ya like other footenotes? [^2]

## Is it table time?

### Let's try a table. Here's a bunch of linux stuff

| command     | action | example |
| ----------- | ------ | ------- |
| man         | See the manual page for any of these commands for a more detailed explanation plus extra options (which they pretty much all have) |  `man ls` |
| scp         | Copy a file from one machine to another using ssh like protocol | `scp /path/to/file username@a:/path/to/destination` |
| ssh         | Login with an ssh to another machine | `ssh username@hostname` |
| sed         | Search and replace inside a file (dangerous but useful!) |  `sed -i '' 's/#Text To Replace/Text To Replace With/g' /etc/ssh/sshd_config` |
| whoami      | See which user you are in the shell | `whoami` |
| grep        | Search an output (or file) for a particular phrase. Grep is really powerful, combine with pipes** and stuff | `grep "string" /path/to/file` |
| head / tail | Look at the first or last few lines of a file | `head file.txt` `tail file.txt` |
| diff        | Compare two files, line by line and output the difference | `diff file1 file2` |
| cmp         | Compare two files, byte by byte | `cmp file1 file2` |
| ps          | Show the currently running system processes | `ps` |
| kill        | Kill a process by it's pid | `kill 12345` |
| chmod       | Change file permissions for different groups. See the man page for different number permission codes. Each number represents different users the order is: owner, group, others | `chmod 777 ./filename` |
| chown       | Change the owner of a file | `chown new_owner file` |
| ifconfig / ipconfig    | Get network information about the system ip address, adaptors etc | `ifconfig` |
| wget        | Download content from webservers | `wget https://wordpress.org/latest.zip` |
| passwd      | Change a user's password (useful for creating a password for root user when one is not created) | `passwd` |
| sudo        | Super user do! Enables users to run programs with security privledges of another user, usually root. | `sudo whatever_command_you_want` |
| su          | command to switch the current user | `su root` |
| alias       | Create a customized shortcut for a command or series of commands | `alias update='sudo apt-get update && sudo apt-get upgrade -y && sudo snap refresh'` |
| whereis     | Locate a file / folder in the file system | `whereis passwd` |
| whatis      | Get a one page manual description of a command | `whatis chmod` |
| top         | Provide a real-time dynamic view of the system resources being used | `top` |
| >           | Output the result of a command to a file (overwrites if the file exists!) | `./command > new_file` |
| >>          | Append the result of a command to a file | `./command >> file_that_already_exists` |
| pipe**      | Run Output the result of a command to another program. See note below by the ** | `./program1 pipe** ./program2` |
| &           | Run the process in the background (use `ps` and `kill` to stop it) | `./some_program &` |
| nohup       | Run a script in the background that won't get canceled by SIGHUP signal. Bonus add `disown` as well to remove from the job list of the current shell
| cd          | change the current working directory | `cd ./new_directory` or absolute path `cd /usr/usrname/home` |
| mv          | Move or rename a file | `mv ./og_file.txt ./new_place/renamed_and_moved_file.txt` |
| ls          | List the contents of a directory (adding `-la` is also useful) | `ls -la` |
| cp          | Copy a file or directory (use `-r` for recursive copy) | `cp ./file ./file_copy` or `cp -r ./dir ./new_dir_with_sub_dirs` |
| rm          | Remove a file (use -d to destroy a directory) | `rm file` or `rm -d folder` |

```
// Fenced code block?
{
    "thisIsRandom": "Yep",
    "howIsThisDifferentFromNormalCodeBlocks?": "It's not"
    "whatsTheAnswer": 42
}
```

### This heading has a custom id {#custom-heading-time-booya}

I mean there's only ~~one more~~ a few more things to try...

Like TASK LISTS!

* [x] Task 1 - make a task list
* [ ] Task 2 - see what the x does
* [ ] Task 3 - Make a sandwich
* [ ] Task 4 - Use an emoji :joy:
* [ ] Task 5 - ... Those don't work. Good to know!

It's very ==VERY IMPORTANT== that I highlight this. Ok that doesn't work either

But what about ~subscript?~. I'm starting to think none of the last things are workin. How about H~2~O or X^2^

> Welp, that was an anti-climatic way to end this test document. I hope you liked reading it because that's all you get! - Pete

[^1]: How you like them footnotes?
[^2]: How do you like THESE footnotes?
