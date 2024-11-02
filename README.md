# TDS Project

# How I scraped the data:    
Queried the GitHub API to identify users in Seattle with more than 200 followers.
Saved the profile links of qualifying users in users.txt, with one link per line.

Created users.csv:

For each user in users.txt, fetched detailed profile data.
Cleaned and standardized fields (e.g., formatted company names).
Saved the data to users.csv with columns: login, name, company, location, email, hireable, bio, public_repos, followers, following, and created_at.
Generated repositories.csv:

For each user in users.csv, fetched up to 500 of their most recently pushed repositories.
Stored repository details (e.g., full_name, created_at, stargazers_count, language, license_name) in repositories.csv.
      

# The most interesting facts and surprising facts I found after analyzing the data:
I observed an intriguing trend between a user's follower count and their number of public repositories. Generally, users with more followers tend to have a higher number of public repositories, though this relationship is not particularly strong.
This suggests that while visibility or popularity may correlate with repository output, other factors likely play significant roles in influencing public contributions

# An actionable recommendation for developers based on my analysis:
Based on my analysis, actionable recommendations are as follows:    
Successful developers average 114.3 public repositories, compared to 85.8 for others. Increasing the number of public repositories may help in gaining more visibility and success.
Maintain more public repositories: Successful developers average 114.3 public repositories, compared to 85.8 for others. Increasing the number of public repositories may help in gaining more visibility and success.

Focus on high-impact languages: Top languages among successful developers are JavaScript, Python, Ruby, Go, and TypeScript. Concentrating efforts on these languages could increase the likelihood of success.

![image](https://github.com/user-attachments/assets/d499dff6-31e5-4d6d-ab79-a0294081ca5c)

