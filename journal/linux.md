# My Journey from Windows to Linux

![LinuxMint](https://img.shields.io/badge/Linux_Mint-87CF3E?style=flat&logo=linux-mint&logoColor=white)
![Manjaro](https://img.shields.io/badge/Manjaro-35BF5C?style=flat&logo=Manjaro&logoColor=white)

<p align="justify">
	After the end of support for windows 10 was announced I decided it was a time to move on to linux. However the switch happened a little bit earlier than I originally planned. I happened to buy a new laptop from sale that had windows 11 installed on it. I was not going to use it so it was time to install linux.
</p>

## Choosing the distribution
<p align="justify">
	However choosing the distribution was a little bit harder than I imagined. I obviously wanted something stable and somewhat easy to use. A few distributions I considered were debian, fedora, manjaro and also linux mint which is based of debian. Stability was my reason to steer away from manjaro.
</p>

<p align="justify">
	Another critical point of my decision was that there were a couple of applications I needed to get working, such as vscode and intellij. I found out that most of the software, that work on linux, are available for debian and mint. That dropped fedora of my list of candidates. 
</p>

<p align="justify">
	After going through my options I decided to go with linux mint, with cinnamon desktop, because I read it was a little bit more simple to use than debian.
</p>

## First install of linux on a physical machine
<p align="justify">
	I decided to go with linux mint, as I already mentioned. I read the installation guide, downloaded the iso and verified it. Luckily on the linux mint forums there were very helpful points on how to verify the iso on windows. I flashed the iso onto the usb stick and disabled the secure boot. After that the live usb started right up and the installer was extremely simple to use. The install even succeeded on the first try.
</p>

<p align="justify">
	I absolutely love the look of the cinnamon desktop. It look quite similar to the desktop on windows 10 of which I am very familiar with. However cinnamon has so much more customization options. I also like the graphical software manager on linux mint very much. There are quite a lot of applications available in single click of a button. All of the applications, I have installed so far from the software manager, have worked out of the box. However it naturally does come with drawbacks, that is that the versions of the applications are quite old.
</p>

<p align="justify">
	Linux mint is also a lot lighter than windows. Another thing is the updating. I always hated when windows started updating suddenly without any warning when I was doing something else. That completely killed the performance of the computer. There is nothing like that on linux mint, all the updates must be specifically installed with admin priviledges.
</p>

<p align="justify">
	All in all linux mint is a very good distribution from someone coming from a windows background. Installation process is very simple and there are good instructions for doing so. Mint also has a big community so solutions to most of the problems can be found on the internet straight away.
</p>

## Time to install linux on my pc
<p align="justify">
	Stability was not a problem this time so I decided to go with manjaro with kde desktop this time because it is arch based. That means it has access to very up to date software. I knew I was not ready for arch just yet so manjaro seemed like a good compromise. Install process was extermely simple again.
</p>

<p align="justify">
	Manjaro also has a graphical software manager, just like linux mint. However I was simply astounished the first time I had a look what is on the manjaro's graphical software manager. There are naturally drawbacks as well. All the software will simply not work out of the box. Luckily for me pretty much all the software I absolutely needed worked without much of a hassle.
</p>

## Issues I faced with linux so far
### Latex on Manjaro
<p align="justify">
	I could not get latex to work properly on manjaro. This is of course a quite a small problem and mostly due my limited knowledge. However by googling I found a lot of people having the exact same problem with manjaro/arch. I ran into a few solutions as well saying like "I installed these 30 different packages and it started to work". It might have worked for me as well but I did not need to get latex working that badly to install some random packages. Comparing to linux mint latex worked out of the box, just needed to install it.
</p>

### Boot failure and journald on Manjaro
<p align="justify">
	I decided to install linux to my old windows 10 laptop as well. Tried debian, tried fedora tried mint nothing worked. After the linux mint install failed my laptop would not boot anymore from usb. Tried changes basically all the bios settings (secure boot, fast boot, csm, etc.) I simply could not get the laptop to boot anymore. So I completely dismantled it and put it back together to reset the bios. Miraculously I managed to get the laptop to boot and installed manjaro on it. However manjaro did not quite work properly, journald got stuck on activating state and was using burning my cpu which caused freezes after awhile. Also the system was unbale to reboot or shutdown, only the power button worked for shutdown. Surprisingly it always booted right up but the same problem occured everytime. After doing some research I managed to find a temporary fix, which was to set "pci=nomsi" on the grub boot loader. I could not however get the grub to update so need to set the "pci=nomsi" on every boot. I am still happy with the solution, at least the laptop is usable (other distributions I have tried still do not work at all). 
</p>
