# Brian Tow's Portfolio Landing

This portfolio acts as a hub page to highlight the personal projects I have worked on to better my understanding of data mining, data procurement, data visualization, etc.

## Published Projects

### Powerlifting Calculator

- Created a [website](https://bdt833.shinyapps.io/Powerlifting_Calc/) using R Shiny to help powerlifters predict and visualize their lift attempts to maximize performance
- Discovered that bench press attempts are 10-15% more likely to fail on average as compared with squat or deadlift, suggesting bench press requires better training or better strategy in competition
- Feature engineered metrics to judge overall strength of lifters by combining two standard benchmarks, Wilks/Dots coefficient and weight lifted:bodyweight ratio
- Optimized Linear, Elastic Net, and Random Forest regressors using Tidymodels to choose the most accurate predictive model

### Videogame Database

- Created Python scripts to insert data obtained via [IGDB’s API](https://api-docs.igdb.com/) into a PostgreSQL database of videogame data
- Gained insight as to how to create relational databases with multiple tables and generated SQL queries calling multiple tables at once
- Employed R to data scrape [VGChartz](https://www.vgchartz.com/) and collect sales data about top rated video games

### Healthcare Data Breaches

- Determined that hacking is the leading cause of healthcare data breaches, suggesting that cybersecurity protocols should be taken into effect to diminish breach occurrence
- Attempted to employ inferential statistics and modeling, but found that the data does not describe reality well enough to create good models
- Understood that sometimes more or better data is required for statistical applications

## Works in Progress

### Japanese character image classifier

- Employ Keras in Python to create convolutional neural networks for recognizing Japanese characters
- Deploy a web app using Flask in Python
- Integrate JavaScript into web app to submit images to be classified by neural network
