# Project: Healthcare Insurance Cost Analysis

# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

## Dataset Content

-   The dataset contains information on the relationship between personal attributes (age, gender, BMI, family size, smoking habits) and geographic factors, and their impact on medical insurance charges.

## Business Requirements

-   Analyse healthcare insurance data to understand how personal attributes and geographic factors influence insurance costs.
-   Provide insights for estimating healthcare insurance charges based on personal and geographic attributes.

## Hypothesis

-   1. Smoking increases insurance charges
-   2. Increased BMI increases insurance charges
-   3. Investigate if region affect insurance charges

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
-   Outliers were not removed as the large insurance charges are probably legitimate cases for high risk individuals

-   Descriptive Statistics: box plots
-   Correlation Analysis: scatter plots
-   Geographic Analysis:

-   List the data analysis methods used and explain limitations or alternative approaches.
-   How did you structure the data analysis techniques. Justify your response.
-   Did the data limit you, and did you use an alternative approach to meet these challenges?
-   How did you use generative AI tools to help with ideation, design thinking and code optimisation?

## Conclusion

-   To take this further in the future it would be beneficial to use more personal attributes such as lifestyle (active or sedentary) and drug use.

## Reflection

Being my first ever project it was a steep learning curve. Overall I have enjoyed the experience. In hindsight probably spent too long on the project board and getting VSCode set up.
I leaned more heavily on Copilot and ChatGPT than I would have liked. I found it hard to get into my flow when programming.
I have benefitted from using desks in Discord and discussing ideas and problems with others on the Code Institute course.

## Ethical considerations

-   The data is available publically on Kaggle
-   Provenance: "my method the collect is conversation with peoples in hospital and too see datas online the hospistal about insegurance for world with my dataset creation visualization with peoples development method."
-   There is no information present in the data that could identify a person specifically

## Unfixed Bugs

-   Please mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a significant variable to consider, paucity of time and difficulty understanding implementation are not valid reasons to leave bugs unfixed.
-   Did you recognise gaps in your knowledge, and how did you address them?
-   If applicable, include evidence of feedback received (from peers or instructors) and how it improved your approach or understanding.

## Development Roadmap

-   Ongoing challenge of getting used to a new laptop and to Windows (for many years I have used Linux)
-   Initial error message in VSCode, easily remedied by installing the ipnykernel package and restarting VSCode
-   Error message when trying to show plots using plotly, an updated nbformat needed to be installed, please see screenshot
-   Error message, kaleido version was not compatible with my version of plotly, therefore uninstalled kaleido and installed a downgraded version
-   In future projects I would like to save figures in separate files so that they can be included in other documents or attached to emails

## Main Data Analysis Libraries

-   pandas
-   numpy
-   seaborn
-   plotly
-   matplotlib

## Credits

-   Code Institute https://learn.codeinstitute.net/
-   GitHub https://github.com/Code-Institute-Org/data-analytics-template and https://github.com/5pence/sept-2025-da and https://github.com/mbriscoe/MatplotlibDemo
-   Copilot in VSCode to help with generating code and formatting
-   Chatgpt for general coding queries and fixing some errors
-   Kaggle data https://www.kaggle.com/datasets/willianoliveiragibin/healthcare-insurance
-   NHS website for information on obesity categories https://www.nhs.uk/conditions/obesity/

## Acknowledgements

-   Special thanks to my tutor Emma Lamont and data coaches Spencer Bariball and Mark Briscoe for their ongoing help and support. Thank you also to my fellow bootcampers for their ongoing help and support.
