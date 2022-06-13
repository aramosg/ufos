# ufos
Module 11 - Javascript

drawback
- spelling - si el usuario no conoce exactamente como escribir un dato, no encontrara nada
- se carga toda la data al abrir la pagina. Esto puede ser un problema si los datos son muchos

Recommendations
- la bd es fija - si queremos agregar nuevos datos, debemos actualizar el archivo JS. El impacto es minimo, pero no es lo mejor. Lo mejor seria una BD
- nueva funcionalidad - registro de nuevos eventos por parte de los usuarios
- cargar solamente un pequeño set de datos para la pantalla inicial como muestra. Modificar los datos conforme se modifican los filtros (usar paginacion?)
- usar algo como "auto complete" para orientar a los usuarios y que la busqueda sea mas rapida
- Hacer campos dependientes - Pais > estado > ciudad (por ejemplo)

---------------

The written analysis has the following:

- Overview of the analysis:
-- The purpose is well defined (2 pt)

- Results
-- There is a description of how to perform a search, with images. (4 pt)

- Summary
-- The summary addresses one drawback of this webpage (2 pt)
-- The summary addresses two additional recommendations for further development (4 pt)

---------------

# Module 11 – UFOs sightings!
# Unit Challenge
## Overview of the analysis
Dana, our customer, has been given the opportunity to write an article on his own. She has selected to write about UFOs sightings in her hometown. She has a JS file with data describing UFO sightings from different states and cities. 

To get started, she is planning to build a website to expose the data to a wider audience. She will be using JS to develop an interactive site, showing the available data so far. The data contains some details about the sightings:
1. Date
2. City
3. State
4. Country
5. Shape
6. Duration
7. Comments

The website that will be built will allow the users to filter the data table using date, city, state, country, and/or shape. It will be also possible to combine any of these filters. 


## Results - How to perform a search?

When loading the page for the first time, the full data table will be loaded. If the user is curious enough, he/she will be able to scroll through the whole data set.

**Initial page - full data table**
![Observations for June](/resources/homepage_full_data_table.png)

### Performing a search using the available filters

### Resetting the filters - showing the whole data set


## Summary
### Drawbacks of this webpage


### Recommendations for further development

