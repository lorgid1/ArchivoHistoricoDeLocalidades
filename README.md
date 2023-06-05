# AHL

Repository analyzing the Historical Archive of Localities published by INEGI (Instituto Nacional De Estadística y Geografía). The dataset contains 4 tables:
* Habitantes - With information about population.
* Movimientos – With information about administrative modifications.
* Res_hist - With a list of the historical sources of the locality.
* Maestro - With cartographic data from INEGI.

The main part of the information is in the population table (Habitantes), it is where the number of male and female inhabitants for each locality is contained. There are some gaps in the information for each community in the dataset that have their answer in the administrative modifications table (Movimientos). Without unravelling the information that is contained in movements the data it offers is not able to be utilized to its full potential. Movimientos is the main interest of this repository, inside the ORI_MODIF column is the answer to the time gaps found in Habitantes. 

The project is divided in several Jupyter Notebooks. Each has 2 versions, one in Spanish and the other in English. The English version will have _EN at the end. The files this project contains are:
 * unir_csvs_ahl.ipynb
 >> Notebook makes an initial exploration of the format and columns of the data and joins the separated state data rows in one CSV.
 * analisis_habitantes.ipynb
 >> Notebook that analyzes the habitantes.csv with population data.
 * analisis_movimientos.ipynb
 >> Notebook that analyzes movimientos.csv and the administrative movements it holds.

