# 🎵 Music Recommendation System

Hey there! 👋 Welcome to my music recommendation system project. I've built this to help discover new music based on user listening histories.

## 📊 About the Data

The dataset contains:
- 110,000 unique users
- 163,206 unique songs
- ~1.45 million user-song interactions

Each interaction includes:
- User ID
- Song ID
- Play count frequency
- Artist name
- Song title

## 🛠️ Approaches

I've experimented with three different recommendation approaches:

1. **Collaborative Filtering**
   - User-based approach looking at similar listening patterns
   - Handles the cold start problem with negative sampling

2. **Matrix Factorization**
   - Decomposing the user-song interaction matrix
   - Learns latent features for both users and songs

3. **Autoencoder**
   - Neural network approach to learn compressed representations
   - Good at capturing non-linear patterns in the data

## 🚀 Getting Started

1. Create a virtual environment:
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # On Windows use: .venv\Scripts\activate
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebooks in order:
   - `00_processing.ipynb`: Data preparation
   - `01_eda.ipynb`: Exploratory analysis
   - `02_collab_filtering.ipynb`: Collaborative filtering model
   - `03_matrix_factorization.ipynb`: Matrix factorization approach
   - `04_autoencoder.ipynb`: Autoencoder implementation

## 📁 Project Structure

- `data/`: Contains the dataset (not tracked in git)
- `*.ipynb`: Jupyter notebooks for each stage of the project
- `.gitignore`: Standard Python gitignore file
- `requirements.txt`: List of Python dependencies


Happy listening! 🎧