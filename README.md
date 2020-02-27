 Intro to Command line interface 

![image alt](https://media.giphy.com/media/vAWN2mjW9dSLu/giphy.gif)

## What ?

- A command-line interface is a means of interacting with a computer using commands from the user.
- It is also referred to as a Terminal, Shell, Console or Prompt.
- Ubuntu's CLI (*command line interface*) uses Bash as the language to interact with.

## Why ?

> When you use programs with Graphical User Interfaces (GUI) certain buttons perform certain tasks on the computers.

- The Command Line Interface does that too, but it allows you to do it with more precision and power. You type words and hit enter, the shell interprets those words, and works with the OS and files to execute the command.

- It is much faster since there are no graphics involved.


## How ?

# Code-along time!

### Code-along Recap

- [`pwd`](http://www.linfo.org/pwd.html) - print working directory
> prints the current directory you are in.

![image alt](https://i.imgur.com/HKAopX6.gif)

- [`ls`](https://www.rapidtables.com/code/linux/ls.html) - list
> prints the contents of the current directory.

![image alt](https://i.imgur.com/6iX0vwX.gif)

- [`cd`](http://www.linfo.org/cd.html) - change directory (change folder)
> changes the current directory to the target directory

![image alt](https://i.imgur.com/QuGOvzd.gif)

- [`clear`](http://www.linfo.org/clear.html)
> clears the terminal's previous outputs

![image alt](https://i.imgur.com/KMR4qId.gif)

- [`mkdir`](http://www.linfo.org/mkdir.html) - make directory
> creates a new directory in the current directory.

![image alt](https://i.imgur.com/KP2hZtR.gif)

- [`touch`](http://www.linfo.org/touch.html)
> creates a new file in the current directory.

![image alt](https://i.imgur.com/vn7U2yN.gif)


- [`code some-file`](https://code.visualstudio.com/docs/editor/command-line)
> opens the target file with visual studio code.
- After openning the editor write something in the `new-file`, and then make sure to save it by hittinh `ctrl + s`.

![image alt](https://i.imgur.com/KRLGlsW.gif)


- [`cat`](http://www.linfo.org/cat.html) - concatenate
> prints the file's content onto the terminal.

> let's imagine we added some content or code to our new file

![image alt](https://i.imgur.com/tTl165x.gif)

- `cd .` - all directories in linux have `.`
> the `.` is the a reference for the current directory, so when you do `cd .` what you essentially told the computer to do is change directory to the current directory :sweat_smile:.
<!-- > technically -->

![image alt](https://imgur.com/kSte5uf.gif)

- `cd ..` - all directories in linux also have `..`
> change to the parent directory of the current directory or go back a directory.

![image alt](https://i.imgur.com/6ZDBkAf.gif)

- `cd ~` - `~` is called tilda and refers to the computer's home.
> change directory to the computer's home directory.

![image alt](https://i.imgur.com/JZiA0Zp.gif)

- [`code .`](https://code.visualstudio.com/docs/editor/command-line) - again `.` one dot in linux translates to current directory.
> so here we are saying open the current directory with visual studio code.

![image alt](https://i.imgur.com/9CtiDIo.gif)



### What is `sudo` ?

>Ever got a 'Permission denied' error while working on the command line? Chances are that you were trying to perform an operation that requires admin permissions. 
>
> a solution for that would be is sudo for example
`sudo run-admin-command`
- The `sudo` (superuser do) command is used to execute a command with elevated privileges (usually as an admin/superuser).
- It is usually located at the very start of the command.
- You will most likely to be asked to input your computer's password after running a command with `sudo`


## Further Reading/Practicing

- Detailed walkthrough : https://learnpythonthehardway.org/book/appendixa.html
- Good video for the basics: https://www.youtube.com/watch?v=cBokz0LTizk
- Customizing your terminal :smile: : right click in your terminal and click `prefrences` and make your own terminal!.


## Advanced Topics

- Pipes in bash https://quickleft.com/blog/command-line-tutorials-redirection-pipes/
- Further customize your terminal with .bashrc https://vitux.com/how-to-customize-ubuntu-bash-prompt/
- Grep and deep dive with Regex -https://www.digitalocean.com/community/tutorials/using-grep-regular-expressions-to-search-for-text-patterns-in-linux
