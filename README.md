# 🎧 Real-Time Spotify Analyzer

This Jupyter Notebook project analyzes the **currently playing track on Spotify** using the **Spotify Web API** via the `spotipy` library. It extracts detailed audio features of the song and provides a real-time snapshot of the track's characteristics.

---

## 🚀 Features

- ✅ Connects to the Spotify Web API using `spotipy`
- ✅ Authenticates with Spotify using Client ID & Secret
- ✅ Fetches:
  - Track name
  - Artist(s)
  - Album
  - Popularity
  - Track duration
  - Tempo (BPM)
  - Energy, Danceability, Valence, etc.
- ✅ Displays all extracted information in a clean format

---

## 🛠️ Tech Stack

| Tool        | Purpose                           |
|-------------|-----------------------------------|
| Python      | Core programming language         |
| Jupyter Notebook | Interactive environment    |
| Spotipy     | Spotify Web API wrapper           |
| pandas      | Data handling                     |
| matplotlib  | (Optional) Visualization support  |

---

## 🔐 Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/MariSubila/Real-Time-Spotify-Analyzer.git
--- 

## Install the required libraries:

  pip install spotipy pandas

---
  
## Set up your Spotify Developer credentials:

* Go to Spotify Developer Dashboard

* Create a new application

* Copy your Client ID and Client Secret

* Use them in the notebook to authenticate

---
## Run the notebook:

jupyter notebook spotify.ipynb

