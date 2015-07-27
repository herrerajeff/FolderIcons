# Folder Icons
Folder icons for Apple Dock organization.

## Categories:
* Music
* Design
* Web Design
* Productivity

![alt text](preview.png "Folder Icon Preview")


## For spaces on dock enter on terminal:
''' defaults write com.apple.dock persistent-apps -array-add '{"tile-type"="spacer-tile";}' '''


## To refresh dock to reflect changes:

''' killall Dock '''

Click and drag to move around, or drag off the dock to remove.


## Organizing applications into folders:
Best practice is using Aliases.
1. Right click an Application > Make Alias
1. Drag Alias into your folder
1. Drag folder from Finder into Dock

## Changing Folder Icons:
1. Right click folder > Get Info
1. Drag .icns file into the folder image on top left
1. If folder is already in Dock; run ''' killall Dock ''' in Terminal.
