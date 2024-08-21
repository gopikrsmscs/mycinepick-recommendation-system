# mycinepick-recommendation-system
## Overview
MyCinePick is a personalized movie recommendation system built using collaborative filtering techniques and hosted on Streamlit. The app provides tailored movie suggestions based on user input, making it easy to discover new movies aligned with individual preferences. By selecting a user from the dropdown menu, the system generates the top-k movie recommendations, leveraging user-user similarity.

## Features
- **User-Specific Recommendations**: Provides personalized movie recommendations by analyzing user ratings and identifying similar users.
- **Interactive Web App**: Hosted on Streamlit, allowing users to interact with the system through a user-friendly interface.
- **Collaborative Filtering**: Utilizes user-user collaborative filtering to generate recommendations.
- **Dropdown Selection**: Users can select their name from a dropdown menu to receive customized movie recommendations.
- **Customizable Recommendations**: Users can specify the number of recommendations (k) they wish to receive.
## Running the App

```bash
    streamlit run app.py
```

## Dataset

- Movie_data.csv: Contains user ratings for movies, with columns for User_ID, Movie_ID, Rating, and Timestamp.
- Movie_Id_Titles.csv: Maps Movie_IDs to their respective Movie_Titles.

## Contributing

Contributions are welcome! If you have any ideas for improving the recommendation system or adding new features, feel free to submit a pull request.