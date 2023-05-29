# Netflix Movie Recommender System

This code is a movie recommender system implemented using Python and the Streamlit library. The recommender system uses a dataset stored in a CSV file (`DataFrame.csv`) to provide movie recommendations based on user input.

## Installation

To run this code, you need to have the following dependencies installed:

- Python 3.x
- numpy
- pandas
- streamlit

You can install these dependencies using pip:

```shell
pip install numpy pandas streamlit
```

## Usage

1. Ensure that the required CSV file (`DataFrame.csv`) is in the same directory as the code file.
2. Run the code using the command:

```shell
streamlit run app.py
```

3. After running the code, a web-based user interface will be launched with the title "Movie Recommender System."
4. The interface will display a dropdown menu containing a list of movie titles.
5. Select a movie from the dropdown menu to get recommendations for similar movies.
6. The code will load precomputed movie similarity data from a pickled file (`similarity.pkl`).
7. The top ten recommended movies will be displayed in a table format.
8. Click the "Recommend" button to view the recommended movies.


