#  FMA (Free Music Archive) Dataset

## Overview

The FMA (Free Music Archive) dataset is a large-scale music dataset designed for Music Information Retrieval (MIR) research. It provides structured metadata, genre hierarchy, and pre-computed audio features for machine learning tasks.

This dataset is suitable for:

-  Music Recommendation Systems  
-  Genre Classification  
-  Audio Feature Analysis  
-  Machine Learning & Deep Learning Applications  

> Note: This is publicly available **secondary data**, not first-hand collected data.

---

## 📊Dataset Details

- **Total Tracks:** 106,574  
- **Total Genres:** 163 (Hierarchical Structure)  
- **Metadata Size:** 342 MB  
- **Format:** CSV  
- **Data Type:** Secondary Dataset  
- **Source:** Free Music Archive (FMA)

---

## 📂 Files Included

| File | Description |
|------|------------|
| `tracks.csv` | Metadata for tracks (ID, title, artist, genre, tags, play counts, license, dates) |
| `genres.csv` | Hierarchical genre structure (163 genres) |
| `features.csv` | Audio features extracted using librosa |
| `echonest.csv` | Audio features provided by Spotify/Echo Nest |

---

## 🧠 Metadata Structure

### 📄 tracks.csv
Contains:
- `track_id`
- `title`
- `artist_name`
- `genre`
- `tags`
- `play_count`
- `license`
- `date_created`
- Additional track-level attributes

---

### 📄 genres.csv
Contains:
- `genre_id`
- `parent_genre`
- `genre_title`

---

### 📄 features.csv
Contains extracted audio features such as:
- MFCC (Mel-frequency cepstral coefficients)
- Spectral centroid
- Spectral bandwidth
- Chroma features
- Zero-crossing rate
- Tempo-related features

---

### 📄 echonest.csv
Contains:
- Danceability
- Energy
- Acousticness
- Instrumentalness
- Liveness
- Valence
- Other high-level audio descriptors

---

## 📥 Download Instructions

Due to GitHub file size limitations, the dataset is **not stored in this repository**.

Download the metadata from:

https://os.unil.cloud.switch.ch/fma/fma_metadata.zip

After downloading:

1. Extract the ZIP file
2. Place the extracted CSV files inside the `FMA/` folder

---

## 🎯 Use Cases in This Repository

This dataset will be used for:

- Music recommendation system development  
- Genre classification using ML models  
- Feature-based similarity analysis  
- Exploratory data analysis (EDA)  
- Audio metadata research  

---

## 📚 Citation

If using this dataset for academic research, please cite the original FMA dataset publication.

---

## ⚖ License & Usage

The dataset is publicly available for research and academic purposes.  
Please refer to the original FMA website for detailed licensing information.

---

## 👨‍💻 Project Context

This dataset is collected as part of research in **Audio & Music Analysis**, focusing on machine learning applications in music recommendation and feature analysis.


