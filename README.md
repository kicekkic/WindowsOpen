# Introduction
One day I thought that I have enough of the hidden telemetry and bloatware that Microsoft gives us in our system so I decided to make my own (there are lots of them) collection of stuff you can do to optimize your computer. I will be attaching scripts and websites that I researched and made sure that they are safe. As I said earlier, there are thousands of other repositories like that but this one is my own because honestly, you can't really trust people these days - and I know that Im also on the same level of trustworthiness as other people but Its up to you what you will do with the information here (and I have no idea how you found my rep).
## The Actual Tutorials
Select the tutorial depending on your situation.
### If you didn't install the system yet
1. Download [Rufus](https://rufus.ie).
2. Either choose Windows 10 or 11, then continue on - do not check anything in "Customize Your Windows Experience".
3. Download the .xml file from this repo and then paste it into the USB with your system.
4. Insert it into your PC and run it. The .xml file contain all tweaks to disable and uninstall unnecessary software and telemetry, you can make your own by going to this [repo](https://github.com/memstechtips/UnattendedWinstall/tree/main).
5. When you finally get to the Desktop screen, connect to internet and run "LAUNCH-CTT-WINUTIL.ps1", it will give you a window with various programs you can install with basically one click.
6. If you used the ISO file, then you don't have to look at the other tabs as the .xml file basically did all of this for you, except for one tiny thing. Go to "Tweaks" tab and check "All .NET Framework" and "HyperV Virtualization" and then click "Install Features". Then go to "Updates" tab and click "Security (Recommended) Settings.
### If you have the system already installed (don't want to do a clean install)
1. Run [Winutil](https://github.com/ChrisTitusTech/winutil) in powershell.
2. Make sure you first install a browser of your choice. After installing all of the apps you want, move on to "Tweaks" tab.
3. Click "Desktop" or "Laptop" button at "Recommended Selections", depending on which device you use.
4. In "Advanced Tweaks" check "Remove OneDrive", "Remove Microsoft Edge" (It's said Its not recommended because you won't have a web browser, and If you're following this tutorial, then you already have another browser), optionally you can also check "Disable UAC", but that's up to you. Make sure to change "DNS" to "Cloudflare".
5. "Customize Preferences" is entirely optional, but I would recommend enabling "Dark Theme", "Show File Extensions" and disabling "Bing Search in Start Menu" and "Sticky Keys". After that click "Add and Activate Ultimate Performance Profile" and at the end click "Run Tweaks".
6. Go to "Config" tab and check "All .NET Framework", "HyperV Virtualization" and "Legacy Media" and click "Install Features".
7. Go to "Updates" tab and click "Security (Recommended) Settings".
### Further Fixing
After you've either followed the first tutorial or second one, this section is basically an extension of both scenarios, basically what you do after you followed the tutorial above.
1. Download and install [Rectify](https://rectify11.net/)
2. In the installation menu, customize it to your needs.
3. Congratulations, you have debloated and optimized your Computer successfully.

# License
Do whatever you want with this.

https://www.youtube.com/watch?v=mwUBeqHqSas
