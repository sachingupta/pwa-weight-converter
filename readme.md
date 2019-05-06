# Tutorial followed
https://medium.com/backticks-tildes/build-your-first-progressive-web-app-a-weight-converter-app-and-deploy-to-netlify-b55ed4a86413


# # 3 basic criteria for a PWA

#1 Service worker
A service worker is a script that allows your browser to run in the background, 
separate from a web page, opening the door to features that don’t need a web page or user interaction. 
Today, they already include features like push notifications and background sync. 
Read more https://developers.google.com/web/fundamentals/primers/service-workers/ 

#2 Manifest file
The web app manifest is a simple JSON file that tells the browser about your web application 
and how it should behave when ‘installed’ on the user’s mobile device or desktop. 
Having a manifest is required by Chrome to show the Add to Home Screen prompt. 
Read more https://developers.google.com/web/fundamentals/web-app-manifest/

#Icons

This icons control your application and are provided in different sizes for different devices. 
Your PWA app will not work without them.

Your PWA Icons sizes should be in px and in the following sizes: 72x72 , 96x96 , 128x128 , 144x144 , 152x152 , 192x192 , 384x384 , 512x512
You can use the Web Manifest Generator to generate your manifest.json https://app-manifest.firebaseapp.com/