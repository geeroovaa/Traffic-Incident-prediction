# Traffic-Incident-prediction
311 traffic incident prediction power
The 311 NYC Service Request database hosts thousands of complaints per day. Among the most popular ones is the one regarding poor street conditions. Only in 2016, around 90,000 inquiries were made with geotagged locations by latitude and longitude for this type of complaint. Having previously worked on Vision Zero, a road traffic safety project that aims to reduce traffic accidents, I decided to assess if there is a relation between the number of street condition complaints and the number of traffic accidents recorded in the NYPD Motor Vehicle Collisions dataset, for the same locations for the year 2016.
Two variables were identified to tackle this problem: the number of traffic accidents and the number of street condition complaints for the same locations. The datasets were cleaned and merged according to their geotags.
A Pareto table was created to focus on where the 80% of the counts resided. The data presented the following attributes:
The data was normalized by its mean and transformed into a logarithmic scale;  an ordinary least squares regression model was run.
We can infer by the R-squared value of the model (0.45) that there is certain relation between both variables. The slope coefficient suggests that there would be 74 traffic accidents for every 100 poor street condition complaints for that same location.



