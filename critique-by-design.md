| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Redesign of “The Best Migration Destinations in 2025” Visualization

## Step one: the visualization

**Original Source**:  
[Visual Capitalist - Ranked: 2025’s Best Countries to Live and Work](https://www.visualcapitalist.com/ranked-2025s-best-countries-to-live-and-work/)

**Screenshot of Original Visualization**:  
![Original Visualization](./images/original_viz.png)  
*(Replace with your actual screenshot)*

I selected this visualization because it presents timely and practical data that’s highly relevant to globally mobile professionals. The original chart is a heatmap-style matrix showing 16 countries across seven dimensions of opportunity — including factors like earning potential, career advancement, and livability. While it provides detailed data, it quickly becomes visually overwhelming and doesn’t effectively tell a story.

I saw an opportunity to simplify this chart, enhance clarity, and introduce a geographic layer to make the data more accessible and interpretable for decision-makers, especially those considering where to relocate in 2025.

---

## Step two: the critique

I used **Stephen Few’s Data Visualization Effectiveness Profile** to critique the original visualization. Some key takeaways:

- **Usefulness (6/10)**: The chart displays important dimensions but lacks an intuitive summary view.
- **Perceptibility (5/10)**: The color variations across many columns make it hard to extract overall insight.
- **Engagement (4/10)**: As a static image, the viewer must put in extra work to find meaning.
- **Appropriateness (6/10)**: While it’s data-rich, the format is not ideal for comparison or big-picture understanding.

The visualization was aesthetically sharp but lacked clear takeaways or spatial context. My critique led me to rethink how to prioritize simplicity and audience usability in my redesign.

---

## Step three: Sketch a solution

I decided to simplify the visual by using a **choropleth world map** that displays each country’s **Total Opportunity Score** as a color-coded value. This offers a clear, instant geographic view of which countries are most attractive.

I used Tableau to prototype this solution. The dataset was loaded in wide format. I created a calculated field that converted the percentage score into a numeric format (e.g., 0.84 → 84), which I used as the color encoding on the map.

**Screenshot of Sketch / Tableau Mockup**:  
<div class='tableauPlaceholder' id='viz1743589716935' style='position: relative'><noscript><a href='#'><img alt='Why Are These the Best Migration Destinations in 2025? ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Bo&#47;Book1partly&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Book1partly&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Bo&#47;Book1partly&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1743589716935');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>
---

## Step four: Test the solution

_We had a class-based feedback session, and I collected informal peer feedback._

**Questions Asked**:

- Can you tell me what you think this is?
- Can you describe to me what this is telling you?
- Is there anything you find surprising or confusing?
- Who do you think is the intended audience for this?
- Is there anything you would change or do differently?

| Question | Interview 1 (MISM student) | Interview 2 (Design student) |
|----------|-----------------------------|-------------------------------|
| What do you think this is? | “A world map showing how attractive countries are for migration.” | “It looks like a global ranking based on opportunity scores.” |
| What does it tell you? | “Switzerland and Singapore are top destinations.” | “You can see regional patterns easily — Europe does well overall.” |
| Surprising/confusing? | “Maybe label the color scale more clearly.” | “Tooltip could include one or two factors, not just score.” |
| Intended audience? | “People thinking about relocating or comparing countries.” | “Policy advisors or global workforce planners.” |
| Changes? | “Add a score legend title.” | “Maybe a bar chart beside it, but this is already clean.” |

**Synthesis**:  
Peers appreciated the clarity and ease of use compared to the original heatmap. Feedback suggested minor tooltip and legend enhancements, which I incorporated into the final design. The overall approach — showing the Total Opportunity Score on a map — was validated as effective.

---

## Step five: build the solution

I built the final solution in **Tableau Public**. I used a choropleth map colored by a calculated field representing the numeric Total Opportunity Score. Each country was shaded using a sequential color scale, and tooltips included country names and their scores.

**Final Redesign Screenshot**:  
![Final Visualization](./images/final_map.png)

This redesign transforms a complex heatmap into a geographically grounded, highly interpretable map. It simplifies comparison and lets the viewer quickly answer: *Where are the best places to migrate in 2025?* Without overloading them with too many variables, the map offers a powerful entry point for further exploration.

---

## References

- Visual Capitalist. “Ranked: 2025’s Best Countries to Live and Work.”  
  https://www.visualcapitalist.com/ranked-2025s-best-countries-to-live-and-work/
- Tableau Public. https://public.tableau.com
- Stephen Few. *Data Visualization Effectiveness Profile*
- World Happiness Report 2024 dataset (used for reference structure)

---

## AI acknowledgements

I used **ChatGPT** to guide me through the critique method, help structure this write-up, draft clear descriptions of my redesign process, and offer suggestions for visualization improvements. All design decisions, Tableau work, and content refinement were done by me.

