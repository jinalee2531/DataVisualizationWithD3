
## 1. Summary

This data visualization represents annual loan amount traded in Prosper by state on a choropleth map of US States, since November 2005 to March 2014.
Prosper is the company providing person-to-person lending platform on the web. As soon as readers open this page, the visualization starts to run animation presenting loan amount of each states on the choropleth map of year in order,
after which, audiences can see the result of a specific year by selecting a year button. You would easily see the trends of traded loan amount each year by states.
The visualization is created with D3.js.


## 2. Design 

To show trends of loan amount among states effectively, the loan amount data of each state was mapped on the US choropleth map.
Encoded loan amount value with size of circles on the choropleth map of United States.

Took the author driven structure for the very beginning of this visualization, which is an animation showing result of each year orderly.
After the animation is ended, let audiences can explore the result of a specific year by clicking buttons representing the year.

Considered pre-attentive processing principle to enhance perception of selected factor: 
Background color of a text representing each year would be changed when it is selected, and color of a circle over mouse on the choropleth map would change.

A tooltip containing state name and amount value shows up if mouseover a specific circle representing amount of loan.



## 3. Feedback

- More information related to circles such as amount values and states names would make the visualization more clear.
- Changing color of a circle over mouse would be more conspicuous.
- Some circles are too small to notice on the choropleth map. It would be better to adjust scale of circle to notice.


## 4. Resources consulted to create this visualization

- US Choropleth Projection : https://github.com/d3/d3-3.x-api-reference/blob/master/Geo-Projections.md
- Queue() : http://bl.ocks.org/mapsam/6090056
- Prosper Wikipedia: https://en.wikipedia.org/wiki/Prosper_Marketplace
- data set : Loan Data from Prosper https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1471821128880000&usg=AFQjCNEdv4UZxzYQGN5jmuTYHLXKmbHrOQ