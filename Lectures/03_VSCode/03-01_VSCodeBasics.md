# Visual Studio Code Basics (with C++ Development Tricks)

+ [Visual Studio Code Basics (with C++ Development Tricks)](#visual-studio-code-basics-with-c-development-tricks)
    + [What Does Visual Studio Code Do?](#what-does-visual-studio-code-do)
    + [Getting Started](#getting-started)
        + [Basics](#basics)
        + [Files and Folders](#files-and-folders)
        + [Editing Hacks](#editing-hacks)
    + [Code Faster](#code-faster)
    + [Extensions](#extensions)
    + [Get Your C++ Program Running](#get-your-c-program-running)

## What Does Visual Studio Code Do?

+ Intelligent code completion
+ Debugging within the text editor
+ Fast and Powerful Editing
+ Code Navigation and Refactoring
+ Source Control

Why can't you use other editors like Atom, Sublime, XCode, Vim, etc.? Well, you can. It's just that this is what I use and I really love how easy, fast, and powerful VSCode is. 

**Extensions** and intuitive shortcuts make coding or even writing docs in general more fun and more productive. 


## Getting Started



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

## Extensions

A list of my go-to VSC extensions.

+ [advanced-new-file](https://marketplace.visualstudio.com/items?itemName=patbenatar.advanced-new-file)
    ```
    Name: advanced-new-file
    Id: patbenatar.advanced-new-file
    Description: Create files anywhere in your workspace from the keyboard
    Version: 1.2.2
    Publisher: patbenatar
    VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=patbenatar.advanced-new-file
    ```
+ Anaconda Extension Pack
    ```
    Name: Anaconda Extension Pack
    Id: ms-python.anaconda-extension-pack
    Description: The Anaconda Extension Pack is a set of extensions that enhance the experience of Anaconda customers using Visual Studio Code
    Version: 1.0.1
    Publisher: Microsoft
    ```
+ [Bracket Pair Colorizer 2](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2)
    ```
    Name: Bracket Pair Colorizer 2
    Id: coenraads.bracket-pair-colorizer-2
    Description: A customizable extension for colorizing matching brackets
    Version: 0.2.1
    Publisher: CoenraadS
    VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2
    ```
+ [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)
    ```
    Name: Code Spell Checker
    Id: streetsidesoftware.code-spell-checker
    Description: Spelling checker for source code
    Version: 2.0.8
    Publisher: Street Side Software
    VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker
    ```
+ [Dracula Official](https://marketplace.visualstudio.com/items?itemName=dracula-theme.theme-dracula)
    ```
    Name: Dracula Official
    Id: dracula-theme.theme-dracula
    Description: Official Dracula Theme. A dark theme for many editors, shells, and more.
    Version: 2.24.0
    Publisher: Dracula Theme
    VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=dracula-theme.theme-dracula
    ```
+ [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
    ```
    Name: GitLens — Git supercharged
    Id: eamodio.gitlens
    Description: Supercharge the Git capabilities built into Visual Studio Code — Visualize code authorship at a glance via Git blame annotations and code lens, seamlessly navigate and explore Git repositories, gain valuable insights via powerful comparison commands, and so much more
    Version: 11.6.0
    Publisher: Eric Amodio
    VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens
    ```
+ [Jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter)
    ```
    Name: Jupyter
    Id: ms-toolsai.jupyter
    Description: Jupyter notebook support, interactive programming and computing that supports Intellisense, debugging and more.
    Version: 2021.8.2041215044
    Publisher: Microsoft
    VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter
    ```
+ [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
    ```
    Name: Markdown All in One
    Id: yzhang.markdown-all-in-one
    Description: All you need to write Markdown (keyboard shortcuts, table of contents, auto preview and more)
    Version: 3.4.0
    Publisher: Yu Zhang
    VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one
    ```
+ [Markdown Preview Enhanced](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced)
    ```
    Name: Markdown Preview Enhanced
    Id: shd101wyy.markdown-preview-enhanced
    Description: Markdown Preview Enhanced ported to vscode
    Version: 0.6.0
    Publisher: Yiyi Wang
    VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced
    ```
+ [Paste Image](https://marketplace.visualstudio.com/items?itemName=mushan.vscode-paste-image)
    ```
    Name: Paste Image
    Id: mushan.vscode-paste-image
    Description: paste image from clipboard directly
    Version: 1.0.4
    Publisher: mushan
    VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=mushan.vscode-paste-image
    ```
+ [Peacock](https://marketplace.visualstudio.com/items?itemName=johnpapa.vscode-peacock)
    ```
    Name: Peacock
    Id: johnpapa.vscode-peacock
    Description: Subtly change the workspace color of your workspace. Ideal when you have multiple VS Code instances and you want to quickly identify which is which.
    Version: 3.10.1
    Publisher: John Papa
    VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=johnpapa.vscode-peacock
    ```
+ [Polacode](https://marketplace.visualstudio.com/items?itemName=pnp.polacode)
    ```
    Name: Polacode
    Id: pnp.polacode
    Description: 📸  Polaroid for your code
    Version: 0.3.4
    Publisher: P & P
    VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=pnp.polacode
    ```
+ [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
    ```
    Name: Prettier - Code formatter
    Id: esbenp.prettier-vscode
    Description: Code formatter using prettier
    Version: 9.0.0
    Publisher: Prettier
    VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode
    ```
+ [Python Indent](https://marketplace.visualstudio.com/items?itemName=KevinRose.vsc-python-indent)
    ```
    Name: Python Indent
    Id: kevinrose.vsc-python-indent
    Description: Correct python indentation.
    Version: 1.14.2
    Publisher: Kevin Rose
    VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=KevinRose.vsc-python-indent
    ```
+ [Tabnine](https://marketplace.visualstudio.com/items?itemName=TabNine.tabnine-vscode)
    ```
    Name: Tabnine - Code Faster with the All-Language AI Assistant for Code Completion, autocomplete JavaScript, Python, TypeScript, PHP, Go, Java, node.js, Ruby, C/C++, HTML/CSS, C#, Rust, SQL, Bash, Kotlin, R
    Id: tabnine.tabnine-vscode
    Description: 👩‍💻🤖 JavaScript, Python, Java, Typescript & all other languages - AI Code completion plugin. Tabnine makes developers more productive by auto-completing their code.
    Version: 3.4.29
    Publisher: TabNine
    VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=TabNine.tabnine-vscode
    ```
+ [Todo Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree)
    ```
    Name: Todo Tree
    Id: gruntfuggly.todo-tree
    Description: Show TODO, FIXME, etc. comment tags in a tree view
    Version: 0.0.214
    Publisher: Gruntfuggly
    VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree
    ```
+ [vscode-imgur](https://marketplace.visualstudio.com/items?itemName=MaxfieldWalker.vscode-imgur)
    ```
    Name: vscode-imgur
    Id: maxfieldwalker.vscode-imgur
    Description: imgur integration for vscode
    Version: 0.0.3
    Publisher: Maxfield Walker
    VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=MaxfieldWalker.vscode-imgur
    ```
+ [Word Count](https://marketplace.visualstudio.com/items?itemName=ms-vscode.wordcount)
    ```
    Name: Word Count
    Id: ms-vscode.wordcount
    Description: Markdown Word Count Example - a status bar contribution that reports out the number of works in a Markdown document as you interact with it.
    Version: 0.1.0
    Publisher: Microsoft
    VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=ms-vscode.wordcount
    ```
+ [Word Count CJK](https://marketplace.visualstudio.com/items?itemName=holmescn.vscode-wordcount-cjk)
    ```
    Name: Word Count CJK
    Id: holmescn.vscode-wordcount-cjk
    Description: A word count extension that supports CJK languages.
    Version: 1.3.1
    Publisher: 张鹏程
    VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=holmescn.vscode-wordcount-cjk
    ```

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

