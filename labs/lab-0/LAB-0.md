# Lab 0

## Learning Goals
- Understand the interface of a shell (terminal) and how it works
- Learn various commands to navigate your filesystem

## 1. Launching The Shell
The process differs slightly across platforms but is more or less the same. Every OS has a **terminal** which is the program used to interface with the **shell** (command-line).

### Windows
Launch `Windows Terminal`. If your OS is slightly out of date or Windows Terminal is not installed, run `PowerShell` instead

### MacOS
Launch `iTerm2`

### Linux
If you have Linux installed you probably already know how to access the 
command-line. However here are some common terminals if you do not know how to 
access the command line: `Konsole`, `GNOME Terminal`, `Alacritty`, and `Kitty`.

## 2. The Shell Prompt
Once the terminal is open you are going to see the shell prompt

### Windows
```
C:\Users\(YOUR USERNAME)>
```
The first part of the prompt is the filepath to the current directory (folder).

### Linux/MacOS
```
(USERNAME)@(HOSTNAME) ~ $
```
`USERNAME` is your system username (the one you use to login with)

`HOSTNAME` is the name of your computer (e.g. John's Macbook, Mason's PC)

The `~` is a special symbol that represents your user directory, we will discuss this more in the next section.

To start lets learn the first shell command, `echo`. `echo` is simple, whatever text you give it, it prints it back out in the terminal. So for example
`echo Hello, World!` will print `Hello World!`

Try it out on your own and see what happens.