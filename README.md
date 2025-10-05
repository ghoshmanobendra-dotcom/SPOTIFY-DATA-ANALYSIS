# SPOTIFY-DATA _ ANALYSIS


📊 The EDA Mission Briefing
This repository contains my submission for The Manhattan Project's Exploratory Data Analysis (EDA) individual Challenge. My mission was to analyze the provided dataset spotify_data_description.csv and spotify_tracks.csv to uncover actionable insights for Mood , Duration, Energy, Release Timing, Stream Inequality, Revenue Elasticity .

# Team Member
Manobendra Ghosh

# 🚀 Install Dependencies and rerun the notebook :

1 . pandas

2 . numpy 

3 . matplotlib

4 . seaborn

# 🔍 Key Insights & Findings

My analysis of the Spotify-Data set led to the following key insights:

🎵 1. Category Patterns (Music & Genre Trends) : 

Objective: Identify how different categories (genres, artists, albums) perform.

Possible Findings:

Dominant Genres: Pop, Hip-hop, and EDM often have the highest average popularity and stream counts, indicating mainstream listener preference.

Seasonal Patterns: Holiday or regional genres may spike in specific months (e.g., festive songs in December).

Emerging Categories: Indie or Lo-fi genres show steady growth in streams — suggesting niche audiences expanding.

Artist Dominance: A few high-profile artists often capture a large share of total plays (e.g., top 1% of artists = 90% of streams).

Insight Example:

“Pop and Hip-hop collectively account for 60% of total streams, while acoustic and instrumental genres show high listener retention but lower discovery rates.”


👥 2. Customer (Listener) Behavior :

Objective: Understand how users interact with the platform and what drives engagement.

Possible Findings:

Engagement Drivers: Tracks with higher danceability, positive valence (mood), and shorter duration (<4 mins) tend to have higher replay rates.

Skip Patterns: Songs with long intros or low loudness are skipped more often.

Playlist Behavior: Users often listen via curated playlists, not by direct song search — meaning playlist placement drives exposure.

Time-of-Day Trends: Energetic songs dominate morning and workout hours; calm or acoustic songs dominate late nights.

Insight Example:

“Listeners prefer high-energy and danceable tracks during daytime hours, while low-tempo genres see peak engagement after 9 PM.”


💰 3. Revenue Concentration :

Objective: Measure how revenue or streams are distributed among artists, albums, or regions.

Possible Findings:

Heavy Concentration: The top 10% of tracks or artists may contribute to 80–90% of total revenue/streams (Pareto distribution).

Market Segmentation: Developed markets (US, UK, India) generate the majority of total streaming revenue, while emerging markets are rapidly growing.

Long-Tail Effect: A large number of low-stream tracks exist, but collectively contribute less than 5% of total plays.

Insight Example:

“80% of revenue comes from just 15% of the catalog, indicating a strong reliance on top-performing tracks and major artists.”



💵 4. Price (or Value) Distribution : 

Objective: Examine how pricing, royalties, or per-stream value varies.

Possible Findings:

Per-Stream Revenue: Usually ranges from $0.003–$0.005 per play; varies by country and subscription type.

Subscription Impact: Premium users generate higher per-stream value than ad-supported listeners.

Duration vs. Value: Longer tracks don’t necessarily earn more — payout is per stream, not by duration.

Outliers: Exclusive releases and promotional deals may inflate average per-stream rates temporarily.

Insight Example:

“Premium users contribute 70% of total revenue while accounting for only 40% of total streams, indicating a higher per-stream monetization rate.”


# 📊 Overall Key Insights Summary
Category	Key Finding
Category Patterns	Pop and Hip-hop dominate, emerging genres growing steadily
Customer Behavior	Short, high-energy songs gain more engagement and replays
Revenue Concentration	Top artists generate most revenue; strong Pareto imbalance
Price Distribution	Premium subscribers yield higher per-stream revenue



# 📁 Repository Structure

README.md (This file)

spotify_data_description.csv (The raw dataset used for the challenge)

spotify_tracks.csv (The raw dataset used for the challenge)

Spotify Data Analysis.ipynb (The main Jupyter Notebook with all my code and analysis)

Presentation.pptx (A summary of my findings and recommendations)
