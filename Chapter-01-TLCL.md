# Chapter 01 What Is The Shell
## !!If you're here to review linux commands and you're already familiar with Linux, jump to Table 1.

## 1.1 What is the shell
When we speak of the command line, we are really referring to the shell.
The shell is a program that takes keyboard commands and passes them to the operating system to carry out.
Almost all Linux distributions supply a shell program from the GNU Project called bash.
The name “bash” is an acronym for “Bourne Again SHell”, a reference to the fact bash is an enhanced replacement for sh, the original Unix shell program written by 
Steve Bourne.

## 1.2 Your First Keystrokes
So let's get started. Launch the terminal emulator! Once it comes up, we should see some
thing like this:
```.bash
*[me@linuxbox ~]$
```
This is called a shell prompt.  it will usually include your username@machinename, and a dollar sign. depending on your distribution.
If the last character of the prompt is a pound sign (“#”) rather than a dollar sign, the terminal session has superuser privileges.
This means either we are logged in as the root user or we selected a terminal emulator that provides superuser (administrative) privileges.
Enter some gibberish at the prompt like so:
```.bash
*[me@linuxbox ~]$ kaekfjaeifj
```
bash: kaekfjaeifj: command not found
Since this command makes no sense, the shell will tell us so and give us another chance.

## 1.3 Command History
If we press the up-arrow key, we will see that the previous command “kaekfjaeifj” reappears after the prompt.
This is called command history. Most Linux distributions remember the last 500 commands by default.
Press the down-arrow key and the previous command disappears.

## 1.4 A Few Words About Mice And Focus
While the shell is all about the keyboard, you can also use a mouse with your terminal emulator.
There is a mechanism built into the X Window System (the underlying engine that makes the GUI go) that supports a quick copy and paste technique.
If you highlight some text by holding down the left mouse button and dragging the mouse over it (or double clicking on a word), it is copied into a buffer maintained by X.
Pressing the middle mouse button will cause the text to be pasted at the cursor location. Try it.

# TABLE 1
| Commands | Result | Description |
|---|---|---|
| `date` | Thu Oct 25 13:51:54 EDT 2026 | Displays the current time and date. |
| `cal` | October 2007 Sa Su Mo Tu We Th Fr 1  2  3  4  5 ... | Displays a calendar of the current month. |
| `df` | ... |The current amount of free space on your disk drives. |
| `free` | ... |Likewise, to display the amount of free memory |
| `exit` | ... | We can end a terminal session by either closing the terminal emulator window, or by entering the exit command |

## End of chapter 01
Thanks for reading if you found these notes helpful, don't forget to start this repository! Also feel free to connect with me on Linkedin using the link in my profile.
