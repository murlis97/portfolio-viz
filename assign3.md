## Assignment 3
______
### Percentage of Higher Secondary Schools with Computers in each State in India
## Percentage of Higher Secondary Schools with Computers in each State in India

The following Tableau Visualization is an improved version of the [visualization from Data.gov.in website](https://data.gov.in/major-indicator/percentage-schools-computers). This visualization had some clear and obvious flaws that affected the final message that was being conveyed. I could immediately imagine a different version of the chart which improved the final message and aesthetic appeal of the graph. 

__Process Followed__

---

I started with the good charts matrix to understand areas of improvement for the graph. Contextual awareness needed only a few improvements for this viz as its target audience was a Government Department which studied this data thoroughly. The design execution for this viz had many flaws. I noted down the flaws and the [Data Visualization Effectiveness Profile](http://www.perceptualedge.com/articles/visual_business_intelligence/data_visualization_effectiveness_profile.pdf) 
allowed me to bucket these flaws and understand more areas of improvement. The truthfulness of the data was something I didn't question earlier, but knowing that in some regions the data source is questionable so it is difficult to take the data on its face value. It also highlighted that the data needs to be analysed at a more granular level to create actionable outcomes. Analysing the intuitiveness of the data also pointed out that the states with lower percentage of computers need to be highlighted instead of the states with a high percentage of computers. 
I noted down these changes and created the following [wireframe](https://drive.google.com/file/d/13cbaSyjnx-4aGqIaIz3Te6JrbRPa4WuL/view?usp=sharing) for the proposed graph. 

I shared the visual with my roommates asking them the following questions: 
``` markdown
- Can you describe to me what this is telling you?
- Who do you think is the intended audience for this?
- How would this visual serve the audience?
- Is there anything you find surprising or confusing?
- Suggestions on colouring the graph
- How else would this data be better represented? (Bar graph, contingency table or something else)
```
The feedback for these questions was: 
``` markdown
1. Yes, I am able to comprehend the map and see which states have higher secondary schools with computers and which do not.
2. IT department of every government state
3. Maybe, provide information about how each state is progressing in terms of educating young children and may even give us prediction children of which states will have higher literacy levels in terms of technology and which states aren't investing much in education.
This can help the government to identify key states which aren't investing much in the education sector and therefore, make the required changes in the old policies or launch new policies for the overall development of the country.
4. states which aren't spending much should be red as red is best visible to naked eye and shows warning sign as well. Blue - for states which are doing good
5. I think this is the best possible way to show data state by state but if county data would be possible, it would have been amazing.

1. The map is describing the percentage of higher secondary schools having computers in the Indian States.
2. Government of India or Ministry of Education of India.
3. This visual can serve as a measure of literacy as well as IT skills in Indian youth. Further, this can be an eye-opener for the Indian government to introduce IT education in higher secondary schools as IT is the future.
4. High variance - 0% in some of the states while 100% in other states.
5. Depending on the percentage, the states should be marked as red which have below 30%, amber for 30%-70%, and green for 70% and above.
6. Bar graph would be an alternative to provide a good visualization.
```
The feedback pointed out one key aspect that I had missed. The visualization data was based on data from 2016 only but the source had data from 3 years. Including data from multiple years would improve the interactiveness of the visualization while also allowing the user to get a better picture of improvements in various states during these years. 
Over the course of 3 years, there are many states moving from low to high while some states shockingly seem to move from higher percentage of computer-equipped schools to a lower percentage. The data source does not have any information about the number of schools surveyed each year and changes in school categories, like some students moving from Secondary only to Secondary and High School category. 
These changes need to be incorporated from the data source itself to improve the truthfulness of the visualization. 
But other aspects are greatly improved with this detailed study and it allowed me to create the following in Tableau: 

<div class='tableauPlaceholder' id='viz1615241706744' style='position: relative'>
   <noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Se&#47;SecondarySchoolswithComputers&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a></noscript>
   <object class='tableauViz'  style='display:none;'>
      <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' />
      <param name='embed_code_version' value='3' />
      <param name='site_root' value='' />
      <param name='name' value='SecondarySchoolswithComputers&#47;Dashboard1' />
      <param name='tabs' value='no' />
      <param name='toolbar' value='yes' />
      <param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Se&#47;SecondarySchoolswithComputers&#47;Dashboard1&#47;1.png' />
      <param name='animate_transition' value='yes' />
      <param name='display_static_image' value='yes' />
      <param name='display_spinner' value='yes' />
      <param name='display_overlay' value='yes' />
      <param name='display_count' value='yes' />
      <param name='language' value='en' />
   </object>
</div>
<script type='text/javascript'>                    var divElement = document.getElementById('viz1615241706744');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='650px';vizElement.style.height='1000px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='650px';vizElement.style.height='1000px';} else { vizElement.style.width='100%';vizElement.style.height='900px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>

__________


## [Portfolio Home Page](/portfolio-viz/)
