Shreeman Hariharan: Worked on making the heatmap for Milestone 7 display the location points in a more visible fashion and display the map itself in a more clear way such that the map colors do not interfere with the heatmap layer colors. Added more fake data to make the 
heatmap feature more apparent. Worked on adding a navbar that could be used later for client-side features such as adding locations,
deleting locations, exiting the map etc. Worked on the video for Milestone 6 as the narrator in the video.

Belal Aboabdo: Worked on heatmap and changing themes/vizualizations to make data more readable and visable. Compiled list of types of data we can use to graphically represent in the future. Also attempted to create second visualization with Vega API but was unsuccessful. Reasearched D3 API instead to use for later visualizations. Directed and filmed video for Milestone 6 video prototype.  

Ameer Muhtaseb: Worked on researching d3/Vega for our second visualization, discovering d3 would be much easier to use for the purposes of our project. Worked on collecting data to use in that second visualization. Tested the toggle feature that Khaled created. Played around with Vega trying to see if there was some sort of extra functionality that d3 does not offer that would be worth the extra work to set up.

Khaled Ahmad: Worked on installing Node Js to our application, and connected it with the D3.js. Left the routes open so that we can use the public folder, and just have static html pages for now. Node JS was needed to implement some of the d3 visualizations. Lastly i created the toggle button, which toggles between visualizations. It is done in JS with the use of iFrames. 


This functionality below is the heatmap feature that allows the user to view where they have travelled to on a map. The more colors there
are in a circle on the heatmap, the more places in that region the user has been to. In terms of improvement from Milestone 5, this new map has a neutral map layer coloring of landscape and water as the map colors previously interfered with the heatmap layering that displayed the locations travelled to. In addition, the radius of the travel points is larger than the one from last time, allowing for greater visibility of where the user has travelled to. A toggle feature has been added to the heatmap so that the user can switch to other forms of visualizations of where they have travelled, such as graphs and charts. 
![alt tag](https://github.com/ameezus/cogs121/blob/master/ms7heatmap.PNG)


This functionality below is the graph view of the travel locations that allows the user to graphically visualize where they have travelled in terms of cities worldwide. The bubbles in this graph represent individual cities that the user has travelled to and the bubbles are
sized based on how long the user has traveled at that location for. This is an improvement from Milestone 5 because 
Milestone 5 did not have any graphical representation of the travel data and just has a basic heatmap. The toggle feature is also
included on this graph view as the user can switch to a different way of viewing the travel data.
![alt tag](https://github.com/ameezus/cogs121/blob/master/ms7vegagraph.PNG)

