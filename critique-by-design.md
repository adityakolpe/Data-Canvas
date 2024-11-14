| [home page](https://adityakolpe.github.io/Data-Canvas/) | [visualizing debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Liam's Guide to Find Affordable Pizza Slice in NYC

## Step one: the visualization

I selected [Liam's NYC Slice data visualization](https://elkue.com/nyc-slice/) because of my genuine interest in pizza and my constant quest to find affordable yet delicious pizza spots. This visualization offers an engaging way to explore various pizza options across New York City, highlighting locations, prices, and other useful information. 

Beyond my personal love for pizza, I appreciate how this visualization simplifies the search for budget-friendly pizza places. It makes the data accessible and fun, allowing users to compare options at a glance, which aligns perfectly with my goal of discovering great pizza at reasonable prices.

![image](https://github.com/user-attachments/assets/da5c0fbf-92c8-4bed-9b26-115bf277ca58)
![image](https://github.com/user-attachments/assets/f48a6fdd-fec6-4ebe-a23e-3f8a601ba8cf)

## Step two: the critique
Overall observations about the data visualization:
What stood out to me?  What did I find that worked really well?  What didn't?  What, if anything, would I do differently?
-> Overall the visualization is informative and makes me want to eat more pizza (I already had 2 in the last 3 days). I am going to NYC later this month and I wanted to know where should I have an affordable pizza. As the dots on the map represent the places, we do not have a year filter so we need to hover over each dot and see if it is the latest year. I would love to have a year filter so that I can easily filter by year.

Primary audience:
Primary audience are the people who love pizza (like me and Joey from friends). This visualization is effective in helping us understand the prices at which the shops sold a slice of pizza in that year.

Anything missing?
I would add a year filter so that I can look at the latest prices and choose a shop to actually go have pizza there. I would also include a trends plot which would tell us the price trend of a slice of pizza at that particular place over the years. 

![image](https://github.com/user-attachments/assets/1831eb58-0421-4495-a000-d1051ad6b740)


## Step three: Sketch a solution

I initially sketched a bar chart visualization to show the popularity of different pizza places in NYC based. My goal was to highlight the most affordable spots people were talking about, with higher bars indicating more pocket-friendly. After creating the chart, I showed it to a few friends, hoping it would clearly communicate which places were most recommended. However, they found it confusing, as the bars alone didn’t convey the location or the price pizza. The visualization didn’t fully capture what I wanted to convey.

## Step four: Test the solution

Questions: 

- Can you tell me what you think this is?

- Can you describe to me what this is telling you?

- Is there anything you find surprising or confusing?

- Who do you think is the intended audience for this?

- Is there anything you would change or do differently?

Results: 

| Question | Interview 1 | Interview 2 |
|----------|-------------|-------------|
|Can you tell me what you think this is? | Its a data visualization of pizza price variations in NYC | Pizza price documentation |
|Can you describe to me what this is telling you? | Trend of price changes for 2 types of pizzas - plain and pepperoni. | Pizza prices at different shops in NYC - lower to higher |
|Is there anything you find surprising or confusing? | No not really, could understand once I dragged points across the map | Nothing surprising or confusing |
|Who do you think is the intended audience for this? | Pizza lovers/ tourists finding a cheap pizza place in the city | Pizza lovers |
|Is there anything you would change or do differently? | Location is not visible | Would like to see latest prices |

Synthesis: 

From the feedback, a few patterns emerge around clarity, interactivity, and the information users value most. Both interviewees understood that the visualization was about pizza prices in NYC, but their interpretations varied slightly, suggesting that the main takeaway could be clarified. One respondent mentioned wanting to see the latest prices, while the other found location visibility to be an issue, indicating that both recent data and clear location markers are important to the audience. 

From this feedback, I learned that while the overall purpose of the visualization is understood, enhancing specific details like recent price information and visible location markers would make it more useful. Users seem interested in current data and precise location details, which indicates that focusing on these aspects will improve usability.

For the final redesign, I’ll prioritize displaying updated prices more prominently, perhaps adding a filter for users to view the latest prices specifically. I’ll also enhance the map section, ensuring that each pizza place’s location is clearly marked and easy to spot at a glance. Adding tooltips or labels for each location could further aid users in quickly identifying places without having to explore each point individually. Together, these changes should create a more intuitive and informative experience for pizza enthusiasts looking for affordable options in NYC.

## Step five: build the solution

<div class='tableauPlaceholder' id='viz1731550776254' style='position: relative'><noscript><a href='#'><img alt='Liam&#39;s Guide to Find Affordable Pizza Slice in NYCClick on a Pizza Place Name or Select a year to filter ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Li&#47;LiamsGuidetoFindCheapPizzaSliceinNYC&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='LiamsGuidetoFindCheapPizzaSliceinNYC&#47;Dashboard1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Li&#47;LiamsGuidetoFindCheapPizzaSliceinNYC&#47;Dashboard1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1731550776254');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1016px';vizElement.style.height='991px';} 
  else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1016px';vizElement.style.height='991px';} 
  else { vizElement.style.width='100%';
        vizElement.style.height='1077px';}                     
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>




I began by attempting to replicate the original visualization displayed on the website, aiming to match its design and structure. Once I achieved a similar layout, I decided to adjust the color scheme to make the pricing data more intuitive: higher prices were set to appear in red, while lower prices were shown in blue. This color coding helped make affordability stand out visually. 

Exploring further, I experimented with additional visualizations, including line plots to capture price trends over time for each pizza place. I also created a new sheet displaying a sorted table of store names and prices, with the most affordable options at the top. To enhance interactivity, I tried adding a year filter that would synchronize across all sheets, though I encountered some challenges with getting the filter to apply uniformly.

Next, I designed a dashboard incorporating three sheets: the map view, the table of names and prices, and the trend line plot. I enabled interactive filtering so that selecting any element in one sheet would update the others accordingly. I also attempted to set up an action that would filter all sheets simultaneously by year but encountered some technical issues. As a workaround, I set the year filter on one sheet to impact another related plot.

In the final stages, I rearranged the dashboard for ease of use. The table with names and prices was placed prominently to make it easy to identify affordable options, and I ensured that clicking on a store name would filter the trend line and map view. This setup allows users to view the price trends of a selected pizza place over time, see its location on the map, and get a clear price comparison in the table. With this dashboard, users have all the essential information they need to plan their next pizza outing effectively.
