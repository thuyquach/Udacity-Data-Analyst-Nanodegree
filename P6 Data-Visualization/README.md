
###1. Summary:
This is Make Effective Data Visualization project for Udacity Nanodegree Data Analyst. I choose the baseball data which  contains 1,157 baseball players including their handedness (right or left handed), height (in inches), weight (in pounds), batting average, and home runs. I explored baseball performance in relation with players' handedness using R and make the data visualization using dimple js.

The results showed that left-handed baseball players have higher number of home run and batting average (Fig.1). Though majority of player are hand-righted, the number of left-handed player was 316 out of 1145 total number of player (27%). It is very interesting since there is only 12% of general public are left-handed. Further research on how baseball play supported the findings that left-handed giving player did have some advantages. 1) When a right-handed batter swings, his momentum takes him toward third base. He has to re-start toward first base. But a lefty’s swing takes him toward first base. 2) Left-handed hitters fair better when against righty pitchers, who are the majority, because the pitch looks like it starts out right in front of him the whole way rather than behind righty's shoulder. 

###2. Design: 
Since the performances (home runs and batting average) are numberical data and the handed-ness is categorical data, I dediced to use bar graph to visualization their correlations. In order to combine three variables in one graph, I uses two-y graph. Home runs (y1) vs. handed-ness relations is visualized as a bar graph and batting average (y2) is visualized as as bubble combined line chart. To differientiate the average and maximum batting average, I assigned different colors (red and yellow color) for the bubble chart. I also added the legend and customized the font size to fit into the bl.ocks.org.

###3. Feedback and change of design:

Feedback 1:
* Understanding and find my data story interesting.
* Suggest reorder the categories to visualize the trend of number of home runs.

My follow-up: I changed the order of the x axis to both, right and left for both graphs. The trends does tell the story better.

Feedback 2:
* Clearly understand the story of the data. It is interesting to see both-hand players did not do as well as the left-hand players.
* Suggest change the color of the bar of the second graph to other color than blue as in first graph.

My follow-up: I played with several colors of the bar and decided to go with gray.

Feedback 3:
* The graphs are clear and easy to understand. The information extraction and analysis is interesting. 
* The explanation on how a game would play out with righty and a lefty is a bit harder to understand since the feedbacker does not know much about baseball.
* If technically possible, the second graph can be converted to a pie chart, so it would show better the distribution of R-B-L.
* In the legend of the first graph, if we put "maximum batting" and "average batting" close to left axis, and the legend of "home run" to the right axis, it would be clearer which y-axis the audience should look at".

My follow-up:
* Add a link to wiki on how baseball play.
* I do not change to pie chart since bar graph is fine to show the distribution of players. Also, I have learned many problems that may cause from pie chart. So, I usually limit the use of it.
* I change the legend property and the font size to make it easier for audience to look at.

Feedback 4: 
* Interesting work, plot used is simple yet effective in presenting all the needed data to support your finding on handedness in baseball and their correlation with player's performance.
* There are some areas where the code was written inconsistently (identation and typo)
* Need to add finding into the summary section
* Tooltip need to correct to be consistent with second graph
* Not quite sure why maximum and average batting are visualized with connected dots. The lines do not really add additional information there as there is no continuous relationship between B, R, and L handedness. Instead what it should be used here is a dodged bar plot.


My follow-up: 
* Fix identation and typo in my code
* Add finding in summary section
* Correct tooltip
* Remove the line from dots. I do not change bubble plots to dodged bar because have two y axises. It would be difficult for audience to distinguish the data.
###4. Resources: 
* udacity.com
* stackoverflow.com
* dimplejs.org