# netgis-client
WebGIS-Client in development for NetGIS / Geoportal RLP.

## Disclaimer:
In early development, things will change and break frequently!

## Principles:
- **Small Footprint:** Because this map clients purpose is to be included in other websites in multiple instances, no frameworks are used to keep it lean. Obviously some libraries like OL are necessary (see dependencies), but the goal is to mostly rely on browser APIs only.
- **Backwards Compatibility:** This map client may be used in work environments with relatively old hardware and software.
- **Modularization:** Functionality is encapsulated in module classes (classic JS prototyped objects).
- **Programming Patterns:** At the core this client makes heavy use of the Observer and State patterns. Where possible pure functions shall be implemented to reduce side effects.

## Dependencies:
### Core:
- OpenLayers 6
- FontAwesome 5

### Optional:
- Proj4js
- JSTS
- ShapefileJS
- JSPDF
- GIFJS

## Documentation:
- Follow the [Tutorial](https://github.com/sebastianpauli/netgis-client/blob/main/TUTORIAL.md)
- See the [How To](https://github.com/sebastianpauli/netgis-client/blob/main/HOWTO.md) guides for more examples
- View the [Online Documentation](https://sebastianpauli.net/netgis/docs/)
- See the [Demo](https://github.com/sebastianpauli/netgis-client/tree/main/demo) folder for example implementations
