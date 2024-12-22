## uRated : From the Base to the Best
Your Go-To Solution for the Next Michael Jackson

**Paper Trip's uRated Docs**: https://github.com/Paper-Trip/uRated-docs

A platform that tracks and analyses the social media growth of artists across multiple platforms (Spotify, YouTube, Instagram, etc.). The platform would allow users to see how an artist’s following, engagement, and other key metrics are evolving over time. The goal is to provide insights into which artists are gaining momentum, showing significant growth, and are therefore trending.
- **Artist Database**: You will have a collection of artist profiles, each containing their social media links and usernames.
- **Data Collection**: The back-end system will periodically collect data from various social media platforms (such as followers, listeners, views, etc.) to track the artist’s performance. The data will be stored in a database for easy retrieval.
- **Growth Tracking**: The platform will compute and track the growth or decline of each artist’s numbers, highlighting those who are experiencing the highest growth.
- **Trending Artists**: Based on the calculated growth metrics, the platform will show trending artists – those who are growing at the fastest rate, allowing users to discover new artists before they become mainstream.
- **Search and Filtering**: Users can set parameters (like a minimum follower count of 100k) to view artists who meet specific thresholds of popularity and growth.
The focus is on presenting data-driven insights into artist trends, and not just static follower counts, but more dynamic and real-time metrics to showcase the artists that are truly on the rise.
#### **Developer Notes:**
We start by [[Building the Backend]]. [[Data Server]] and [[Auth-server]] modules will be separated from the start to avoid future complexity.