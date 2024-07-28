---
title: "[New] A Beginner's Tutorial on Using LUTs in AR"
date: 2024-07-27T07:59:07.525Z
updated: 2024-07-28T07:59:07.525Z
tags: 
  - screen-recording
  - ai video
  - ai audio
  - ai auto
categories: 
  - ai
  - screen
description: "This Article Describes [New] A Beginner's Tutorial on Using LUTs in AR"
excerpt: "This Article Describes [New] A Beginner's Tutorial on Using LUTs in AR"
keywords: "AR LUT Basics,Beginners Guide to LUTs,Using LUTs in AR,LUTs for AR Devices,Introduction to AR LUTs,Learning AR LUT Techniques,Essential AR LUT Tutorial"
thumbnail: https://thmb.techidaily.com/33493674183189bab67b88de79a85b9996c293935f6ec3a823ac568973956aae.jpg
---

## A Beginner's Tutorial on Using LUTs in AR

Color LUTs (Lookup Textures) are tables of RGB color values. In Spark AR, you can use color LUTs to quickly create color gradation effects throughout the scene. Go through the article and create your color LUT effect.

<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
## Part 1\. What are Luts in Spark AR used for?

To create a color filter effect in [Spark AR](https://sparkar.facebook.com/ar-studio/), you need a color LUT in Spark AR.

To develop AR effects for mobile cameras, you can use the Mac and Windows augmented reality platform Spark AR Studio. Imagine it like Sketch or Photoshop for augmented reality. The color values of the camera texture are mapped to the x, y, and z coordinates of the location in the color LUT. This location contains a corresponding output color that is drawn over the scene to create a color gradient effect.

<!-- affiliate ads begin -->
<a href="https://martinic.evyy.net/c/5597632/1422856/4482" target="_top" id="1422856"><img src="//a.impactradius-go.com/display-ad/4482-1422856" border="0" alt="" width="580" height="309"/></a>
<!-- affiliate ads end -->
![create a color gradient effect](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-1.jpg)

## Part 2\. How to use LUTs in Spark AR?

**How to apply a color LUT to the whole scene in Spark AR:**

##### Step1Add a color LUT to your project

1. In the Assets panel, click Add Asset.
2. Select Import, then Color LUT, and select your file from your computer.

When you import a color LUT, compression is always set to None, and filtering is set to Low by default.

##### Step2Apply to the whole scene

1. In the Assets panel, right-click the LUT color.
2. Select Actions and then **Apply to Camera**.

A patch graph is automatically set that applies a color LUT to the entire scene.

![apply to the whole scene](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-2.jpg)

**The color LUT patch graph**

The patch graph that renders the color gradation effect looks like this:

<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/924299/11305" target="_top" id="924299"><img src="//a.impactradius-go.com/display-ad/11305-924299" border="0" alt="" width="520" height="100"/></a>
<!-- affiliate ads end -->
![color lut patch graph](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-3.jpg)

**To create the effect:**

* Fix Scene Render Pass renders cameraTexture0 and all objects in the scene that are children of the device. This creates the output texture.
* ColorLUTShader looks up the RGBA values of this texture in the Tension color LUT array and converts them to a new green color. This will change the texture and create a gradient effect.
* Finally, the Screen Output patch renders the green color.

## Part 3\. Free LUTs resource for Spark AR

Here are the best free LUTs resources for Spark AR:

<!-- affiliate ads begin -->
<a href="https://mushroom-supplies.sjv.io/c/5597632/1692242/18134" target="_top" id="1692242"><img src="//a.impactradius-go.com/display-ad/18134-1692242" border="0" alt="" width="834" height="592"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1692242/18134" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 1\. [Frost Zombie (Technical Showcase)](https://we.tl/t-1uj4wJKluG)

Client filter pieces occasionally end up on the scrap heap. It was a poor Frost Zombie in this instance. Since this is one of my simpler filters, I felt it was okay to publish the build information. Four objects make up much of the scene: an EyeColor block, a custom canvas segmentation, a face mesh, and an emitter for the breath mist (my personal favorite). To show the layers used in generating the primary zombie texture, I also moved to Substance Painter. This is a demonstration of my methods rather than a step-by-step manual.

![frost zombie](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-4.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2090698/16836" target="_top" id="2090698"><img src="//a.impactradius-go.com/display-ad/16836-2090698" border="0" alt="" width="720" height="300"/></a>
<!-- affiliate ads end -->
### 2\. Fur

Here are the key building principles.

* Geometric layers, often known as shells, produce depth.
* Normals is used to create shells from a single mesh.
* Alpha decreases with each shell.
* Deeper shells are darker.
* Height is generated from a single grayscale channel.
* No fur is generated in the black areas of the height texture.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152835&QTY=1&AFFILIATE=108875&CART=1"><img src="https://download.terabyteunlimited.com/banners/ad_800x450_d.jpg" border="0"></a>
<!-- affiliate ads end -->
![fur](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-5.jpg)

### 3\. Shockwave

Even while using large image sequences is frequently discouraged, you can still use them to make some extremely spectacular effects! I'll explain how the screen tap computation procedure relates to texture position in this walkthrough. If you want to apply this approach and texture sequence in your projects or give it a try.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=36506229&QTY=1&AFFILIATE=108875&CART=1"><video width="100%" height="" class="rounded-t-md shadow-lg relative z-20" controls="" autoplay="" loop="" muted="" playsinline="" webkit-playinginline="">
<source type="video/mp4" src="https://aidaform.com/images/videos/aidaform-welcome-site.mp4"><source type="video/webm" src="https://aidaform.com/images/videos/aidaform-welcome-site.webm"></video></a>
<!-- affiliate ads end -->
![shockwave](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-6.jpg)

### 4\. Transition Curves

There are 11 distinct animation curves included with Spark AR in the Transition patch. Here is a helpful visual aid because it might be challenging to distinguish between a quartic and a quintic when working on a project. With the SDF circle doubled (to sharpen the edge) and inserted into the Patch Pack's alpha channel, the circles are likewise straightforward rectangles. Since RGB values are three times one, the object is white.

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1821134/17882" target="_top" id="1821134"><img src="//a.impactradius-go.com/display-ad/17882-1821134" border="0" alt="" width="320" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1821134/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![transition curves](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-7.jpg)

### 5\. Realistic Smoke

By adding smoke to a scene, you can easily add a lot of detail and realism. Nothing revolutionary is happening here. The particle emitter creates flat planes of smoke texture that are forced upward. The force slowly shifts left and right as seen in the patch editor. The Fade particle script (created by Josh Beckwith) enlarges the particles and fades them out at the same time.

![realistic smoke](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-8.jpg)

### 6\. Rainbow Glitter

Given how beautifully Glitter Rain was received, I believed it would be fitting to broaden the potential with an HDR setting. While Glitter Rain made use of two different colors, this technique makes use of an entirely colorless substance and gets its color information via HDR.

![rainbow glitter](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-9.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
### Closing Thoughts

Spark AR is an amazing website for LUTs and color grading. Whether you're a new student or a seasoned pro, Spark AR Studio has all the features and capabilities you need to become a good video editor. You can download free LUTs from Spark AR and apply them to your videos. The article guides on how to use LUTs in Spark AR and how to download free LUTs. So, Spark AR is one of the best online websites for LUTs I have tried.

[Free Download](https://tools.techidaily.com/wondershare/filmora/download/)For Win 7 or later(64-bit)

[Free Download](https://tools.techidaily.com/wondershare/filmora/download/)For macOS 10.14 or later

[Free Download](https://tools.techidaily.com/wondershare/filmora/download/)For macOS 10.14 or later

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

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
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-from-beginner-to-pro-the-top-tips-for-instagram-stories/"><u>[New] 2024 Approved  From Beginner to Pro  The Top Tips for Instagram Stories</u></a></li>
<li><a href="https://youtube-data.techidaily.com/024-approved-utilizing-famebit-techniques-for-youtube-sponsorship-success/"><u>[New] 2024 Approved  Utilizing FameBit Techniques for YouTube Sponsorship Success</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-5-easy-steps-to-record-voice-on-your-windows-11-pc/"><u>[New] 5 Easy Steps to Record Voice on Your Windows 11 PC</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-crafting-visual-tales-expertly-warping-and-twisting-in-photoshop/"><u>[New] Crafting Visual Tales  Expertly Warping & Twisting in Photoshop</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-unveiling-zooms-hidden-visual-treasures-with-filters/"><u>[Updated] 2024 Approved  Unveiling Zoom's Hidden Visual Treasures with Filters</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-brain-benders-await-at-the-best-room-sanctuaries/"><u>[Updated] Brain Benders Await at the Best Room Sanctuaries</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-comprehensive-degree-of-view-analysis/"><u>[Updated] Comprehensive Degree of View Analysis</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-seeing-more-than-ever-samsungs-galaxy-s8-and-4k-breakthrough/"><u>[Updated] Seeing More Than Ever  Samsung's Galaxy S8 and 4K Breakthrough</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-10-top-ranked-no-cost-image-format-switchers-jpg-to-gif/"><u>2024 Approved  10 Top-Ranked No-Cost Image Format Switchers (JPG to GIF)</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-best-matches-ultimate-websites-for-acquiring-snapchat-ringtones/"><u>2024 Approved  Best Matches  Ultimate Websites for Acquiring Snapchat Ringtones</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/2024-approved-make-your-mark-with-the-hottest-tiktok-tags-and-trends-now/"><u>2024 Approved  Make Your Mark with the Hottest TikTok Tags & Trends Now</u></a></li>
<li><a href="https://location-fake.techidaily.com/8-solutions-to-fix-find-my-friends-location-not-available-on-apple-iphone-13-pro-max-drfone-by-drfone-virtual-ios/"><u>8 Solutions to Fix Find My Friends Location Not Available On Apple iPhone 13 Pro Max | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/a-guide-oppo-reno-10-proplus-5g-wireless-and-wired-screen-mirroring-drfone-by-drfone-android/"><u>A Guide Oppo Reno 10 Pro+ 5G Wireless and Wired Screen Mirroring | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/a-guide-to-creating-gentle-sound-cuts-and-fades-with-pp/"><u>A Guide to Creating Gentle Sound Cuts and Fades with PP</u></a></li>
<li><a href="https://extra-tips.techidaily.com/best-of-the-best-10-timeless-family-vacation-films/"><u>Best of the Best  10 Timeless Family Vacation Films</u></a></li>
<li><a href="https://android-unlock.techidaily.com/best-samsung-galaxy-s23-tactical-edition-pattern-lock-removal-tools-remove-android-pattern-lock-without-losing-data-by-drfone-android/"><u>Best Samsung Galaxy S23 Tactical Edition Pattern Lock Removal Tools Remove Android Pattern Lock Without Losing Data</u></a></li>
<li><a href="https://extra-tips.techidaily.com/building-profitable-collaborations-with-brands-on-youtube/"><u>Building Profitable Collaborations with Brands on Youtube</u></a></li>
<li><a href="https://extra-tips.techidaily.com/crafting-engaging-storytelling-podcasts-with-applee-devices/"><u>Crafting Engaging Storytelling Podcasts with Apple'e Devices</u></a></li>
<li><a href="https://extra-tips.techidaily.com/discovering-the-ideal-live-stream-provider-a-top-10-list/"><u>Discovering the Ideal Live Stream Provider  A Top 10 List</u></a></li>
<li><a href="https://extra-tips.techidaily.com/exploring-intensified-illumination-for-advanced-hdr-video/"><u>Exploring Intensified Illumination for Advanced HDR Video</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/future-employment-preparing-for-ai-driven-transformation/"><u>Future Employment: Preparing for AI-Driven Transformation</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-captivating-stories-in-motion-best-video-theme-choices/"><u>In 2024, Captivating Stories in Motion  Best Video Theme Choices</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-comprehensible-guide-to-shifting-photosvideos-in-ios-world/"><u>In 2024, Comprehensible Guide to Shifting Photos/Videos in iOS World</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-lg-360-camera-full-review/"><u>In 2024, LG 360 Camera Full Review</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-smilesketcher-easy-to-use-digital-comedy-tool/"><u>In 2024, SmileSketcher  Easy-to-Use Digital Comedy Tool</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-will-pokemon-go-ban-the-account-if-you-use-pgsharp-on-oneplus-ace-2-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Will Pokémon Go Ban the Account if You Use PGSharp On OnePlus Ace 2 Pro | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/magix-music-maker-2024-review/"><u>Magix Music Maker 2024 Review</u></a></li>
<li><a href="https://extra-tips.techidaily.com/movie-magic-for-editing-select-excerpts-handpicked/"><u>Movie Magic for Editing  Select Excerpts Handpicked</u></a></li>
<li><a href="https://extra-tips.techidaily.com/sound-syncing-simplified-for-inshot-edits/"><u>Sound Syncing Simplified for InShot Edits</u></a></li>
<li><a href="https://extra-tips.techidaily.com/summit-elite-25-testing-analysis/"><u>Summit Elite 25 Testing Analysis</u></a></li>
<li><a href="https://extra-tips.techidaily.com/the-soundtrack-of-your-phone-classic-tones-download-site-guide/"><u>The Soundtrack of Your Phone  Classic Tones Download Site Guide</u></a></li>
<li><a href="https://howto.techidaily.com/top-4-android-system-repair-software-for-oppo-find-x6-bricked-devices-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Top 4 Android System Repair Software for Oppo Find X6 Bricked Devices | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/transformative-color-workflow-with-cg-central-luts/"><u>Transformative Color Workflow with CG Central LUTs</u></a></li>
<li><a href="https://extra-tips.techidaily.com/xs-100-i-bring-your-movies-to-life-with-revolutionary-technology/"><u>XS 100 I  Bring Your Movies to Life with Revolutionary Technology</u></a></li>
</ul></div>
