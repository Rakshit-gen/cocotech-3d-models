# CocoTech 3D layer models

Interactive 3D models of the two CocoTech products, with each layer pulled apart:

- **Supercapacitor test cell**: current collectors, coconut-shell activated carbon electrodes, separator with electrolyte, and the ions that gather at each electrode when charged.
- **Coir acoustic panel**: breathable fabric facing and the coir fiber + bio-based binder core, shown against a wall.

Drag to rotate, scroll to zoom, use the slider to separate or collapse the layers, and click a layer to isolate it.

Layers and descriptions come from the [cocotech](https://github.com/Rakshit-gen/cocotech) research notes. The models are schematic and not to scale: layer thicknesses are exaggerated so each one is visible.

## Run

```sh
python3 -m http.server 4173 --bind 127.0.0.1
```

Open http://127.0.0.1:4173. three.js loads from jsDelivr, so an internet connection is needed.
