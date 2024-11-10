# Music Genre Classification with PCA

![Music Genre Analysis](https://res.cloudinary.com/dgwuwwqom/image/upload/v1731226570/Music.png)

This project explores a dataset of music tracks to classify genres based on various musical features using Principal Component Analysis (PCA) and machine learning techniques.

## 📁 Dataset Overview

The dataset consists of multiple numerical and categorical features describing the characteristics of various music tracks:

- **Tempo**: Beats per minute (BPM) of the track.
- **Dynamic Range**: The difference between the quietest and loudest parts of a track (measured in decibels).
- **Vocal Presence**: The prominence of vocals in a track.
- **Percussion Strength**: The intensity and presence of percussion instruments like drums and cymbals.
- **String Instrument Detection**: The presence and prominence of string instruments (e.g., guitars, violins).
- **Electronic Element Presence**: The extent of electronic sounds used in a track.
- **Rhythm Complexity**: The intricacy and variation of rhythm patterns.
- **Drums Influence**: Contribution of drums to the overall sound.
- **Distorted Guitar**: The usage of distorted guitar sounds, commonly found in rock or metal genres.
- **Metal Frequencies**: Use of frequencies associated with metal music.
- **Ambient Sound Influence**: Incorporation of ambient sounds to add texture.
- **Instrumental Overlaps**: Interaction and overlap of various instruments.
- **Genre**: The categorized genre of each track (target variable).

## 🔍 Project Workflow

1. **Data Preprocessing**:
    - Data loading, exploration, and cleaning.
    - Handling missing values and encoding categorical features.

2. **Feature Scaling**:
    - Standardizing numerical features for improved model performance.

3. **Dimensionality Reduction**:
    - Applying PCA to reduce the dimensionality of the dataset while preserving significant variance.

4. **Model Training & Evaluation**:
    - Using a Logistic Regression model to classify music genres.
    - Evaluating model performance using accuracy score and classification reports.

5. **Visualization**:
    - Visualizing the dataset, PCA results, and classification outcomes using Matplotlib and Seaborn.

## 🛠️ Technologies Used

- Python (Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn)
- Machine Learning (Logistic Regression, PCA)
- Data Visualization

## 📊 Results

The model's performance metrics, along with visualizations, help in understanding how well different features contribute to genre classification. The use of PCA helps in reducing the feature space, thereby improving model interpretability.

## 🚀 How to Run the Project

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/music-genre-classification.git
    cd music-genre-classification
    ```
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the Jupyter Notebook:
    ```bash
    jupyter notebook Music\ Genre\ Classification\ with\ PCA\ -\ Solution.ipynb
    ```

## 📄 License

This project is open-source and available under the MIT License.
