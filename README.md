### netcdf2mp4: A python script to create animated data visualizations from spatio-temporal netcdf datasets stored as animated GIF and  MP4 video file.

This script uses ```gdal``` to read NetCDF data, uses ```matplotlib``` to plot the data for each point in time, and uses ```imageio``` to create an animated GIF. Finally, it uses ```moviepy``` to convert the animated gif to MP4 video format, which will reduce file size. For example, the below GIF is 29MB, and the corresponding MP4 file is less than 3MB.

For example, this script can be used to visualize the average monthly temperature for each 0.5° x 0.5° grid cell from 1901-2020 from the CRU TS monthly high-resolution gridded multivariate climate dataset (Harris et al. 2020; https://www.nature.com/articles/s41597-020-0453-3).

### CRU average temperature (1901-2020):
<img width="450" src="https://github.com/johannesuhl/cru_data_processing/blob/main/cru_tmp_animated_global2.gif">

### References:

Harris, I., Osborn, T. J., Jones, P., & Lister, D. (2020). Version 4 of the CRU TS monthly high-resolution gridded multivariate climate dataset. Scientific data, 7(1), 1-18. https://doi.org/10.1038/s41597-020-0453-3
