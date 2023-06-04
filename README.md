![Netflix Logo](https://www.freepnglogos.com/uploads/netflix-tv-logo-png-9.png)
[![GitHub stars](https://img.shields.io/github/stars/msadeqsirjani/CineMetrics?style=social)](https://github.com/msadeqsirjani/CineMetrics/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/msadeqsirjani/CineMetrics?style=social)](https://github.com/msadeqsirjani/CineMetrics/network/members)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

# Netflix Dataset Analysis

Astonishing, fascinating, and mesmerizing analysis of the Netflix dataset to uncover hidden patterns and associations between directors, casts, and genres. The project is divided into three phases: data pre-processing, finding associative rules, and AI clustering using Decision Tree and SVM based on the film's description.

## Table of Contents

- [Data Pre-processing](#data-pre-processing)
- [Finding Associative Rules](#finding-associative-rules)
- [AI Clustering](#ai-clustering)
- [Dataset Structure](#dataset-structure)
- [Contributing](#contributing)

## Data Pre-processing

In this phase, we clean the dataset by handling missing values, removing duplicates, and converting data types to ensure smooth analysis.

## Finding Associative Rules

We analyze the dataset to find associative rules between the director, cast, and genre. This allows us to understand the relationships between these elements and draw meaningful conclusions.

## Clustering

In the final phase, we use clustering techniques (Decision Tree and SVM) to find the film's genre based on the film's description.

## Dataset Structure

The dataset is structured as follows:

- `show_id`: A unique identifier for each movie/TV show.
- `type`: The title of the movie/TV show.
- `title`: Director of the movie.
- `director`: Actors involved in the movie/TV show.
- `cast`: The country where the movie/TV show was produced.
- `country`: The date it was added to Netflix.
- `date_added`: The actual release year.
- `release_year`: The TV show/movie rating.
- `rating`: The total duration, in minutes or number of seasons.
- `duration`: The movie/TV show's category.
- `listed_in`: Description.

## Contributing

We welcome contributions! If you're interested in contributing to this project, please follow these steps:

1. Fork the repository
2. Create a new branch with a descriptive name (`git checkout -b new-feature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to your branch (`git push origin new-feature`)
5. Open a Pull Request

For more information about contributing, please refer to the [CONTRIBUTING.md](CONTRIBUTING.md) file.