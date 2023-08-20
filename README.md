# Movie-Recommendation-Sysrem
## Introduction

The Movie Recommendation System is a personalized recommendation engine designed to assist users in discovering movies that align with their preferences. This system utilizes collaborative filtering techniques and user behavior analysis to suggest movies that users are likely to enjoy based on their similarities in movies.

## Technology Used
```
    Python(3.10.5)
    Streamlit version(1.17.0)
    Use of TMDB movie dataset ( to fetch the information of movies )
    Use of TMDB credit dataset ( to fetch the information of crew of movies ) 

```

## How It Works ?
The recommendation system employs two main approaches: Collaborative Filtering and Content-Based Filtering.

### **Collaborative Filtering**
Collaborative Filtering is based on the idea that users who agreed in the past will agree again in the future. It identifies patterns by analyzing the historical preferences and behaviors of users. This approach can be further categorized into:

- ***User-Based Collaborative Filtering :***  It identifies users who have similar movie preferences to the target user and suggests movies that those similar users have liked.

- ***Item-Based Collaborative Filtering :***  It focuses on the similarities between movies themselves. If two movies have been enjoyed by the same users, they are likely to be related and can be recommended to each other.

### **Content-Based Filtering**
Content-Based Filtering suggests movies based on their features and attributes, such as genre, actors, directors, and keywords. This approach targets the inherent characteristics of the movies themselves, rather than relying solely on user behavior.

## Benefits

- ***Personalization :*** Users receive tailored movie recommendations based on their individual preferences.

- ***Discovery :*** Users can discover new movies that align with their tastes, leading to a more engaging experience.

- ***Increased Engagement :*** By providing relevant suggestions, the system encourages users to spend more time on the platform.






