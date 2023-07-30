# Exoplanet-Spectra

Spectral fitting with $\texttt{PICASO}$ module. Project page - https://github.com/natashabatalha/picaso/tree/master

Configurations needed (on my side):
1. Download references folder from the module repo and keep it in same folder as script.
2. pip install xarray[complete], or xarray, netCDF4 and h5netcdf, https://docs.xarray.dev/en/stable/getting-started-guide/installing.html
3. Download opacities.db from https://zenodo.org/record/3759675#.YuN4E-zMLvU and keep it in folder references/opacities.
4. Download cloudy and cloud-free models from https://zenodo.org/record/7236759 and place them in Models folder.
5. Download ck04models for stellar spectra, wget command at https://natashabatalha.github.io/picaso/installation.html page.

Finally, of course, download the transit spectra from https://exoplanetarchive.ipac.caltech.edu/cgi-bin/atmospheres/nph-firefly?atmospheres
