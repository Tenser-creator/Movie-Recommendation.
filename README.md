# Movie Recommendation Based on Emotion

A Flask web app that captures a live webcam frame, detects the user's dominant
facial emotion using OpenCV, and recommends movies that match that mood.

> Based on an open-source template ([original project](https://github.com/M-yadav007/Move-Recommendation-based-on-emotion)),
> customized and extended as a personal learning project.

## What I changed

- Integrated the project with Flask for a web interface.
- Customized the HTML pages for a better user experience.
- Added image preprocessing before emotion detection.
- Improved single-face detection to reduce incorrect predictions.
- Modified the recommendation logic to display emotion-based movie suggestions.

## Features
- Real-time facial emotion detection via OpenCV
- Flask web interface showing detected emotion + movie list
- Emotion detection using webcam
- Emotion-based movie recommendations
  

## Installation
1. Clone the repo: `git clone https://github.com/Tenser-creator/Movie-Recommendation..git`
2. Install dependencies: `pip install -r requirements.txt`
3. Run: `python app.py`
4. Visit `http://localhost:5000`

## Contact
Dhruv Balaiwar — balaiwardhruv@gmail.com
