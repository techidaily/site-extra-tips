---
title: "[New] A Beginner's Tutorial on Using LUTs in AR"
date: 2024-05-24T14:34:30.177Z
updated: 2024-05-25T14:34:30.177Z
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
thumbnail: https://www.lifewire.com/thmb/c8e1nttdP23ElJeWx5VVLngvtIM=/400x300/filters:no_upscale():max_bytes(150000):strip_icc()/SafariTwitterSidebar-56a5d5143df78cf7728a0f97.jpg
---

## A Beginner's Tutorial on Using LUTs in AR

Color LUTs (Lookup Textures) are tables of RGB color values. In Spark AR, you can use color LUTs to quickly create color gradation effects throughout the scene. Go through the article and create your color LUT effect.

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

### 1\. [Frost Zombie (Technical Showcase)](https://we.tl/t-1uj4wJKluG)

Client filter pieces occasionally end up on the scrap heap. It was a poor Frost Zombie in this instance. Since this is one of my simpler filters, I felt it was okay to publish the build information. Four objects make up much of the scene: an EyeColor block, a custom canvas segmentation, a face mesh, and an emitter for the breath mist (my personal favorite). To show the layers used in generating the primary zombie texture, I also moved to Substance Painter. This is a demonstration of my methods rather than a step-by-step manual.

![frost zombie](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-4.jpg)

### 2\. Fur

Here are the key building principles.

* Geometric layers, often known as shells, produce depth.
* Normals is used to create shells from a single mesh.
* Alpha decreases with each shell.
* Deeper shells are darker.
* Height is generated from a single grayscale channel.
* No fur is generated in the black areas of the height texture.

![fur](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-5.jpg)

### 3\. Shockwave

Even while using large image sequences is frequently discouraged, you can still use them to make some extremely spectacular effects! I'll explain how the screen tap computation procedure relates to texture position in this walkthrough. If you want to apply this approach and texture sequence in your projects or give it a try.

![shockwave](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-6.jpg)

### 4\. Transition Curves

There are 11 distinct animation curves included with Spark AR in the Transition patch. Here is a helpful visual aid because it might be challenging to distinguish between a quartic and a quintic when working on a project. With the SDF circle doubled (to sharpen the edge) and inserted into the Patch Pack's alpha channel, the circles are likewise straightforward rectangles. Since RGB values are three times one, the object is white.

![transition curves](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-7.jpg)

### 5\. Realistic Smoke

By adding smoke to a scene, you can easily add a lot of detail and realism. Nothing revolutionary is happening here. The particle emitter creates flat planes of smoke texture that are forced upward. The force slowly shifts left and right as seen in the patch editor. The Fade particle script (created by Josh Beckwith) enlarges the particles and fades them out at the same time.

![realistic smoke](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-8.jpg)

### 6\. Rainbow Glitter

