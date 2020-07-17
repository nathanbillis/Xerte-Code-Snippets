# Overview
Fades and Zooms in the title over 3 seconds.

## Demo
[![Image from Gyazo](https://i.gyazo.com/06eb91639269d4a9f454de998b7c27e6.gif)](https://gyazo.com/06eb91639269d4a9f454de998b7c27e6)


# Styles
```css
@keyframes fadeZoomIn {
0% {opacity: 0; transform: scale(.3); }
100% {opacity: 1; transform: scale(1); }
}
.fadeZoomIn {
animation: fadeZoomIn 3s;
-webkit-animation: fadeZoomIn 3s;
}
```
# Script
```javascript
$("#pageContents").addClass("fadeZoomIn");
```