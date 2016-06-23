  <h1>Exploration of Better Life Index (BLI) data and its relation with Educational Graduate Field Distribution</h1>

###All actual programming code can be found in a different repository. For the implementation please go to: https://github.com/JaapN/Project

#####@author: Jaap Nieuwenhuizen

######!!! See REPORT.md for a more proper and extensive description and introduction of the product as implemented. Note that much of what has been written in this document was conceptualised 4 weeks ago, even though the subject has been changed by then. So, once again, for a more proper introduction and description of the product, view REPORT.md.

Previous title:
'Exploration of educational field distribution by mapping of average student skills, employment rate, personal earnings and life satisfaction – investigating educational profile correlations with seemingly generic variables?'


Sources:

  <b>Data BLI:</b> <a href="http://stats.oecd.org/Index.aspx?DataSetCode=BLI"><font color="blue">http://stats.oecd.org/Index.aspx?DataSetCode=BLI</font></a><br>
  <b>Data Grad Fields:</b> <a href="https://stats.oecd.org/Index.aspx?DataSetCode=EAG_GRAD_ENTR_FIELD"><font color="blue">https://stats.oecd.org/Index.aspx?DataSetCode=EAG_GRAD_ENTR_FIELD</font></a><br>
  <b>D3:</b> <a href="//d3js.org/d3.v3.min.js"><font color="blue">//d3js.org/d3.v3.min.js</font></a><br>
  <b>D3 World Datamap:</b> <a href="http://datamaps.github.io/scripts/0.4.4/datamaps.world.min.js"><font color="blue">http://datamaps.github.io/scripts/0.4.4/datamaps.world.min.js</font></a><br>
  <b>D3 Queue:</b> <a href="https://d3js.org/d3-queue.v2.min.js"><font color="blue">https://d3js.org/d3-queue.v2.min.js</font></a><br>
  <b>D3 Tooltip:</b> <a href="http://labratrevenge.com/d3-tip/javascripts/d3.tip.v0.6.3.js"><font color="blue">http://labratrevenge.com/d3-tip/javascripts/d3.tip.v0.6.3.js</font></a><br>
  <b>D3 Encoding topology:</b> <a href="//cdnjs.cloudflare.com/ajax/libs/topojson/1.6.9/topojson.min.js"><font color="blue">//cdnjs.cloudflare.com/ajax/libs/topojson/1.6.9/topojson.min.js</font></a><br>
  <b>Colour Schemes:</b> <a href="http://colorbrewer2.org/"><font color="blue">http://colorbrewer2.org/</font></a>
  <br></br>

  See more at: <a href="http://stats.oecd.org/"><font color="blue">http://stats.oecd.org/</font></a><br>
  - <b>Fields:</b> 'Education and Training' --> 'Education at a Glance' --> 'Distribution of graduates and entrants by Field' --> 'Share of graduates by field'.<br>
  - <b>Better Life Index (BLI):</b> 'Social Protection and Well-Being' --> 'Better Life Index (2016)'.
  The data for the educational graduate field distribution is from 2013. The data for the Better Life Index variables is from 2016.


  
•	what problem will be solved for the user:

The user will be able to colour the world/Europe with a variety of predictors. There are no assumptions about the correlation and causation direction. The data is from the OECD website, the predictors being measures of Better Life Index. When clicking on a country, full barchart information will pop up with the full graduate field distribution data of the respective country (if there is any data). The map allows the user to select a country based on the number of the selected general variable, and explore its child well-being data in more detail. It implies a connection between the general variable and the country's grad field distribution; this is all but confirmed however. The linked barcharts nonetheless attempt to allow the user to explore the relationship between the selected general variable and graduate field distribution. Arguably more interesting is that there will also be more graphs displaying the relationship between the different general better life index measures.

•	what features will be available to solve the problem:

A map, linked barcharts and graphs.

•	an overview sketch of what the application will look like for the user; if you envision the application to have multiple screens, sketch these all out:

See doc.

•	what data sets and data sources will you need, how you will get the data into the right form for your app:

http://stats.oecd.org/index.aspx

Export custom CSV files and reformat those.

•	what separate parts of the application can be defined (decomposing the problem) and how these should work together:

The map should work together with the barcharts. The barcharts should be plotted with data of the respective country. Options should be offered to explore correlations between variables.


•	what external components (APIs) you need to make certain features possible:

None?

•	technical problems or limitations that could arise during development and what possibilities you have to overcome these:

Getting the barcharts to work in linked view. Implementing linked views. Adding an operative select menu for building and displaying various graphs. But especially converting the data to usable data structures.

•	a review of similar applications or visualizations in terms of features and technical aspects (what do they offer? how have they implemented it?):

The last assignment of Data Processing is fairly comparable conceptually.

Minimum viable product
Be sure to make clear which parts of the application define the minimum viable product (MVP) and which parts may be optional to implement.

The MVP should be a map colored by 4 variables, barcharts when clicking on a country, and at least one graph (it should offer a select menu to pick which variables to plot against each other).

----------
