# Music Recommender System

This repository contains a music recommender system with implementations for both collaborative filtering and content-based recommendation approaches.

## Table of Contents
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
  - [Collaborative Recommender System](#collaborative-recommender-system)
  - [Content-Based Recommendation System](#content-based-recommendation-system)
- [Contributing](#contributing)
- [License](#license)

## Project Structure

```plaintext
music_recommender-master/
│
├── collaborative_recommender_system/
│   ├── recommeders/
│   │   ├── __init__.py
│   │   ├── knn_recommender.py
│   │   ├── CF_knn_music_recommender.ipynb
│   │   ├── CF_matrix_factorization_music_recommender.ipynb
│
├── content_based_recommendation_system/
│   ├── content_based_music_recommender.ipynb
```

### Description of Files

- `collaborative_recommender_system/recommeders/`
  - `__init__.py`: Initialization file for the recommenders module.
  - `knn_recommender.py`: Implementation of the K-Nearest Neighbors recommender.
  - `CF_knn_music_recommender.ipynb`: Jupyter Notebook for the KNN-based collaborative filtering recommender.
  - `CF_matrix_factorization_music_recommender.ipynb`: Jupyter Notebook for the matrix factorization-based collaborative filtering recommender.

- `content_based_recommendation_system/`
  - `content_based_music_recommender.ipynb`: Jupyter Notebook for the content-based music recommender.

## Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/yourusername/music_recommender-master.git
    cd music_recommender-master
    ```

2. (Optional but recommended) Create a virtual environment to manage dependencies:

    ```sh
    python -m venv music_recommender_env
    source music_recommender_env/bin/activate  # On Windows: music_recommender_env\Scripts\activate
    ```

3. Install the required packages:

    ```sh
    pip install -r requirements.txt
    ```

## Usage

### Collaborative Recommender System

1. Navigate to the collaborative recommender directory:

    ```sh
    cd collaborative_recommender_system/recommeders
    ```

2. Run the Jupyter Notebooks to explore the collaborative filtering approaches:

    ```sh
    jupyter notebook CF_knn_music_recommender.ipynb
    ```

    ```sh
    jupyter notebook CF_matrix_factorization_music_recommender.ipynb
    ```

### Content-Based Recommendation System

1. Navigate to the content-based recommender directory:

    ```sh
    cd content_based_recommendation_system
    ```

2. Run the Jupyter Notebook to explore the content-based recommendation approach:

    ```sh
    jupyter notebook content_based_music_recommender.ipynb
    ```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request or open an Issue.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
