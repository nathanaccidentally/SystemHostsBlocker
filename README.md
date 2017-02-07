# SystemHostBlocker
A simple host blocker built for speed.

SimpleHostBlocker is an alternative to an ad blocker that works system wide, even when outside of a browser. This means it can block ads and trackers and games and keep your privacy protected. All outside sources used for gathering hosts will be included here in the Readme file and/or the host file itself.

## Blocks Ads
As well as speeding up your browser, SystemHostsBlocker also blocks ads and trackers and can prevent you from spyware, malicious ads, and popups that take up your whole page. This works by blocking the host of the ads.

## Block Malaware
SystemHostBlocker will also help your computer to say safe from malaware and spyware by blocking malicious sources and sites that may or have been proven to include malaware.

**THE MAJORITY OF THE MALAWARE SITES WERE SOURCED FROM [MALEWARE DOMAIN LIST](http://www.malwaredomainlist.com/)**

# Downloads
1. [Unified Blocker (Blocks Ads, Trackers, Malicious Websites, all the goodies.)](https://github.com/nathanaccidentally/SystemHostBlocker/raw/master/hosts.zip)
2. [Updating Script for Windows](https://dl.dropboxusercontent.com/s/m46ei5iyki9yovs/updatehosts.bat?dl=0)
3. [iOS Unified Blocker](https://github.com/nathanaccidentally/SystemHostBlocker/raw/master/iosblocker.zip)

## Installation on Mac OS
**Method 1: (Manual)**

1. Download the blocker from the Downloads section of the readme file and extract it to your desktop
2. Right click the Finder icon in your application bar, and click 'Go to Folder'
3. Then type ```/private/``` and hit enter.
4. Right click on the folder titled ```etc``` and click 'Get Info'
5. In the bottom right corner, click the lock icon and type in an admin password to unlock it.
6. Then, at the bottom, chage all user permissions to read and write.
7. Hit the gear icon in the bottom left corner and click 'Apply to enclosed items' and hit confirm.
8. Next find your host file in the folder ```etc``` and double click to open in TextEdit.
9. Paste in the contents of the SystemHostBlocker host file **BELOW** the text already in the host file. Failure to do this will result in internet not working and a possible failure to boot (as i've been told.)
10. Save the host file and close TextEdit. You're all done!

## Installation on a Windows PC
**Method 1: (Manual)**

1. Download the blocker from the Downloads section of the readme file and extract it to your desktop
2. Open Explorer and go to ```C:\Windows\System32\drivers\etc\hosts```
3. Drag the hosts file from the zip download into the folder
4. Accept the replacement! You're done!

## Installation on iOS (Jailbroken)
1. Download iOS Unified Blocker from the Downloads section.
2. Open the zip file in iFile or Filza and unzip it.
3. Delete the hosts file in ```/etc/hosts```
3. Go back to the folder you unzipped and copy the file called ```systemhostblocker``` and paste it in ```/etc/```
4. Rename the newly pasted file to ```hosts``` and save it.

**OR**
1. Add the repo https://nathanaccidentally.github.io to Cydia
2. Install System Hosts Blocker **Using this method does not require the Uninstall step below!**

**UNINSTALLING:**

1. Delete the hosts file at ```/etc/hosts```
2. Go to the folder you unzipped when you downloaded the blocker (iosblocker.zip)
3. Copy the file titled ```stockhost```
4. Move it to ```/etc/``` and rename the file ```hosts```

## Updating Windows Script

1. Install [Git](https://git-scm.com/downloads)
2. Install the [Updating Script for Windows](https://github.com/nathanaccidentally/SystemHostBlocker#downloads)
3. Edit the file and replace ```(User)``` with your username.
4. Right click and run as admin. Your hosts will update!

You can keep running this and each time you do it will install the latest version of SystemHostsBlocker.
