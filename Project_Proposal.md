### Analysis Objective
The NYC Department of Health and Mental Hygiene (NYC DOHMH) is planning to support the city’s reopening. And they want to launch a “Fight For Covid” campaign by providing Covid Hygiene kits in some public areas, such as subway stations. By doing this, they want to remind people to keep following pandemic rules during reopening phases. In order to find target subway stations, we'd like to:
* Visualize the trends of Covid-19 cases in NY and by boroughs.
* Analyze the correlations between subway usages and the number of Covid cases in NY and by boroughs.

### Client Organization
 NYC Department of Health and Mental Hygiene(NYC DOHMH)

### Data Description
The following datasets will be used for the analysis:
| Dataset | Link | Data Description |
| --- | --- | --- |
| data-by-day | https://github.com/nychealth/coronavirus-data/tree/master/trends | This dataset contains daily Covid trend data by boroughs |
| turnstile_xxxxxx|  http://web.mta.info/developers/turnstile.html | Weekly turnstile usage data |
| NY Subway Geospatial Data| https://data.cityofnewyork.us/Transportation/Subway-Stations/arq3-7z49 | Geo information of subway stations in NY |

The features that will be included in the analysis:
 * Weekly Covid cases by boroughs of the latest 52 weeks
 * Weekly turnstile entries by boroughs of the latest 52 weeks

### Tools
* Python3
* SQLite

### MVP Goal
Observe whether there's any correlation between the subway usages and the COVID cases in NYC and by boroughs.


