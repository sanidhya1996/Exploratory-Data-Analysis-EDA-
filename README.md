# Exploratory-Data-Analysis-EDA-

# Play Store App Review Analysis 🎮📊

[![Python Version](https://img.shields.io/badge/python-3.7%2B-blue.svg)](https://python.org)
[![Pandas](https://img.shields.io/badge/Library-Pandas-green)](https://pandas.pydata.org/)
[![Matplotlib](https://img.shields.io/badge/Library-Matplotlib-brightgreen)](https://matplotlib.org/)
[![Seaborn](https://img.shields.io/badge/Library-Seaborn-orange)](https://seaborn.pydata.org/)
[![License](https://img.shields.io/badge/License-MIT-red.svg)](https://opensource.org/licenses/MIT)

---

## 📄 Project Overview
The Play Store App Review Analysis project explores what factors contribute to successful apps on Google Play Store. By analyzing the dataset, we identified trends related to app categories, user ratings, pricing, content ratings, genres, and user sentiment. This project provides actionable insights for app developers and marketers to optimize their app strategies, attract users, and increase engagement.

---

## 🎯 Objectives
- Understand distribution across app categories.
- Analyze the impact of **free vs paid apps**.
- Explore **content ratings** and their implications.
- Analyze user **sentiment** and **reviews**.
- Determine Android version compatibility and its influence on installs.
- Identify trends in app performance (e.g., highest installs, ratings).

---

## 📂 Dataset Details
### Primary Datasets Used:
1. **Play Store Data**:
   - Contains metadata like app name, category, installs, ratings, type, etc.
2. **User Reviews Data**:
   - Focuses on user sentiments: positive, negative, and neutral.

#### Key Features:
- `App`: Name of the app.
- `Category`: The category to which the app belongs (e.g., Game, Health, etc.).
- `Rating`: Average rating on the Play Store.
- `Installs`: Number of installs/downloads.
- `Price`: Price of the app (if paid).
- `Type`: Free or Paid app type.
- `Sentiment`: User review sentiment - Positive, Negative, Neutral.
- `Android Ver`: Minimum Android version required for compatibility.

---

## 🛠️ Tech Stack
- **Programming Language**: Python
- **Tools & Libraries**:
  - Data Manipulation: `Pandas`, `NumPy`
  - Data Visualization: `Matplotlib`, `Seaborn`
  - Additional Analysis: `TextBlob` (for Sentiment Analysis)

---

## 🖼️ Key Visualizations
These visualizations helped interpret the data efficiently:  
1. **Number of Apps per Category**: Count of apps across categories like "Games", "Family", and "Sports".
2. **Free vs Paid Apps**: A pie chart indicating the overwhelming dominance of free apps (98.7%).
3. **Content Rating Distribution**: Bar chart showing how platforms target broad audience groups (`Everyone`, `Teen`, etc.).
4. **Top Categories by App Installs**: Bar chart to visualize which categories garner the highest installs (`Communication`, `Social` genres).
5. **User Sentiment Analysis**: Pie chart showcasing the split of reviews into Positive, Neutral, and Negative sentiments.
6. **Android Version vs Installs**: Bar chart identifying which Android versions are most popular among users.
7. **Correlation Heatmap**: Visualizing relationships between features like installs, reviews, and app price.

---

## 🔍 Key Insights
### Categories & Genres:
- **Top Categories**: The `Game` category has the highest number of apps, followed by `Family` and `Sports`.
- Apps in the `Communication` and `Social` categories receive the **highest installs**, indicating heavy usage.

### Pricing:
- **98.7% apps are free**, emphasizing that free apps dominate the Play Store.
- Paid apps struggle in terms of downloads compared to free ones.

### Content Rating:
- Most apps are rated for `Everyone`, ensuring a broad appeal among users.
- Categories like `Teen` and `Everyone10+` are also common.

### App Reviews & Sentiments:
- **Positive reviews** account for 63.6% of all reviews.
- Categories like `Games` and `Auto & Vehicles` received higher-than-average ratings, alongside consistent user satisfaction.

### Android Compatibility:
- Apps marked as `Varies with device` have the highest installs, suggesting compatibility plays a key role.
- Supporting newer Android versions significantly increases app reach.

---

## 🚀 How to Use This Project

### Install Dependencies
Ensure you have Python and the necessary libraries installed on your system. Use the following command:
```bash
pip install pandas numpy matplotlib seaborn


📊 Recommendations for Clients
Focus on Popular Categories: Focus on apps in lucrative genres like Games, Communication, and Social.
Offer Free Apps: Given the dominance of free apps, offer freemium models to attract users and build engagement.
Broad Compatibility: Develop apps compatible with a wide range of Android versions to maximize reach.
Leverage Positive Sentiments: Respond to reviews and maintain high satisfaction levels to sustain good ratings.
Optimize Price Strategy: Consider pricing based on user demand (lower prices might help paid apps attract users).
🔮 Future Improvements
Predictive Analysis: Build a model to predict app success based on its features.
Advanced Sentiment Analysis: Apply NLP to deep dive into user feedback.
Demographics Insights: Incorporate geography or user demographics for targeted recommendations.
🙌 Acknowledgments
This analysis utilized publicly available datasets, and special thanks to the Google Play Store for providing the data. Libraries like Pandas, Matplotlib, and Seaborn powered the analysis effortlessly.

📜 License
This project is licensed under the MIT License.

## 📧 Contact
For questions, suggestions, or collaboration, feel free to reach out:
- **Name**: Sanidhya Shekhar  
- **Email**: [sanidhyashekhar1996@gmail.com](mailto:sanidhyashekhar1996@gmail.com)

---

## 📂 GitHub Repository
Access the full project and codebase on GitHub:  
🔗 [Play Store App Review Analysis](github.com/sanidhya1996/Exploratory-Data-Analysis-EDA-/)
