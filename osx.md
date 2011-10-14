# OS X Tips

## Change default screenshot location
To change the default location for screen captures so they get saved in a specific location instead of cluttering the desktop, you need to use the defaults command in the Terminal to change the path. It can be done like this:

1. Create the folder in which you want the screen captures to be saved in the location of your choice.

2. Open a Terminal window and type this:
> defaults write com.apple.screencapture location /Full/Path/To/Folder

3. Log out and log back in, and the change will have taken effect.

