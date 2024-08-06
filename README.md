# Data and code for analyzing the experiment testing if people associate [r] and [l] with a zigzag or straight line

This represents a streamlined analysis focusing on the main predictions and variables.

The structure of this repostiroy is as follows:

- `1_language_coding.Rmd` contains the manual coding of the languages in terms of [r] and [l],
-  `2_r_l_preparation.Rmd` cleans and prepares the data for analysis,
-  `3_r_l_modeling.Rmd` performs the actual analysis and produces the "pretty" plots.

Please note that comiling should be done in order, but `3_r_l_modeling.Rmd` should be smart enough to call the previous ones if needed.

- `autotyp_areas_map.jpg` is the map of the AUTOTYP areas used here
- `theme_timo.R` is a plotting theme
- **data** contains the various data needed for the analysis
- **plots** is where the plots are stored
- **simuli** contains info about the stimuli
- **cached_results** is where the various Bayesian models are saved to spare time when compiling the `Rmarkdwon` script.

