## XFX GPU Problem with Hackintosh

> XFC had been report as problematic GPU realate with many referencs
> - [From Opencore](https://dortania.github.io/GPU-Buyers-Guide/modern-gpus/amd-gpu.html#polaris-10-and-20-series)
> - [TonyMac Thread](https://www.tonymacx86.com/threads/no-fix-xfx-rx560-4gb-cannot-work.225772/)

![enter image description here](https://raw.githubusercontent.com/LyhourChhen/opencore-configuration-ryzentosh/master/Guide-for-XFX/screenshots/Screen%20Shot%202020-10-31%20at%209.08.01%20AM.png)

**Stories** I been deal with installation for a week, day and night becuase i really want to make it done but still no light of working while i read and recheck all about my EFI and configuration in OC, and double inspect again in OC sentry, everything is fine and i always `Can't found bootstrap`. So i decided to switch to my old GPU which i known it did not work becuase it Nvidia 1050ti, But what? Miracle happend, the intallation has been preceed just need some juked of configuration, the installation is completed, any hardware is pretty fine so i think time to switch GPU to AMD since AMD is support by the new of MAC-OX, Unfortunately it didn't `Kernal Pinic Occured`, I have no idea what the hell is this, so i go eveyplace both forum, facebook, group but still no sign of working, until one guy said **XFX** won't support unless i make **VBIOS**, so i did and eveything fine now.
But what if you accidently bought it like me, anythings to Hack it work...?

### Solution
>  This solution may not perfect since i have glicted many time, but i can rock it to work and can be acceptable. 

- Tools and File Patch
	- [VBIOS PATCH (Only for rx560 4gb - you can research or find one for your. pls don't forget to backup your vbios incase problem occured)](https://www.techpowerup.com/vgabios/192320/sapphire-rx560-4096-170419)
	- [ATI Flash (To flash room)](https://www.techpowerup.com/download/ati-atiflash/)

- Precess (Window)
	- Unzip ATI to someplace.
	- open CMD as Admin 
	- move your patch to the same folder with ATI
	- Navigate to your folder with CMD command [Sample](https://www.youtube.com/watch?v=RPODNcIq5z4)
	- `amdvbflash -f -p 0 nameofyourrom.rom`
- Hope it work!!


### @2020 LyhourChhen


