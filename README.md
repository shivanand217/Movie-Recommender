# Recommendation-Engine

--- Recommendation engine for Movie Lens Dataset.

#### Used Metric
- [x] Euclidean.
- [x] Pearson Coefficient.

## Contributing Guides :crown:
#### This Can be Further Extended.

-- Tasks.
- [ ] Tanimoto score. In what cases could this be used as the similarity metric instead
      of Euclidean distance or Pearson coefficient? Create a new similarity function using
      the Tanimoto score.
      
     The Tanimoto coefficient between two points, a and b, with k dimensions is calculated as:
     
     ![alt text](https://docs.tibco.com/pub/spotfire/6.5.3/doc/html/images/hc_tanimoto_coefficient_eq_1.png)
     
     The Tanimoto similarity is only applicable for a binary variable, and for binary variables the Tanimoto coefficient ranges from 0 to      +1 (where +1 is the highest similarity).

- [ ] User-based efficiency. The user-based filtering algorithm is inefficient because it
      compares a user to all other users every time a recommendation is needed. Write
      a function to precompute user similarities, and alter the recommendation code  
      to use only the top five other users to get recommendations.

:tada:  :smiley: _**Happy Contributing**_ :smiley: :tada:
