PYDAR
===================================

A Python package to access, download, view, and manipulate Cassini RADAR images in one place

* **Find relevant flyby observation numbers and IDs for a feature, range of regions, or specific latitude/longitude**
	* retrieveIDSByFeatureName()
	* retrieveIDSByLatitudeLongitude()
	* retrieveIDSByLatitudeLongitudeRange()
	* retrieveIDSByTime()
	* retrieveIDSByTimeRange()
* **Use flyby observation numbers/IDs to retrieve flyby observation data (.FMT, .TAB, .LBL, .IMG) from SBDR and BIDR by default**
	* extractFlybyDataImages()
	* convertFlybyIDToObservationNumber()
	* convertObservationNumberToFlybyID()
* **Access specific observation data AAREADME and .LBL readme information**
	* returnAllAAREADMEOptions()
	* readAAREADME()
	* returnAllLBLOptions()
	* readLBLREADME()
* **Display PDS image retrieved for flyby observation**
	* displayImages()
* **Extract Metadata from .FMT and .TAB files**
	* extractMetadata()

.. note::

   This project is under active development
   
   This is Beta quality software that is being actively developed, use at your own risk. This project is not supported or endorsed by either JPL or NASA. The code is provided “as is”, use at your own risk.



Contents
--------

.. toctree::

   data
   functions
