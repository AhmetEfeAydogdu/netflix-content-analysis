# Film–Soundtrack Popularity Relationship Analysis

This project looks at whether popular films also tend to have popular soundtrack tracks. Using publicly available Kaggle datasets for both movies and Spotify songs, the goal is to combine the two and see if there is a noticeable connection between a film’s popularity and the popularity of the music linked to it.

---

## Problem Definition

Films and soundtrack tracks each have their own popularity metrics.  
Here, the main question is:

**“Do films with higher popularity scores also have more popular soundtrack songs?”**

To explore this, film metadata and Spotify track data are matched and compared.

---

## Why This is Interesting

Soundtracks are a big part of a film’s identity. Some movies become memorable largely because of their music, while some songs gain popularity thanks to the film they appear in.

Checking how film success and soundtrack success align together can give simple but meaningful insights into how the two areas influence each other.

---

## Methodology

1. **Data Collection:**  
   Film data is taken from Kaggle (TMDB-based datasets).  
   Track data comes from large Spotify datasets on Kaggle.

2. **Matching:**  
   Films and related soundtrack tracks are paired using title-based matching.

3. **Features:**  
   - Film: popularity, release year, budget.  
   - Tracks: popularity, tempo, energy, valence, etc.

4. **Analysis:**  
   Basic correlation checks and regression models are used to see how strongly film popularity relates to soundtrack popularity.

---

## Expected Outcomes

- A clearer view of whether film popularity aligns with soundtrack popularity.  
- Simple visualizations showing the relationship between film features and music features.  
- A combined dataset linking films with the tracks associated with them.

---

## Notes

All data comes from open Kaggle datasets.  
No video or audio files are used—only metadata.
