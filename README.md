# Superstore Case Study
**Introduction**

In this project, using sample data from a Superstore, I built a Commercial dashboard in Tableau that Stakeholders can self-serve with.
In addition to this dashboard, I used SQL to deliver insight on two business problems and provide recommendations.
<br>

**Dataset**

The excel dataset contains 3 sheets, 'Orders', 'Returns' and 'People'.
The Orders sheet is where the bulk of the sales data is held;
the Returns sheet states whether an order was returned so we can join it to the sales data to get Net sales (Total sales - Returns)
and finally, the People tab which assigns Managers to a region in order to track regional performance and pick out under/over performing regions.

<br>
<br>

For us to understand what story the data is telling us I have visualised the data in a performance dashboard in Tableau that could be used as a self-service tool for stakeholders.
The dashboard will be the first point of call for performance which we can easily use to spot any trends and to see how metrics are performing.

Viewing the dashboard will trigger various commercial questions about performance and customer behaviour which we can use to guide our strategy.
These questions will be answered using SQL to retrieve the necessary data that will then be analysed further in Excel.

<br>
<br>

**Dashboard walkthrough**
<br>
The dashboard is comprised of 4 key tabs:

- **Yearly Performance**; shows yearly sales growth and how topline metrics have moved over the years.
- **Performance**; a dynamic sheet that holds the main commercial KPIs, where specific dates can be selected.
- **Location**; a geographic view of US State's performance, with their respective metrics that will be displayed if hovered over.
- **Profitability**; a view that shows profitability broken down to a regional and category/sub-category level and the impact discounting is having to margin.

<br>
<br>

**Hindsight**
<br>
When working with this limited dataset, it is important to 

- If we had access to more data, such as Sessions, Customer or Marketing tables we would be able to track and analyse other important KPIs to better understand customer behaviour. We would be able to connect multiple data points to tell a more detailed story.
- In usual instances, for us to be able to make sense of current performance, we would have a form of Budget/Forecast to compare current performance to which would give us context.
However, in this case study budget numbers were not provided, so comparisons are being made to historic performance alone.
- In this case study, the only Country/Territory included was United States which limits the global views this dashboard could be used for.
