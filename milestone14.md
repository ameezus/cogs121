Belal Aboabdo: Set up share to Facebook which shares a link to the deployed app to the users Facebook. Also worked on 
finishing up final D3 graphs and deploying the Heroku.

Ameer Muhtaseb: I worked on some UI changes to make the app look a bit cleaner and nicer. I also cleaned up some code for a 
few of the visualizations and worked on deploying the app to heroku.

Khaled Ahmad: I worked implementing the backend of the application, grabbing all the data from the Facebook API and scrubing 
it then adding it to the visualization. I also implemented the login sysytem, and the photomap visualization. I connected all
the data from FB to the d3 visualizations. 

Shreeman Hariharan: I worked on the navigation panel by making vertical and adding the feature where the legend for the 
graph is shown in response to hovering the mouse over the link. I also made this navbar more informative by adding small
thumbnail images next to the link text for reference.

App Features:
- This app simply allows users to visualize through a heatmap and graphs where they have travelled to. In order to avoid the
issue with manual insertion of locations, the application fetches location check-in data from the users' Facebook profiles.

- The app allows users to login via Facebook and import locations where they checked-in via Facebook in order to be displayed
on graphs and a heatmap by the application.

- The app contains different graphical representations for users to be able to visualize their travel data. These representations 
include a heatmap (made with Google Maps), bubble graph, circle graph, line graph, and a bar graph. All of these graphs 
except for the heatmap are created using Vega. 

Heatmap:
![alt tag](https://github.com/ameezus/cogs121/blob/master/ms7heatmap2.png) 

Bubble graph:
![alt tag](https://github.com/ameezus/cogs121/blob/master/bubble.png)

Photo Map:
![alt tag](https://github.com/ameezus/cogs121/blob/master/photo.png)

- The app contains a navbar (image below) that allows users to navigate through the website. Hovering the mouse over each link 
label allows the user to see a description/legend of each graph/map representation. The user can randomly choose a graph to be 
displayed.

![alt tag](https://github.com/ameezus/cogs121/blob/master/navbarnew.png)
