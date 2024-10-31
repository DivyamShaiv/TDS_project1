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
What I found interesting was the correlation between the number of followers of a user and number of repository. Number of public repositories are likely to be more with the more amount of followers. Although the relationship is not vert strong. 


# An actionable recommendation for developers based on my analysis:
    


