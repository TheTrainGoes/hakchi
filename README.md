# hakchi - engrish

Since version 2.30 you can turn your SNES Mini into NES Mini/Famicom Mini and vice-versa on the fly!

Since version 2.30 you can now turn your SNES Mini into a NES Mini/Famicom Mini and vice-versa on the fly!  You can even change the SNES Mini into a Super Famicom Mini, or a Japanese Super Famicom Mini!

—

It's easy to do. First of all, you need firmware image (NAND-B partition image) of target console (don't confuse it with kernel image!). So if you want to boot NES Mini image on SNES Mini you need firmware image of NES Mini. Usually it has ".hsqs" extension. It's not legit to share it on the net because it contains games and other copyrighted data. You can dump it yourself using "Kernel -> Dump decrypted NAND-B partition" command in menu.

It's easy to do. First of all, you need the firmware image (NAND-B partition image) of the target console (don't confuse this with the kernel image!). So if you want to boot the NES Mini image on a SNES Mini you will need the firmware image of an NES Mini. Usually it has the ".hsqs" extension. It's not legit to share it on the net because it contains games and other copyrighted data. You can dump it yourself using the “Kernel -> Dump decrypted NAND-B partition" command in Kernel menu.

—

Of course you need real console to do it. So if you want to boot NES Mini on SNES Mini, you need to dump decrypted NAND-B partition image from NES Mini. Probably you don't have NES Mini if you want to do it, so you can just find this image on torrents or ask your friends with target console to dump it.
Add this ".hsqs" file as usual game: via "Add more games" button or just drag'n'drop it on hakchi2 window.

Of course you need a real console to do this dump. So if you want to boot an NES Mini on your SNES Mini, you will need to dump the decrypted NAND-B partition image from the NES Mini.  If you do not have an NES Mini and still want to do it, you should be able to find the image through torrents, or ask your friends with target console to dump it for you.
Add this ".hsqs" file as you would normally add a game: via "Add more games" button or just drag'n'drop it onto the hakchi2 window.

—

You can rename it or assign image to it, just like with any game.

You can rename it and assign an image to it, just like with any other added game.

—

Please note that command line must begin with "/bin/hsqs".
Now, sync. It should work already.

Please note that command line must begin with "/bin/hsqs".
Now, sync. It should work already.

—

But you want to customize your virtual console too, isn't it? At least you should add shortcut to return to original firmware. To do it select your target console using menu:

But you want to customize your virtual console too? At the very least, you should add a shortcut that lets you return to the original firmware. To do this, select your target console using Settings -> Console type -> (choose your console type).

—

So if you have SNES Mini and want to boot NES Mini firmware on it, select "NES Mini" in menu. Now you can customize games for target console. You can add any games as usual.

So if you have an SNES Mini and want to boot to the NES Mini firmware on it, select "NES Mini" in the menu. Now you can customize games for the target console. You can add any games as usual.

—

But first of all, do right click on games list and select "Create custom command".

But first of all, right click on the games list and select "Create custom command".

—

Now type into command line field "/bin/hsqs auto" (without quotes). This command will return your console to original firmware. Also you can change name and image for this menu item.

Now type into the command line field "/bin/hsqs auto" (without quotes). This command will return you to your consoles original firmware. Also you can change name and image for this menu item.

—

Connect your console to PC, turn it on, wait for green icon in lower left corner and sync. Now you can switch back to original firmware.

Connect your console to your PC, turn it on, wait for the green icon in lower left corner and then sync. Now you can switch back to original firmware.

—

That's all! Now you can switch between different consoles and customize every virtual console individually.
Please note:
* All consoles/firmwares shares additional modules, so you don't need to install them multiple times.
* All consoles/firmwares shares same configuration with one exception: global command line arguments.

That's all! Now you can switch between different consoles and customize every virtual console individually.
Please note:
* All consoles/firmwares share added modules, so you don't need to install them multiple times.
* All consoles/firmwares share the same configurations, with one exception: global command line arguments.
