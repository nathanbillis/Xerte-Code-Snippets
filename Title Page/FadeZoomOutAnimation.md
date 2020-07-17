# Overview
Fades and Zooms out the title over 3 seconds.

## Demo
[![Image from Gyazo](https://i.gyazo.com/9113382c38b790b1b6d6da03bb8357ce.gif)](https://gyazo.com/9113382c38b790b1b6d6da03bb8357ce)

# Styles
```css
@keyframes fadeZoomOut {
0% {opacity: 1; transform: scale(1); }
100% {opacity: 0; transform: scale(.3); }
}
.fadeZoomOut {
animation: fadeZoomOut 3s;
-webkit-animation: fadeZoomOut 3s;
}
```
# Script
```javascript
$("#pageContents").addClass("fadeZoomOut");
```