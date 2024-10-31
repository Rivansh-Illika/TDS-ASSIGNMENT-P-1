# GitHub Seattle Users and Repositories

- This project uses the GitHub API to gather information on users in Seattle with more than 200 followers, as well as details of their repositories.
- An interesting finding was that Seattle-based developers with high follower counts frequently use languages like JavaScript and Python.
- Recommendation: Developers could grow their GitHub visibility by contributing to popular repositories in trending languages like JavaScript and Python.

## Project Overview

This project collects data on GitHub users in Seattle with over 200 followers, along with their repository information. Using the GitHub API, we gathered data on:

1. **User Profiles**: Including GitHub usernames, company affiliations, bio, and follower statistics.
2. **Repositories**: Information such as repository names, creation dates, star counts, primary language, and license type.

## Files

- **users.csv**: Contains data on GitHub users in Seattle with over 200 followers.
- **repositories.csv**: Contains repository data for these users, including up to 500 of their most recently pushed public repositories.

## How to Run the Code

1. Clone this repository.
2. Obtain a GitHub personal access token (PAT) and set it in your environment as `GITHUB_TOKEN`.
3. Run the `data_collection.py` script in Google Colab or locally to generate `users.csv` and `repositories.csv`.
4. Update the findings and recommendations in `README.md` as needed after further analysis.

## Insights and Recommendations

- **Data Insight**: Many highly-followed GitHub users in Seattle work at large tech firms or startups, and focus on web and software development.
- **Developer Tip**: To increase visibility, developers could engage with popular repositories and trending languages, as these often attract more followers.

## Future Work

Future analysis could include repository activity trends, collaborations, and contribution patterns to gain deeper insights into Seattle's GitHub community.