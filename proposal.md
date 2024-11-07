Proposal_P8105
================

## Motivation

From recreation to community gathering, parks play an important role as
a a public service. Auyeung et al.’s report on New York City’s park
usage describe the multifaceted role of parks in supporting community
health and well-being, such as through providing a common space for
socializing and physical activity, along with access to nature in an
urban setting (Auyeung et al., 2016). In particular, we are interested
in the role of sanitation infrastructure in public parks such as public
bathrooms and drinking fountain availability and maintenance in
promoting community health in New York City.  
Swayne et al.’s study analyzing public restroom access in sanitation
justice discuss the public health implications of public bathroom
availability among vulnerable populations like homeless/unhoused people
who are reliant on public bathrooms, such as associations between lack
of public bathroom access with dehydration and urinary tract infections
due to restroom avoidance. Access to public bathrooms is also necessary
for reducing the spread of infectious disease, such as through
preventing public defecation or encouraging hand washing (Swayne et al.,
2023). The presence of accessible bathrooms in public spaces like parks
therefore plays an important role in public health and equitable health
outcomes. However, to ensure that these health advantages are attained,
public bathrooms also have to be regularly maintained as lack of
necessities (such as soap, hot water, or toilet paper) or the presence
of other hazards can nullify these benefits. Additionally, facilities
like drinking fountains provide a convenient and free source of clean
water to the public which can prevent dehydration along with
environmental benefits such as reduced usage of single-use plastic water
bottles. Water fountains in public parks offer a clean, convenient
drinking water source to the public \[add more about why fountains are
important\]  
This project intends to explore access to facilities such as public
bathrooms and water fountains in New York City parks in relation to (do
we want to study these in relation to something like parks
funding/income/etc?)

## Intended Final Product

Our project aims to create a comprehensive, user-friendly website that
improves the visibility and accessibility of NYC park data. This
platform is designed to support individuals interested in public health,
urban planning, and community resources by providing accessible and
insightful information.  
The website will present a series of interactive dashboards and
visualizations that offer comprehensive insights into NYC park data,
covering aspects such as public sanitation, drinking fountains, restroom
facilities, and additional data sources. These visualizations are
designed to enable users to intuitively explore and analyze the
distribution and condition of public amenities across NYC parks through
dynamic, data-driven displays. To further enhance interactivity, the
platform integrates a Shiny app, allowing for real-time data
manipulation and in-depth analysis. \[Additionally, a dedicated section
links our findings to key public health indicators (e.g., sanitation
access, environmental safety, and mental health), providing valuable
context on how these factors contribute to park safety and community
well-being.\] By integrating and presenting these datasets, we aim to
empower communities, researchers, and policymakers to make data-informed
decisions that enhance public health and urban quality of life.

## Data Source

### Public Toilet Locations and Availability in NYC Parks (616 \* 6)

- **Source**: [Directory of Toilets in Public
  Parks](https://data.cityofnewyork.us)
- **Description**: Contains information on toilet locations, opening
  years, accessibility, and usage, which helps analyze the distribution
  of sanitation facilities across parks.

### Drinking Fountain Locations and Condition (3849 \* 13)

- **Source**: [NYC Parks Drinking
  Fountains](https://data.cityofnewyork.us)
- **Description**: Details the locations and operational status of
  drinking fountains, including park names, coordinates, and maintenance
  data, allowing us to assess their distribution and usability across
  parks.

### Public Restroom Conditions & Hazards (56.4k \* 22)

- **Source**: [Parks Inspection Program - Public Restroom
  Inspections](https://data.cityofnewyork.us)
- **Description**: Provides detailed restroom inspection data, including
  cleanliness, maintenance status, and safety hazards, allowing us to
  evaluate the overall state of restrooms and identify improvement
  areas.

### Additional Data Sources

We may also explore supplementary datasets for a more comprehensive
view: - **Dog Runs**: Insights into dog-friendly spaces that may reflect
park health. - **Crime Data**: Analysis of park-related crime to
understand safety concerns and their impact on amenities.

## Planned Analyses / Visualizations / Coding Challenges

Analysis Challenges: Data Fragmentation: The datasets are from multiple
sources (toilets, drinking fountains, crime data, etc.), which requires
data consolidation and normalization to provide consistent analysis.
Correlation Complexity: Determining the relationships between different
factors such as restroom availability, visitor flow, and public safety
can be challenging due to the influence of multiple variables.
Visualization Challenges: Conciseness for Website: Since the final
product is a website generated through GitHub, the final datasets used
should be kept as streamlined as possible. What’s more, visualizations
need to be concise for web display, ensuring clarity while being
lightweight to support quick loading. Selecting Appropriate
Visualization Types: Choosing the right visualization method (e.g.,
scatter plot, box plot) for each type of analysis to enhance
readability. Coding Challenges: Data Cleaning and Integration: Data
sources come in different formats and may have missing values, requiring
effort to clean and merge for analysis. Standardizing Variables in Team
Collaboration: To avoid data conflicts or confusion during team
collaboration, it’s best to establish a unified naming convention to
ensure consistency in the project.

# Project Timeline

## 10/28 - 11/8

- **Decide project theme, goals, and research questions**: Clarify focus
  areas for sanitation’s role in public parks.
- **Complete project proposal**: Draft proposal outlining objectives,
  data sources, and expected outcomes.

## 11/11 - 11/15

- **Data cleaning and organization**: Preprocess datasets for analysis.
- **Report**: Begin writing “Motivation,” “Related Work,” “Initial
  Questions,” and “Data” sections.
- **Website initialization**: Set up website framework and tools.
- **Project review meeting**: Discuss feedback and refine tasks.

## 11/18 - 11/22

- **Exploratory Data Analysis (EDA)**: Analyze patterns in sanitation
  data.
- **Website**: Add EDA findings to website.

## 11/25 - 11/29

- **Report**: Document key EDA findings.
- **Interactive website development**: Implement Shiny app and
  dashboards.

## 12/2 - 12/6

- **Report**: Complete “Additional Analysis” and “Discussion.”
- **Video**: Create project summary video for website.
- **Website completion**: Finalize layout and navigation.
- **Peer assessment**: Gather feedback and make final adjustments.
