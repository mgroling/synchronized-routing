CARMENTA LAKE TAHOE PUBLIC DOMAIN GEOGRAPHIC DATA -- README


INFORMATION
-----------

This directory contains some of the geographic data from USGS
Lake Tahoe Clearinghouse found at http://tahoe.usgs.gov/.

The data contains:

* DLGs (digital line graphs) (vector) in shape format

   o buildings
   o docks and general lines
   o lakes
   o rivers
   o roads
   o vegetation

  The 3dlg0798.pdf USGS document in this directory has more info
  about the names and the contents of the attributes.

* Some DOQs (aerial orthophoto)

  DOQs are complete and cover the whole Lake Tahoe region.
  The files were converted from MrSID format to JPEG 2000.
  The maximum resolution is 1 meter.

* DEM (Digital Elevation Model)

  10 meter resolution .hdr format

  These files were converted from USGS DEM (ASCII) format 
  to .hdr (binary) format to save space.

* Land Cover

  The Land Cover data is in TIFF format and 30 m resolution. It has
  raster values indicating where for example trees and crops grow. 
  There is a JPG image in the same directory with some explanations,
  and there is also an official metadata text file explaining the 
  various classes. The .aux.xml file, constructed by Carmenta, 
  contains a machine-readable raster attribute table with descriptions
  based on the official metadata text file, as well as vegetation heights 
  estimated by Carmenta.

* Geonames

  Placenames in Shapefile format. These files have been created from data 
  downloaded from the geonames.org (http://www.geonames.org/) web site. 
  Please read the readme.txt in the same directory for more information.

HOW TO USE THE DATA IN CARMENTA ENGINE
--------------------------------------

The Carmenta Engine SDK installation contains various sample configuration 
files that show you how to use this data in Carmenta Engine.


RESTRICTIONS FOR USING THIS DATA
--------------------------------

Carmenta has received this message from USGS concerning the restrictions 
for using the Lake Tahoe data:

---
> We are glad that you are using the Lake Tahoe Clearinghouse.  All of the data
> we make available there is in the public domain.  You may use it freely for 
> your own purposes.  As a courtesy, we ask that you credit USGS and the Lake 
> Tahoe Clearinghouse as the data source if you reproduce the data.
>
> Thank you for letting us know that the Clearinghouse has been helpful to you.
>
> Sincerely,
>
> Leonard Gaydos
> US Geological Survey
---

All we (Carmenta) require of you if you re-distribute this data
(our compilation and conversions) is that this README file
is always included in your distribution.


OUR RESPONSIBILITY FOR CORRECTNESS OF CONVERTED DATA
----------------------------------------------------

We (Carmenta) take no responsibility for the correctness of the 
converted data. There might be errors. The converted data should 
be used for demonstration purposes only.


More information about Carmenta's products is available at
http://www.carmenta.com


Carmenta AB
