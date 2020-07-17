# Overview
Fades In the title over 3 seconds.

## Demo
[![Image from Gyazo](https://i.gyazo.com/cd578256ffe818ecde338c7909441f65.gif)](https://gyazo.com/cd578256ffe818ecde338c7909441f65)

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
```