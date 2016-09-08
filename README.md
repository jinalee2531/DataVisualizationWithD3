
# 1. Summary

This data visualization represents the amount of money loaned in Prosper Loan across state on a choropleth map, between November 2005 to March 2014.
[Prosper](https://en.wikipedia.org/wiki/Prosper_Marketplace) is the company providing person-to-person lending platform on the web. As soon as readers open this page, the visualization starts to run animation presenting loan amount of each states on the choropleth map of year in order. After which, audiences can see the result of a specific year by selecting a year button. You would easily see the trends of traded loan amount each year by states. The visualization is created with D3.js.


# 2. Design 

To show trends of loan amount among states effectively, the loan amount data of each state was mapped on the US choropleth map.
I encoded loan amount value with size of circles on the choropleth map,
so that readers would compare amounts of lending for each state with time intuitively at one place.

For audiences' better understanding of messages that I would deliver through the visualization, I put breif introduction above the map.
With knowledge of the Prosper Loan Company and the data set, readers would feel easier to follow the visualization.

Took the author driven structure for the very beginning of this visualization, which is an animation showing result of each year orderly.
After the animation is ended, let audiences can explore the result of a specific year by clicking buttons representing the year.

I selected light-sky of a low charoma to fill the map, and chose highlighting yellow for the circles on the map to make the chart so that audiences easily notice both of them clearly.
Also it avoids red and green combination which is hardly discriminated for some people.

Considered pre-attentive processing principle to enhance perception of selected factor: 
Background color of a text representing each year would be changed when it is selected, and color of a circle over mouse on the choropleth map would change.

A tooltip containing state name and amount value shows up if mouseover a specific circle representing amount of loan.



# 3. Resources consulted to create this visualization

- Source of data set : [Loan Data from Prosper](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv)
- [US Choropleth Projection] (https://github.com/d3/d3-3.x-api-reference/blob/master/Geo-Projections.md)
- [SEC Outlines Its Reasoning For Shutting Down P2P Lender Prosper](https://goo.gl/qx5bFe)
- [Which States are Open to Lending Club and Prosper?] (http://www.lendingmemo.com/lending-club-and-prosper-states/) 
