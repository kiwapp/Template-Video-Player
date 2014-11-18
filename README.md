Template_Video_Player
=====================

This app provides a video player looping on a playlist.  
This playlist can have an unlimited number of videos.  

## File organisation
- `app/` : Folder who contains all application sources. 
    - `./index.html` : The index file, it loads the application and dependencies
    - `./manifest.json` : Kiwapp application manifest
    - `./kiwapp.js` : Kiwapp library enabling bridge to native
    - `./kiwappVideo.js` : Kiwapp library providing acces to video player methods
- `app.zip` : zip file of content App folder, add this zip to the Kiwapp Retail Manager 
- `video-demo.avi` : video file to test the application (this video works only on Android devices, no iOS). 

## About the application

This application is built with Kiwapp libraries only.

## Make it work

First, you have to upload the app.zip file to the Kiwapp Retail Manager.  
Once is done, some configuration is needed :

- In the `Template gallery` section, find your application.  
- Then click on the `Details` button and then `Advanced settings.  
- Here you can upload resources binded to this application. Upload your `video`in an `assets/` repository.  
- Once you did, go to the `shops`section, and find your `App Set`.  
- Click on the gear to the right of your application to `Setup app`.  
- You have an interface to customize the playlist. This interface lets you add pathes to videos. Click on the button `Add the pathes to the videos you want to play. The order will be the playlist order.` to add a path to a video. This will be the first played video in the playlist. Order matters.  
- Give the path to the video you previously uploaded. Here the path is `../assets/video-demo.avi`.
- Click on `OK` button
- The setup is done ! Test your application downloading it on a device !