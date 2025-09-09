# README
This repo contains files that make life easier - vimrc files, powershell scripts, etc.

## kali-vimrc
Pretty standard - tabs, not spaces and includes the set spell command to turn spell-check on in .txt and .md files.
Also allows for .vimrc files placed in subdirectories to be appended to the master .vimrc.

## reminder_commands
.txt file that contains powershell commands to create a powershell script, create, and delete a reminder.
Currently set to create a popup window that says "Document progress".
Can easily modify the message and the time interval - there's one command to set the interval to 30 minutes and another for 1 minute.

## writeup_repo_vimrc
Extra .vimrc file to copy a python file with a certain name to another file with a '''python\*''' wrapper.
Intended for easier use with Obsidian. Anytime you :w the file in vim, it automatically gets copied to the Obsidian file in the Obsidian code format.
Currently set to copy challenge\*.py files to the notes.md and backup.md files in the challenge\* directory.
The name of the python file is easily changeable.
I haven't tried changing the notes.md file, backup.md file, or the fact that they're in a directory.
Changing every instance of 'assignment' in this file will change the name of the file to copy and the directory to copy to.
