# SAO Vaccine Pass

A very inspired UI for showing your vaccine pass in Hong Kong. 

Coded without any use of frameworks, which should make it load very quickly. 

## Background

https://www.thestandard.com.hk/breaking-news/section/4/198149/Hong-Kong-drops-LeaveHomeSafe-check-in-mandate,-amber-code-scrapped

For some people, it may not be desirable to use LeaveHomeSafe anymore when the need is just to present a Vaccine QR code. 

This is especially true due to the permissions it requests and the data it transmits. 

## Demo

https://evnchn.github.io/SAO-Vaccine-Pass-demo/offline.html

## Usage guide

Use either ```index.html```, ```offline.html```, or the Demo URL above. 

For ```index.html```, SVG files need to be placed in the same directory. 

If you open the HTML file directly on the mobile device: 
- Best method: Edit ```scancontent``` variable in the HTML file (or else it will link to https://youtu.be/dQw4w9WgXcQ as a default)

Alternatively
- https://evnchn.github.io/SAO-Vaccine-Pass-demo/offline.html#REPLACE_THIS
- Edit REPLACE_THIS in the URL to be the content of the QR code. 
- Since it is a URL hash, editing it doesn't cause the page to refresh. 
  - Refresh manually to see the change. 

## Custom skins

Edit the ```top```, ```bottom``` images respectively. 

## Todos

Easier means of changing QR code content. 

Easier means of changing "Vaccine QR code" text to something else without using Adobe Illustrator. 

## Resources used

- https://stackoverflow.com/questions/14068103/disable-antialising-when-scaling-images
- https://github.com/metafloor/bwip-js
- https://github.com/SAO-UI/sao-assets
  - https://www.deviantart.com/darkblackswords
