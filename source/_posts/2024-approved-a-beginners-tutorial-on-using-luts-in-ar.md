---
title: "\"2024 Approved  A Beginner's Tutorial on Using LUTs in AR\""
date: 2024-07-27T09:53:38.636Z
updated: 2024-07-28T09:53:38.636Z
tags: 
  - screen-recording
  - ai video
  - ai audio
  - ai auto
categories: 
  - ai
  - screen
description: "\"This Article Describes 2024 Approved: A Beginner's Tutorial on Using LUTs in AR\""
excerpt: "\"This Article Describes 2024 Approved: A Beginner's Tutorial on Using LUTs in AR\""
keywords: "AR LUT Basics,Beginners Guide to LUTs,Using LUTs in AR,LUTs for AR Devices,Introduction to AR LUTs,Learning AR LUT Techniques,Essential AR LUT Tutorial"
thumbnail: https://thmb.techidaily.com/5cb2e70fe5fc4984663e55071f50818b86ad28c6053861679577418a188e88c7.jpg
---

## A Beginner's Tutorial on Using LUTs in AR

Color LUTs (Lookup Textures) are tables of RGB color values. In Spark AR, you can use color LUTs to quickly create color gradation effects throughout the scene. Go through the article and create your color LUT effect.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-writer-free-word-processor-1x.3d9c80d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
## Part 1\. What are Luts in Spark AR used for?

