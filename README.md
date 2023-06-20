# Data Science Project - California Traffic Accident Classification

For this project, I attempted to classify whether a traffic accident on California highways would result in a fatality. 

This dataset contains every instance of a traffic collision in the state of California from 2001 to 2020. For the purposes of this analysis, we will only be analysing traffic collisions that 
happened in the year 2020. A Random Forest classifier will be used to predict whether a traffic collision resulted in a fatality or not. Since we are dealing with real life data, where a signficant 
imbalance exists between nonfatal and fatal accidents (99.4 / 0.6), our main metric of evaluation will be recall (or sensitivity). Recall tells us the fraction of correctly identified positive predictions
from all positive cases. 

In this case, a positive case is a fatal traffic accident, and therefore False Negatives are more costly than False Positives (a fatal crash predicted nonfatal vs a nonfatal crash being predicted fatal).
