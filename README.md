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
6. If you used the ISO file, then you don't have to look at the other tabs as the (my edited) .xml file basically did all of this for you, except for two tiny things. Go to "Tweaks" tab and check "All .NET Framework" and "HyperV Virtualization" and then click "Install Features". Then go to "Updates" tab and click "Security (Recommended) Settings.
### If you have the system already installed (don't want to do a clean install)
1. Run [Winutil](https://github.com/ChrisTitusTech/winutil) in powershell.
2. Make sure you first install a browser of your choice. After installing all of the apps you want, move on to "Tweaks" tab.
3. Click "Desktop" or "Laptop" button at "Recommended Selections", depending on which device you use.
4. In "Advanced Tweaks" check "Remove OneDrive", "Remove Microsoft Edge" (It's said Its not recommended because you won't have a web browser, and If you're following this tutorial, then you already have another browser), optionally you can also check "Disable UAC", but that's up to you. Make sure to change "DNS" to "Cloudflare".
5. "Customize Preferences" is entirely optional, but I would recommend enabling "Dark Theme", "Show File Extensions" and disabling "Bing Search in Start Menu" and "Sticky Keys". After that click "Add and Activate Ultimate Performance Profile" and at the end click "Run Tweaks".
6. Go to "Config" tab and check "All .NET Framework", "HyperV Virtualization" and "Legacy Media" and click "Install Features".
7. Go to "Updates" tab and click "Security (Recommended) Settings".
### Further Windows 11 Fixing
**Skip step 1 and 2 for now, since Rectify V4 is being released soon so It's better to wait for important bugs to be fixed**

After you've either followed the first tutorial or second one, this section is basically an extension of both scenarios (for Windows 11), basically what you do after you followed the tutorial above.
1. Download and install [Rectify](https://rectify11.net/)
2. During installation, make sure to not check "Themes" and "ExplorerFrame.dll.mun".
3. Run [Win11Debloat](https://github.com/Raphire/Win11Debloat).
4. Select option 2.
5. Select "3" If you didn't follow the ISO tutorial, otherwise you can skip to step 8.
6. Click "Only show installed apps".
7. Customize it to your needs, as it also removes stuff some people consider not bloatware like Bing's Weather. When you're done, click "Confirm".
8. Choose "n", If you followed the ISO tutorial, .xml file disables it, otherwise you should remember that winutil disabled it.
9. Next prompt is yours, decide for yourself. (Pinned apps)
10. Next prompt for disabling telemetry, choose "y", It is always worth checking If everything is disabled.
11. You of course want to get rid of ads in explorer, etc; choose "y".
12. Next one obviously choose "y". (Cortana)
13. Of course disable Co-Pilot, choose "y".
14. Definetely disable Recall, too much problems with it, choose "y".
15. For old context menu, Rectify already does that for you, so choose "n". **At the time of writing this, when Rectify is preparing for V4, choose "y".**
16. For the next prompts (changing something in services, explorer, context menu) always choose "n".
17. Congratulations, you successfully debloated, optimized and customized your Windows 11 with just practically 3 programs.
### Further Windows 10 Fixing
1. Run [Win11Debloat](https://github.com/Raphire/Win11Debloat). Yes, It is made for Windows 11, but it also works for Windows 10, just have to be more careful.
2. Select option 2.
3. Select "3" If you didn't follow the ISO tutorial, otherwise you can skip to step 8.
4. Click "Only show installed apps".
5. Customize it to your needs, as it also removes stuff some people consider not bloatware such as Bing's Weather. When you're done, click "Confirm".
6. Choose "n", If you followed the ISO tutorial, .xml file disables it, otherwise you should remember that winutil disabled it.
7. For the next prompt choose "n".
8. Obviously you want to be sure that all telemetry is disabled, so choose "y".
9. For all the other prompts, always choose "n" as they are all made for Windows 11 specifically.
10. Congratulations, you have debloated, optimized and customized your Windows 10 with just practically 2 programs.
# Extras
Soon

# License
MIT License
