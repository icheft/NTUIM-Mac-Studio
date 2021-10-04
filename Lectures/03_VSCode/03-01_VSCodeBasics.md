# Visual Studio Code Basics (with C++ Development Tricks)

## What Does Visual Studio Code Do?

+ Intelligent code completion
+ Debugging within the text editor
+ Fast and Powerful Editing
+ Code Navigation and Refactoring
+ Source Control

Why can't you use other editors like Atom, Sublime, XCode, Vim, etc.? Well, you can. It's just that this is what I use and I really love how easy, fast, and powerful VSCode is. 

**Extensions** and intuitive shortcuts make coding or even writing docs in general more fun and more productive. 


## Getting Started

### Flows

+ Explorer
+ Search
+ Source Control
+ Debug
+ Extensions
+ Split
+ Zenmode
+ Minimap
+ Find and Replace
+ Navigate Files
+ Move Around
+ Intellisense
+ Settings
    + font family
    + word wrap
    + format on save
    + Shortcuts
+ Extensions
    + Themes
    + Prettier
    + Highlight
    + advanced-new-file
    + Todotree
    + Markdown
+ Settings Sync
    + the old way (setting sync)
    + new way (integrated)


### Basics


+ Command Palette (`⇧⌘P`)
+ Keyboard shortcuts ([cheatsheet](https://code.visualstudio.com/docs/getstarted/tips-and-tricks#_keyboard-reference-sheets))
+ Quick Open (`⌘P`)
+ Command line
    + `$ code <project_name>`
+ Customization
    + Theme
    + Keyboard shortcuts
    + Settings
    + Extension

### Files and Folders

+ Integrated Terminal (`` ⌃` ``)
+ Sidebar (`⌘B`)
+ Side by side editing (`⌘\`)
+ Switch between editors (`⌘1`, `⌘2`, `⌘3`)
+ Close stuff (`⌘W`)

### Editing Hacks

+ Multi cursor selection (`⌥⌘↑` or `⌥⌘↓` or `⌥ click` or `⌘D`)
+ Box selection (`⇧ ⌥ drag`)
+ Lines
    + Copy line up / down (`⇧⌥↑` or `⇧⌥↓`)
    + Move line up and down (`⌥↑` or `⌥↓`)
+ Shrink / expand selection (`⌃⇧⌘←` or `⌃⇧⌘→`)
+ Symbols
    + Go to Symbol in File (`⇧⌘O` or `⌘P + @`)
        + add `:` to group symbols
    + Go to Symbol in Workspace (`⌘T`)
+ Formatting
    + Format on Save
    + `⇧⌥F`
+ Code folding
    + Click
    + `⌥⌘[` and `⌥⌘]`
+ Navigation/Delete
    + `⌘↑` or `⌘↓`
    + `⌘←` or `⌘→`
    + `⌥⌘←` or `⌥⌘→`
    + `⌘x`
    + `⌘⌫`
+ Markdown
    + Full Preview (`⇧⌘V`)
    + Side-by-side Preview (`⌘K V` key combination) 



## Code Faster

1. Open a Project via Command Line
2. Let go of your mouse 
    1. Command Pallette (`⌘⇧P`)
    2. File (`⌘P`)
3. Find Symbols
    1. `⌘F`
    2. `⌘⇧O`
    3. `⌘⇧.`
4. Move around
    1. Move to the front/end of the line `⌘←`/`⌘→`
    2. Skip a word `⌥←`/`⌥→` 
    3. Select a word `⇧⌥←`/`⇧⌥→` 
    4. Select letter `⇧←`/`⇧→` 
    5. Multi-editing
        1. Select re-occurring characters `⌘D` 
        2. `⌥ Click`
    6. Go to `⌃ G`
    7. Move line `⌥↑`/`⌥↓`
    9. Move and copy `⇧⌥↑`/`⇧⌥↓`
    10. Cut a line `⌘ X`
5.  Comments (`⌘ /`)
6.  Terminal
    1.  Toggle terminal ``⌃ ` ``
    2.  Navigate cursor
    3.  Clear Terminal
    4.  Create a task (`⇧⌘ B`)
    5.  Navigate through different terminals
        1.  `⇧⌘ ]`/`⇧⌘ [`
        2.  `⌥⌘ ←`/`⌥⌘ →`
7. Git
8. Snippets



## Get Your C++ Program Running

Let's first check what standard library version are your computer using.

```cpp
#include <iostream>

int main()
{
    std::cout << __cplusplus << std::endl;
}
```

By default, it should display `199711`, which means we are using C++98. 