To create a color filter effect in [Spark AR](https://sparkar.facebook.com/ar-studio/), you need a color LUT in Spark AR.

To develop AR effects for mobile cameras, you can use the Mac and Windows augmented reality platform Spark AR Studio. Imagine it like Sketch or Photoshop for augmented reality. The color values of the camera texture are mapped to the x, y, and z coordinates of the location in the color LUT. This location contains a corresponding output color that is drawn over the scene to create a color gradient effect.

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

![color lut patch graph](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-3.jpg)

**To create the effect:**

* Fix Scene Render Pass renders cameraTexture0 and all objects in the scene that are children of the device. This creates the output texture.
* ColorLUTShader looks up the RGBA values of this texture in the Tension color LUT array and converts them to a new green color. This will change the texture and create a gradient effect.
* Finally, the Screen Output patch renders the green color.

## Part 3\. Free LUTs resource for Spark AR

Here are the best free LUTs resources for Spark AR:

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389"><img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 1\. [Frost Zombie (Technical Showcase)](https://we.tl/t-1uj4wJKluG)

Client filter pieces occasionally end up on the scrap heap. It was a poor Frost Zombie in this instance. Since this is one of my simpler filters, I felt it was okay to publish the build information. Four objects make up much of the scene: an EyeColor block, a custom canvas segmentation, a face mesh, and an emitter for the breath mist (my personal favorite). To show the layers used in generating the primary zombie texture, I also moved to Substance Painter. This is a demonstration of my methods rather than a step-by-step manual.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537547&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/vcfpro.png" border="0">Video Converter Factory Pro</a>
<!-- affiliate ads end -->
![frost zombie](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-4.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/300__250banner.jpg" border="0"></a>
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
<!-- affiliate ads end -->
![fur](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-5.jpg)

### 3\. Shockwave

Even while using large image sequences is frequently discouraged, you can still use them to make some extremely spectacular effects! I'll explain how the screen tap computation procedure relates to texture position in this walkthrough. If you want to apply this approach and texture sequence in your projects or give it a try.

![shockwave](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-6.jpg)

### 4\. Transition Curves

There are 11 distinct animation curves included with Spark AR in the Transition patch. Here is a helpful visual aid because it might be challenging to distinguish between a quartic and a quintic when working on a project. With the SDF circle doubled (to sharpen the edge) and inserted into the Patch Pack's alpha channel, the circles are likewise straightforward rectangles. Since RGB values are three times one, the object is white.

![transition curves](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-7.jpg)

<!-- affiliate ads begin -->
<a href="https://checkout.mirillis.com/order/checkout.php?PRODS=4704640&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/547a5a56d43f6d40f9a6a2f76501d013/products/1_mirillis_action_boxshot_store_1x.jpg" border="0">
	Home Use license is dedicated for personal, non-commercial use only. 
	If Action! is used for commercial gain or to further any commercial purpose, 
	a Commercial Use license is required. Multi-license (volume discount) is intended for single 
 
	company, user or members of the same household. Action! - screen and game recorder</a>
<!-- affiliate ads end -->
### 5\. Realistic Smoke

By adding smoke to a scene, you can easily add a lot of detail and realism. Nothing revolutionary is happening here. The particle emitter creates flat planes of smoke texture that are forced upward. The force slowly shifts left and right as seen in the patch editor. The Fade particle script (created by Josh Beckwith) enlarges the particles and fades them out at the same time.

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1725213/17190" target="_top" id="1725213"><img src="//a.impactradius-go.com/display-ad/17190-1725213" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1725213/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![realistic smoke](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-8.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
### 6\. Rainbow Glitter

Given how beautifully Glitter Rain was received, I believed it would be fitting to broaden the potential with an HDR setting. While Glitter Rain made use of two different colors, this technique makes use of an entirely colorless substance and gets its color information via HDR.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075461/7443" target="_top" id="2075461"><img src="//a.impactradius-go.com/display-ad/7443-2075461" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075461/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![rainbow glitter](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-9.jpg)

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
<li><a href="https://youtube-blog.techidaily.com/024-approved-ephemeral-film-sculptor/"><u>[New] 2024 Approved  Ephemeral Film Sculptor</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-exceptional-quality-hd-video-documenters/"><u>[New] 2024 Approved  Exceptional Quality HD Video Documenters</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/new-2024-approved-mastering-the-art-of-twitters-live-video-engagement/"><u>[New] 2024 Approved  Mastering the Art of Twitter's Live Video Engagement</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-a-deep-dive-into-metaverse-vs-multi-meva-key-differences-explored/"><u>[New] A Deep Dive Into Metaverse Vs. Multi-Meva  Key Differences Explored</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-an-easy-nft-creation-pathway-for-starters/"><u>[New] An Easy NFT Creation Pathway For Starters</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-animated-adventures-easy-steps-for-snapchats-cute-filters/"><u>[New] Animated Adventures  Easy Steps for Snapchat's Cute Filters</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-aural-tales-the-best-of-radio-plays/"><u>[New] Aural Tales  The Best of Radio Plays</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-cameras-collide-in-motorsport-showdown-gopro-vs-drift-ghost-s/"><u>[New] Cameras Collide in Motorsport Showdown! GoPro Vs. Drift Ghost-S</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-top-10-picks-best-facebook-video-players/"><u>[New] In 2024, Top 10 Picks  Best Facebook Video Players</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-unlocking-the-mystery-of-storing-instagram-videos-pc-and-mac-users-guide/"><u>[New] Unlocking the Mystery of Storing Instagram Videos (PC & Mac Users Guide)</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-integrating-effective-annotations-for-dynamic-storytelling/"><u>[Updated] 2024 Approved  Integrating Effective Annotations for Dynamic Storytelling</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-clearer-captures-await-with-next-gen-tracker-tech/"><u>[Updated] Clearer Captures Await with Next-Gen Tracker Tech</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-comprehensive-guide-to-enhancing-tiktoks-adding-texts-professionally-for-2024/"><u>[Updated] Comprehensive Guide to Enhancing TikToks  Adding Texts Professionally for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-creating-temporal-distortions-a-guide-to-movie-magic-for-2024/"><u>[Updated] Creating Temporal Distortions  A Guide to Movie Magic for 2024</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-efficiently-establish-your-zoom-space/"><u>[Updated] Efficiently Establish Your Zoom Space</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-gopro-hero-session-vs-polaroid-cubeplus-which-one-is-better-for-you/"><u>[Updated] GoPro Hero Session Vs Polaroid Cube+  Which One Is Better for You?</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-how-to-download-windows-movie-maker-6-for-2024/"><u>[Updated] How to Download Windows Movie Maker 6 for 2024</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-in-2024-the-ultimate-roundup-post-vlc-media-players/"><u>[Updated] In 2024, The Ultimate Roundup  Post-VLC Media Players</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-comparing-huawei-p10-with-industry-standards-of-smartphones/"><u>2024 Approved  Comparing Huawei P10 with Industry Standards of Smartphones</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-complete-understanding-of-srt-covering-everything-important/"><u>2024 Approved  Complete Understanding of SRT, Covering Everything Important</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-monetize-more-strategies-for-youtubes-updated-partner-plan/"><u>2024 Approved  Monetize More  Strategies for YouTube's Updated Partner Plan</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-top-10-best-stabilized-camera-gimbals-for-iphone-android-and-dslr/"><u>2024 Approved  Top 10 Best Stabilized Camera Gimbals for iPhone, Android, and DSLR</u></a></li>
<li><a href="https://location-fake.techidaily.com/8-solutions-to-fix-find-my-friends-location-not-available-on-oppo-find-x7-drfone-by-drfone-virtual-android/"><u>8 Solutions to Fix Find My Friends Location Not Available On Oppo Find X7 | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/a-year-in-review-exploring-vivacuts-evolution-and-its-video-editors-guide/"><u>A Year in Review  Exploring VivaCut’s Evolution and Its Video Editor’s Guide</u></a></li>
<li><a href="https://extra-tips.techidaily.com/broad-overview-delving-into-google-podcasts-application-for-2024/"><u>Broad Overview  Delving Into Google Podcasts Application for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/building-your-virtual-persona-with-minimal-hassle-for-2024/"><u>Building Your Virtual Persona with Minimal Hassle for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/choosing-the-best-camera-for-filming-mirrorless-or-dslr/"><u>Choosing the Best Camera for Filming  Mirrorless or DSLR</u></a></li>
<li><a href="https://extra-tips.techidaily.com/decoding-the-smudge-expertly-ranked-10-internet-photo-tools/"><u>Decoding the Smudge  Expertly Ranked 10 Internet Photo Tools</u></a></li>
<li><a href="https://extra-tips.techidaily.com/discover-the-ultimate-30-list-of-free-vectr-and-illustration-sites-online/"><u>Discover the Ultimate 30 List of Free Vectr and Illustration Sites Online</u></a></li>
<li><a href="https://extra-tips.techidaily.com/expert-insights-powerdirector-app-release-2024-guidebook/"><u>Expert Insights  PowerDirector App, Release 2024 Guidebook</u></a></li>
<li><a href="https://extra-tips.techidaily.com/expertly-crafted-images-with-lut-techniques-in-photoshop-cs6/"><u>Expertly Crafted Images with LUT Techniques in Photoshop CS6</u></a></li>
<li><a href="https://extra-tips.techidaily.com/from-concept-to-comic-10-must-have-strategies-for-making-gifs/"><u>From Concept to Comic  10 Must-Have Strategies for Making GIFs</u></a></li>
<li><a href="https://extra-tips.techidaily.com/from-hashtags-to-challenges-insta-meets-tiktok/"><u>From Hashtags to Challenges  Insta Meets TikTok</u></a></li>
<li><a href="https://extra-tips.techidaily.com/from-script-to-sound-crafting-captivating-podcast-episodes/"><u>From Script to Sound  Crafting Captivating Podcast Episodes</u></a></li>
<li><a href="https://extra-information.techidaily.com/green-canvas-essential-templates-to-enhance-your-cinematographic-journey/"><u>Green Canvas  Essential Templates to Enhance Your Cinematographic Journey</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-location-on-tiktok-to-see-more-content-on-your-tecno-spark-10c-drfone-by-drfone-virtual-android/"><u>How to Change Location on TikTok to See More Content On your Tecno Spark 10C | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-stop-google-chrome-from-tracking-your-location-on-tecno-pop-7-pro-drfone-by-drfone-virtual-android/"><u>How to Stop Google Chrome from Tracking Your Location On Tecno Pop 7 Pro? | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/identifying-excellent-video-production-experts/"><u>Identifying Excellent Video Production Experts</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-break-free-from-conventions-advanced-distortion-art-in-photoshop/"><u>In 2024, Break Free From Conventions  Advanced Distortion Art in Photoshop</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-build-diy-virtual-reality-google-cardboard-hack/"><u>In 2024, Build DIY Virtual Reality  Google Cardboard Hack</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-how-to-fake-gps-on-android-without-mock-location-for-your-motorola-moto-e13-drfone-by-drfone-virtual/"><u>In 2024, How to Fake GPS on Android without Mock Location For your Motorola Moto E13 | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/innovative-10-plugin-upgrades-for-fcp-users/"><u>Innovative 10 Plugin Upgrades for FCP Users</u></a></li>
<li><a href="https://extra-tips.techidaily.com/is-there-money-in-evaluating-merchandise-vids/"><u>Is There Money in Evaluating Merchandise Vids?</u></a></li>
<li><a href="https://extra-tips.techidaily.com/narrative-blueprint-a-basic-overview/"><u>Narrative Blueprint  A Basic Overview</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-in-2024-the-modern-editors-handbook-cutting-and-mixing-in-avidemux/"><u>New In 2024, The Modern Editors Handbook Cutting and Mixing in Avidemux</u></a></li>
<li><a href="https://screen-recording.techidaily.com/premier-apple-products-mimicking-old-ps2-games/"><u>Premier Apple Products Mimicking Old PS2 Games</u></a></li>
<li><a href="https://extra-tips.techidaily.com/pro-equipment-list-for-adventure-documentaries/"><u>Pro Equipment List for Adventure Documentaries</u></a></li>
<li><a href="https://extra-tips.techidaily.com/prototypical-360-rotation-camera-study/"><u>Prototypical 360° Rotation Camera Study</u></a></li>
<li><a href="https://extra-tips.techidaily.com/secure-your-snapshots-anywhere-anytime-the-ultimate-cloud-choices/"><u>Secure Your Snapshots Anywhere, Anytime  The Ultimate Cloud Choices</u></a></li>
<li><a href="https://extra-tips.techidaily.com/storytelling-with-style-making-instagram-text-dance/"><u>Storytelling with Style  Making Instagram Text Dance</u></a></li>
<li><a href="https://change-location.techidaily.com/the-magnificent-art-of-pokemon-go-streaming-on-vivo-s17e-drfone-by-drfone-virtual-android/"><u>The Magnificent Art of Pokemon Go Streaming On Vivo S17e? | Dr.fone</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/the-ultimate-expressive-guide-top-108-crucial-croatian-linguistic-tools/"><u>The Ultimate Expressive Guide: Top 108 Crucial Croatian Linguistic Tools</u></a></li>
<li><a href="https://techidaily.com/this-is-how-you-can-recover-deleted-pictures-from-realme-c53-by-fonelab-android-recover-pictures/"><u>This is how you can recover deleted pictures from Realme C53.</u></a></li>
<li><a href="https://extra-tips.techidaily.com/top-6-virtual-reality-vr-gloves-to-check-out/"><u>Top 6 Virtual Reality (VR) Gloves to Check Out</u></a></li>
<li><a href="https://some-approaches.techidaily.com/transformative-techniques-applying-luts-for-dynamic-effects-in-after-effects-for-2024/"><u>Transformative Techniques  Applying LUTs for Dynamic Effects in After Effects for 2024</u></a></li>
<li><a href="https://ai-voice.techidaily.com/updated-a-list-of-the-top-spongebob-voice-generators/"><u>Updated A List of The Top SpongeBob Voice Generators</u></a></li>
<li><a href="https://techidaily.com/xiaomi-won-t-play-hevc-h-265-media-how-to-fix-by-aiseesoft-video-converter-play-hevc-video-on-android/"><u>Xiaomi won’t play HEVC H.265 media, how to fix?</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/be-content-protection-can-you-record-playbacks-for-2024/"><u>YouTube Content Protection  Can You Record Playbacks for 2024</u></a></li>
</ul></div>
