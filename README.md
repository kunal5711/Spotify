# Music Recommendation System

This project is a simple music recommendation system that suggests songs based on their energy levels. It uses a dataset from Spotify and calculates song similarities to provide recommendations.

## Table of Contents

- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Usage](#usage)
- [Features](#features)
- [Contributing](#contributing)

## Introduction

This music recommendation system is designed to help users discover songs with similar energy levels to their favorite tracks. It uses a dataset of songs from Spotify and calculates song similarities based on their energy attributes.

## Prerequisites

Before you can run the project, you'll need to have the following dependencies and tools installed:

- Python 3.x
- pandas
- numpy
- scikit-learn
- pickle (Python module)

You can install these dependencies using pip:

```bash
pip install pandas numpy scikit-learn

```
## Usage
```bash
recommended_songs = recommend_songs("Song name among the data set", spotify, similarities)
print(recommended_songs)
```

## Example
recommended_songs = recommend_songs("More Hearts Than Mine", spotify, similarities)
recommended_songs

### Output
['My Heart Went Oops',\
 'Friday 13th (feat. Octavian)',\
 'Cornelia Street - Live From Paris',\
 'Welcome to Chilis',\
 'Demon Time (Lil Yachty feat. Draft Day)']

## Features
Recommends songs based on energy levels.\
Uses a custom similarity metric based on energy attributes.\
Preprocesses the dataset to improve recommendation accuracy.

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.
