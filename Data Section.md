Data Section:

Data source- https://data.gov.in/resources/approved-hotelsrestaurantsair-catering-unitstime-share-resortsapartmentsconvention (csv format)

The above data has been published by the Ministry of Tourism for Classifying/ Re-classifying Hotels under various categories at the project level. The aims and objectives of this scheme are to provide world-class standard services to tourists.

For this project, analysis is carried using pandas Dataframe and cleaning up the irrelevant data columns for this analyze which are 'PHONE', 'FAX', 'EMAIL ID' and 'WEBSITE'. We will use the Nominatim library from geocoders.geopy package to find the longitude and latitude for each these locations. A new data column 'Loc' has been created combining 'HOTEL NAME' & 'STATE' for restricting only to India. For Data Visualization Seaborn and Matlabplot libraries have been used. Visualize these hotel locations on a folium map.

The Foursquare API to find the top venues in the neighbourhoods of these Hotels. This will help understand to the nature of life around these locations. For illustration purposes analyse the popular venues located within 500m radius is considered .
