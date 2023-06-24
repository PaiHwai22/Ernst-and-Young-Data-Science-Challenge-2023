# Ernst-and-Young-Data-Science-Challenge-2023
File uploads for EY Data Challenge Sustainability goals in World Hunger March 2023 Competiton. The challenge consists of 2 levels and provides acess to sentinel datasets and suggests some useful indexes. 
Goals of Level 1 challenge : predict the presence, or non-presence, of rice crops at a given location. 
Goals Level 2 challenge : build a machine learning model that estimates rice crop yield for a given location.

Dataset Description: 
Satilite Datasets
- Sentinel 1 radar dataset
  Sentinel-1 missions operate in the C-band frequency, corresponding to 5.6 cm wavelength.
  The radar signal can be transmitted and received at either horizontal (H) or vertical (V) polarization.
  The Sentinel-1 data contains two basic polarization "bands", VV and VH, with the first letter indicating the transmitted polarisation and   the latter the received polarisation. The VV and VH bands give us surface backscatter at any location. This backscatter tells us about      the "structure" of the crop, such as its growth progress from small plants to large plants, and then to bare soil after harvesting.
  
  - Sentinel 2 optical dataset (challenge of cloud penetration)
  Optical data is used to measure the "greenness" of vegetation during the growth cycle.
  Differences in band or index values can be used to distinguish differences in crop types (Figure 3) and crop yield

Indexes:
Radar Vegitation Index(RVI): used for sentinel 1
equation for RVI: sqrt (1- VV / (VV+VH)) * 4 * (VH / (VV + VH))
Normalized Vegitation Index (NDVI): used for sentinel 2
abstracted equation for NDVI: (NIR-Red) / (NIR+Red)

The submission files of this project is contributed by undergrad students Pai Hwai and Josiah Teh from James Cook University Singapore. 
