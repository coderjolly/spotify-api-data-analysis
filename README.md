# spotify-api-data-analysis

About a decade ago, the term "data engineering" emerged in forward-thinking companies like Facebook, Netflix, LinkedIn, and Airbnb, driven by their need to manage vast amounts of real-time data efficiently. To cope, engineers at these firms crafted custom tools and platforms for handling data swiftly, reliably, and at scale, moving away from traditional ETL tools.

So, Apache Airflow was used to create an ETL pipeline from the Spotify API, focusing primarily on user activity analysis. The approach involved extracting data from Spotify accounts via the Spotipy API, storing it in SQL Server Management Studio using the Snowflake Schema method. Next, we connected this database to PowerBI to build analytical dashboards. Finally, we managed scheduling using Apache Airflow, crafting a comprehensive on-premise solution.

