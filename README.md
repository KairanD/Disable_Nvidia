# What is this script for?

If you have an old laptop with Nvidia graphics (Kepler architecture or older), you'll probably find problems when trying to run up-to-date or rolling release Linux distros with the proprietary driver. This happens because old versions of the driver are often left unsupported by Nvidia, resulting in compilation errors with newer kernel versions. Fixes are usually late.

On the other hand, the Nouveau open source driver is not able to provide proper energy management, resulting in overheating problems and low battery life. So, what do you choose? Overheating (Nouveau) or system breakages (Nvidia proprietary)?

Well, there is a third way. These cards are generally not great performers for today standard's. If you're not using your computer for games or any specific work that relies on the card, you can simply disable it to use the laptop with only the integrated graphics adapter (iGPU). This is what this script does.

# Disclaimer:

I wrote this guide after collecting information from some sites and wikis. It may result in system instability or even breakage. And, of course, you'll be unable to use the dedicated Nvidia card (unless you undo the changes). Use it at your own risk.
