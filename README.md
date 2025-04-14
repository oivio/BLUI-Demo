This Repository is updated demo for UE5 Custom Web Browser plugin for https://github.com/getnamo/BLUI-Unreal/ 

BLUI is an Unreal Engine plugin that allows easy interaction with the Chromium Embedded Framework. It provides a simple Material Instance and input functions to help streamline the rendering of rich HTML interfaces.
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

Installation:
If you clone fork or clone repository make sure to download Win.zip from from https://github.com/oivio/BLUI-Demo/releases it is only requierd for source code.
After downloading it have to be just unziped and placed inside Directory -> Plugins\BLUI-Unreal\ThirdParty\cef\
