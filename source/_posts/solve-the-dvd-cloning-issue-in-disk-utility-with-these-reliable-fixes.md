---
title: Solve the DVD Cloning Issue in Disk Utility with These Reliable Fixes
date: 2024-10-03T22:39:49.169Z
updated: 2024-10-06T01:52:10.964Z
categories:
  - macxdvd
thumbnail: https://thmb.techidaily.com/2c72878e4c5b851b7d621c520b7075b9d80e911d0e1db9a60b0603055e403b62.jpg
---

## Solve the DVD Cloning Issue in Disk Utility with These Reliable Fixes

[![macx video converter pro icon](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/icon11.png)](https://tools.techidaily.com/macxdvd/products/)

* [MacX Video Converter Pro](https://tools.techidaily.com/macxdvd/products/)
* [Guide](https://tools.techidaily.com/macxdvd/products/)
* [Support](https://tools.techidaily.com/macxdvd/products/)
* [Free Download](https://tools.techidaily.com/macxdvd/products/)

![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/icon7.png) [Home](https://tools.techidaily.com/macxdvd/products/) \> [DVD](https://tools.techidaily.com/macxdvd/products/) \> [Decrypt DVD](https://tools.techidaily.com/macxdvd/products/) \> Disk Utility Won't Copy DVD

## Fix Disk Utility DVD Copy Errors and Copy Protected DVDs

![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/icon6.png) By [Bella Brown](https://tools.techidaily.com/macxdvd/products/) ｜Last updated on September 26, 2023

* [![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/share-fa.jpg)](https://www.facebook.com/sharer/sharer.php?u=https://www.macxdvd.com/mac-dvd-video-converter-how-to/disk-utility-wont-copy-dvd-fixed.htm)
* [![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/share-tw.jpg)](https://twitter.com/intent/tweet?url=https://www.macxdvd.com/mac-dvd-video-converter-how-to/disk-utility-wont-copy-dvd-fixed.htm&text=)
* [![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/share-email.jpg)](https://www.macxdvd.com/mac-dvd-video-converter-how-to/mailto:info@example.com?&subject=&body=https://www.macxdvd.com/mac-dvd-video-converter-how-to/disk-utility-wont-copy-dvd-fixed.htm)
* [![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/share-in.jpg)](https://www.linkedin.com/shareArticle?mini=true&url=https://www.macxdvd.com/mac-dvd-video-converter-how-to/disk-utility-wont-copy-dvd-fixed.htm&title=&summary=&source=)

_"I am trying to copy a DVD using Disk Utility. I do all the steps: open Disk Utility > Choose DVD > New Image From Name of Disc, Save, all that. But every time it copies, it inevitably fails, giving the same error message 'The operation couldn't be completed. (com.apple.diskutility error 3.)'."_

This is a user on Apple Communities who can't copy a DVD with Disk Utility. In fact, besides com apple diskutility error 3, there are many other errors like operation failed with status 5, error status 27, "cannot copy - input/output error", stuck screen loading disks with a spinner graphic, etc. that prevent Disk Utility to copy a DVD on Mac successfully. In this post, we're going to solve all these Disk Utility DVD copy errors and let you copy protected DVDs on Mac without trouble.

![disk utility copy DVD error](https://www.macxdvd.com/mac-dvd-video-converter-how-to/article-image/disk-utility-error.jpg) 

## Understand the Limitations of Disk Utility

Before we start to fix Disk Utility DVD copy errors, there are some limits that you should know. Make sure they are not the reasons to "Disk Utility will not copy DVD" issues. 

1. Apple products including iDVD, DVD Studio Pro, Disk Copy, and Disk Utility **can't copy DVDs with protections**. So if you're trying a commercial disc, it may give your problems like cannot copy - input/output error. If you want to [copy protected DVD to Mac](https://tools.techidaily.com/macxdvd/products/), you will the help from a third-party helper.
2. You **can't** burn DVD using Disk Utility anymore if you're running **OS X 10.11 or later** as Apple has removed the burning functionality since El Capitan.
3. You should know that Disk Utility is a great tool to create disk image of a DVD, portable drive or desktop drive. The CDR image is a DVD/CD Master file used to create DVD copies, **not a playable** video format or the like.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886003/19272" target="_top" id="1886003">
  <img src="//a.impactradius-go.com/display-ad/19272-1886003" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886003/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## When Disk Utility will Not Copy DVD, You May Try:

**1\. Kill the FSCK process** 

Killing the FSCK process has solved many Disk Utility DVD copy errors, especially errors like Disk Utility won't load discs... 

in terminal  
 ps -ef | grep fsck

* $ ps -ef|grep fs
* 0 55 1 0 3:39PM ?? 0:03.45 /System/Library/Frameworks/CoreServices.framework/Versions/A/Frameworks/FSEvent s.framework/Versions/A/Support/fseventsd
* 0 110 1 0 3:39PM ?? 0:00.02 autofsd
* 0 126 1 0 3:39PM ?? 0:01.44 /usr/sbin/cfprefsd daemon
* 501 326 1 0 3:39PM ?? 0:01.47 /usr/sbin/cfprefsd agent
* 0 14893 86 0 4:45PM ?? 1:41.64 /System/Library/Filesystems/hfs.fs/Contents/Resources/./fsck\_hfs -y /dev/disk2s2
* 501 18726 3828 0 5:02PM ttys000 0:00.00 grep fs

Then sudo kill the fsck process. Once the fsck process is killed, the Disk Utility should restart and copy the DVD as expected. 

**2\. Reset PRAM/NVRAM or SMC**

Resetting the PRAM/SMC is a way to clear corrupted files related to stuff like RAM disk, Disk cache, Startup disk, etc. It can also help solve many DVD playback and copy problems on Mac like [Mac DVD player not responding](https://tools.techidaily.com/macxdvd/products/). Also there are users reported that they successfully solved Disk Utility DVD copy errors by resetting them.

Reset the SMC: shut down the Mac > press and hold the power button for 10s and restart > press and hold the right Shift, Option and left Control key for 10s > keep holding the keys and then press and hold the Power button for 10s > then release and wait for seconds > restart. 

Reset the NVRAM/PRAM: shut down the Mac > press the Power button > before you see a grey screen, press the Command, Option, P and R keys at the same time until you see a grey screen > keep holding the keys until the Mac restarts and hear a second startup chime > release.

**3\. Restart the computer in Safe Mode**

Restart the computer in Safe Mode: restart your Mac, press and hold the Shift key when it lights up > release it when you see the login screen. Then restart again and check if it solves com apple diskutility error 3 DVD/status 5 or the like. 

If this doesn't help, then boot to the Recovery Mode: Restart the computer and press and hold down the COMMAND and R keys once you hear the startup chime. Keep holding the keys until the Apple logo appears. After several minutes, the Utilities menu screen appears.

**4\. Copy DVD from folder**

If Disk Utility will not copy DVD to disk image, as reported by a user on Apple Communities, you can copy all the contents of the DVD to, for example VIDEO\_TS folder or ISO image (but since El Capitan, you can no longer just drag disk images from the Finder into Disk Utilities; instead, you must choose the relevant image using the File > Open Disk menu). Then use Disk Utility > click New Image > Create new image from folder.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2126493/26400" target="_top" id="2126493">
  <img src="//a.impactradius-go.com/display-ad/26400-2126493" border="0" alt="https://techidaily.com" width="640" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2126493/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## If Disk Utility will Not Copy DVD, Try MacX (Any DVD Supported) 

The above are the methods that are reported to be efficient to fix part of Disk Utility DVD copy errors like com apple diskutility error 3, status 5, etc. Trying the above fixes may cost you a lot of time and energy as some of them are quite complicated. Most importantly, they won't fix all the "Disk utility won't copy DVD" issues. If you can't fix it or want to bypass the limits of Disk Utility (Disk Utility won't copy protected DVDs, limited output formats), use[**MacX DVD Ripper Pro**](https://tools.techidaily.com/macxdvd/products/) to copy DVDs.

* Four DVD copy modes: clone DVD to ISO image in 1:1 ratio, copy the main title/full title to MPG, backup DVD to MKV.
* Create digital copies of DVDs in any formats: MP4, HEVC, MOV, AVI, WMV, MP3, other video/audio formats and Mac, PC, iPhone, iPad, TVs, 350+ other devices.
* Support DVDs of any types: discs protected with Region, RCE, CSS, Disney-X project, Sony ARccOS, UOPs, etc. as well as scratched DVDs, latest titles, workout DVDs, etc.
* Unique Level-3 Hardware Acceleration enables 47x real-time faster to convert DVD to MP4!
* Safe Mode and special title check mechanism bypass any errors with Disk Utility when you copy DVD.

[Download for Mac](https://tools.techidaily.com/macxdvd/products/) [Download for PC](https://tools.techidaily.com/macxdvd/products/) 

**Step 1.** Insert the DVD that Disk utility will not copy into the computer. Run the program and click the Disc button to load the DVD. 

**Step 2.** Once loaded, it will automatically detect the correct title of the DVD and then pop up a window asking you to select and output format. 

* To copy a DVD to DVD: select DVD Backup > [copy DVD to ISO Image](https://tools.techidaily.com/macxdvd/products/). You will get a 1:1 image copy and then you can burn it to a blank disc using Finder.
* To simply copy a DVD to Mac: select Backup > Main Title/Full title will do. These options are faster than ISO image and will contain the main content of the DVD.
* To copy a DVD for eaier playback on other devices: select General Profiles > choose MP4 or other video formats. Or you can find the exact profile for your device.

![Copy a DVD for macOS](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../mac-dvd-ripper-pro/step-images/dvd-to-iso-700.jpg) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151893/7443" target="_top" id="2151893">
  <img src="//a.impactradius-go.com/display-ad/7443-2151893" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151893/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**Step 3.** Click Run to start the DVD copy.

_Disclaimer: This post is to help users whose Disk Utility will not copy DVD or get com apple diskutility error 3 status 5, input/output error, or the like. It does not in any way advocate copying a DVD for any commercial or other illegal use. Please consult the law in your country before you copy any disc._

ABOUT THE AUTHOR

![author- bella](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/bella.png) 

[Bella Brown ![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/share-in1.jpg)](https://www.linkedin.com/in/bella-brown-920145104/) 

Bella has been working with DVD digitization for over 12 years. She writes articles about everything related to DVD, from disc drive, DVD copyright protection, physical structure, burning and backup tips. The unceasing passion of DVD movies helps her build a rich DVD library and ensure a practical solution to address almost all possible DVD issues. Bella is also a crazy fan for Apple products.

Related Articles

![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/pic7.jpg)

[Top 10 Free DVD Copy Software Burning Freeware for PC Mac](https://tools.techidaily.com/macxdvd/products/) 

![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/pic6.jpg)

<!-- affiliate ads begin -->
<span id="1977032">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977032.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977032">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977032.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977032%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977032/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

[DVD Won't Play with "Supported Disc Not Available" Error](https://tools.techidaily.com/macxdvd/products/) 

![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/pic5.jpg)

[Fix "Can't Rip Lionsgate DVDs" or Rip Protected DVDs Smoothly](https://tools.techidaily.com/macxdvd/products/) 

![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/pic4.jpg)

[Best DVD Decrypters for Mac - 100% Work to Rip Protected DVD Movies](https://tools.techidaily.com/macxdvd/products/) 

![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/pic3.jpg)

[How to Rip Protected DVD Movies on Mac for FREE](https://tools.techidaily.com/macxdvd/products/) 

![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/pic2.jpg)

[Fixed: Can't Rip Sony DVDs with Bad Sectors](https://tools.techidaily.com/macxdvd/products/) 

![Digiarty Software](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../icon/logo.png) 

Digiarty Software, Inc. (MacXDVD) is a leader in delivering stable multimedia software applications for worldwide users since its establishment in 2006.

### Hot Products

* [MacX DVD Ripper Pro](https://tools.techidaily.com/macxdvd/products/)
* [MacX Video Converter Pro](https://tools.techidaily.com/macxdvd/products/)
* [MacX MediaTrans](https://tools.techidaily.com/macxdvd/products/)

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657399/16446" target="_top" id="1657399">
  <img src="//a.impactradius-go.com/display-ad/16446-1657399" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1657399/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Tips and Tricks

* [DVD Topics >>](https://tools.techidaily.com/macxdvd/products/)
* [Video Solutions >>](https://tools.techidaily.com/macxdvd/products/)
* [Data Transfer >>](https://tools.techidaily.com/macxdvd/products/)
* [Online Video >>](https://tools.techidaily.com/macxdvd/products/)
* [Hot Topics >>](https://tools.techidaily.com/macxdvd/products/)

<!-- affiliate ads begin -->
<span id="1155462">
					<video width="1024" height="576" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1155462.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/14559-1155462">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1155462.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:640px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fpropmoneyinc.pxf.io%2Fc%2F5597632%2F1155462%2F14559'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1155462/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Company

* [About Us >>](https://tools.techidaily.com/macxdvd/products/)
* [Tech & Sales FAQ >>](https://tools.techidaily.com/macxdvd/products/)
* [User Guides >>](https://tools.techidaily.com/macxdvd/products/)
* [Contact Us >>](https://tools.techidaily.com/macxdvd/products/)
* [Partner >>](https://tools.techidaily.com/macxdvd/products/)

[Home](https://tools.techidaily.com/macxdvd/products/) | [About](https://tools.techidaily.com/macxdvd/products/) | [Privacy Policy](https://tools.techidaily.com/macxdvd/products/) | [Terms and Conditions](https://tools.techidaily.com/macxdvd/products/) | [License Agreement](https://tools.techidaily.com/macxdvd/products/) | [Resource](https://tools.techidaily.com/macxdvd/products/) | [News](https://tools.techidaily.com/macxdvd/products/) | [Contact Us](https://tools.techidaily.com/macxdvd/products/)

Copyright © 2024 Digiarty Software, Inc (MacXDVD). All rights reserved

Apple, the Apple logo, Mac, iPhone, iPad, iPod and iTunes are trademarks of Apple Inc, registered in the U.S. and other countries.  
Digiarty Software is not developed by or affiliated with Apple Inc.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://vp-tips.techidaily.com/new-restore-pristine-photos-easily-discover-top-10-online-enhancers/"><u>[New] Restore Pristine Photos Easily Discover Top 10 Online Enhancers</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-click-to-victory-the-best-12-pc-games-for-dedicated-players/"><u>[Updated] Click to Victory The Best 12 PC Games for Dedicated Players</u></a></li>
<li><a href="https://discover-amazing.techidaily.com/best-3-no-cost-substitutes-for-windows-media-center-in-windows-10-and-11/"><u>Best 3 No-Cost Substitutes for Windows Media Center in Windows 10 & 11</u></a></li>
<li><a href="https://screen-capture.techidaily.com/best-tech-to-preserve-classroom-interactions/"><u>Best Tech to Preserve Classroom Interactions</u></a></li>
<li><a href="https://android-frp.techidaily.com/easy-guide-to-asus-rog-phone-7-ultimate-frp-bypass-with-best-methods-by-drfone-android/"><u>Easy Guide to Asus ROG Phone 7 Ultimate FRP Bypass With Best Methods</u></a></li>
<li><a href="https://discover-amazing.techidaily.com/effortless-mov-to-flv-conversion-preserving-high-quality-video/"><u>Effortless MOV to FLV Conversion: Preserving High-Quality Video</u></a></li>
<li><a href="https://discover-amazing.techidaily.com/guia-completa-para-optimizar-la-configuracion-de-video-en-handbrake-para-dispositivos-tablet-androide/"><u>Guía Completa Para Optimizar La Configuración De Video en HandBrake Para Dispositivos Tablet Androide</u></a></li>
<li><a href="https://discover-amazing.techidaily.com/guia-paso-a-paso-para-minimizar-los-videos-hd4k8k-reduccion-del-tamano-hasta-un-90/"><u>Guía Paso a Paso Para Minimizar Los Videos HD/4K/8K: Reducción Del Tamaño Hasta Un 90%</u></a></li>
<li><a href="https://discover-amazing.techidaily.com/herausragende-videoqualitat-erhalten-grossenkompensierter-mp4-formatumwandlung-zur-optimierung-von-onlineinhalten/"><u>Herausragende Videoqualität Erhalten: Größenkompensierter MP4-Formatumwandlung Zur Optimierung Von Onlineinhalten</u></a></li>
<li><a href="https://tech-haven.techidaily.com/masterful-use-of-chatgpt-cutting-out-inefficient-tools/"><u>Masterful Use of ChatGPT: Cutting Out Inefficient Tools</u></a></li>
<li><a href="https://games-able.techidaily.com/perfect-gaming-environment-customizing-the-xboxs-smooth-refresh-rate/"><u>Perfect Gaming Environment: Customizing the Xbox's Smooth Refresh Rate</u></a></li>
<li><a href="https://win-amazing.techidaily.com/realtek-asio-audio-device-driver-simple-installation-steps-for-windows-10-users/"><u>Realtek Asio Audio Device Driver | Simple Installation Steps for Windows 10 Users</u></a></li>
<li><a href="https://discover-amazing.techidaily.com/resolved-issue-installing-adobe-media-encoder-with-premiere-pro-and-after-effects/"><u>Resolved Issue: Installing Adobe Media Encoder with Premiere Pro and After Effects</u></a></li>
<li><a href="https://discover-amazing.techidaily.com/specifications-detaillees-pour-lia-video-winx-informations-a-jour-et-officielles/"><u>Spécifications Détaillées Pour L'IA Vidéo Winx: Informations À Jour Et Officielles</u></a></li>
<li><a href="https://discover-amazing.techidaily.com/tecniche-di-ottimizzazione-perfette-per-i-file-video-mp4-nel-2023/"><u>Tecniche Di Ottimizzazione Perfette per I File Video MP4 Nel 2023</u></a></li>
<li><a href="https://program-issues.techidaily.com/troubleshooting-guide-resolving-pc-crashes-in-slime-rancher-2/"><u>Troubleshooting Guide: Resolving PC Crashes in Slime Rancher 2</u></a></li>
<li><a href="https://extra-tips.techidaily.com/twitch-time-reversal-17-methods-to-master-your-live-stream/"><u>Twitch Time Reversal 17 Methods to Master Your Live Stream</u></a></li>
<li><a href="https://fox-info.techidaily.com/unlocking-potential-in-spotifys-ad-ecosystem/"><u>Unlocking Potential in Spotify's Ad Ecosystem</u></a></li>
<li><a href="https://discover-amazing.techidaily.com/winxvideo-advanced-recording-of-screenshots-live-webcams-and-sound-with-ai-capabilities/"><u>WinxVideo: Advanced Recording of Screenshots, Live Webcams, and Sound with AI Capabilities</u></a></li>
</ul></div>

