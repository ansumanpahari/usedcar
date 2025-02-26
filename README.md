# Machine Learning and Artificial Intelligence
**Required Assignment 11.1: What Drives the Price of a Car?**

The project is to find out the features which influences a used car price. Using those, develop sevaral ML algorhithms and finally find an optionmal algorithm that can predict the price of a used car.

## Findings Based on Assignment
Run through all phases of CRISP-DM. Evaluated several algorithms and finally selected a model and based on mse on test data set.

### Best Model
    - Ridge Model
        - Polynomial feature 3
        - 1.0 is the Hyperparameter
### Limitation
    - Polynomial feature for Lasso kept at 2.
    - Polynomial feature for Ridge with all features kept 3.
    - Couldn't go higher because of limited resource (mem/cpu)
### File Structure
- data folder - Contains data (csv) file
- images folder - Contains images
- prompt Jupyter file - The main juypter file. Contains code.