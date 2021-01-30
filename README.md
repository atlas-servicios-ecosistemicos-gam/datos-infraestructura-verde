# Infraestructura verde
## CBIMA
```shell
cd cbima
gdalwarp -t_srs EPSG:3857 -of vrt IV_CBI_RIO_MARIA_AGUILAR.TIF /vsistdout/ | gdal_translate -co compress=lzw  /vsistdin/ IV_CBI_RIO_MARIA_AGUILAR_WEB.TIF
del IV_CBI_RIO_MARIA_AGUILAR.*
gdalwarp -t_srs EPSG:4326 -of vrt IV_CBI_RIO_MARIA_AGUILAR_WEB.TIF /vsistdout/ | gdal_translate -co compress=lzw  /vsistdin/ IV_CBI_RIO_MARIA_AGUILAR.TIF
```

## CBIRT
```shell
cd cbirt
gdalwarp -t_srs EPSG:3857 -of vrt IV_CBI_RIO_TORRES.TIF /vsistdout/ | gdal_translate -co compress=lzw  /vsistdin/ IV_CBI_RIO_TORRES_WEB.TIF
del IV_CBI_RIO_TORRES.*
gdalwarp -t_srs EPSG:4326 -of vrt IV_CBI_RIO_TORRES_WEB.TIF /vsistdout/ | gdal_translate -co compress=lzw  /vsistdin/ IV_CBI_RIO_TORRES.TIF
```

## Curridabat
```shell
cd curridabat
gdalwarp -t_srs EPSG:3857 -of vrt IV_CURRIDABAT.TIF /vsistdout/ | gdal_translate -co compress=lzw  /vsistdin/ IV_CURRIDABAT_WEB.TIF
del IV_CURRIDABAT.*
gdalwarp -t_srs EPSG:4326 -of vrt IV_CURRIDABAT_WEB.TIF /vsistdout/ | gdal_translate -co compress=lzw  /vsistdin/ IV_CURRIDABAT.TIF
```

## La Unión
```shell
cd launion
gdalwarp -t_srs EPSG:3857 -of vrt IV_LA_UNION.TIF /vsistdout/ | gdal_translate -co compress=lzw  /vsistdin/ IV_LA_UNION_WEB.TIF
del IV_LA_UNION.*
gdalwarp -t_srs EPSG:4326 -of vrt IV_LA_UNION_WEB.TIF /vsistdout/ | gdal_translate -co compress=lzw  /vsistdin/ IV_LA_UNION.TIF
```

## Montes de Oca
```shell
cd montesdeoca
gdalwarp -t_srs EPSG:3857 -of vrt IV_MONTES_DE_OCA.TIF /vsistdout/ | gdal_translate -co compress=lzw  /vsistdin/ IV_MONTES_DE_OCA_WEB.TIF
del IV_MONTES_DE_OCA.*
gdalwarp -t_srs EPSG:4326 -of vrt IV_MONTES_DE_OCA_WEB.TIF /vsistdout/ | gdal_translate -co compress=lzw  /vsistdin/ IV_MONTES_DE_OCA.TIF
```

## San José
```shell
cd sanjose
gdalwarp -t_srs EPSG:3857 -of vrt IV_SAN_JOSE.TIF /vsistdout/ | gdal_translate -co compress=lzw  /vsistdin/ IV_SAN_JOSE_WEB.TIF
del IV_SAN_JOSE.*
gdalwarp -t_srs EPSG:4326 -of vrt IV_SAN_JOSE_WEB.TIF /vsistdout/ | gdal_translate -co compress=lzw  /vsistdin/ IV_SAN_JOSE.TIF
```

## Corredores-cantones
```shell
cd corredores-cantones
gdalwarp -t_srs EPSG:3857 -of vrt IV_CORREDORES_CANTONES.TIF /vsistdout/ | gdal_translate -co compress=lzw  /vsistdin/ IV_CORREDORES_CANTONES_WEB.TIF
del IV_CORREDORES_CANTONES.*
gdalwarp -t_srs EPSG:4326 -of vrt IV_CORREDORES_CANTONES_WEB.TIF /vsistdout/ | gdal_translate -co compress=lzw  /vsistdin/ IV_CORREDORES_CANTONES.TIF
```

## Corredores
```shell
cd corredores
gdalwarp -t_srs EPSG:3857 -of vrt IV_CORREDORES.TIF /vsistdout/ | gdal_translate -co compress=lzw  /vsistdin/ IV_CORREDORES_WEB.TIF
del IV_CORREDORES.*
gdalwarp -t_srs EPSG:4326 -of vrt IV_CORREDORES_WEB.TIF /vsistdout/ | gdal_translate -co compress=lzw  /vsistdin/ IV_CORREDORES.TIF
```
