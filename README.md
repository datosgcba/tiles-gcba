# tiles-gcba
Documentación para consumir los tiles publicados en BA Data

## Tiles Mapa BA

[Dataset](https://data.buenosaires.gob.ar/dataset/tiles-mapa-interactivo-buenos-aires "Tiles Mapa BA")

Para consumir los tiles del mapa de Buenos Aires, consumir esta URL: https://servicios.usig.buenosaires.gob.ar/mapcache/tms/1.0.0/amba_con_transporte_3857@GoogleMapsCompatible/{z}/{x}/{-y}.png desde algún sistema GIS que permita importar los tiles como capa base.

Accediendo directamente a la URL no se obtiene ningún resultado, esta URL debe ser consumida desde algún sistema GIS. Por ejemplo, desde QGIS se obtiene en "XYZ Tiles" -> "New Connection" y pasando la URL de los tiles en el campo correspondiente.

## Tiles Fotografía Aérea

[Dataset](https://data.buenosaires.gob.ar/dataset/tiles-fotografia-aerea "Tiles Fotografía Aérea")

Para consumir los tiles de fotografía aérea, consumir esta URL: http://servicios.usig.buenosaires.gob.ar/mapcache/tms/1.0.0/fotografias_aereas_2017_caba_3857@GoogleMapsCompatible/%7Bz%7D/%7Bx%7D/%7B-y%7D.png desde algún sistema GIS que permita importar los tiles como capa base.

Accediendo directamente a la URL no se obtiene ningún resultado, esta URL debe ser consumida desde algún sistema GIS. Por ejemplo, desde QGIS se obtiene en "XYZ Tiles" -> "New Connection" y pasando la URL de los tiles en el campo correspondiente.
