

# Linguistic Data of 32k Film Subtitles

## Team Members
- Tanishka Adhlakha
- Harshal Shinde
- Amogh Inamdar
- Yash Gaikwad

## Project Overview
This project explores the linguistic data from 32,000 film subtitles to understand how language influences movie ratings and genres. We focus on various aspects of movie data, including movie names, release dates, runtimes, ratings, and the usage of different types of words, which could potentially impact a movie's success.

## Repository Contents
- **Film_subtitles_analysis.html**: Main project file containing all data analyses and visualizations.
- **Film_subtitles_analysis_code.Rmd**: Main project R code containing all data analyses and visualizations.

## Key Insights
1. **Genre Distribution**: Analysis of how movies are distributed across genres over the years.
2. **Ratings vs Votes**: Exploration of how ratings correlate with the number of votes across genres.
3. **Emotional Impact**: Investigation of how the emotional undertones of subtitles correlate with movie ratings.

## Conclusion
The project provides deep insights into how subtitle content can affect movie reception and ratings. We found significant relationships between the emotional content of subtitles and the genres' popularity and ratings. 

## How to Run
Open `Film_subtitles_analysis.html` in any web browser to view the project analysis and findings.

## Running the Analysis

To run the R Markdown file (`Film_subtitles_analysis_code.Rmd`) and reproduce the analysis, follow these steps:

1. **Install R and RStudio**
  
2. **Install Required Packages:**
   - Open RStudio and install the necessary R packages by running the following commands in the console:
     ```R
     install.packages(c("tidyverse", "lubridate", "ggplot2", "dplyr", "stringr"))
     ```
   Replace the package names in the `install.packages()` function with those used in your R Markdown file.

3. **Open and Run the R Markdown File:**
   - .Rmd file will execute all the code chunks and generate a report in HTML, PDF, or Word format, depending on the settings in your document.



## References
- Data sourced from [Robertjoellewis' Film Subtitles Dataset](https://data.world/robertjoellewis/film-subtitles)
- Various academic references and IMDB data insights.

