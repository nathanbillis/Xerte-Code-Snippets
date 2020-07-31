# Overview
This code snippet will add to the footer copywrite infomation and remove the progress bar. To add this to the view you'll need to enable a few settings at project level. 

You will need to Enable:
- Progress bar		
- Script
- Styles

This should be added a the index of the learning object. It should look like the image below: 

[![Xerte Screenshot](https://i.gyazo.com/58a8bff595bb3b2dce0745567a418bd6.png)](https://gyazo.com/58a8bff595bb3b2dce0745567a418bd6)

## Example
[![Image from Gyazo](https://i.gyazo.com/fd0b1faa72fa5a4e23f34b8d05340d61.png)](https://gyazo.com/fd0b1faa72fa5a4e23f34b8d05340d61)
# Styles
```css
/*
 * Font Styling for the footer, font-size changes the 
 * footer size and padding-top changes the padding from  
 * the top of the box.
 */

p.ctext{
    font-size: 0.9em;
    padding-top: 15px;
    }
```
# Script
```javascript
// Remove footer progress text and replace with the copywrite text.
$( "#x_footerProgress p" ).replaceWith( "<p class=ctext>&#169; University of York 2020 </p>" );

// The following line removes the progress bar, to add it back delete the line below.
$( ".pbContainer").remove();
```