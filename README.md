# Web Design Challenge (Latitude)


## Latitude - Latitude Analysis Dashboard with Attitude

For this project a web dashboard was created using visualizations about weather characteristics. 

Individual pages were created for each plot as well as a means by which one can navigate between them. The pages contain the visualizations and corresponding explanations. A page was also created where a comparison of all of the plots is shown and another page was created where all the data used to build the visualizations.

### Website Details

The website consists of 7 pages total, including:

* The [landing page](#landing-page) contains:
  * An explanation of the project.
  * Links to each visualizations page. A sidebar containing preview images of each plot, and the ability to click an image and be taken to that visualization.
* Four [visualization pages](#visualization-pages), each contain:
  * A descriptive title and heading tag.
  * The visualization for the selected comparison.
  * A paragraph describing the plot and its significance.
* The ["Comparisons" page](#comparisons-page) contains:
  *  All of the visualizations on the same page so they can be easily compared.
* The ["Data" page](#data-page) contains:
  * A responsive table containing the data used in the visualizations.
    * The table must be a bootstrap table component. [Hint](https://getbootstrap.com/docs/4.3/content/tables/#responsive-tables)
    * The data must come from exporting the `.csv` file as HTML, or converting it to HTML. Try using a tool you already know, pandas. Pandas has a nifty method approprately called `to_html` that allows you to generate a HTML table from a pandas dataframe. See the documentation [here](https://pandas.pydata.org/pandas-docs/version/0.17.0/generated/pandas.DataFrame.to_html.html)

#### <a id="landing-page"></a>Landing page

Large screen:

![Landing page large screen](Images/landingResize.png)

Small screen:

![Landing page small screen](Images/landing-sm.png)
￼

#### <a id="comparisons-page"></a>Comparisons page

Large screen:

![comparison page large screen](Images/comparison-lg.png)

Small screen:

![comparison page small screen](Images/comparison-sm.png)

#### <a id="data-page"></a>Data page

Large screen:

![data page large screen](Images/data-lg.png)


Small screen:

![data page small screen](Images/data-sm.png)

#### <a id="visualization-pages"></a>Visualization pages

You'll build four of these, one for each visualization. Here's an example of one:

Large screen:

![visualize page large screen](Images/visualize-lg.png)

Small screen:

![visualize page small screen](Images/visualize-sm.png)

#### <a id="navigation-menu"></a>Navigation menu

Large screen:
![nav menu large screen](Images/nav-lg.png)

Small screen:
![nav menu small screen](Images/nav-sm.png)
