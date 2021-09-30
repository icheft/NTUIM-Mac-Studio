# Terminal Cheatsheet for Mac

Modified from [0nn0's terminal-mac-cheatsheet](https://github.com/0nn0/terminal-mac-cheatsheet#english-version) and [UT Martin's Terminal Basics Cheatsheet](https://www.utm.edu/staff/jguerin/resources/utilities/terminal_basics.html).


> _Letters are shown capitalized for readability only._  _Capslock should be off._

- [Terminal Cheatsheet for Mac](#terminal-cheatsheet-for-mac)
    - [SHORTCUTS](#shortcuts)
    - [<mark>CORE COMMANDS<mark>](#markcore-commandsmark)
    - [FILE MANAGEMENT](#file-management)
    - [DIRECTORY MANAGEMENT](#directory-management)
    - [HELP](#help)
    - [GIT](#git)
      - [Configuration](#configuration)
      - [Core Commands](#core-commands)
      - [Synchronization of Changes](#synchronization-of-changes)
      - [Undo Changes](#undo-changes)
      - [Branches](#branches)
    - [OTHER COMMANDS](#other-commands)
  - [WE WILL TALK MORE ABOUT TERMINAL IN OUR NEXT LECTURE](#we-will-talk-more-about-terminal-in-our-next-lecture)

### SHORTCUTS

| Key/Command | Description |
| ----------- | ----------- |
| Cmd + K    | Clears the Screen |
| Ctrl + Y   | Paste whatever was cut by the last cut command |
| <mark>Ctrl + C<mark>   | Kill whatever you are running.  Also clears everything on current line |
| <mark>Ctrl + D<mark>   | Exit the current shell when no process is running, or send EOF to a the running process |
| <mark>Tab<mark>  | Auto-complete files and folder names |

### <mark>CORE COMMANDS<mark>

| Key/Command | Description |
| ----------- | ----------- |
| cd [folder] | Change directory e.g. `cd Documents` |
| cd |  Home directory |
| cd ~ |  Home directory |
| cd /  | Root of drive |
| cd ..  | Previous directory |
| cd .  | Current directory |
| ls | Short listing |
| ls -l | Long listing |
| ls -a | Listing incl. hidden files |
| sudo [command] | Run command with the security privileges of the superuser (Super User DO) |
| open [file] | Opens a file ( as if you double clicked it ) |
| top | Displays active processes. Press q to quit |
| vim [file] | Opens the file using the vim editor |
| vi [file] | Opens the file using the vim editor |
| clear |  Clears the screen |
| pwd |  "Print working directory" |

### FILE MANAGEMENT

| Key/Command | Description |
| ----------- | ----------- |
| <mark>touch [file]<mark> |   Create a new file |
| . |  Current folder, e.g. `ls .` |
| .. | Parent/enclosing directory, e.g. `ls ..` |
| <mark>ls -l</mark> .. | Long listing of parent directory |
| cd ../../ | Move 2 levels up |
| <mark>cat<mark> | Concatenate to screen |
| rm [file] |  Remove a file, e.g. `rm data.tmp` |
| rm -i [file] | Remove with confirmation |
| rm -r [dir] | Remove a directory and contents |
| rm -f [file] | Force removal without confirmation |
| <mark>cp [file] [newfile]<mark> | Copy file to file |
| cp [file] [dir] | Copy file to directory |
| <mark>mv [file] [new filename]<mark> |  Move/Rename, e.g. `mv file1.ad /tmp` |
| pbcopy < [file] | Copies file contents to clipboard |
| pbpaste | Paste clipboard contents |
| pbpaste > [file] | Paste clipboard contents into file, `pbpaste > paste-test.txt` |

### DIRECTORY MANAGEMENT

| Key/Command | Description |
| ----------- | ----------- |
| <mark>mkdir [dir]<mark> | Create new directory |
| mkdir -p [dir]/[dir] |  Create nested directories |
| rm -R [dir] | Remove directory and contents |
| less [file]|  Output file content delivered in screensize chunks |
| [command] > [file] |  Push output to file, keep in mind it will get overwritten |
| [command] >> [file] | Append output to existing file |
| [command] < [file] |  Tell command to read content from a file |
| touch [file] | Create a new [file] |

### HELP

| Key/Command | Description |
| ----------- | ----------- |
| [command] -h |  Offers help |
| [command] --help | Offers help |
| man [command] |  Show the help manual for [command] |
| which [command] |  Show the source of [command] |

### GIT
#### Configuration

| Key/Command                              | Description                                         |
| ---------------------------------------- | --------------------------------------------------- |
| `git config --global user.name [name]`   | Set author name to be used for all commits          |
| `git config --global user.email [email]` | Set author email to be used for all commits         |
| `git config color.ui true`               | Enables helpful colorization of command line output |

#### Core Commands

| Key/Command                 | Description                                              |
| --------------------------- | -------------------------------------------------------- |
| `git init [directory]`      | Creates new local repository                             |
| `git clone [repo]`          | Creates local copy of remote repository                  |
| `git add [directory]`       | Stages specific [directory]                              |
| `git add [file]`            | Stages specific [file]                                   |
| `git add -A`                | Stages all changed files                                 |
| `git add .`                 | Stages new and changed files, NOT deleted files          |
| `git add -u`                | Stages changed and deleted files, NOT new files          |
| `git commit -m "[message]"` | Commit everything that is staged                         |
| `git status`                | Shows status of changes as untracked, modified or staged |

#### Synchronization of Changes

| Key/Command   | Description                                                                           |
| ------------- | ------------------------------------------------------------------------------------- |
| `git fetch`   | Downloads all history from the remote branches                                        |
| `git merge`   | Merges remote branch into current local branch                                        |
| `git pull`    | Downloads all history from the remote branch and merges into the current local branch |
| `git push`    | Pushes all the commits from the current local branch to its remote equivalent         |

*Tip: `git pull` is the combination of `git fetch` and `git merge`*

#### Undo Changes

| Key/Command                 | Description                                                                                 |
| --------------------------- | ------------------------------------------------------------------------------------------- |
| `git checkout -- [file]`    | Replace file with contents from HEAD                                                        |
| `git revert [commit]`       | Create new commit that undoes changes made in [commit], then apply it to the current branch |
| `git reset [file]`          | Remove [file] from staging area                                                             |
| `git reset --hard HEAD`     | Removes all local changes in working directory                                              |
| `git reset --hard [commit]` | Reset your HEAD pointer to previous commit and discard all changes since then               |

#### Branches

| Key/Command                | Description                        |
| -------------------------- | ---------------------------------- |
| `git branch [branch]`      | Create a new branch                |
| `git checkout [branch]`    | Switch to that branch              |
| `git checkout -b [branch]` | Create and checkout new branch     |
| `git merge [branch]`       | Merge [branch] into current branch |
| `git branch -d [branch]`   | Deletes the [branch]               |
| `git push origin [branch]` | Push [branch] to remote            |
| `git branch`               | Lists local branches               |
| `git branch -r`            | Lists remote branches              |
| `git branch -a`            | Lists local and remote branches    |

See `~/.gitconfig`.

### OTHER COMMANDS

| Key/Command | Description |
| ----------- | ----------- |
| [command-a] \| [command-b] | Run command A and then pass the result to command B e.g ps auxwww \| grep google |
| grep [search_pattern] [file] | Search for all lines that contain the pattern, e.g. `grep "Tom" file.txt` |
| history n |  Shows the stuff typed – add a number to limit the last n items |
| code [directory/file] |  Open [directory/file] in Visual Studio Code |
|  ps -acx \| grep "[task]" |  Find the ID of [task] |
| kill [taskID] |  Terminate task with [taskID] |

## WE WILL TALK MORE ABOUT TERMINAL IN OUR NEXT LECTURE