# Covid-Simulation-Pred-w-GameTheory

This repository contains a Jupyter Notebook implementing a deep learning workflow for analyzing and modeling data with a focus on small population datasets.
Here we analyse the spread of a disease in France to compare different strategies and scenarios against it. We run a multiagent simulation to create a dataset on a subpopulation, and create a deep learning surrogate model from that data to predict it on a higher scale. We assess the best course of action through the number of contamination and deaths predicted. Our results show that focusing the vaccine on people that are contaminated can be more efficient than focusing on fragile or elderly people to mitigate the number of deaths. It also shows that lockdowns are efficient in diminishing the spread of a disease, and that the degree of compliance of the  population affects its efficiency

## Project Structure

The project is organized into the following sections:

1. **Importing Libraries**: Includes necessary dependencies such as `numpy`, `pandas`, and deep learning libraries.
2. **Data Processing**: Functions for loading and preprocessing data from CSV files.
3. **Deep Learning Model**: A model tailored for scenarios with limited data, addressing specific challenges of small population datasets.
4. **Scenarios and Analysis**: Simulated cases to demonstrate the model's capabilities and performance.

## Dependencies

Make sure you have the following Python libraries installed:

- `numpy`
- `pandas`
- `tensorflow` or `keras`
- `matplotlib`

You can install these dependencies via pip:

```bash
pip install numpy pandas tensorflow matplotlib
```


## Features

- **Customizable Deep Learning Model**: Tailored for small datasets.
- **Interactive Analysis**: Explore various scenarios and visualize results.

## Contributing

Contributions are welcome! If you would like to contribute, please fork the repository and submit a pull request.