# Input Folder  

Data for processing goes in the `input` subfolder. For example, to run Odense, you need `odense_dk_2020_1600m_buffer.gpkg` and `odense_dk_2020_10000m_pedestrian_osm_20200813.graphml` in the `input` folder.  

# Output Folder  
Output data goes in the `output` subfolder.

This subfolder contains:  
City-specific sample point level statistics, generated by the Sample Point Estimates script:  
- studyregion_country_yyyy_1600m_buffer_outputyyyymmdd.gpkg, for example, `odense_dk_2020_1600m_buffer_output20200820.gpkg`

Hexagon level statistics and city level statistics, generated by the City & Intercity Aggregations script:  
- global_indicators_hex_250m.gpkg  (hexagon level)
- global_indicators_city.gpkg  (city level)

# GTFS Folder

This folder contains GTFS public transport configuration and data:
- gtfs_config.py
- gtfs_frequent_transit_headway_yyyy-mm-dd_python.gpkg
