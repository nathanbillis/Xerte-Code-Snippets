# Overview
Fades out the title over 3 seconds.

## Demo
[![Image from Gyazo](https://i.gyazo.com/7c27b2bfed13a28f483b63cb007cd55c.gif)](https://gyazo.com/7c27b2bfed13a28f483b63cb007cd55c)

# Styles
```css
@keyframes fadeOut {
0% {opacity: 1; }
100% {opacity: 0;}
}
.fadeOut {
animation: fadeOut 3s;
-webkit-animation: fadeOut 3s;
}
```
# Script
```javascript
$("#pageContents").addClass("fadeOut");
```