🎬 Sophia Duran’s Letterboxd Lens

A Data-Driven Dive into 6+ Years of Film Watching Behavior

This project transforms my personal Letterboxd watch history into an interactive, insightful dashboard—combining cinematic storytelling with the power of data science. From favorite directors and genre deep-dives to global film origins and evolving taste patterns, it's a visual journey through the movies that shaped me.

📁 Contents

notebook.ipynb – Core Google Colab notebook containing all data processing, enrichment, and visualizations.

letterboxd-sophia_duran-*.zip – Exported data from Letterboxd (diary, watched, ratings, etc.).

watched_enriched.csv – TMDb-enriched dataset with genre, runtime, director, and origin country metadata.

README.md – Project overview and setup guide.

🧠 Key Features

📅 Monthly Watch Activity

See when I watch the most films, with bar and line charts breaking it down by month over the years.

🎭 Top Genres Watched

Which genres do I gravitate toward most? A horizontal bar chart shows the top 10, powered by TMDb metadata.

🎬 Most Watched Directors

Explore which filmmakers dominate my watched list, whether intentionally or subconsciously.

🌟 Highest Rated Genres & Directors

See which categories consistently earn high ratings from me—with filters to ensure statistical significance.

🌍 World Map of Film Origins

An interactive choropleth shows which countries my favorite stories come from.

📈 Ratings Over Time

Visualize how my ratings shift across months and years, including both scatter and line plots.

💎 Unique Stats

One-off highlights and deep cuts, like standout director debuts or hidden gems that earned high praise.

🛠️ Tech Stack

Google Colab for coding and visualization

Python (pandas, matplotlib, seaborn) for data wrangling and plotting

DuckDB for in-notebook SQL querying

TMDb API for metadata enrichment (genres, directors, runtime, etc.)

GeoPandas for country-level map visualization

📬 Credits & Contact
Made by Sophia Duran
Data from Letterboxd & TMDb

🔗 Portfolio | LinkedIn | GitHub

