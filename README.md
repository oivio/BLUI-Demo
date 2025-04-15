<p dir="auto" align="center">
  <a href="https://github.com/getnamo/BLUI-Unreal/releases">
<img src="https://camo.githubusercontent.com/69cced9981121f9c9f0c12493cb9eef88fed4a9912be16b6c412a5a61ba6b231/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f72656c656173652f6765746e616d6f2f424c55492e7376673f7374796c653d666c61742d737175617265" alt="release" data-canonical-src="https://img.shields.io/github/release/getnamo/BLUI.svg?style=flat-square" style="max-width: 100%;"></a>
<a target="_blank" rel="noopener noreferrer nofollow" href="https://cloud.githubusercontent.com/assets/1334174/5969395/201a1202-a7f1-11e4-98a4-12bc6793f830.png"><img src="https://cloud.githubusercontent.com/assets/1334174/5969395/201a1202-a7f1-11e4-98a4-12bc6793f830.png" alt="BLUI-logo" style="max-width: 100%;"></a>
<a href="https://github.com/getnamo/BLUI-Unreal/releases"><img src="https://camo.githubusercontent.com/45cd18b2a50b8fb9d4de5c66b850b1ea1cff429e94caec9d4949e7603ea5f186/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f646f776e6c6f6164732f6765746e616d6f2f424c55492d556e7265616c2f746f74616c2e737667" alt="Github All Releases" data-canonical-src="https://img.shields.io/github/downloads/getnamo/BLUI-Unreal/total.svg" style="max-width: 100%;"></a>
</p>

<p dir="auto" align="center">
  This Repository is updated demo for UE5 BLUI Plugin for https://github.com/getnamo/BLUI-Unreal/ 

  <img src="https://github.com/user-attachments/assets/04fbe2ed-8d89-4c6a-9f14-50ce612951ee" align="center" width="80%" height="80%">
</p>

<b>BLUI</b> is an Unreal Engine plugin that allows easy interaction with the Chromium Embedded Framework. It provides a simple Material Instance and input functions to help streamline the rendering of rich HTML interfaces.
It tries to stay out of the way as much as possible. All rendering of the DOM and processing of the JavaScript happens in a separate process, just like Chromium. 
The only updates the texture inside the material instance when Chromium requests a redraw, not every tick, saving a bit more processing along the way.

Features:
- Chromium Powered (same thing that powers Google Chrome!)
- Fully compatible with every web technology that Chrome/Chromium works with. (HTML5, WebAudio, WebSockets etc.)
- No specific ties to any in game class, simple use Blueprints (or C++) to create a new "BluEye" object and grab its material instance, then you can paint it on anything!
- Execute JavaScript in the "browser" from your game to pass data to the web page
- Using blu_event JS native function you can pass data from the page's JavaScript back into UE4!
- C++ or Blueprints, works with both!
- Setting up the editor and project

Installation :</br>
If you clone fork or clone repository make sure to download Win.zip from from https://github.com/oivio/BLUI-Demo/releases it is only requierd for source code.
After downloading it have to be just unziped and placed inside Directory -> Plugins\BLUI-Unreal\ThirdParty\cef\