Given how beautifully Glitter Rain was received, I believed it would be fitting to broaden the potential with an HDR setting. While Glitter Rain made use of two different colors, this technique makes use of an entirely colorless substance and gets its color information via HDR.

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
<li><a href="https://extra-tips.techidaily.com/updated-construct-chuckles-adobe-meme-creation/"><u>[Updated] Construct Chuckles  Adobe Meme Creation</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-action-camera-essentials-a-novices-purchase-primer/"><u>[New] Action Camera Essentials  A Novice’s Purchase Primer</u></a></li>
<li><a href="https://extra-tips.techidaily.com/the-ultimate-tutorial-on-phantoms-reverse-recording/"><u>The Ultimate Tutorial on Phantom's Reverse Recording</u></a></li>
<li><a href="https://extra-tips.techidaily.com/assemble-mp3-files-with-powerpoint-narratives/"><u>Assemble MP3 Files with PowerPoint Narratives</u></a></li>
<li><a href="https://extra-tips.techidaily.com/ideal-hosts-elevating-youtube-video-audiences/"><u>Ideal Hosts Elevating YouTube Video Audiences</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-10-must-have-plug-ins-for-final-cut-cinematography/"><u>[Updated] 10 Must-Have Plug-Ins for Final Cut Cinematography</u></a></li>
<li><a href="https://extra-tips.techidaily.com/huawei-p10-analysis-unveiling-performance-and-design/"><u>Huawei P10 Analysis  Unveiling Performance & Design</u></a></li>
<li><a href="https://extra-tips.techidaily.com/prestigious-zooids-introduction-spotlight/"><u>Prestigious Zooids  Introduction Spotlight</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-ascending-altitudes-in-depth-analysis-of-the-gopro-karma-drone/"><u>2024 Approved  Ascending Altitudes  In-Depth Analysis of the GoPro Karma Drone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-complete-biomechanical-study-2023/"><u>[New] Complete Biomechanical Study 2023</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-5-strategies-for-enhancing-iphone-hdr-footage-in-premiere-pro/"><u>In 2024, 5 Strategies for Enhancing iPhone HDR Footage in Premiere Pro</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-best-15-gopro-cutting-and-editing-software/"><u>[Updated] Best 15 GoPro Cutting and Editing Software</u></a></li>
<li><a href="https://extra-tips.techidaily.com/amplifying-visuals-expert-guide-to-snapchat-zoom-for-2024/"><u>Amplifying Visuals  Expert Guide to Snapchat Zoom for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/link-audio-clips-to-powerpoint-slides/"><u>Link Audio Clips to PowerPoint Slides</u></a></li>
<li><a href="https://extra-tips.techidaily.com/visual-representations/"><u>Visual Representations</u></a></li>
<li><a href="https://extra-tips.techidaily.com/harmonizing-history-best-theme-songs-in-anime/"><u>Harmonizing History  Best Theme Songs in Anime</u></a></li>
<li><a href="https://extra-tips.techidaily.com/wholesale-sky-shelves-economic-bulk-data-holder/"><u>Wholesale Sky Shelves  Economic Bulk Data Holder</u></a></li>
<li><a href="https://extra-tips.techidaily.com/subtly-lowering-volume-alives-guide/"><u>Subtly Lowering Volume  Alive’s Guide</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-best-value-shooters-with-full-spherical-capture/"><u>[New] Best Value Shooters with Full Spherical Capture</u></a></li>
<li><a href="https://extra-tips.techidaily.com/acquiring-high-clarity-imagery-without-limitations-for-2024/"><u>Acquiring High-Clarity Imagery without Limitations for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/youtube-tricks-for-enhancing-screen-real-estate/"><u>YouTube Tricks for Enhancing Screen Real Estate</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-budget-friendly-cloud-strategies-revealed/"><u>[New] Budget-Friendly Cloud Strategies Revealed</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-canva-cinematography-perfecting-music-cropping-and-editing/"><u>2024 Approved  Canva Cinematography  Perfecting Music Cropping and Editing</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-deep-dive-into-freeweb-recorder-v2-interface/"><u>2024 Approved  Deep Dive Into FreeWeb Recorder V2 Interface</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-android-app-not-installed-error-on-xiaomi-civi-3-disney-100th-anniversary-edition-quickly-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Android App Not Installed Error on Xiaomi Civi 3 Disney 100th Anniversary Edition Quickly? | Dr.fone</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-in-2024-windows-8-video-editor-easy-avi-file-editing-made-possible-2023-edition/"><u>New In 2024, Windows 8 Video Editor Easy AVI File Editing Made Possible - 2023 Edition</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-2024-approved-resize-with-confidence-the-up-to-date-aspect-ratio-guide-for-social-media/"><u>Updated 2024 Approved Resize with Confidence The Up-to-Date Aspect Ratio Guide for Social Media</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/crafting-engaging-bio-stories-a-guide-to-stand-out-on-fb-for-2024/"><u>Crafting Engaging Bio Stories – A Guide to Stand Out on FB for 2024</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-create-cartoon-avatars-from-your-photos-for-2024/"><u>Updated Create Cartoon Avatars From Your Photos for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/step-by-step-guide-to-watching-facebook-live-events-for-2024/"><u>Step-by-Step Guide to Watching Facebook Live Events for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-melodies-that-matter-instagram-music-guide/"><u>[New] Melodies that Matter  Instagram Music Guide</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-the-complete-guide-to-reversed-videos-on-instagram/"><u>[New] 2024 Approved  The Complete Guide to Reversed Videos on Instagram</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-song-selection-guide-copyright-free-melodies-for-montages-for-2024/"><u>Updated Song Selection Guide Copyright-Free Melodies for Montages for 2024</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-vn-video-editor-pc-edition-a-brief-inspection-for-2024/"><u>Updated VN Video Editor PC Edition A Brief Inspection for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/the-art-of-connection-4-ways-to-tie-in-your-fb-story-for-2024/"><u>The Art of Connection  4 Ways to Tie in Your Fb Story for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-optimal-sound-systems-under-100-for-immersive-gameplay/"><u>In 2024, Optimal Sound Systems Under $100 for Immersive Gameplay</u></a></li>
</ul></div>

