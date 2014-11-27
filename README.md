Touch Emulator
========

Improved version of [Touch Emulator](http://hammerjs.github.io/touch-emulator/) which has following
changes:

- Dots now have CSS *z-index* 9999
- For better usability you can use four predefined themes: *default*, *dark*, *red*, *blue*. Usage:
````html
<script> TouchEmulator({ theme: 'red' }); </script>
````
- ... or you can apply your own colors via *background* and *border* options:
````html
<script> TouchEmulator({ background: '#ff0', border: '5px solid #0ff' }); </script>
````
If you define a theme **and** a background or border, background or border will overwrite the theme values.
- Customizable *opacity*, *width* and *height* of dots:
````html
<script> TouchEmulator({ opactiy: 1.0, width: '100px', height: '100px' }); </script>
````
