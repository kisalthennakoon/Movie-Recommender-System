# Collaborative Movie Recommender System

## Overview

This collaborative movie recommender system leverages user ratings data to provide personalized movie recommendations. By extracting and analyzing user ratings, the system employs gradient descent methods to iteratively learn optimal weights for both movie features and user preferences. This enables the system to accurately predict movie ratings for users based on similar users' preferences and movie characteristics. Additionally, the system can identify similar movies and recommend personalized movie suggestions to new users based on their unique interests.

## Features

- **Personalized Recommendations:** Recommends movies to users based on their ratings and preferences.
- **Similar Movie Finder:** Identifies movies similar to a given movie using learned features.
- **New User Integration:** Adapts to new users by dynamically adjusting weights according to their ratings for known movies.

## Requirements

To run this project, you need the following libraries:

- pandas
- tensorflow
- numpy
- keras
- re
- sklearn
- ipywidgets
- IPython
  
## Usage
1. Open the Jupyter Notebook in Movie Recommender folder.
2. Install all the libraries and download the data mentioned under the requirements title.
3. Run all cells. from the final two cells, you can find similar movies and recommendations respectively.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.



