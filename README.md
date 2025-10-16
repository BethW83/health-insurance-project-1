# Project: Healthcare Insurance Cost Analysis

# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

<img src ="dataset-cover.jpg" alt="Kaggle dataset cover" style="width: 300px; height: auto;">

## Dataset Content

The dataset contains information on the relationship between personal attributes (age, gender, BMI, family size, smoking habits) and geographic factors, and their impact on medical insurance charges.

Columns include:

-   `age`: Age of the insured
-   `sex`: Gender
-   `bmi`: Body Mass Index
-   `children`: Number of dependents
-   `smoker`: Smoking status
-   `region`: One of four regions
-   `charges`: health insurance charges

## Business Requirements

-   Analyse healthcare insurance data to understand how personal attributes and geographic factors influence insurance costs.
-   Provide insights for estimating healthcare insurance charges based on personal and geographic attributes.

## Hypothesis

1. Smoking increases insurance charges
2. Increased BMI increases insurance charges
3. Investigate if region affects insurance charges

## Project Plan

-   Set up new repository and project board on GitHub https://github.com/users/BethW83/projects/2 (please see screenshot of project board at the end of day 1)
-   Get the data from Kaggle
-   Clean the data
-   Transform the data
-   Visualisations following the business requirements
-   Regularly commit to GitHub
-   Document clearly and concisely

## Analysis techniques used

-   When cleaning the data no missing values were found. There was one duplicate row removed. The minimum and maximum values were realistic.
-   To transform the data one column was renamed and an extra column was added for bmi category.
-   Outliers were not removed as the large insurance charges are probably legitimate cases for high risk individuals.
-   Descriptive Statistics: Seaborn and Plotly were used to display figures for hypothesis 1, to show different attributes vs charges with smoker being the hue/colour.
-   Correlation Analysis: Matplotlib was used to show the correlation between BMI and charges, and smoking in hypothesis 2.
-   Geographic Analysis: Seaborn and Plotly were used to display figures for hypothesis 3, to show region vs charges.
-   I used ChatGPT for help when trying to find the best way to generate a useful histogram. Copilot was useful to help with keeping my code efficient and readable.

## Conclusions

-   Hypothesis 1: the four figures clearly show that smokers have higher health insurance charges than non-smokers
-   Hypothesis 2: the bar plot clearly shows that health insurance charges increase with increasing BMI (there is a correlation with being a smoker also)
-   Hypothesis 3: the violin plot and histogram are inconclusive and no conclusion can be drawn that region affects insurance charge without further investigation
-   Extra hypothesis 4: the bar plot shows that insurance charges peak at 3 children and then decrease
-   **Overall conclusion:**
-   _Health insurance charges are higher for smokers compared to non-smokers_
-   _Health insurance charges increase with increasing BMI_
-   _Within this project a clear relationship between region and insurance charges has not been found, further investigation is required_
-   To take this further in the future it would be beneficial to use more personal attributes such as lifestyle (active or sedentary) and any drug use

## Reflection

Being my first ever project it was a steep learning curve. Overall I have enjoyed the experience. In hindsight probably spent too long on the project board and getting VSCode set up.
I leaned more heavily on Copilot and ChatGPT than I would have liked. I found it hard to get into my flow when programming, which I feel has lead to me using simple charts rather than the more interactive plotly figures.
I have benefitted from using desks in Discord and discussing ideas and problems with others on the Code Institute course.

## Ethical considerations

-   The data is available publically on Kaggle
-   Provenance: "my method the collect is conversation with peoples in hospital and too see datas online the hospistal about insegurance for world with my dataset creation visualization with peoples development method."
-   There is no information present in the data that could identify a person specifically

## Unfixed Bugs

-   I was hoping to include a sunburst to display the data by regions but I couldn't get it working within the time so I created a histogram instead because I wanted to include another figure in plotly and finish hypothesis 3.
-   VSCode suggested I update the pip version. I decided not to update during the project as this might have a knock on effect to reinstall/upgrade other libraries. As this is only a two day project with time constraints I didn't want to risk it going wrong. I will upgrade pip tomorrow for security and to ensure future compatibility.

## Development Roadmap

-   Ongoing challenge of getting used to a new laptop and to Windows (for many years I have used Linux)
-   Initial error message in VSCode, easily remedied by installing the ipnykernel package and restarting VSCode
-   Error message when trying to show plots using plotly, an updated nbformat needed to be installed, please see screenshot
-   Error message, kaleido version was not compatible with my version of plotly, therefore uninstalled kaleido and installed a downgraded version
-   Installed packages added to requirements.txt
-   In future projects I would like to save figures in separate files so that they can be included in other documents or attached to emails (rather than screenshots)
-   For future projects is a good idea to carry out a peer review (time permitting)

## Main Data Analysis Libraries

-   Pandas and Numpy: used throughout
-   Seaborn: used to create scatter and boxplots in hypothesis 1 and a scatter plot in hypothesis 2, and a violin plot in hypothesis 3
-   Plotly: used to create a bar chart in hypothesis 1 and a histogram in hypothesis 3
-   Matplotlib: used to create a bar plot in hypothesis 2

## Credits

-   Code Institute https://learn.codeinstitute.net/
-   GitHub https://github.com/Code-Institute-Org/data-analytics-template and https://github.com/5pence/sept-2025-da and https://github.com/mbriscoe/MatplotlibDemo
-   Copilot in VSCode to help with generating code and formatting
-   Chatgpt for general coding queries and fixing some errors
-   Kaggle data https://www.kaggle.com/datasets/willianoliveiragibin/healthcare-insurance
-   NHS website for information on obesity categories https://www.nhs.uk/conditions/obesity/

## Acknowledgements

-   Special thanks to my tutor Emma Lamont and data coaches Spencer Bariball and Mark Briscoe for their ongoing help and support. Thank you also to my fellow bootcampers for their ongoing help and support.
