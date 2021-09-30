# macOS on the Go


+ [macOS on the Go](#macos-on-the-go)
    + [From Windows to macOS](#from-windows-to-macos)
        + [Empty Desktop](#empty-desktop)
        + [Eye-Opener](#eye-opener)
        + [Specific Apps Demo](#specific-apps-demo)
    + [Random Tips and Tricks](#random-tips-and-tricks)
        + [Apple Ecosystem](#apple-ecosystem)
        + [Backups and Time Machine](#backups-and-time-machine)
    + [Useful Apps](#useful-apps)
        + [Preinstalled Apps](#preinstalled-apps)
        + [Programming/Coding](#programmingcoding)
        + [Productivity](#productivity)
        + [Utilities](#utilities)
        + [Demo](#demo)

## From Windows to macOS

### Empty Desktop

+ System Preferences/Settings
    + System Preferences
    + Menu and Menu bar
    + Apps Preferences/Settings
+ Spotlight (`⌘ ␣`) → The MOST IMPORTANT FEATURE! Keep it in mind for now!
    + Search
+ Dock
    + Running Apps shown 
        ![Image](https://i.imgur.com/mk5u1xK.png)
    + Empty Space (**First Encounter with Terminal!**)
        ```
        defaults write com.apple.dock persistent-apps -array-add '{"tile-type"="spacer-tile";}'; killall Dock
        ```
+ Trackpad
    + Make use of your Trackpad → System Preferences
        + Speed
        + Taptic
    + Option + Click
    + Right Click

### Eye-Opener

+ Apps
    + App Store
    + Closing the Program/Application
        + Close vs. Quit (Shortcut and stuff)
        + Status on Dock
    + Office Equivalences
    + Finder (See next parent list)
    + Launch Apps
        + Spotlight
    + Switch/Quit between Apps (Shortcut)
        + Three Fingers Up: Show all windows
        + Three Fingers Down: Show all windows within the same app
    + Uninstall Apps
+ Finder
    + Like File Explorer in Windows
    + Always running
    + Home Directory
    + Download
    + Folder Shortcuts
        + Can also put things in the dock
    + Creating/Renaming/Copying/Moving/Deleting Files/Folders
        + Creating 
            + Files using Terminal
            + Folders using Right Click/Shortcuts
        + Renaming
            + Return Key
            + Double Click
            + Right Click
        + Copying
            + `⌘ C` `⌘ V`
            + Right Click
            + Drag
        + Moving
            + `⌘ C` `⌘ ⌥  V`
            + Right Click + Option
        + Deleting
            + `⌘ ⌫`
            + Right Click
    + Show Hidden Files (`⌘ ⇧ .`)
    + Views/Perspectives (Use `⌘ 1` or `2` `3` `4` to change view settings)
+ Resizing Windows 
    + The Old Ways
    + Magnet
+ Scrolling
    + Don't have to "focus" on the to-be-scrolled windows
+ Keyboard Shortcut
    + Screenshot
    + Use Safari to demonstrate
+ Files (Using Pages)
    + Opening a New File
    + Input Source
    + Save Files (Save As...)
+ Notification Center



### Specific Apps Demo

+ Safari
    + Open a New Window
    + Open a New Tab
    + Close an Open Tab
    + Search
    + Bookmarks
    + Backward/Forward


## Random Tips and Tricks

+ Desktops
+ Dock
    + Hide-and-Show
    + Resizing (Directly from Dock; System Preferences)
+ Screenshots
    + Shortcut
    + No Floating Thumbnails
    + Copy to Clipboard
    ```
    defaults write com.apple.screncapture disable-shadow -bool true
    defaults write com.apple.screencapture type JPG (originally in PNGs; size-wise difference)
    killall SystemUIServer
    ```
+ PDFs
+ Hot-corners
    + Put display to sleep
+ Shortcuts
    + Text Shortcuts
    + Keyboard Shortcut Customizations
+ Volume/Brightness
    + `⌥ ⇧` + Volume/Brightness
    + Night Shift
+ **Alfred is Legit** 🔥🔥🔥
+ Option Key (`⌥`)
+ Customization
    ![Image](https://i.imgur.com/7CN9ggQ.png)
    + Path Bar (`View > Show Path Bar`)
    + Status Bar (`View > Show Status Bar`)
+ Three-Finger Dragging

### Apple Ecosystem

+ Apple Watch Unlock


### Backups and Time Machine

+ RAID1 Setting
+ Time Machine Setting
+ CCC


## Useful Apps 

### Preinstalled Apps

+ Safari
+ Automator
+ Notes
+ Terminal
+ XCode → Visual Studio Code
+ Time Machine

### Programming/Coding

+ Visual Studio Code
+ iTerm2

### Productivity

+ OmniFocus
+ Notability
+ iThoughtsX
+ MoneyWiz 2
+ Day One
+ Freedom
+ PDF Expert

### Utilities

+ Alfred (Spotlight's alternative)
+ Bartender
+ Magnet
+ Dynamo
+ Cheatsheet
+ [AlDente](https://github.com/davidwernhart/AlDente)
+ Parallels
+ HazeOver
+ Carbon Copy Cloner
+ OnyX
+ Rocket (Emoji)
+ iStat Menus
+ The Unarchiver
+ Yoink (which I didn't use at the time of this tutorial)
+ Capto

### Demo

+ KeyCastr
+ MousePose