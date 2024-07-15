# News Management System

## Introduction

In the age of information, staying updated with the latest news is crucial for individuals to remain informed about events that impact their lives. The News Management System project aims to address this need by providing a comprehensive platform where users can access, rate, and interact with news articles across various categories.

This project encompasses both administrative and user functionalities, ensuring a seamless experience for all stakeholders involved. Administrators are empowered with tools to manage news content effectively, while users enjoy features tailored to their preferences and needs.

## Core Objectives

1. **User Authentication:** Secure login mechanisms to authenticate users and provide access to the system's functionalities. Through a robust login system, users can ensure the privacy and integrity of their accounts.
2. **Content Management:** Administrators can post, remove, and update news articles, ensuring the platform maintains a relevant and up-to-date repository of information. The system supports categorization of news articles, facilitating easy navigation and filtering.
3. **User Interaction:** Users can engage with news content by rating articles based on their relevance and quality. This rating system helps users identify noteworthy articles and contributes to generating trending news topics.
4. **Search Functionality:** A powerful search feature allows users to discover news articles based on keywords, titles, or dates, enhancing accessibility and user experience.
5. **Personalization:** Users can customize their news feed by selecting preferred categories, ensuring they receive relevant content tailored to their interests and preferences.
6. **Bookmarking:** Users can bookmark favorite news articles for later reference, providing a convenient way to revisit articles of interest at their convenience.
7. **Trending News Section:** The system dynamically generates a trending news section based on user ratings, highlighting popular topics and articles gaining traction within the community.

## Data Structures Used

- **Unordered Map:** Utilized to store news articles with the date as the key and a vector of news articles as the value. This structure provides fast access to news articles for a specific date.
- **Vector:** Employed to store users and trending news. Vectors are efficient for dynamic storage of elements and provide constant time complexity for accessing elements by index.
- **List:** Used to store categories, offering flexibility in managing and updating categories.
- **Unordered Map for Comments:** Allows easy management and retrieval of comments associated with specific news articles.
