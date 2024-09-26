---
title: Solve the DVD Cloning Issue in Disk Utility with These Reliable Fixes
date: 2024-09-24T17:32:46.200Z
updated: 2024-09-25T18:48:52.417Z
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

**Step 3.** Click Run to start the DVD copy.

_Disclaimer: This post is to help users whose Disk Utility will not copy DVD or get com apple diskutility error 3 status 5, input/output error, or the like. It does not in any way advocate copying a DVD for any commercial or other illegal use. Please consult the law in your country before you copy any disc._

ABOUT THE AUTHOR

![author- bella](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/bella.png) 

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137228/26400" target="_top" id="2137228">
  <img src="//a.impactradius-go.com/display-ad/26400-2137228" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137228/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

[Bella Brown ![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/share-in1.jpg)](https://www.linkedin.com/in/bella-brown-920145104/) 

Bella has been working with DVD digitization for over 12 years. She writes articles about everything related to DVD, from disc drive, DVD copyright protection, physical structure, burning and backup tips. The unceasing passion of DVD movies helps her build a rich DVD library and ensure a practical solution to address almost all possible DVD issues. Bella is also a crazy fan for Apple products.

Related Articles

![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/pic7.jpg)

[Top 10 Free DVD Copy Software Burning Freeware for PC Mac](https://tools.techidaily.com/macxdvd/products/) 

![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/pic6.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151894/7443" target="_top" id="2151894">
  <img src="//a.impactradius-go.com/display-ad/7443-2151894" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151894/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

[DVD Won't Play with "Supported Disc Not Available" Error](https://tools.techidaily.com/macxdvd/products/) 

![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/pic5.jpg)

[Fix "Can't Rip Lionsgate DVDs" or Rip Protected DVDs Smoothly](https://tools.techidaily.com/macxdvd/products/) 

![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/pic4.jpg)

[Best DVD Decrypters for Mac - 100% Work to Rip Protected DVD Movies](https://tools.techidaily.com/macxdvd/products/) 

![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/pic3.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130873/7443" target="_top" id="2130873">
  <img src="//a.impactradius-go.com/display-ad/7443-2130873" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130873/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

[How to Rip Protected DVD Movies on Mac for FREE](https://tools.techidaily.com/macxdvd/products/) 

![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/pic2.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151865/7443" target="_top" id="2151865">
  <img src="//a.impactradius-go.com/display-ad/7443-2151865" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151865/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

[Fixed: Can't Rip Sony DVDs with Bad Sectors](https://tools.techidaily.com/macxdvd/products/) 

![Digiarty Software](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../icon/logo.png) 

Digiarty Software, Inc. (MacXDVD) is a leader in delivering stable multimedia software applications for worldwide users since its establishment in 2006.

<!-- affiliate ads begin -->
<span id="1982456">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982456.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982456">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982456.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982456%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982456/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Hot Products

* [MacX DVD Ripper Pro](https://tools.techidaily.com/macxdvd/products/)
* [MacX Video Converter Pro](https://tools.techidaily.com/macxdvd/products/)
* [MacX MediaTrans](https://tools.techidaily.com/macxdvd/products/)

### Tips and Tricks

* [DVD Topics >>](https://tools.techidaily.com/macxdvd/products/)
* [Video Solutions >>](https://tools.techidaily.com/macxdvd/products/)
* [Data Transfer >>](https://tools.techidaily.com/macxdvd/products/)
* [Online Video >>](https://tools.techidaily.com/macxdvd/products/)
* [Hot Topics >>](https://tools.techidaily.com/macxdvd/products/)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2002018/7443" target="_top" id="2002018">
  <img src="//a.impactradius-go.com/display-ad/7443-2002018" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2002018/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-http.techidaily.com/updated-in-2024-earnings-enigma-the-revenue-of-a-youtuber/"><u>[Updated] In 2024, Earnings Enigma The Revenue of a YouTuber</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-the-soundtrack-of-success-on-instagram/"><u>[Updated] In 2024, The Soundtrack of Success on Instagram</u></a></li>
<li><a href="https://discover-amazing.techidaily.com/macx800/"><u>限定キャンペーン：MacX動画変換プロの特別企画！800個分無料提供</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/capturing-hulu-live-anywhere-a-practical-how-to-manual/"><u>Capturing Hulu Live Anywhere - A Practical How-To Manual</u></a></li>
<li><a href="https://discover-amazing.techidaily.com/effizientes-iphone-bildmanagement-umgehend-ladenlos-entfernen-dank-ios-15-features/"><u>Effizientes iPhone-Bildmanagement – Umgehend Ladenlos Entfernen Dank IOS 15 Features</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/erase-with-ease-on-macos-using-the-best-stellar-eraser-app-ideal-for-mobile-users/"><u>Erase with Ease on macOS Using the Best Stellar Eraser App - Ideal for Mobile Users</u></a></li>
<li><a href="https://discover-amazing.techidaily.com/extraction-of-dvd-audio-on-macos-free-ripper-tool/"><u>Extraction of DVD Audio on macOS - Free Ripper Tool</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-xiaomi-redmi-13c-5g-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Xiaomi Redmi 13C 5G without Losing Data | Dr.fone</u></a></li>
<li><a href="https://discover-amazing.techidaily.com/how-to-resolve-non-charging-problems-on-your-iphone-a-comprehensive-guide/"><u>How To Resolve Non-Charging Problems on Your iPhone: A Comprehensive Guide</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/keep-your-snaps-alive-strategies-for-longevity/"><u>Keep Your Snaps Alive – Strategies for Longevity</u></a></li>
<li><a href="https://discover-amazing.techidaily.com/transferring-images-from-iphone-to-mac-top-10-easy-methods/"><u>Transferring Images From iPhone to Mac: Top 10 Easy Methods</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/unleashing-computer-power-with-insights-from-toms-hardware-gurus/"><u>Unleashing Computer Power with Insights From Tom's Hardware Gurus</u></a></li>
</ul></div>

