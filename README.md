# stack-ticket-data-wip

This repo contains the code used to analyze data for the article [Stick It to the Ticket](https://stack.dailybruin.com/2020/01/18/ticket-data/), published on The Stack at the Daily Bruin during the fall of 2019, when I began as a Data Journalist intern. In this article, I worked with three other students to generate the analysis and data visualizations for the article.

### Article Inspiration
Parking is notoriously difficult in around the UCLA and Westwood area. Many students that choose to bring cars on campus have a few options to avoid fees: purchasing a parking spot from UCLA (hard and lottery-system based), buying a spot off of someone living in the surrounding apartments, or park and move your car frequently to avoid citations. Me and my team were inspired to generate an analysis of parking citations in and around UCLA to determine what areas, times of day/week, and reasons are most commonly cited by police officers.

### Challenges
* Incredibly messy data due to the manually input address names
* Niche geospatial coordinates that required research to translate into working longitudinal/latitudinal points
* Inaccurate reporting of latitudinal and longitudinal data as the two columns were swapped and mislabeled
* Researching to contextualize reasons for spikes in parking citations
* Generating a JavaScript map and plotly graph visuals for website use.

### My Code Contributions
Used libraries: dplyr, sp, rgdal, raster, chron
* Generating breakdowns of ticket citations by month, violation codes, time of day
* Transforming coordinates into GPS plottable latitudinal and longitudinal data using [California specific spatial reference coordinates equation](https://epsg.io/102645)

Outside of my code contributions, I helped with drafting the article and learned how to generate plotly graphics from senior data journalist members of The Stack.
