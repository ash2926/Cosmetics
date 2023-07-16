# Cosmetics Ingredient Analysis and Visualization

This repository contains a project focused on analyzing and visualizing the ingredients of cosmetics products. The code utilizes t-SNE for dimension reduction, creating a scatter plot to visualize the similarity between cosmetic products based on their ingredients. The analysis is performed on a dataset containing information about various cosmetics products, including their ingredients, brand, price, and rank.

## Dataset

The dataset used for this project is loaded from the `cosmetics.csv` file. It contains information about different cosmetics products, including their labels, ingredients, and other relevant details.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/cosmetics-ingredient-analysis.git
   ```

2. Navigate to the project directory:

   ```bash
   cd cosmetics-ingredient-analysis
   ```

3. Install the required dependencies. It is recommended to set up a virtual environment before installing the dependencies. Use a package manager of your choice (e.g., pip or conda) to install the necessary packages listed in the `requirements.txt` file:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Activate your virtual environment, if you set one up.

2. Open the Jupyter notebook `cosmetics_analysis.ipynb`. This notebook contains the code for data preprocessing, tokenization, dimension reduction with t-SNE, visualization using Bokeh, and analysis of similar cosmetics based on ingredients.

3. Customize the analysis as needed. Feel free to modify the parameters, such as the number of components in t-SNE or the color scheme in the scatter plot, to suit your preferences.

## Results

Upon executing the notebook, you will obtain the following outcomes:

- Dimension Reduction: The notebook applies t-SNE to reduce the dimensionality of the ingredients in the dataset, creating two-dimensional representations.

- Scatter Plot: The notebook generates a scatter plot using Bokeh to visualize the similarity between cosmetic products based on their ingredients. Each point represents a cosmetic product, and hovering over a point displays its name, brand, price, and rank.

- Analysis of Similar Cosmetics: The notebook identifies similar cosmetics based on ingredients and displays their information and ingredient lists.

## Contributing

Contributions to this project are welcome. If you have any suggestions, bug reports, or feature requests, please open an issue on the GitHub repository.

## Contact

For any questions or inquiries, please contact [your-email@example.com](mailto:your-ayeshaf2529@gmail.com).

**Enjoy exploring cosmetics ingredients!**
