# LOD3 Building Models Combined

In this folder, FME saves the LOD3 building models as a combined CityGML 2.0 data set.

To upgrade them to CityGML 3.0, the [citygml-tools](https://github.com/citygml4j/citygml-tools) can be used with the following command:

```bash
citygml-tools upgrade ./lod3_building_models.gml 
```
