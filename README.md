# Global_Music_Streaming_Preferences_Project

## 1. Introduction
The purpose of this analysis was to explore global music streaming preferences and behaviors across countries, age groups, and platforms. Using the dataset provided, we examined listening patterns, platform choices, subscription types, and user engagement to identify key trends and actionable insights. The ultimate goal was to generate recommendations for companies like Spotify or Amazon Music to increase their audience base.

## 2. Key Findings

### 2.1 Genre Popularity by Country
Varied Preferences Across Countries:
-   USA and UK leaned toward Reggae and EDM, while Germany strongly preferred EDM.
-   Brazil and South Korea favored Rock, India favored Reggae, Japan favored Jazz, and Australia favored Pop.
-   Least popular genres varied, with Pop surprisingly low in several countries despite global chart success.
Statistical Results: Chi-square tests showed no significant relationship between country and genre popularity, suggesting preferences may be due to chance rather than strong cultural patterns.

Visualization: Genre Popularity by Country
![Genre Popularity](https://github.com/erlopez-data-analyst/Global_Music_Streaming_Preferences_Project/blob/57686158155f24f1d4108669f9daa149b433a156/Top%20Genre%20by%20Countries%20(Frequency).png))

### 2.2 Streaming Platform Preferences
Platform by Country
- Amazon Music was the most popular overall.
- Preferences varied — YouTube was top in Canada, Apple Music in Japan, and Tidal in Australia & France.
Platform by Age Group
- Under 18 preferred Tidal.
- 18–25 and 36–50 leaned toward Amazon.
- 26–35 leaned toward Deezer.
- 50+ also favored Tidal.
Statistical Results: Chi-square tests showed no significant relationship between platform and country/age, suggesting patterns may be influenced by availability or marketing rather than demographics.

Visualization: Popular Streaming Platform Preference
![Streaming Platform](https://github.com/erlopez-data-analyst/Global_Music_Streaming_Preferences_Project/blob/57686158155f24f1d4108669f9daa149b433a156/Popular%20Streaming%20Platform%20by%20Country.png)

### 2.3 Listening Time Patterns
Overall: Nighttime was the most popular listening period, followed closely by afternoon, with mornings least preferred.

By Country
- UK, USA, Brazil, France → Night listening.
- Japan & South Korea → Morning listening.
- India & Australia → Afternoon listening.
Statistical Results: No significant differences across groups, though country-level patterns were visible.

Visualization: Listening Time Patterns by Country
![Listening Time Patterns](https://github.com/erlopez-data-analyst/Global_Music_Streaming_Preferences_Project/blob/57686158155f24f1d4108669f9daa149b433a156/Listening%20Time%20Preference%20by%20Country.png)

### 2.4 Engagement by Subscription
- Free vs Premium: Engagement patterns (minutes streamed, repeat rate, discover weekly use) were not significantly different.
- Insight: Users appear to engage heavily regardless of subscription type, though free users tolerate ads.

Visualization: Subscription Type Preference by Country
![Subscription Type Preference](https://github.com/erlopez-data-analyst/Global_Music_Streaming_Preferences_Project/blob/4e7f833d0f4fe9635e17c8b46a0cca77e78a27ba/Subscription%20Type%20Preference%20by%20Country.png)

Visualization: Subscription Type vs Engagment (Box & Whiskers Graph)

![Subscription Type vs Engagement](https://github.com/erlopez-data-analyst/Global_Music_Streaming_Preferences_Project/blob/4e7f833d0f4fe9635e17c8b46a0cca77e78a27ba/Sub%20vs.%20Engagement.png)

Visualization: Subscription Type vs Min Streamed (Box & Whiskers Graph)

![Subscription Type vs Min Streamed](https://github.com/erlopez-data-analyst/Global_Music_Streaming_Preferences_Project/blob/4e7f833d0f4fe9635e17c8b46a0cca77e78a27ba/Sub%20vs.%20Mins%20Streamed.png)

Visualization: Subscription Type Preference vs Song Repeat Rate (Box & Whiskers Graph)

![Subscription Type vs Repeat Rate](https://github.com/erlopez-data-analyst/Global_Music_Streaming_Preferences_Project/blob/4e7f833d0f4fe9635e17c8b46a0cca77e78a27ba/Sub%20vs.%20Repeat%20Song%20Rate.png)

### 2.5 Artist Popularity
Top Global Artists: Bad Bunny, Adele, Post Malone, Dua Lipa, and Ed Sheeran.

By Country
- Australia → Post Malone, Brazil → Dua Lipa, India → Drake, France → BTS, Japan → Billie Eilish, USA/UK/Canada → Bad Bunny.
Insight: Artist preferences are highly individualized, showing less consistent cultural influence compared to genre or platform.

Visualization: Word Cloud Global Popular Artist
![Subscription Type Preference #1]([Gloabl Artist Popularity (Word Cloud).png](https://github.com/erlopez-data-analyst/Global_Music_Streaming_Preferences_Project/blob/4e7f833d0f4fe9635e17c8b46a0cca77e78a27ba/Gloabl%20Artist%20Popularity%20(Word%20Cloud).png))

Visualization: Bar Chart Global Popular Artist
![Subscription Type Preference #2](https://github.com/erlopez-data-analyst/Global_Music_Streaming_Preferences_Project/blob/4e7f833d0f4fe9635e17c8b46a0cca77e78a27ba/Global%20Artist%20Popularity%20(Bar%20Chart).png)

Visualization: Treemap Popular Artist by Country
![Subscription Type Preference #3](https://github.com/erlopez-data-analyst/Global_Music_Streaming_Preferences_Project/blob/4e7f833d0f4fe9635e17c8b46a0cca77e78a27ba/Top%20Artist%20by%20Country.png)

### 2.6 Correlation Between Behaviors
Low Correlation
- Minutes streamed, number of songs liked, and repeat rate were largely independent of each other.
- Regression analysis showed weak predictive power (low R² values).
Insight: Listening behavior is driven by multiple factors not captured in the dataset (e.g., mood, context, social influences).

### 2.7 User Segmentation (Clustering)
K-means clustering identified 3 distinct listener groups:
- Cluster 0 – Engaged/Heavy Listeners: High minutes streamed, high engagement.
- Cluster 1 – Casual Listeners: Low minutes streamed, low engagement.
- Cluster 2 – Repeat-Oriented Listeners: Moderate streaming but high repeat rate.
PCA visualization showed some overlap, but meaningful distinctions were still visible.

![Subscription Type Preference #3](https://github.com/erlopez-data-analyst/Global_Music_Streaming_Preferences_Project/blob/4e7f833d0f4fe9635e17c8b46a0cca77e78a27ba/User%20Segmentation%20by%20Streaming%20Behavior.png)

## Recommendations
Based on the findings, here are three strategic recommendations for streaming companies like Spotify or Amazon Music:
1. Localize Genre Promotions
- Since genre preferences vary by country (e.g., Rock in Brazil, Reggae in India, EDM in Germany), platforms should highlight localized playlists and campaigns tailored to each country’s dominant genres.
2. Targeted Platform & Age Group Strategies
- Different age groups gravitate toward different platforms (Tidal for younger and older groups, Amazon for middle groups). Platforms should design targeted ads, partnerships, and incentives for each demographic to strengthen user acquisition.
3. Enhance Engagement Through Personalization
- Since subscription type doesn’t strongly influence engagement, focus should shift toward personalized discovery features (AI-driven playlists, daily mixes, mood-based suggestions) to increase time spent on-platform and differentiate from competitors.

## Conclusion
This analysis reveals that while global streaming behaviors share common traits (such as preference for night listening and high engagement regardless of subscription), country-level differences in genre and platform preferences offer valuable opportunities for localized strategies. By leveraging these insights, companies can better target new users, personalize experiences, and strengthen engagement, ultimately growing their audience base in an increasingly competitive streaming market.
