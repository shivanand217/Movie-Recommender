# Recommendation-Engine

--- Recommendation engine for Movie Lens Dataset.

#### Used Metric
- [x] Euclidean.
- [x] Pearson Coefficient.

## Contributing Guides :crown:
#### This Can be Further Extended.

-- Tasks.
- [] Tanimoto score. Find out what a Tanimoto similarity score is. In what cases
     could this be used as the similarity metric instead of Euclidean distance or
     Pearson coefficient? Create a new similarity function using the Tanimoto score.

- [] Tag similarity. Using the del.icio.us API, create a dataset of tags and items. Use
     this to calculate similarity between tags and see if you can find any that are
     almost identical. Find some items that could have been tagged “programming”
     but were not.

- [] User-based efficiency. The user-based filtering algorithm is inefficient because it
     compares a user to all other users every time a recommendation is needed. Write
     a function to precompute user similarities, and alter the recommendation code  
     to use only the top five other users to get recommendations.

