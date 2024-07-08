---
title: "In 2024, A Beginner's Tutorial on Using LUTs in AR"
date: 2024-05-24T14:07:54.931Z
updated: 2024-05-25T14:07:54.931Z
tags: 
  - screen-recording
  - ai video
  - ai audio
  - ai auto
categories: 
  - ai
  - screen
description: "This Article Describes In 2024, A Beginner's Tutorial on Using LUTs in AR"
excerpt: "This Article Describes In 2024, A Beginner's Tutorial on Using LUTs in AR"
keywords: "AR LUT Basics,Beginners Guide to LUTs,Using LUTs in AR,LUTs for AR Devices,Introduction to AR LUTs,Learning AR LUT Techniques,Essential AR LUT Tutorial"
thumbnail: https://www.lifewire.com/thmb/4rrIDG7880IVGiEmcN8e0zeGrqQ=/400x300/filters:no_upscale():max_bytes(150000):strip_icc()/Robothandholdinganapple-fbe6ff482ed641e188dd6650b9ac132e.jpg
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
<li><a href="https://extra-tips.techidaily.com/new-creating-a-unique-identity-in-the-flood-of-live-streams/"><u>[New] Creating a Unique Identity in the Flood of Live Streams</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-a-nostalgic-journey-through-time-with-stop-motion-classics/"><u>In 2024, A Nostalgic Journey Through Time with Stop-Motion Classics</u></a></li>
<li><a href="https://extra-tips.techidaily.com/acid-pro-evaluation-finding-reliable-counterparts-for-2024/"><u>ACID Pro Evaluation  Finding Reliable Counterparts for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/from-script-to-screen-effective-editing-on-windows-10-for-filmmakers/"><u>From Script to Screen  Effective Editing on Windows 10 for Filmmakers</u></a></li>
<li><a href="https://extra-tips.techidaily.com/perfect-your-visual-storytelling-inserting-titles-into-photo-videos-on-windows/"><u>Perfect Your Visual Storytelling  Inserting Titles Into Photo Videos on Windows</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-acclaimed-top-5-effortless-action-camcorders/"><u>2024 Approved  Acclaimed Top 5 Effortless Action Camcorders</u></a></li>
<li><a href="https://extra-tips.techidaily.com/av1-triumph-surpassing-vp9-performance/"><u>AV1 Triumph  Surpassing VP9 Performance</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-behind-the-shoot-spots-seeking-budget-friendly-stunning-tiktok-backdrops/"><u>[Updated] Behind-the-Shoot Spots  Seeking Budget-Friendly, Stunning TikTok Backdrops</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-virtual-reality-technology-current-state-and-future-challenges/"><u>[New] Virtual Reality Technology  Current State and Future Challenges</u></a></li>
<li><a href="https://extra-tips.techidaily.com/advances-in-syma-x8c-flight-autonomy/"><u>Advances in Syma X8C Flight Autonomy</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-auditory-artifacts-essential-ringtone-archives-online/"><u>[Updated] Auditory Artifacts  Essential Ringtone Archives Online</u></a></li>
<li><a href="https://extra-tips.techidaily.com/supercharge-your-selfie-game-on-iphone-the-10-must-download-apps/"><u>Supercharge Your Selfie Game on iPhone  The 10 Must-Download Apps</u></a></li>
<li><a href="https://extra-tips.techidaily.com/step-into-success-10-pivotal-steps-for-exceptional-smm-achievement/"><u>Step Into Success  10 Pivotal Steps for Exceptional SMM Achievement</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-best-action-cameras-with-a-front-facing-screen/"><u>2024 Approved  Best Action Cameras with A Front Facing Screen</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-control-screen-size-with-swift-iphone-adjustments/"><u>[Updated] Control Screen Size with Swift iPhone Adjustments</u></a></li>
<li><a href="https://extra-tips.techidaily.com/infinite-storage-pathways-select-services-showcase/"><u>Infinite Storage Pathways  Select Services Showcase</u></a></li>
<li><a href="https://extra-tips.techidaily.com/optimal-methods-to-source-stock-photography-and-visuals/"><u>Optimal Methods to Source Stock Photography and Visuals</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-a-beginners-guide-to-quantum-hdr-systems/"><u>[Updated] A Beginner’s Guide to Quantum HDR Systems</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-best-10-heavy-lift-drones/"><u>In 2024, Best 10 Heavy Lift Drones</u></a></li>
<li><a href="https://extra-tips.techidaily.com/highest-ranked-live-streamers-with-local-channel-access-2024/"><u>Highest-Ranked Live Streamers with Local Channel Access, 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/unveiling-the-power-of-free-countdown-tools-for-time-management/"><u>Unveiling the Power of Free Countdown Tools for Time Management</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-covert-measures-for-efficient-home-based-learning/"><u>2024 Approved  Covert Measures for Efficient Home-Based Learning</u></a></li>
<li><a href="https://extra-tips.techidaily.com/from-novice-to-pro-comprehensible-periscope-steps/"><u>From Novice to Pro  Comprehensible Periscope Steps</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-crack-the-code-top-10-hidden-iphone-x-functions/"><u>[Updated] Crack The Code  Top 10 Hidden iPhone X Functions</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-5-easy-steps-to-record-voice-on-your-windows-11-pc/"><u>[New] 5 Easy Steps to Record Voice on Your Windows 11 PC</u></a></li>
<li><a href="https://extra-tips.techidaily.com/eight-unbeatable-tablets-offering-richer-image-editing-experiences/"><u>Eight Unbeatable Tablets Offering Richer Image Editing Experiences</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-depth-review-samsungs-immersive-360-degree-camera/"><u>In-Depth Review  Samsung's Immersive 360-Degree Camera</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-calm-and-clear-how-to-smooth-out-a-jittery-gopro-video/"><u>[Updated] Calm and Clear  How to Smooth Out a Jittery GoPro Video</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-craft-your-story-leading-drawers-in-ipados/"><u>2024 Approved  Craft Your Story  Leading Drawers in iPadOS</u></a></li>
<li><a href="https://extra-tips.techidaily.com/top-choices-for-turning-photos-into-cinematic-content/"><u>Top Choices for Turning Photos Into Cinematic Content</u></a></li>
<li><a href="https://extra-tips.techidaily.com/beginners-booklet-on-backdrops-and-blending/"><u>Beginner's Booklet on Backdrops & Blending</u></a></li>
<li><a href="https://extra-tips.techidaily.com/photographys-best-haven-seamlessly-merge-free-and-charged-digital-space/"><u>Photography's Best Haven  Seamlessly Merge Free and Charged Digital Space</u></a></li>
<li><a href="https://extra-tips.techidaily.com/streamlining-color-correction-leveraging-look-up-tables-from-cg-central/"><u>Streamlining Color Correction  Leveraging Look-Up Tables From CG Central</u></a></li>
<li><a href="https://extra-tips.techidaily.com/eliminating-watermarks-from-your-stock-collections/"><u>Eliminating Watermarks From Your Stock Collections</u></a></li>
<li><a href="https://extra-tips.techidaily.com/building-competence-with-lut-software-for-2024/"><u>Building Competence with LUT Software for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/win11s-top-5-cost-free-applications-for-recording-screens/"><u>Win11's Top 5 Cost-Free Applications for Recording Screens</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-budgeting-basics-starting-a-successful-podcast/"><u>[Updated] Budgeting Basics  Starting a Successful Podcast</u></a></li>
<li><a href="https://extra-tips.techidaily.com/audiophiles-pathway-selecting-video-audio/"><u>Audiophile's Pathway  Selecting Video Audio</u></a></li>
<li><a href="https://extra-tips.techidaily.com/traveling-lens-quieter-assistant-360/"><u>Traveling Lens Quieter Assistant 360°</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-best-practices-where-to-download-text-overlays/"><u>[New] Best Practices  Where to Download Text Overlays</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-from-setup-to-sharing-comprehensive-guide-for-instagram-and-obs-integration/"><u>In 2024, From Setup to Sharing  Comprehensive Guide for Instagram & OBS Integration</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-transform-vimeo-videos-top-techniques-to-trim-and-tailor-online-sequences-for-2024/"><u>[New] Transform Vimeo Videos  Top Techniques to Trim and Tailor Online Sequences for 2024</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-2024-approved-mastering-audio-quality-an-in-depth-look-at-noise-reduction-in-audacity/"><u>New 2024 Approved Mastering Audio Quality An In-Depth Look at Noise Reduction in Audacity</u></a></li>
<li><a href="https://apple-account.techidaily.com/apple-id-locked-for-security-reasons-on-apple-iphone-11-pro-max-find-the-best-solution-here-by-drfone-ios/"><u>Apple ID Locked for Security Reasons On Apple iPhone 11 Pro Max? Find the Best Solution Here</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-pro-mobile-techniques-for-snapchat-recording-for-2024/"><u>[Updated] Pro Mobile Techniques for Snapchat Recording for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-amazon-primes-trending-series-twitters-choice-2023/"><u>2024 Approved  Amazon Prime's Trending Series - Twitter's Choice, 2023</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-expert-choices-beyond-obs-for-live-streaming/"><u>[New] Expert Choices Beyond OBS for Live-Streaming</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/stitches-and-scrolls-a-guide-to-textile-talent-on-the-app-for-2024/"><u>Stitches & Scrolls  A Guide to Textile Talent on the App for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-5-ios-friendly-fb-videos-optimal-downloading-apps/"><u>In 2024, 5 iOS-Friendly FB Videos  Optimal Downloading Apps</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-in-2024-integrating-siri-voice-techniques-into-tiktok-sharing/"><u>[New] In 2024, Integrating Siri Voice Techniques Into TikTok Sharing</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/essential-guide-to-the-best-tiktok-to-gif-convertors-listed-for-2024/"><u>Essential Guide to the Best TikTok-to-GIF Convertors Listed for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-master-meetings-the-ultimate-list-of-10-free-recorders/"><u>[New] 2024 Approved  Master Meetings  The Ultimate List of 10 Free Recorders</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-in-2024-unlock-live-photos-from-videos-top-converter-apps-and-tips/"><u>Updated In 2024, Unlock Live Photos From Videos Top Converter Apps and Tips</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-in-2024-legend-intro-maker-create-intro-video-with-ease/"><u>Updated In 2024, Legend Intro Maker – Create Intro Video with Ease</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-2024-approved-auditory-augmentation-of-photo-projects-a-comprehensive-guide/"><u>Updated 2024 Approved Auditory Augmentation of Photo Projects A Comprehensive Guide</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/in-2024-culinary-choreography-top-10-viral-kitchen-moves/"><u>In 2024, Culinary Choreography  Top 10 Viral Kitchen Moves</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-instant-record-and-commentary-assistive-software/"><u>[Updated] Instant Record & Commentary Assistive Software</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/recording-made-simple-a-comprehensive-guide-to-archiving-roblox-games-on-your-macbook-for-2024/"><u>Recording Made Simple  A Comprehensive Guide to Archiving Roblox Games on Your MacBook for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-strategies-for-retrieving-private-chat-photos/"><u>In 2024, Strategies for Retrieving Private Chat Photos</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/score-winning-tech-for-documenting-google-meets-freepaid/"><u>Score-Winning Tech for Documenting Google Meets (Free/Paid)</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-how-to-fix-pokemon-go-route-not-working-on-vivo-v27e-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fix Pokemon Go Route Not Working On Vivo V27e? | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-enhancing-insta-videos-3-simple-border-techniques/"><u>[Updated] Enhancing Insta Videos  3 Simple Border Techniques</u></a></li>
<li><a href="https://howto.techidaily.com/fix-the-error-of-unfortunately-the-processcomandroidphone-has-stopped-on-vivo-t2-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix the Error of Unfortunately the Process.com.android.phone Has Stopped on Vivo T2 5G | Dr.fone</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-explore-silent-bubbles-auditory-display-for-2024/"><u>Updated Explore Silent Bubbles Auditory Display for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-fb-quick-views-snap-and-share/"><u>In 2024, FB Quick Views  Snap & Share</u></a></li>
</ul></div>

