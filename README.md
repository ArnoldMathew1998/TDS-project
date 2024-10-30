# GitHub Users in Barcelona

- Data was scraped using the GitHub API, targeting users in Barcelona with over 100 followers, and included profile and repository details.
- A surprising insight was that users who made their emails public were much more likely to be hireable.
- Developers looking to attract attention might consider keeping their profiles active and public, as bio length and repository count correlated with higher follower counts.

## Project Overview
This project collects and analyzes data for GitHub users in Barcelona with over 100 followers. The data includes user profiles and repositories, structured in CSV files for further analysis.

## Data Collection Process
We used GitHub’s API to extract user data from Barcelona with more than 100 followers. For each user, we captured profile information, then gathered repository data, limiting each user to their 500 most recent public repositories. 

### Files Included
- `users.csv`: Basic information about each user, including bio, location, follower count, and hireability.
- `repositories.csv`: Public repository data for users, including repository name, language, stars, and other features.
- `README.md`: Project description and insights.
- `TSD-project1.ipynb`: Jupyter notebook containing all code used for data scraping, cleaning, and analysis.
  
## Analysis Results
After processing the data, we observed patterns in user behavior and popularity, examining follower counts, hireability status, and the impact of profile visibility features like public email sharing and active repositories. The findings provide actionable insights for developers aiming to increase their GitHub visibility.
