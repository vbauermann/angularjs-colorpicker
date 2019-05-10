# angularjs-colorpicker
AnguarJS colorpicker with no dependencies required.

# Demo page
https://vbauermann.github.io/angularjs-colorpicker/index.html

# Usage
* Include angularjs-colorpicker.min.js and angularjs-colorpicker.min.css:
```html
<script src="js/angularjs-colorpicker.min.js"></script>
<link rel="stylesheet" type="text/css" href="css/angularjs-colorpicker.min.css" />
```
* Add module:
```javascript
angular.module('app', ['colorpicker']);
```
* In your view:
```html
<input color-picker color-picker-model="var"/>
```

#Options
Default option is the first item.
```html
<input color-picker 
       color-picker-model="var"
       color-picker-show-value="true, false"
       color-picker-output-format="'rgba', 'hsla', 'hex'"
       color-picker-position="right, left, top, bottom"
       color-picker-fixed-position="false, true"
       color-picker-show-input-spinner="true"
       color-picker-spinner-rgba-steps="1;1;1;0.1"
       color-picker-spinner-hsla-steps="1;1;1;0.1"
       color-picker-show-cancel-button="false, true"
       color-picker-cancel-button-class="your custom class"
  />
```

#Extra
If you want to change precaculated images for color picker sliders you can find a few directives in "slider-creator" folder.

* For example this code will generate a saturation and value slider:
```html
<div saturation
     saturation-width="230" 
     saturation-height="130">
     <canvas></canvas><br>
     <textarea></textarea>
</div>
```

* Demo:
https://vbauermann.github.io/angularjs-colorpicker/slider-creator/slider-images.html

