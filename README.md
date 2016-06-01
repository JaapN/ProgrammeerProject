Exploration of educational field distribution by mapping of average student skills, employment rate, personal earnings and life satisfaction – investigating educational profile correlations with seemingly generic variables?
@author: Jaap Nieuwenhuizen

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
