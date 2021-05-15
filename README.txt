Plugin Builder Results

Your plugin windForecastRouting was created in:
    D:/Documenti/04_CLOUD/dev/qgis3\wind_forecast_routing

Your QGIS plugin directory is located at:
    C:/Users/ferregutie/AppData/Roaming/QGIS/QGIS3/profiles/default/python/plugins

# Basic usage:

1. download a GRIB file, e.g. with https://plugins.qgis.org/plugins/gribdownloader/ ; recomended model is `icon_eu` with interval 1 (1 hour) and period 5
1. check that the GRIB is EPSG:4326; if not, assign the òprojection manually
1. check under `Layer>properties>Source>Datasets` wich layer of the GRIB contains the needed parameters (*wind*); to be sure, you can download only the wind, and set `Wind Grib Dataset index` to 0
1. in case the GRIB data are not shown on the canvas, deactivate the time panel
1. double check your start and end point are at sea respect to the sea border layer used by the alg (currently natural earth `ne_10m_ocean` 
