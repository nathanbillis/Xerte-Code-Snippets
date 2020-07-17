# Overview
Fades out the title over 3 seconds.

## Demo
[![Image from Gyazo](https://i.gyazo.com/9113382c38b790b1b6d6da03bb8357ce.gif)](https://gyazo.com/9113382c38b790b1b6d6da03bb8357ce)

# Styles
```css
@keyframes fadeIn {
0% {opacity: 0; }
100% {opacity: 1;}
}
.fadeIn {
animation: fadeIn 3s;
-webkit-animation: fadeIn 3s;
}
```
# Script
```javascript
$("#pageContents").addClass("fadeIn");