# LOD2 Building Model Tiles

The LOD2 building models can be directly downloaded as CityGML 2.0 datasets from the [open data portal](https://geodaten.bayern.de/opengeodata/OpenDataDetail.html?pn=lod2) of the [Bavarian State Mapping Agency](https://www.ldbv.bayern.de/englisch.html).
The required tiles are as follows:

- [676_5402.gml](https://download1.bayernwolke.de/a/lod2/citygml/676_5402.gml)
- [676_5404.gml](https://download1.bayernwolke.de/a/lod2/citygml/676_5404.gml)
- [678_5402.gml](https://download1.bayernwolke.de/a/lod2/citygml/678_5402.gml)
- [678_5404.gml](https://download1.bayernwolke.de/a/lod2/citygml/678_5404.gml)

The tiles can be downloaded with the following command:

```bash
curl --remote-name-all https://download1.bayernwolke.de/a/lod2/citygml/{676_5402,676_5404,678_5402,678_5404}.gml
```

The file [correspondances.csv](./correspondances.csv) provides the corresponding IDs between the LOD2 building models and the LOD3 building models.
