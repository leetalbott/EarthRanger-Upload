# EarthRanger-Upload

MoveApps

Github repository: xxx

## Description
Simple app to upload data from a movestack to EarthRanger via API.

## Documentation
This app takes data from a movestack object, coerces to json via jsonlite packager, and iterates over the elements to push to EarthRanger via httr package. 

### Input data
moveStack in Movebank format

### Output data
moveStack in Movebank format

### Artefacts
none.

### Parameters 
none.

### Null or error handling:
**Data:** The data are not manipulated, but empty input with no locations (NULL) leads to an error. For calculations in further Apps the input data set is returned.
