# DOCUMENTING ICE

## Methodology/Code:
Copy of cc5412_Final Project_Documenting ICE.ipynb
* Project was worked in Google Colab. Final ipynb file was dropped into GitHub, which may affect things.

## Data Sources:
Publicly available Bluesky posts.
US Census Bureau, ACS 2023
      Unfortunately due to connection issues, I was unable to integrate this data into the final deliverable. The code is present at the end of the Python
notebook.

## Appendix: Methodology Pitfalls

Encountered several issues in the process of attempting to gather video from social media. Most platforms block scraping or limit the use of their API to paid users or approved researchers. Reddit denied my research request to use their API and scraping was blocked.

Bluesky seemed friendlier to these efforts, which is why it is utilized in the final deliverable.

Issues arose with attempting to collect video files and links directly to the videos.

Thank you to Tim Small for pointing me in the right direction. Based on his code I then made the decision to collect URLs of posts that have video embedded.

Issues kept arising and I kept getting no results, so I continued to debug the code. In the end, the proof of concept shows it’s possible to roughly visualize where and how ICE is operating.

* For the future, it would be great if the project could actually archive the posts somewhere and if the map on github could run the code daily in order to update itself.
