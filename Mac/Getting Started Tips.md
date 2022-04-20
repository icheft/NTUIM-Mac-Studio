#mac-studio


### Getting Started Tips

+ Settings
	+ Trackpad (System preference)
		+ tracking speed
		+ tap to click 
		+ gestures 
		+ drag (Accessibility)
		+ right click
	+ Unlocking Mac
	+ Hot Corners
	+ Keyboard and Shortcuts
	+ Computer name
	+ Control center and menu bar (`⌘`)
+ Usage
	+ **Preferences** (`⌘ + ,`))
	+ Shortcuts (More on that later)
	+ Spotlight (Alfred later)
	+ Finder
		+ show folder on top
		+ default 
		+ Finder Sidebar
		+ search stuff (Preferences/Advance)
		+ Hitting that option key (configuration files for debugs)
		+ status bar
	+ Screenshots
		+ remove shadows (using Terminal)
			```
			defaults write com.apple.screencapture disable-shadow -bool true
			killall SystemUIServer
			```
			to reverse change:
			```
			defaults write com.apple.screencapture disable-shadow -bool false
			killall SystemUIServer
			```
	+ Use stacks (desktop)
		+ using space
		+ using mouse (scroll) to preview all files
	+ Safari
		+ Customize your Safari page (bottom-right corner)
		+ Status bar (View/Show Status Bar)
		+ Develop Menu (for poweruser) (Preferences/Advanced/Show Desktop menu in menu bar)
	+ Dock
		+ Remove items 
		+ Resizing the dock
		+ Position (system preferences)
		+ Hide and show (also with the menu bar) → allow more screen assets
		+ Add empty space
			```
			defaults write com.apple.dock persistent-apps -array-add '{"tile-type"="spacer-tile";}'; killall Dock
			```