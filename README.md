# Light-Zoom
JQuery plugin that use pure css to zoom on images, this enables you to zoom without loading bigger image and zoom even on gif images !

Demo
_____
[Demo](http://codepen.io/JafarAKhondali/pen/bZJqjb)

Installation
_____________
```html
    <link href="glassstyle.css" rel="stylesheet">
    <script src="lightzoom.js"></script>
```


Usage:
______
```javascript
    $(document).ready(function () {
        //Simple usage
        $('img.light-zoom').lightzoom();
        
        //customize
        $('img.light-zoom').lightzoom({
            zoomPower   : 3,    //Default
            glassSize   : 180,  //Default
        });
        
    });
```



