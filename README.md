
P6 - The Death Map
===========================
### Author: Nikolas Thorun


#### Abstract:

Click here to check it out: http://bl.ocks.org/nrthorun/e91fa658ce1471d4d82ad1b31df21951

This visualization shows the homicide rates for every 100 thousand inhabitants in Brazil, registered between 1996 and 2015.
It is clearly shown that the rates are increasing over time and that the difference between genders is huge.
The data were taken from the 'Atlas of Violence' on the IPEA website, the Institute for Applied Economic Research (http://www.ipea.gov.br/atlasviolencia/series).
The animation begins by showing a choroplethic map of Brazil, in which the color intensity indicates the value of the homicide rate, iterating between the years every half a second.
After the end of the animation, a menu appears with the options to see the animation for different genres or to detail a specific year.
If a new animation is selected, a 'skip animation' button is shown.

#### Design:

To represent the 'death map', a choropleth map was chosen, in which the color scale varies from white to red and then to black.
The scale is sequential, that is, as the rate increases the tones darken.
The idea is that states without homicides would turn white, states with more than 100 homicides per 100,000 inhabitants would turn black and the rest of the states would range from light pink to dark red.
After the feedbacks, the title was changed from 'Map of Violence' to 'Map of Death (Homicides)', so as not to pass on the idea that the map represented other types of violence.

#### Feedback:

Several people watched and interacted with the visualization, most of whom said they had no points for improvement to indicate.

Four feedbacks were given:

1 - My brother Peter, the first to whom I showed the visualization, complained that the animation was too slow and that nobody has the time to watch it nowadays.
Feedback was accepted and implemented. The next feedbacks were given after this change.

2 - My girlfriend Natália complained that the animation was too fast and that the title is confusing and gives the wrong idea.
The title feedback was accepted and implemented. The feedback from the animation time was not accepted as the other people did not agree.

3 - My boss Thiago, who is a great data analyst, said that the visualization already shows the data he wants to see, but it would be interesting to open a line graph showing the evolution of the rate over time when we click on any state.
The feedback was accepted, but it was not implemented because it understood that it would take a lot of work to show data that the map already shows, but in another way. But the idea is good will be implemented in a second moment.

4 - My friend André said that it would be interesting to have a 'skip animation' button so that we would not be forced to watch the animations every time we clicked on the genre buttons.
Feedback was accepted and implemented.

#### Resources:

To help build the visualization, the following sources were searched:

Tooltip:
http://bl.ocks.org/Caged/6476579

Example of a choropletic map:
https://bl.ocks.org/mbostock/4060606

Legend:
https://www.visualcinnamon.com/2016/05/smooth-color-legend-d3-svg-gradient.html
http://bl.ocks.org/darrenjaworski/5397362
