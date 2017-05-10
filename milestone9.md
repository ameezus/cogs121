Khaled Ahmad: I worked on implementing a method in which we could easily store data and an api to reach each of the data points. This feature is not yet complete. I also worked on making the vidsualizations more appealing on the screen by centering them. I also looked into the facebook API in order to see if we could get the checkin data and realized checkins are no longer a feature on FB, but there are work arounds that might be better.

Ameer Muhtaseb: I worked on adding another visualization to our app. This visualization is a timeline that displays when and
where the user traveled to/visited. Just like any other timeline the event (place traveled to) is marked down next to the date
it happened on. The time line includes arrows to show when/where a trip started and finished. Different trips will have
different sets of arrows. I also linked a json file to the visualization so that we could add/edit/remove data as necessary.
This visualization came from D3.

Belal Aboabdo: Gathered initial data to represent bundle graph. Also implemented bundle graph using the D3 API and connected graph to node. 

Shreeman Hariharan: Since turning in Milestone 7, I worked on the paper prototype for the "Import From Facebook" screen. After that,
I worked on the data input screen's front-end that allows users to import their data from Facebook or input their data manually.

This functionality is another graphical representation of the data that shows the locations that have been travelled to with
links between the starting and ending locations for trips. The locations with longer arc lengths are ones that have been travelled
to more often as there are more links associated with them. Length of time spent in each destination is also represented by the color of the connection between two destinations. The darker the color the longer time you've spent at that destination. This functionality is an improvement since Milestone 7 because it
now shows the starting and ending locations for each trip that has been taken, which allows the user to track more information
regarding their data.
![alt tag](https://github.com/ameezus/cogs121/blob/master/circle%20graph.PNG)

This functionality is another graphical representation of the data that is displayed on a line graph such that the dates of
travel are shown with respect to where the user has travelled. This functionality is an improvement since Milestone 7 because it
now shows the time information regarding trips taken, which is more useful to the users in visualizing their travel data in a 
better way.
![alt tag](https://github.com/ameezus/cogs121/blob/master/line%20graph.PNG)

This functionality is a feature that allows users to add data points regarding where they have travelled. This feature is an improvement
from Milestone 7 because the app now has a means of allowing users to add locations to their dataset. The user may now add data 
points to their dataset by importing locations from their Facebook account based on places they have checked into or by 
manually entering location names based on city, state, and country.
![alt tag](https://github.com/ameezus/cogs121/blob/master/add%20locations.PNG)
