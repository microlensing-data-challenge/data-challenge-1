# About the Data Challenge

http://microlensing-source.org/data-challenge/


# Lightcurves

Lightcurves are zipped in lc.tar.gz - this will unzip to the directory lc/

Columns: BJD Magnitude Error



# Ephemeris files

There is one ephemeris file for each filter: wfirst_ephemeris_W149.txt and wfirst_ephemeris_Z087.txt. They store the position of WFIRST in the solar system at the times of the observations in each filter. Positions are in units of AU

Columns: BJD X_EQ Y_EQ Z_EQ X_ECL Y_ECL Z_ECL

X,Y,Z_EQ are cartesian coordinates in the J2000 equatorial frame with the solar system barycenter at (0,0,0)

X,Y,Z_ECL are cartesian coordinates in the ICRS ecliptic plane frame with the solar system barycenter at (0,0,0)

Both frames are right handed, the X axis is common to both and increases from the barycenter towards the vernal equinox, Z points towards the north celestial or ecliptic pole, respectively.




# Event Information

There are a few pieces of information that may need to be known for each event that are not in the lightcurve files. These are stored in event_info.txt

Columns: Event_name Event_number RA_(deg) Dec_(deg) Distance A_W149 sigma_A_W149 A_Z087 sigma_A_Z087


Distance, A_W149/Z087 are an estimate of the distance and extinction in each band of the red clump stars. sigma_A_W149/Z087 are dispersions in the extinction.



# Problems?

If you spot any problems with the data set, please contact Matthew Penny: penny@astronomy.ohio-state.edu as soon as possible.


