# d13Slice: A Matlab function for 3-dimensional visualisation of the d13C ocean climatology of Eide et al., 2017.

## Installation instructions
- Firstly, download the zip file `d13slice_data.zip` and extract all of the contents into a location visible to Matlab. This can either be your current working directory (to find this out, type `cd` into your Matlab command line. 
- Secondly, use the function! For specific details see the readme.m file or type `help d13slice` into your command line. 

## References, acknowledgments and gratitudes
This relatively simple function is relatively simple thanks to the hard work of others. All of the data used in this function is redistributed here under explicitly non-commercial conditions. I do not, and will never profit from the distribution of my shabby coding attempt. 

##### d13C Data
The d13C dataset used here is the wonderful ocean climatology of Marie Eide, Are Olsen, Ulysses S. Ninnemann, and Truls Johannessen. Published in 2017 in Global Biogeochemical Cycles (Volume 31, Issue 3), this dataset builds on [WOCE](http://www.ewoce.org/) transects and provides a climatological distribution of the preindustrial d13C of dissolved inorganic carbon in the global oceans. 
- This data is available to download from [Pangaea](https://doi.pangaea.de/10.1594/PANGAEA.872004) and the open access paper it was published with can be read online [here](https://agupubs.onlinelibrary.wiley.com/doi/full/10.1002/2016GB005473).
- the data is redistributed here under a [Creative Commons 3.0 License](https://creativecommons.org/licenses/by/3.0/).

##### Bathymetry Data
Bathymetry data used is the 5-minute gridded elevation data, included in the zip-file as a greatly reduced-in-size text file. The full NetCDF file is downloadable [here](https://www.ngdc.noaa.gov/mgg/global/etopo5.HTML). 
- Reference: Data Announcement 88-MGG-02, Digital relief of the Surface of the Earth. NOAA, National Geophysical Data Center, Boulder, Colorado, 1988.
- Note: I know this is a pretty outdated bathymetry dataset... but it's a hell of a lot smaller than the more recent ETOPO1, and I wanted to be able to include it in the function without it taking hours to download, okay?

##### Colorcet.m
Included in this function is a beautiful script from [Peter Kovesi](https://peterkovesi.com/projects/colourmaps/) called colorcet. This function is used to supply perceptually uniform colormaps to display the data. 
- Included under a [Creative Commons 4.0 License](http://creativecommons.org/licenses/by/4.0/). I have not modified the script at all, leaving it in it's original glory. 
- Check out the [GitHub page](https://github.com/bokeh/colorcet) for the colorcet project for more info. 

