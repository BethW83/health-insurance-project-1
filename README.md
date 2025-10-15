# Project: Healthcare Insurance Cost Analysis

# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

## Dataset Content

-   The dataset contains information on the relationship between personal attributes (age, gender, BMI, family size, smoking habits) and geographic factors, and their impact on medical insurance charges.

## Business Requirements

-   Analyse healthcare insurance data to understand how personal attributes and geographic factors influence insurance costs.
-   Provide insights for estimating healthcare insurance charges based on personal and geographic attributes.

## Hypothesis

-   Smoking increases insurance charges
-   Increased BMI increases insurance charges
-   Investigate if region affect insurance charges

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

## Ethical considerations

-   The data is available publically on Kaggle
-   Provenance: "my method the collect is conversation with peoples in hospital and too see datas online the hospistal about insegurance for world with my dataset creation visualization with peoples development method."
-   There is no information present in the data that could identify a person specifically

## Dashboard Design

-   List all dashboard pages and their content, either blocks of information or widgets, like buttons, checkboxes, images, or any other item that your dashboard library supports.
-   Later, during the project development, you may revisit your dashboard plan to update a given feature (for example, at the beginning of the project you were confident you would use a given plot to display an insight but subsequently you used another plot type).
-   How were data insights communicated to technical and non-technical audiences?
-   Explain how the dashboard was designed to communicate complex data insights to different audiences.

## Unfixed Bugs

-   Please mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a significant variable to consider, paucity of time and difficulty understanding implementation are not valid reasons to leave bugs unfixed.
-   Did you recognise gaps in your knowledge, and how did you address them?
-   If applicable, include evidence of feedback received (from peers or instructors) and how it improved your approach or understanding.

## Development Roadmap

-   What challenges did you face, and what strategies were used to overcome these challenges?
-   What new skills or tools do you plan to learn next based on your project experience?
-   Ongoing challenge of getting used to a new laptop and to Windows (for many years I have used Linux)
-   Initial error message in VSCode, easily remedied by installing the ipnykernel package and restarting VSCode
-   Error message when trying to show plots using plotly, an updated nbformat needed to be installed, please see screenshot

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
