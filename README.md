# 3d-mode
lThis is a experimental custom element that allows 3D objects (currently, OBJ and gLTF format) to be loaded into a document and rendered inline, just like any other external resource. Additionally, any CSS transforms applied to the element will be passed on to the 3D model, allowing complex objects to be placed and maniplulated using just CSS.
![preview (1)](https://zjxdeyxmnx84qs2guhiviw.on.drv.tw/host/)


## Limitations

* Support for the gLTF and OBJ model formats - other formats will be added in the future.
* File format is currently determined by file extension (`.obj` for OBJ and `.gltf`/`.glb` for gLTF).
* At the moment Safari doesn't scroll models because of a bug with `scrollTop`.
* `transform-style: flat` isn't supported yet.
