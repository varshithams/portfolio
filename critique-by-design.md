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

### Step three: sketch out a solution

While line charts are suitable for this data, I would explore the use of an [area chart with clusters](area-chart-with-clusters) to represent the cumulative time spent with different people.

### Step four: Test the solution

I asked two of my CMU friends who are studying MISM-BIDA and are in their mid-20s to give feedback for the [area chart with clusters](area-chart-with-clusters) that I made to represent the cumulative time spent with different people. Their responses to my questions go like this:

**Friend 1:**

_What do you think this is?_
" How much time do people spend with whom at a particular age"

_Can you describe to me what this is telling you?_
" At the age of 70, people spend a lot of time which I never expected. They spend more time with children at the age of 35-40 and the most shocking thing is people spend very less time with their friends at the age of 60-75 which I never expected or was not ready for. The correlation with being alone or with a partner exists. You are either alone or with your partner for most of your life. "

_Is there anything you find surprising or confusing?_
"A surprising element to me is at the age of 55 - 75, time spent with friends is less. Either with family or with your partner as well is less which means it's mostly alone which is scary. Numerical in y axis for time spent with friends( 0 - 50 - 100) is different when compared to other category( 0 - 100- 200) which is confusing"

_Who do you think is the intended audience for this?_
"Introverts like me. People who want to date or looking for a relationship. This might also help people who are studying psychology. Lets say I want to build a resort, I would want to look at this graph as I would know who my target audiences are based on age to increase my marketing there"

_Is there anything you would change or do differently?_
" As I mentioned earlier I would change the numerical values in time spent  with friends matching the other categories. I would also want to know more about the span of those individuals whose data was collected. Time spent - these words keep repeating in yaxis I would remove it and keep it simple making it easier to read or find the categories"

_How much would you rate this on 10?_
" I would rate this 9/10 as it was easy to understand as a whole, but if you make those changes that I mentioned I think it would be much easier"



**Friend 2:**

_What do you think this is?_

_Can you describe to me what this is telling you?_

_Is there anything you find surprising or confusing?_

_Who do you think is the intended audience for this?_

_Is there anything you would change or do differently?_

### Step five: Build your solution

There are some things that I learnt from the feedback.

