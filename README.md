Growing up in a digital era: measures of child-being, their relationship with each other, and their relationship with the digital era – how does the number of Internet users of a country correlate with the different measures of child well-being?
Jaap Nieuwenhuizen

•	what problem will be solved for the user:

The user will be able to explore a map colored by percentage of Internet users per country and data about child well-being of the respective country. The map and the linked barcharts show the relationship between Internet users (or Internet more in general), and measures of child well-being. There will also be more graphs displaying the relationship between the different measures of child well-being, such as literacy and birth weight.

(Alternative idea: The user will be able to explore and analyse possible correlates (most notably, percentage of Internet users) with educational field of study in all countries of the world. It will display whether a high number of Internet users (implying accessible Internet) stimulates different life choices. More importantly, the graph will explore whether STEM disciplines (Science, Technology, Engineering, Mathematics) are more common in countries with a high number of Internet users. After all, the Internet is a huge source of information, and is gradually getting more and more important. The same map will also be constructed by GDP instead of Internet users as well.).

•	what features will be available to solve the problem:

A map, linked barcharts and graphs.

(Alternative: Clicking on a country pops up a barchart with the study-field distribution data for the respective country. The colors of the colored map will depend on the percentage of Internet users.)

•	an overview sketch of what the application will look like for the user; if you envision the application to have multiple screens, sketch these all out:

See doc.

(Alternative: Map (colored by Internet users) and linked barcharts. Possibly two maps (Internet users and GDP). Perhaps even graphs (between STEM/Science, math and computing + engineering and Internet users / GDP).).

•	what data sets and data sources will you need, how you will get the data into the right form for your app:

http://stats.oecd.org/index.aspx
Child well-being: http://stats.oecd.org/Index.aspx?DataSetCode=BLI
For the map (Internet): http://www.internetlivestats.com/internet-users-by-country/

Export CSV files and reformat those.

•	what separate parts of the application can be defined (decomposing the problem) and how these should work together:

The map should work together with the barcharts. The barcharts should be plotted with data of the respective country. Options should be offered to explore correlations between variables.

(Alternative: an interactive map and barcharts. Perhaps even two maps, and perhaps even graphs as well. But the latter aren’t part of the MVP.)

•	what external components (APIs) you need to make certain features possible:

None?

•	technical problems or limitations that could arise during development and what possibilities you have to overcome these:

Getting the barcharts to work in linked view. Implementing linked views. Adding an operative select menu for building and displaying various graphs.

(Alternative: Quite uncertain as of now. Perhaps the formatting of the csv files to usable data objects. And getting nice design to display the data with…

Actually, being able to select the data I need to draw the graphs with; this probably isn’t that easy to do, as there are a lot of redundant columns and rows in my data as well.).

•	a review of similar applications or visualizations in terms of features and technical aspects (what do they offer? how have they implemented it?):

The last assignment of Data Processing is relatively comparable in concept.

Minimum viable product
Be sure to make clear which parts of the application define the minimum viable product (MVP) and which parts may be optional to implement.

The MVP should be a map colored by Internet users (in percentages), barcharts when clicking on a country, and at least one graph (it should offer a select menu to pick which variables to plot against each other).

(Alternative: The world map (by Internet users) with linked views to explorative barchart (field of study) defines the MVP.).
