# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 
    # Visualization 1 - Python
    > What software did you use to create your data visualization?
    I used Python, the pandas library for data manipulation and Matplotlib for creating the scatter plot. 

    > Who is your intended audience? 
    The intended audience includes Toronto residents, city planners, local tourism organizers, immigrants, and anyone interested in the two spcific neighbourhood walking tours.

    > What information or message are you trying to convey with your visualization? 
    The visualization conveys which walking tours are available in the selected neighbourhoods, specifically highlighting the distribution of tours for ‘West Humber Clairville’ and ‘Rexdale-Kipling’. The goal is to make it easy to see what tour options exist in each neighbourhood at a glance.

    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
    Key design considerations included:
    1. Marker types and colors: Red stars for West Humber Clairville and green stars for Rexdale-Kipling to distinguish neighbourhoods clearly.
    2. Axes labeling: X-axis shows neighbourhoods, Y-axis shows tour titles, giving context to what each point represents.3. Grid lines: Horizontal dashed grid lines aligned with neighbourhood rows make it easier to track tours across neighbourhoods.
    3. Legend placement: Positioned near the plot to identify the markers without cluttering the visual.
    4. Figure size and rotation: Adjusted figure size (8×8) and rotated X-axis labels (30°) to improve readability of text and prevent overlap.

    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    Using Python with pandas and Matplotlib ensures full reproducibility: anyone with the dataset and the same code can generate the exact same visualization. Because the data and code are explicit, results are consistent and can be updated easily if the dataset changes.
    > How did you ensure that your data visualization is accessible?  
    1. Color choice: Red and green markers were chosen for high contrast, but for accessibility, marker shape also differs (stars).
    2. Text readability: Axis labels, plot title, and legend are clearly visible and sized appropriately.
    3. Grid lines: Help viewers align tours with neighbourhoods visually.

    These choices improve readability for viewers with varying visual abilities.

    > Who are the individuals and communities who might be impacted by your visualization?  
    1. Residents who want to explore local walking tours.
    2. Tourism organizations planning community events or marketing neighbourhood tours.
    3. City planners assessing distribution of walking tours across Toronto.
    4. Researchers or students studying urban planning, accessibility, or tourism patterns.

    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    Included: Specific Neighbourhood and Title because the goal is to show which tours exist in these specific neighbourhoods.

    Excluded: Other Neighbourhoods, and dataset features such as Ward, DescriptionWard_name, order , etc, since they are not relevant to this specific comparison of neighbourhood tour offerings. This keeps the plot simple and readable.

    > What ‘underwater labour’ contributed to your final data visualization product?
    Cleaning and inspecting the dataset to ensure neighbourhood names and tour titles were accurate.
    Deciding which neighbourhoods to focus on (West Humber Clairville and Rexdale-Kipling).
    Choosing marker styles, colors, figure size, rotation, and grid alignment for clarity and readability.
    Iteratively testing code to handle different numbers of tours and long tour names without overlapping points.
    Ensuring the plot was reproducible and accessible by setting proper labels, legends, and colors.


    # Visualization 2 - Excel
    > What software did you use to create your data visualization?
    I used Microsoft Excel to create the pivot table and bar chart. Excel was used to filter, summarize, and visualize the dataset using pivot tables, which allow dynamic exploration of data.    
    
    > Who is your intended audience? 
    The intended audience includes city planners, local tourism organizers, researchers, and Toronto residents interested in exploring walking tours by ward. It could also serve students or analysts studying urban accessibility or community engagement.
    > What information or message are you trying to convey with your visualization? 
    The visualization conveys the number of StrollTO tours available in each ward and allows filtering by neighbourhood. It highlights which wards have more tours and can help identify areas with fewer or more walking opportunities.

    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
    Pivot table structure: Using Ward Names in rows and Count of Titles in values makes it easy to compare tour counts.
    Filters for neighbourhoods: Allows viewers to focus on specific neighbourhoods of interest.
    Bar chart: Chosen for clarity and easy comparison of numeric values.
    Axis labels and title: Clearly indicate what the chart represents.
    Sorting: Wards can be sorted alphabetically or by count to emphasize patterns.
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    Pivot tables in Excel are fully reproducible: anyone with the same dataset can recreate the pivot table and chart by following the same steps. If the tool were not reproducible, updates to the dataset would require manually rebuilding the visualization, increasing the risk of errors and inconsistencies.

    > How did you ensure that your data visualization is accessible?  
    Clear labels and titles make the chart understandable.
    Filters allow users to focus on relevant neighbourhoods or wards.
    Bar chart orientation ensures numeric comparison is easy to interpret.
    High-contrast colors and readable fonts improve visibility for all viewers.

    > Who are the individuals and communities who might be impacted by your visualization?  
    Local residents looking for walking tours.
    Tourism organizations planning events or promoting community activities.
    City planners assessing distribution of tours across wards.
    Researchers or students analyzing patterns in urban accessibility or community engagement.

    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    Included: Ward Name (rows), Title (values), Neighbourhood (filter) because these directly show number of tours per ward and neighbourhood.
    Excluded: Other columns because they are not relevant to the focus on counting tours per ward.
    
    > What ‘underwater labour’ contributed to your final data visualization product?
    Cleaning and inspecting the dataset to ensure ward names and neighbourhoods are accurate.
    Setting up the pivot table correctly with rows, values, and filters.
    Sorting and formatting the chart for readability and accessibility.
    Iteratively adjusting labels, titles, and filters to ensure clarity.
    Verifying counts against raw data to ensure accuracy of representation.


- This assignment is intentionally open-ended - you are free to create static or dynamic data visualizations, maps, or whatever form of data visualization you think best communicates your information to your audience of choice! 
- Total word count should not exceed **(as a maximum) 1000 words** 
 
### Why am I doing this assignment?:  
- This ongoing assignment ensures active participation in the course, and assesses the learning outcomes: 
* Create and customize data visualizations from start to finish in Python
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story  
- This would be a great project to include in your GitHub Portfolio – put in the effort to make it something worthy of showing prospective employers!

### Rubric:

| Component         | Scoring  | Requirement                                                                 |
|-------------------|----------|-----------------------------------------------------------------------------|
| Data Visualizations | Complete/Incomplete | - Data visualizations are distinct from each other<br>- Data visualizations are clearly identified<br>- Different sources/rationales (text with two images of data, if visualizations are labeled)<br>- High-quality visuals (high resolution and clear data)<br>- Data visualizations follow best practices of accessibility |
| Written Explanations | Complete/Incomplete | - All questions from assignment description are answered for each visualization<br>- Explanations are supported by course content or scholarly sources, where needed |
| Code              | Complete/Incomplete | - All code is included as an appendix with your final submissions<br>- Code is clearly commented and reproducible |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 11/02/2025`
* The branch name for your repo should be: `assignment-3`
* What to submit for this assignment:
    * A folder/directory containing:
        * This file (assignment_3.md)
        * Two data visualizations 
        * Two markdown files for each both visualizations with their written descriptions.
        * Link to your dataset of choice.
        * Complete and commented code as an appendix (for your visualization made with Python, and for the other, if relevant) 
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-3`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
