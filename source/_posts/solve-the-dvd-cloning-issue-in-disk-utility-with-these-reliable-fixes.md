---
title: Solve the DVD Cloning Issue in Disk Utility with These Reliable Fixes
date: 2024-09-29T17:30:22.113Z
updated: 2024-09-30T16:13:12.397Z
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
<span id="1977028">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977028.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977028">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977028.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977028%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977028/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**Step 3.** Click Run to start the DVD copy.

_Disclaimer: This post is to help users whose Disk Utility will not copy DVD or get com apple diskutility error 3 status 5, input/output error, or the like. It does not in any way advocate copying a DVD for any commercial or other illegal use. Please consult the law in your country before you copy any disc._

ABOUT THE AUTHOR

![author- bella](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/bella.png) 

[Bella Brown ![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/share-in1.jpg)](https://www.linkedin.com/in/bella-brown-920145104/) 

Bella has been working with DVD digitization for over 12 years. She writes articles about everything related to DVD, from disc drive, DVD copyright protection, physical structure, burning and backup tips. The unceasing passion of DVD movies helps her build a rich DVD library and ensure a practical solution to address almost all possible DVD issues. Bella is also a crazy fan for Apple products.

Related Articles

![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/pic7.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148642/16836" target="_top" id="2148642">
  <img src="//a.impactradius-go.com/display-ad/16836-2148642" border="0" alt="https://techidaily.com" width="300" height="50"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148642/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

[Top 10 Free DVD Copy Software Burning Freeware for PC Mac](https://tools.techidaily.com/macxdvd/products/) 

![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/pic6.jpg)

[DVD Won't Play with "Supported Disc Not Available" Error](https://tools.techidaily.com/macxdvd/products/) 

![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/pic5.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115921/19272" target="_top" id="2115921">
  <img src="//a.impactradius-go.com/display-ad/19272-2115921" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115921/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

[Fix "Can't Rip Lionsgate DVDs" or Rip Protected DVDs Smoothly](https://tools.techidaily.com/macxdvd/products/) 

![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/pic4.jpg)

[Best DVD Decrypters for Mac - 100% Work to Rip Protected DVD Movies](https://tools.techidaily.com/macxdvd/products/) 

![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/pic3.jpg)

[How to Rip Protected DVD Movies on Mac for FREE](https://tools.techidaily.com/macxdvd/products/) 

![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/pic2.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135402/19272" target="_top" id="2135402">
  <img src="//a.impactradius-go.com/display-ad/19272-2135402" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135402/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

[Fixed: Can't Rip Sony DVDs with Bad Sectors](https://tools.techidaily.com/macxdvd/products/) 

![Digiarty Software](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../icon/logo.png) 

Digiarty Software, Inc. (MacXDVD) is a leader in delivering stable multimedia software applications for worldwide users since its establishment in 2006.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148649/16836" target="_top" id="2148649">
  <img src="//a.impactradius-go.com/display-ad/16836-2148649" border="0" alt="https://techidaily.com" width="720" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148649/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Hot Products

* [MacX DVD Ripper Pro](https://tools.techidaily.com/macxdvd/products/)
* [MacX Video Converter Pro](https://tools.techidaily.com/macxdvd/products/)
* [MacX MediaTrans](https://tools.techidaily.com/macxdvd/products/)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135400/19272" target="_top" id="2135400">
  <img src="//a.impactradius-go.com/display-ad/19272-2135400" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135400/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Tips and Tricks

* [DVD Topics >>](https://tools.techidaily.com/macxdvd/products/)
* [Video Solutions >>](https://tools.techidaily.com/macxdvd/products/)
* [Data Transfer >>](https://tools.techidaily.com/macxdvd/products/)
* [Online Video >>](https://tools.techidaily.com/macxdvd/products/)
* [Hot Topics >>](https://tools.techidaily.com/macxdvd/products/)

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
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-elevate-your-videography-with-top-instagram-techniques/"><u>[New] 2024 Approved Elevate Your Videography with Top Instagram Techniques</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-in-2024-unlock-your-creativity-with-top-title-methods/"><u>[New] In 2024, Unlock Your Creativity with Top Title Methods</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-2024-approved-a-hackers-guide-to-scoring-cool-images-at-pexels/"><u>[Updated] 2024 Approved A Hacker's Guide to Scoring Cool Images at Pexels</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-six-winning-strategies-to-recording-and-saving-mov-on-windows-11/"><u>[Updated] 2024 Approved Six Winning Strategies to Recording and Saving .mov on Windows 11</u></a></li>
<li><a href="https://discover-amazing.techidaily.com/1-effizientes-herausfilmen-von-untertiteln-srt-aus-dvds-auf-mac-und-pc-schritt-fur-schritt-anleitung/"><u>1. Effizientes Herausfilmen Von Untertiteln (SRT) Aus DVDs Auf Mac Und PC: Schritt-Für-Schritt-Anleitung</u></a></li>
<li><a href="https://discover-amazing.techidaily.com/7-free-premium-4k-media-players-of-2023-for-pc-windows-10plus-and-mac-systems/"><u>7 FREE Premium 4K Media Players of 2023 for PC (Windows 10+) and MAC Systems</u></a></li>
<li><a href="https://discover-amazing.techidaily.com/1725288368188-aiwinxvideo/"><u>AIWinxVideoの使い方解説 - プログラムセットアップと最新版アップデート</u></a></li>
<li><a href="https://discover-amazing.techidaily.com/aumenta-la-qualita-del-tuo-video-con-winxvideo-ai-il-miglior-metodo-di-ottimizzazione/"><u>Aumenta La Qualità Del Tuo Video Con Winxvideo AI: Il Miglior Metodo Di Ottimizzazione</u></a></li>
<li><a href="https://discover-amazing.techidaily.com/convertissez-facilement-vos-fichiers-mp4-en-mp3-pour-windows-11-avec-le-convertisseur-audio-gratuit-mp4-to-mp3/"><u>Convertissez Facilement Vos Fichiers MP4 en MP3 Pour Windows 11 Avec Le Convertisseur Audio Gratuit MP4 to MP3</u></a></li>
<li><a href="https://blog-min.techidaily.com/guide-mastering-the-art-of-free-zune-video-converter-factory/"><u>Guide: Mastering the Art of Free Zune Video Converter Factory</u></a></li>
<li><a href="https://discover-amazing.techidaily.com/handbrake-unterstutzung-fur-av1-codec-and-umwandlung-von-av1-dateien/"><u>HandBrake Unterstützung Für AV1 Codec & Umwandlung Von AV1 Dateien</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reverse-error-0x7e1-on-win1011/"><u>How to Reverse Error 0X7E1 on Win10/11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-vivo-y100t-location-by-number-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Vivo Y100t Location by Number | Dr.fone</u></a></li>
<li><a href="https://discover-amazing.techidaily.com/is-av1-codec-compatible-with-handbrake-encoder-software/"><u>Is AV1 Codec Compatible with HandBrake Encoder Software?</u></a></li>
<li><a href="https://discover-amazing.techidaily.com/top-10-no-cost-dvd-duplication-programs-how-to-copy-your-dvd-without-paying-a-dime/"><u>Top 10 No-Cost DVD Duplication Programs: How to Copy Your DVD Without Paying a Dime</u></a></li>
<li><a href="https://windows11.techidaily.com/transform-messy-script-into-neat-text-with-microsoft-onenotes-new-feature/"><u>Transform Messy Script Into Neat Text with Microsoft OneNote's New Feature!</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/uncovered-the-hidden-youtube-shorts-fix-for-2024/"><u>Uncovered The Hidden YouTube Shorts Fix for 2024</u></a></li>
</ul></div>

