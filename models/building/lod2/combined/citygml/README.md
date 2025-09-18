# LOD2 Building Model Combined

In this folder, FME will save the combined LOD2 building models from the individual tiles as CityGML 2.0 file.

To upgrade it to CityGML 3.0, run the following command using the [citygml-tools](https://github.com/citygml4j/citygml-tools):

```bash
citygml-tools upgrade ./lod2_building_models.gml 
```
