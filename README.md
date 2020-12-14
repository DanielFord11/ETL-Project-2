# ETL-Project-2

This is a planning tool for the manual video content curators at my work. (I work at a cable company) It allows users to search our inventory by genre, targeted age range, and rotten tomatoes score. 

Then, using the returned results set it collects the OMDB popularity score and Twitter buzz (how many hashtags mention the movie in the past 24hrs and what the combine follower count of the people making those posts)

Right now it stores the results in a spreadsheet which is more accommodating to the users. However, it could also store them longterm in a db

Lastly, it juxtaposes metrics to actual internal consumption data to give a visual sense of which metrics are more predictive of internal video content performance
