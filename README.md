# jQuery.scrollSpeed
Extension jQuery légère pour modifier la vitesse de défilement dans les navigateurs Web modernes. Prend en charge la direction de défilement vertical ou horizontal, y compris l'assouplissement défini par l'utilisateur.

## Installation
Inclure la dernière version de[jQuery](http://jquery.com/download) et `jQuery.scrollSpeed.js` dans le `<head>` de votre document HTML:
```html
<script src="jQuery.min.js"></script>  
<script src="jQuery.scrollSpeed.js"></script>
```
## Comment utiliser le script
Reference the `scrollSpeed()` method and modify the `step` and `speed` parameters to create the desired scrolling effect. The `step` parameter defaults to `100` units, while `speed` defaults to `800` milliseconds; custom easing is optional. See the live demo: [code.nath.co/scrollSpeed](http://code.nath.co/scrollSpeed)

```javascript
$(function() {  

    // Default
    jQuery.scrollSpeed(100, 800);
    
    // Custom Easing
    jQuery.scrollSpeed(100, 800, 'easeOutCubic');
    
});
```  

## Browser Support
– Google Chrome  
– Safari ( Desktop )  
– Internet Explorer ( Disabled for performance )  
– Firefox  
– Opera ( Not Tested )  

## Release Notes
**jQuery.scrollSpeed 1.0**   
– Initial Release   
**jQuery.scrollSpeed 1.0.1**      
– Added support for horizontal scrolling   
– Minor code cleanup  
**jQuery.scrollSpeed 1.0.2**      
– Added paramater for custom easing  

## Feedback
If you discover any issues or have questions regarding usage, please send a message to [code@nath.co](mailto:code@nath.co) or find me on GitHub [@nathco](https://github.com/nathco).
