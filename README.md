# Movie Recommendation System

## Overview

Welcome to the Movie Recommendation System project! This project demonstrates the implementation of a content-based movie recommender system using cosine similarity.

<p>Have you ever wondered how Netflix suggests movies to you based on the movies you have already watched? Or how e-commerce websites display options such as "Frequently Bought Together"? Behind these seemingly simple options, complex statistical algorithms execute to predict these recommendations. Such systems are called Recommender Systems, Recommendation Systems, or Recommendation Engines.</p>

<p>A Recommender System is one of the most famous applications of Data Science and Machine Learning. In this project, we explore three types of recommender systems:</p>

<ul>
    <li><strong>Demographic Filtering (Simple Recommender)</strong></li>
    <li><strong>Content-Based Filtering</strong></li>
    <li><strong>Collaborative Filtering</strong></li>
</ul>

## Dataset

<p>The dataset used in this project is the <strong>tmdb-5000-movies</strong> dataset, a collection of movie information available on The Movie Database (TMDB). It is often used in machine learning and data analysis to explore patterns and trends in the film industry and for building recommendation systems.</p>

### Dataset Details

<p>The original dataset was generated from The Movie Database API. This product uses the TMDb API but is not endorsed or certified by TMDb. The data was collected from the TMDB 5000 Movie Dataset, a popular movie database website known for its wealth of information on movies, TV shows, and celebrities. The dataset contains two main tables:</p>

#### movies_metadata.csv

<p>Contains general information about the movies, such as:</p>
<ul>
    <li>id</li>
    <li>budget</li>
    <li>genres</li>
    <li>homepage</li>
    <li>keywords</li>
    <li>original_language</li>
    <li>original_title</li>
    <li>overview</li>
    <li>popularity</li>
    <li>production_companies</li>
    <li>production_countries</li>
    <li>release_date</li>
    <li>revenue</li>
    <li>runtime</li>
    <li>spoken_languages</li>
    <li>status</li>
    <li>tagline</li>
    <li>title</li>
    <li>vote_average</li>
    <li>vote_count</li>
</ul>

<p>Each row corresponds to a movie.</p>

#### credits.csv

<p>Includes details about the cast and crew of each movie:</p>
<ul>
    <li>cast</li>
    <li>crew</li>
</ul>

<p>Each row corresponds to a crew member (actor, director, writer, etc.) for a specific movie.</p>

### Dataset Name
<ul>
    <li><strong>tmdb-5000-movies</strong></li>
</ul>

### Language
<ul>
    <li><strong>English</strong></li>
</ul>

### Total Size
<ul>
    <li><strong>4,803 examples</strong></li>
</ul>

## Content-Based Filtering

<p>The content-based filtering method used in this project recommends movies based on their features and the similarities between them. Cosine similarity is employed to measure the similarity between movies based on their descriptions.</p>

## How to Use

<ol>
    <li>Clone the repository:
        <pre><code>git clone https://github.com/yourusername/movies-recommendation-system.git</code></pre>
    </li>
    <li>Navigate to the project directory:
        <pre><code>cd movies-recommendation-system</code></pre>
    </li>
    <li>Install the required dependencies:
        <pre><code>pip install -r requirements.txt</code></pre>
    </li>
    <li>Run the notebook to explore and build the recommender system:
        <pre><code>jupyter notebook Movie_Recommendation_System.ipynb</code></pre>
    </li>
</ol>

## Results

<p>The notebook demonstrates how to build and evaluate the three types of recommender systems mentioned above. The content-based filtering system, in particular, uses cosine similarity to recommend movies similar to the ones a user has already watched and liked.</p>

## Contributing

<p>Contributions are welcome! If you have any improvements or suggestions, please fork the repository and create a pull request.</p>

## License

<p>This project is licensed under the MIT License. See the <a href="LICENSE">LICENSE</a> file for details.</p>

## Acknowledgments

<ul>
    <li>The Movie Database (TMDb) for providing the dataset.</li>
    <li>The creators of the tmdb-5000-movies dataset.</li>
</ul>
