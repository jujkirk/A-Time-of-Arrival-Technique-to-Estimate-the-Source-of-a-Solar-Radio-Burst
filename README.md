# A-Time-of-Arrival-Technique-to-Estimate-the-Source-of-a-Solar-Radio-Burst
This is the code used in the upcoming publication: Kirkey, J., Hendrickson, J., Roman-Ramirez, S., Akhavan-Tafti, et al. A Time-of-Arrival Technique to Estimate the Source of a Solar Radio Burst. [To Be Submitted ].

Please download the Jupyter Notebook if you wish to use this code. You will need to add your own burst-observing stations with their latitude, longitude, elevation in meters, and the UTC time they first saw the burst (see specifics in the paper). You will need to add the date and time of the solar flare correlated type III solar radio burst. You also need to download 3 NASA JPL spice kernels for determining the Sun's position. They are de421.bsp, earth_latest_high_prec.bpc, and naif0012.tls. I have uploaded them here, but it is recomended that you download them from NASA's website: https://ssd.jpl.nasa.gov/ephem.html or https://naif.jpl.nasa.gov/pub/naif/generic_kernels/

Here are some references: 

Jupyter Notebook:

Jupyter Notebook (2016): IOS Press Ebooks - Jupyter Notebooks – a publishing format for reproducible computational workflows

NASA JPL Spice Kernels: 

Acton, C.H.; "Ancillary Data Services of NASA's Navigation and Ancillary Information Facility;" Planetary and Space Science, Vol. 44, No. 1, pp. 65-70, 1996.

DOI 10.1016/0032-0633(95)00107-7
Charles Acton, Nathaniel Bachman, Boris Semenov, Edward Wright; A look toward the future in the handling of space science mission geometry; Planetary and Space Science (2017);
DOI 10.1016/j.pss.2017.02.013

NumPY: 

Harris, C.R., Millman, K.J., van der Walt, S.J. et al. Array programming with NumPy. Nature 585, 357–362 (2020). DOI: 10.1038/s41586-020-2649-2. (Publisher link).

Itertools Python Module: 

Van Rossum, G. (2020). The Python Library Reference, release 3.8.2. Python Software Foundation.

Matplotlib: 

J. D. Hunter, "Matplotlib: A 2D Graphics Environment", Computing in Science & Engineering, vol. 9, no. 3, pp. 90-95, 2007.

 Spiceypy:

Annex et al., (2020). SpiceyPy: a Pythonic Wrapper for the SPICE Toolkit. Journal of Open Source Software, 5(46), 2050, https://doi.org/10.21105/joss.02050




