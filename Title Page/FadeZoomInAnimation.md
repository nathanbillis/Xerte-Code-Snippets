# Overview
Fades in the title over 3 seconds.

## Demo
[![Image from Gyazo](https://i.gyazo.com/06eb91639269d4a9f454de998b7c27e6.gif)](https://gyazo.com/06eb91639269d4a9f454de998b7c27e6)


# Styles
```css
@keyframes fadeIn {
0% {opacity: 0; transform: scale(.3); }
100% {opacity: 1; transform: scale(1); }
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