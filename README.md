# 🚀 pythermalgreen 0.2.6
Collaborative project to obtain urban heat island patches through Remote Sensing.

## 🎯 Functions
* Create a urban heat analisys based on Normalized Difference Vegetation Index and Land Surface Temperature
* Soon new releases and automated functions

## 🛠️ Why use pythermalgreen?

* Create environmental impact analysis processes quickly and automatically!
  
## 🌐 How to execute?

You can install the library using Python pip:

```
pip install pythermalgreen
```

The project initially requires raster files processed for NDVI and Earth Surface Temperature to process urban heat island spaces.
```
ndvi_file = 'ndvi.tif'
tst_file = 'tst.tif'
output = 'way/to/save/your/file.tif'
```
To run the code, you just need to use the function:
```
from pythermalgreen import pythermalgreen

thermal_green = pythermalgreen(tst_file, ndvi_file, output)
thermal_green.process()  #run pythermalgreen
```

To get landscape metrics, run:
```
thermal_green.metrics() 
```


This is an example output of a .tif file using PyThermalGreen:
![texto alternativo](https://github.com/guilherber/PyThermalGreen/raw/main/docs/example.jpg)

## 🔗 Important Details

* Use the same geographic projection for interpretation.
* Install requires: 
* 'numpy>=1.22.0'
* 'rasterio==1.3.10',
* 'geopandas==0.14.4',
* 'pandas<=2.2.2',
* 'shapely==2.0.4'
* 'pylandstats'
## 🙌 Contribute!

To collaborate, do not hesitate to send an e-mail to (guissan.gui@gmail.com).

## Citations

Landim-Santos, G. pythermalgreen: Fundamental algorithm to ambiental analisys (2024)


## 📚 Bibliography
* Landim-Santos, G. Infraestutura verde como estratégia para áreas passíveis de plantio com risco ambiental no município de Piracicaba, SP, pela inferencia booleana (2024);
* Guha, S., Govil H. Land Surface temperature and normalized difference vegetation index relationship: a seasonal study on a tropical city. (2020);
* Lombardo, M. Estudos de ilha de calor (1985);
* Turner, G,M. Gardner, H,M Landscape Ecology in theory and pratice (2015);
* Waleed, M. Sajjad, M. Leveraging cloud-based computing and spatial modelling approaches for land surface temperature disparities in reponse to land cover change: Evidence from Pakistan (2022);
* Bosch M. 2019. “PyLandStats: An open-source Pythonic library to compute landscape metrics”. PLOS ONE, 14(12), 1-19. doi.org/10.1371/journal.pone.0225734


