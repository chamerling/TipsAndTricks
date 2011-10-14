# iOS dev tips and tricks

## Reload UI in the main thread
[self.tableView performSelectorOnMainThread:@selector(reloadData) withObject:nil waitUntilDone:YES];

## Open App from URL
[[UIApplication sharedApplication] openURL:webURL];

## Set the company name in XCODE
From a terminal :
defaults write com.apple.Xcode PBXCustomTemplateMacroDefinitions '{ORGANIZATIONNAME="chamerling.org";}'

## Git ignores for Xcode
http://stackoverflow.com/questions/6564257/cant-ignore-userinterfacestate-xcuserstate
git rm -r --cached xcdebugger/
git commit -m "Removed file that shouldn't be tracked"


