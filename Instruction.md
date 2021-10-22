
1. Use the 'titanic' dataset

      - Features: 'pclass', 'sex', 'age', 'fare'
      - Target: 'survived- Drop missing value on used features if any.
        - Perform data splitting with the proportion of 80:20 
        and random_state = 42
2. KNN
- Perform data scaling , and see the accuracy value.
- Find the best K value in the range from 1 to 150. Interpret the results, relating them to overfitting and underfitting.
3. Decision Tree
- Analyze model performance (overfitting, underfitting, sweet spot) using the following hyperparameters:
    - minimum samples split (min_samples_split) with a range of 2150
    - minimum samples leaf (min_samples_leaf) with a range of 1150
- Also explain what the hyperparameter does and its interpretation.