| [home page](https://varshithams.github.io/portfolio/) | [visualizing debt](visualizing-government-debt) |  [heat map](heat-map) | [Area chart](area-chart) | [Bar chart](bar-chart) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

## Critique by Design with Tableau (MakeoverMonday)

### Step One: Choose a data visualization from MakeoverMonday

I chose to redesign [Who do we spend time with across our lifetime?](https://ourworldindata.org/time-with-others-lifetime) which I found on [makeovermonday](https://makeovermonday.co.uk/) website. I found this particular topic very interesting and wanted to know more about it.

<iframe src="https://ourworldindata.org/grapher/time-spent-with-relationships-by-age-us" loading="lazy" style="width: 100%; height: 600px; border: 0px none;"></iframe>

### Step Two: Critique the data visualization

Using the [Data Visualization Effectiveness Profile](https://www.perceptualedge.com/articles/visual_business_intelligence/data_visualization_effectiveness_profile.pdf) (DVEP) to evaluate the line chart depicting how Americans spend their time with various groups across different ages provides a structured approach to critique its utility and design. The DVEP's multi-dimensional evaluation criteria—covering usefulness, completeness, perceptibility, truthfulness, intuitiveness, aesthetics, and engagement—allow for a comprehensive assessment beyond subjective measures.

By using the DVEP, I can affirm that the visualization effectively communicates valuable information for the stakeholders(usefulness). Upon applying the DVEP, it becomes apparent that relational nuances—such as the quality of interactions or the context of 'alone' time—are not captured. Adding layers of data that provide context to the 'alone' time, such as whether it is by choice or circumstance, would give a richer understanding of the data(completeness). In terms of perceptibility, the chart is well-designed with clear, distinguishable lines. However, the DVEP highlights the potential for improvement in the representation of overlapping data points.

The truthfulness criterion within the DVEP ensures the data's accuracy and reliability. The visualization appears to meet this standard, but the DVEP prompts questions about the potential for oversimplification. For example, does the representation of time with children versus with family appropriately differentiate between the two, or is there an overlap that isn't addressed?

The chart scores high on intuitiveness for those familiar with line graphs, but the DVEP suggests that additional guidance could be beneficial for novice users. Aesthetically, the visualization is clean and not overburdened with excessive elements, aligning with the DVEP's emphasis on simplicity. However, it points out the need for a more cohesive color scheme that aids those with color vision deficiencies and improves overall legibility. Lastly, in terms of engagement, the chart tells a compelling story that invites further inquiry, aligning with the DVEP's criteria.

I decided to redesign this and make it more user-friendly and engaging.

### Step three: sketch out a solution

While line charts are suitable for this data, I would explore the use of an [area chart with clusters](area-chart-with-clusters) to represent the cumulative time spent with different people.

<div class='tableauPlaceholder' id='viz1707093783040' style='position: relative'><noscript><a href='#'><img alt='Area Chart with clusters ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ar&#47;Areachartwithclusters-timespentwithrelationship&#47;Areachartwithclusters2&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Areachartwithclusters-timespentwithrelationship&#47;Areachartwithclusters2' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ar&#47;Areachartwithclusters-timespentwithrelationship&#47;Areachartwithclusters2&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>
<script type='text/javascript'> 
  var divElement = document.getElementById('viz1707093783040'); 
  var vizElement = divElement.getElementsByTagName('object')[0]; 
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px'; 
  var scriptElement = document.createElement('script');     
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';  
  vizElement.parentNode.insertBefore(scriptElement, vizElement);      
</script>

Source: https://ourworldindata.org/time-use#who-do-we-spend-time-with-across-our-lifetime

I wanted to choose an area chart specifically because I wanted to know how the data flows or the area looks as we age. While I was doing this, I realized that I could go ahead and create 3 clusters representing young age(red), adulthood(orange), and old age(blue). Now it's much easier to know where we stand right now and where are we spending most of our time. With this information, if we are unhappy with the fact, we can change our lifestyle. I chose very subtle colors that are not harsh on our eyes and aid those with color vision deficiencies. Later added a heading as an Area chart and went ahead to clean the axis by removing redundant words like United States. After further alignment, and font changes I felt the chart conveyed information better than it did originally in the line chart. Now it was time for feedback from my friends.


### Step four: Test the solution

I asked two of my CMU friends who are studying MISM-BIDA and are in their mid-20s to give feedback for the [area chart with clusters](area-chart-with-clusters) that I made to represent the cumulative time spent with different people. Their responses to my questions go like this:

**Friend 1:**

_What do you think this is?_
" How much time do people spend with whom at a particular age"

_Can you describe to me what this is telling you?_
" At the age of 70, people spend a lot of time which I never expected. They spend more time with children at the age of 35-40 and the most shocking thing is people spend very less time with their friends at the age of 60-75 which I never expected or was not ready for. The correlation with being alone or with a partner exists. You are either alone or with your partner for most of your life. "

_Is there anything you find surprising or confusing?_
"A surprising element to me is at the age of 55 - 75, time spent with friends is less. Either with family or with your partner as well is less which means it's mostly alone which is scary. Numerical in y-axis for time spent with friends( 0 - 50 - 100) is different when compared to other category( 0 - 100- 200) which is confusing"

_Who do you think is the intended audience for this?_
"Introverts like me. People who want to date or are looking for a relationship. This might also help people who are studying psychology. Let's say I want to build a resort, I would want to look at this graph as I would know who my target audiences are based on age to increase my marketing there"

_Is there anything you would change or do differently?_
" As I mentioned earlier I would change the numerical values in time spent  with friends matching the other categories. I would also want to know more about the span of those individuals whose data was collected. Time spent - these words keep repeating in the y-axis I would remove it and keep it simple making it easier to read or find the categories"

_How much would you rate this out of 10?_
" I would rate this 9/10 as it was easy to understand as a whole, but if you make those changes that I mentioned I think it would be much easier"



**Friend 2:**

_What do you think this is?_
"How much time a person spends with other people or alone at different point of time in their life"

_Can you describe to me what this is telling you?_
"Time spent alone doesn't fluctuate much. At some age, the fluctuation is there but it's not significant which reflects that the person tends to spend most of the time with himself. Time spent with children - There are situations where people have had children at an early age but there is a major spike in the yellow zone which indicates people tend to spend more time with the kids at that particular age - whatever time you might have had a kid, you will spend more time with them in 30-40. Kids will leave eventually. Time spent with coworkers - red zone  is when you start working so there is a  definite spike, majority of our time is spent there. Most of us are working mostly in the yellow zone at that age so it looks like we are spending more time during adulthood. There is a slight decrease in the yellow zone here and there as the number of people you work with keeps changing. Blue indicates retirement so time spent eventually drops. Time spent with friends - The red zone indicates more friends and more time because that's when we go to college and it's a sweet spot, not enough responsibility, but there is a dip when we reach the yellow zone because responsibility is more and energy is less with friends. And with a partner - increases and keeps increasing which is amazing. With others - more time when you are a kid, and it starts decreasing when you reach adulthood as you are more independent here and decreases more when you become old."

_Is there anything you find surprising or confusing?_
"Confusing - Time spent with friends is a little confusing here with respect to data. Red to yellow there is a major dip. I think more time will be spent in adult age. After work, you want to chill with friends so such a huge dip is confusing.
Surprising - Time spent with a partner is confusing as well because you will be working more in the yellow zone. So is that possible to spend time in the yellow zone that is adulthood? I feel in red it would be more. In the red zone, we might have a partner and time and we often will be able to give time to our partner there. But here according to data, we spend less time there which is very surprising and not right according to me"

_Who do you think is the intended audience for this?_
"Working population which could have other social relevance like the realization of where they are spending time and where they could."

_Is there anything you would change or do differently?_
"I would not change anything"

_How much would you rate this out of 10?_
"10/10 - I could understand what I was seeing. Confusing was with numbers/facts and not with the visualization."

### Step five: Build your solution

There are many things that I learned from the feedback. I have included most of the changes suggested by my friends and made the changes to make the visualization look much better and more understandable.

Changes included a clear heading, more redundancy in the y-axis, and adding another row above the y-axis. I realized I could also add some information with the heading to give more clarity regarding what the graph is trying to convey. One more major thing was the intervals in the y-axis were not unique which I changed here.

<div class='tableauPlaceholder' id='viz1707093684478' style='position: relative'><noscript><a href='#'><img alt='Who do we spend time with across our lifetime? (United States) ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ar&#47;Areachartwithclusters-timespentwithrelationship_updated&#47;Areachartwithclusters3&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Areachartwithclusters-timespentwithrelationship_updated&#47;Areachartwithclusters3' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ar&#47;Areachartwithclusters-timespentwithrelationship_updated&#47;Areachartwithclusters3&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div> 
<script type='text/javascript'> 
  var divElement = document.getElementById('viz1707093684478'); 
  var vizElement = divElement.getElementsByTagName('object')[0];   
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script'); 
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';  
  vizElement.parentNode.insertBefore(scriptElement, vizElement);    
</script>

Source: https://ourworldindata.org/time-use#who-do-we-spend-time-with-across-our-lifetime


Post critique session in the classroom I came up with new inspiration that can be added to my present chart.
Based on the suggestion that I received, I added a timeline of the data and rearranged the categories where I put data with partners and friends on top as people would be excited to more about them. I also changed the label in y-axis from "parents,siblings and other family" to just "other family" to keep it simple.
My classmate also mentioned how surprising this data is about people spending time with partners, friends, or themselves. She mentioned clustering the data made it more clear and understandable. 

<div class='tableauPlaceholder' id='viz1707167584154' style='position: relative'><noscript><a href='#'><img alt='Who do we spend time with across our lifetime? (United States between 2009 and 2019)Studying how people across the world spend their time provides an important perspective for understanding living conditions, economic opportunities, and general well-bei ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ar&#47;Areachartwithclusters-timespentwithrelationship_updated1&#47;Areachartwithclusters3&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Areachartwithclusters-timespentwithrelationship_updated1&#47;Areachartwithclusters3' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ar&#47;Areachartwithclusters-timespentwithrelationship_updated1&#47;Areachartwithclusters3&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>
<script type='text/javascript'> 
  var divElement = document.getElementById('viz1707167584154');
  var vizElement = divElement.getElementsByTagName('object')[0]; 
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px'; 
  var scriptElement = document.createElement('script'); 
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js'; 
  vizElement.parentNode.insertBefore(scriptElement, vizElement);   
</script>

Source: https://ourworldindata.org/time-use#who-do-we-spend-time-with-across-our-lifetime

I also came across this issue in Tableau where I cannot rotate the label in the y-axis to the left-right configuration. I tried every alignment option and went through the [website](https://community.tableau.com/s/question/0D54T00000M1MCLSA3/change-axis-label-direction-from-vertical-to-horizontal) (and discussed with our TA) to find out it's the way the tableau has been designed. This is possible only if the data set is discrete and not continuous like in our case.





