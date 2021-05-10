# GIS-Portfolio
Portfolio for Advanced GIS, Heinz College, Spring 2021

# About me
2nd year MS Public Policy Management - Data Analytics student at Heinz College, Carnegie Mellon University
Claremont McKenna College '18 BA Government, Psychology
Pittsburgh

# What I hope to learn
Throughout this course, I hope to build upon my existing GIS skills and continue to acquire tools that will help me with equity enhancing work in local government work. I've recently taken a class on Tableau, and found the geographic visualizations a bit limiting in functionality, so I'm looking forward to jumping back into ArcGIS to create more complex visualizations! In my tableau class, I did my final project on creating data visualizations for 10 years of abortion data in the US. I hope to be able to expand upon that work (or to gain the skills to be able to expand on that work) by creating a map that illustrates the inter-state travel that some individuals must complete to gain access to abortion. 

# Portfolio

## Assignment 1 Documentation
*Assignment Description: Create a page that includes the color palette you used, a screenshot of your stylized map, and a summary of your design decisions.  You should include an outline of your process from beginning to end, which you'll use to help communicate the steps you took to the organization later.*

Organization: Clean Water Action
Sample Image and Color Palette: 
![Color Scheme](https://user-images.githubusercontent.com/62654408/112781072-25a33580-9018-11eb-9cf5-2b5f7119083d.JPG)

 
Design Decisions
After retrieving a color palette from Adobe for the sample image, I used the Map Styling Wizard to edit the map features to my color palette. Because Clean Water Action’s color palette includes several shades of blue, it immediately became apparent that green would have to be the primary base color, or else it could look misleading in distinguishing between bodies of water and land masses. Light blue was used for roadways, a darker blue was used for waterways, and dark blue was used for points of interest. 
Additionally, because most of the colors are so dark it became clear that words should be a light white with a dark grey outline in order to provide contrast to any and all dark colors beneath. 

This process resulted in this final stylized map:
![Map Screenshot](https://user-images.githubusercontent.com/62654408/112781115-35227e80-9018-11eb-8760-3498c5ab4f91.JPG)



## Assignment 2 Documentation
*Assignment Description: Use ArcGIS Insights to investigate the DEA's pain pill database*

*Discussion Post: Post copy of a screenshot of your own map from the analysis above to the discussion board and write a couple paragraph summary on your thoughts on ArcGIS Insights. What did you learn from working with these data and performing this analysis? (You can reflect on the pain pill analysis, the tutorial content, or both.)*
![image](https://user-images.githubusercontent.com/62654408/117607898-f3aee400-b12a-11eb-8320-d3e19c1d20e1.png)
ArcGIS Insights appears to have similar functionality to Tableau. Both of these platforms are point-and-click friendly, but I found that issues are harder to troubleshoot. For example, I struggled to get the map to filter down to just Mingo county - however this is a simply task in ArcGIS Desktop. Still, being able to compile maps, charts, and tables on one screen is a clear advantage ArcGIS Insights has over ArcGIS Desktop and Tableau.

*Assignment Description: Your supervisor has asked you to prepare a brief comparison between ArcGIS Pro and ArcGIS Insights. A number of your consulting clients are trying to make decisions about which platform to invest time and money training their staff. Create a short deck that you and your coworkers can use (5 - 10 slides) that identifies how the solutions differ, and key considerations for each as a Google Slide deck.*
Link to Slide Deck: https://docs.google.com/presentation/d/1AguDeupcas9LZFxW0rPhxMGthVP50JdtQTzt-SK5kh4/edit?usp=sharing



## Assignment 3 Documentation

*Discussion post: Where you you see using Notebooks in the future?* 
It was interesting to see how ArcGIS pro can integrate with Python through the Notebooks feature - up to this point I had done my data engineering in SQL or R before beginning to map in ArcGIS. While it did integrate quite seamlessly, I do not think that I would use Notebooks in the future - solely because I prefer to use R for data processing and Tableau for creating charts/graphs. The further I get into exploring each of these programs (ArcGIS Pro, R, Tableau, Python), the more it appears that each program can do some element of what the others do but has specialties that make it important to really think about what your end product will be in order to choose the right program for your data analysis needs. For example, R, Tableau, and Python all have ways to produce geographic maps, but none come close to the advanced functionality that ArcGIS offers; R, Python, and ArcGIS all can produce graphs/charts, but the advanced interactivity that Tableau offers is hard to beat. This gets at a core challenge that students interested in data analysis face: is it better to become an expert at one program in particular so that you can maximize the functionality of that program, or to be capable in a wide range of programs and know when to pick/choose each one?

*Discussion post: How might you expand your own use of ArcGIS Pro to better leverage some of the more advanced graphing capabilities in the software?* 
In the future, I could see myself using the selection tool in multiple graphs (like we did to the state and county voter turnout graphs) to best utilize a mix of high-level and granular data. However, like I said above, I still anticipate that I would use Tableau for more advanced graphic tools.



## Assignment 4 Documentation

*Discussion Post: Did working through the exercise give you a broader understanding for how decision trees and the forest-based method work, and what a predictive model tries to do?*
Yes! I had a bit of previous exposure to decision trees and forest-based classification works in Management Science and Data Mining. This exercise was helpful for seeing how these methods translate to geographic data analysis. In particular, I found the distribution of variable importance chart to be very useful at grasping these concepts, and would definitely utilize such a chart if I were to be conducting this type of analysis in the future.

*Discussion Post: Can you imagine using the Forest-Based Classification and Aggregation tool in a real-world scenario?*
Personally, I am not interested in predictive analytics, and doubt that I would use forest-based classification and aggregation in my work in a real-world scenario. However, I have seen predictive tools that may utilize forest-based classification and aggregation in local government. For example, the Allegheny Family Screening Tool utilizes clustering tools (Source (Links to an external site.)). Additionally, I have seen this type of classification tool used precisely in the way it is used in the exercise. While working on political campaigns, we had a voter database that classified voters as reliable voters, turnout voters, and unlikely voters based on a variety of parameters (voter turnout history, geographic residence, age, sex, political affiliation, contact history). Then, at different points in the campaign, we would create targeted contact lists for phone-banking and door-knocking depending on which group we needed to target at that particular time. Our campaign primarily focused on turnout voters. 
