# Road Space Model

This OpenDRIVE dataset is provided as demo data in the [customer area](https://www.3d-mapping.de/en/customer-area/demo-data/) from the company [3D Mapping Solutions](https://www.3d-mapping.de/en/).
It is licensed under [CC BY-NC-SA 4.0](http://creativecommons.org/licenses/by-nc-sa/4.0/).

The dataset can be converted to CityGML 2.0 and 3.0 using [r:trån](https://rtron.io):

```bash
java -jar rtron.jar opendrive-to-citygml ./ ../citygml --convert-to-citygml2 --add-offset 0.0 0.0 -46.47877 --crs-epsg 25832 --remove-road-object-of-type BUILDING
java -jar rtron.jar opendrive-to-citygml ./ ../citygml --add-offset 0.0 0.0 -46.47877 --crs-epsg 25832 --remove-road-object-of-type BUILDING
```
