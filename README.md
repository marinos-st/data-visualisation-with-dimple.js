# Data Visualization with Dimple js

![picture alt](http://www.filmscalpel.com/wp-content/uploads/2015/08/slider_glossary_data_visualization.jpg)


## Summary 

Although there was some element of luck involved in surviving the Titanic sinking, some groups of people were more likely to survive than others, such as women, children, and the upper-class. In this visualization, we are trying to tell this story about how passengers' socioeconomic class, sex, and age affected their chances to survive the sinking. Using animation and interactive features, the viewer can better perceive and understand how those factors influenced the survival rates of Titanic passengers.

## Design 

**Initial design decisions:**

I decided to tell this story using a bar chart, where in the x-axis is the Passenger's Socio-economic Class and in y-axis the Survival Rates. In order to give viewers the opportunity to get insights on those important features, I clustered the passengers to three main groups, based on previous cunducted exploratory data analysis: 1. adult Males, 2. adult Females and 3. Minors (under 18y).

Following this, I created an interactive control panel with 4 options:
**All:** includes all the passengers 
**Males:** includes adult males
**Females:** includes adult females
**Child:** includes minors,younger than 18 years all

The viewer can interact with the visualization, by selecting the group of interest from the panel, in order to examine the Survival rate against the group's Socio-economic class. In addition he can use the animation feature to access and compare the four groups, as they iterate through the screen .

**Changes after feedback received:**

1. Changed the y-axis to "Death Rate", since it feels fairer to focus on those lost their life than those survived. 
2. Added an extra tab "All" to the panel, in order to be able to also view a more general picture.
3. Added Introduction in order to introduce viewers to the story.
4. Changed details in Titles.
5. Removed text box from panels.

**Changes after receiving reviewer's feedback:**

1. Changed the y-axis back to "Survival Rate".
2. Fixed coding style and formatting.
3. Removed bar color updating when changing groups.
4. Updated visualization Introduction text and README Design section, to better suit my chart.


## Feedback 

**Feedback 1:**

* I would like to know the overall Survival rates(women+men+children) per class too, consider adding another tab. 
* I would love to see a text introducing the story you are trying to tell.

**Feedback 2:**

* Consider changing the figure's title, by adding which factors are the ones affecting Survival rates.
* You should consider changing the x-axis Title, making it more clear what you mean by "Class". 
* I think you should write 1st/2nd/3rd on the x-axis, instead of 1/2/3.

**Feedback 3:**

* Consider replacing the "Survival rate" with "Death rate" instead, since I believe this is a more 
straightforward way to present this metric of interest.
* My proposal is to change the default color of control tabs from white to some other soft color,
since now it may seem as a note space instead. 
* I don't understand what count 100% means on the text label that appears above the tab, try to fix this.


## Resources 

[1] https://kaggle.com/c/titanic

[2] https://encyclopedia-titanica.org

[3] https://dimplejs.org/

[4] https://perceptualedge.com/articles/b-eye/encoding_values_in_graph.pdf

[5] https://dimplejs.org/advanced_examples_viewer.html?id=advanced_storyboard_control

[6] https://github.com/PMSI-AlignAlytics/dimple/wiki/dimple.storyboard#pauseAnimation

[7] https://discussions.udacity.com/

[8] http://dillinger.io/

[9] http://www.filmscalpel.com/wp-content/uploads/2015/08/slider_glossary_data_visualization.jpg

