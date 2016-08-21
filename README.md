

1. Summary

This data visualization represents annual loan amount by state traded in Prosper 
on a choropleth map of US States, since 2005 to 2014.

Prosper is the company providing person-to-person lending platform on the web.

As soon as viewers open this page, the visualization starts with animation presenting loan amount of each states on the choropleth map every year,
after which, audiences can see the result of a specific year by selecting a year button.

You would easily see the trends of scale of traded loan amount each year by states.
The visualization is created with D3.js.


2. Design 

- explain any design choices you made including changes to the visualization after collecting feedback

To show trends of loan amount among states effectively, mapped the amount data on the US choropleth map.
Encoded loan amount value with size of circles on the choropleth map of United States.

Took the author driven structure for the very beginning of this visualization, which is an animation showing result of each year orderly.
After the animation is ended, audiences can see the result of a specific year by clicking buttons representing the year.

Considered pre-attentive processing principle to enhance perception of selected factor: 
Background color of a text representing each year would be changed when it is selected, and color of a circle over mouse on the choropleth map would change.

A tooltip containing state and amount value shows up if mouseover on a specific amount circles.



3. Feedback
- include all feedback you received from others on your visualization 
from the first sketch to the final visualization

1) More information with the circles would make the visualization more clear such as amount values and states names.
2) Changing color of a circle over mouse would be more conspicuous.
3) Some circles are too small to notice on the choropleth map. It would be better to adjust scale of circle to notice.


4. Resources consulted to create this visualization

- US Choropleth Projection : https://github.com/d3/d3-3.x-api-reference/blob/master/Geo-Projections.md
- Queue() : http://bl.ocks.org/mapsam/6090056
- Prosper Wikipedia: https://en.wikipedia.org/wiki/Prosper_Marketplace
- data set : Loan Data from Prosper https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1471821128880000&usg=AFQjCNEdv4UZxzYQGN5jmuTYHLXKmbHrOQ