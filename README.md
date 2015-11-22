# NetCDF
####Installing Python####
 >By personal experience, if working in windows installing [Anaconda] (http://docs.continuum.io/anaconda/install) is the best option.
 * Once that Anaconda is installed, is possible to access Pythom from the Windows command prompt by typing just python.
 * The basic packages to work with netcdf files are: hdf (Pyhdf), matplotlib and netcdf (netcd).  If some packages are not installed use the command conda 
   (e.g `conda install netcdf4`).
   
###Reading *.nc files###
>Open Spyder (Anaconda interactive Python dvelopment environment) 
 * Windows>Start>Spyder once open create a new project
 * To read the headers of the netcdf file:
 
 ```
from netCDF4 import Dataset
eg='C:/YoURPATH.../blabla_data.nc'
data=Dataset(eg, mode='r')
print data
```
