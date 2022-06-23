# Learnfiy
## Augumented Reality APP (learnify)


## Features

- Models for Learning English Alphabets
- Models for Learning Mathematics Shapes
- Models for Learning Biology
- Models for Learning Chemistry molucules
- Models to listen music based on the type of markers

## Technology And Frameworks
Web Developnment app to demostrate 3-models working by using built-in library

- [HTML] - HTML enhanced for web apps!
- [CSS] - To design the web page
- [JavaScript] - To add the functionality to our App.

Build in library ->
- [https://ar-js-org.github.io/AR.js/] - lightweight library for Augmented Reality on the Web
- [https://aframe.io/docs] -AFrame is a web framework for building virtual reality (VR) experiences. A-Frame is based on top of HTML

To add Models
- [https://sketchfab.com/features/gltf] - to use built in models

```sh
everything should be embedded in <a-scence> tag
<!-- adding the to the html static file camera -->
<a-entity camera></a-entity>

<!-- To explain how to use barcode marker -->
<a-marker type="barcode" value="0">
    <a-entity position="0 0 0" scale="0.01 0.01 0.01" rotation="0 90 0" gltf-model="#apple"></a-entity>
</a-marker>
```



## License

Ajay Paswan

**Free Software, Hell Yeah!**

