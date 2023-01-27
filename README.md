# The Business Problem 
Microsoft is creating a new movie production company and wants to know the types of movies that are the most profitable.

# The Data Sets I Used
I used data sets from the IMDB database and budget data from "the numbers."


# My Results

The main metric that I focused on was return on investment (ROI). I focused on this metric because I think measuring the amount of money a movie returns against its budget is the safest metric for quantifying the success of a new production company.

With this in mind I first looked at the mean ROI for each genre in the bar chart below.

<img width="1014" alt="Screenshot 2023-01-27 at 8 38 29 AM" src="https://user-images.githubusercontent.com/115309980/215194226-649283fb-c04e-4107-bfaf-79f25d2e1423.png">

Horror movies had the highest mean ROI. In order to get a better understanding of this measure, I decided to look at a histogram of the horror movie ROIs (See below).

<img width="687" alt="Screenshot 2023-01-27 at 3 50 37 PM" src="https://user-images.githubusercontent.com/115309980/215194709-a70e4007-7ef2-4f49-9c76-f04d3a89002f.png">

As you can see, horror movie ROIs are skewed to the right with a few "cult classics" making up a large number of outliers. These outliers have large returns on investments and the idea of trying to create a "cult classic" interested me because of how profitable they could be. Due to the fact that horror movie data was skewed to the right, I decided to make another bar chart looking at median ROI instead of mean ROI (see graph below).

<img width="1010" alt="Screenshot 2023-01-27 at 3 50 45 PM" src="https://user-images.githubusercontent.com/115309980/215195229-e0dff91a-fe87-423f-a7c0-7fd0eaa99030.png">

Looking at the graph above, I noticed that animation, sci-fi and action/adventure movies have the highest median returns on investment. 

I was still interested in exploring this idea of a "cult classic" film because I think they are profitable. For the purposes of this project I decided to define a "cult classic" movie as any movie with a low budget and a high ROI. I defined "low budget" as a movie budget below 25% of movie budgets, which ended up being around $7.08 million. In addition, I defined high ROI as any ROI above 75% of movie ROIs, which ended up being around 279.13%.

I first wanted to see which genre was most likely to produce one of these "cult classic" movie.

<img width="817" alt="Screenshot 2023-01-27 at 3 53 06 PM" src="https://user-images.githubusercontent.com/115309980/215194961-bd7aecc7-fae4-455c-8f56-8f31cbcba8de.png">

Looking at the graph above we can see that horror movies was the genre most likely to produce a "cult classic" film when compared to high ROI genres.

Not only did I find that horror movies had the highest liklihood of becoming a "cult classic" film, but looking at the data below, we can also see that horror movies are the cheapest films to create, meaning that they are low risk.

<img width="1020" alt="Screenshot 2023-01-27 at 3 50 58 PM" src="https://user-images.githubusercontent.com/115309980/215195061-f57f0497-6379-4ef9-89d2-0214483267ac.png">

In order to explore how to further improve ROI for the horror movie genre, I looked at movie release times. I split movie release times into four quarters: Q1, Q2, Q3 and Q4. Q1 represented January, February, and March. Q2 represented the months of April, May and June. Q3 represented July, August and September. Q4 represented the months of October, November and December.

<img width="1024" alt="Screenshot 2023-01-27 at 3 51 17 PM" src="https://user-images.githubusercontent.com/115309980/215195167-80e9d6c2-75c0-452b-b79e-8c22abd3333b.png">

Above we can see that Q4 was the most popular mouth for all movie releases and horror movie releases. Q1 and Q2 were less popular times to release a movie.

<img width="1010" alt="Screenshot 2023-01-27 at 3 51 28 PM" src="https://user-images.githubusercontent.com/115309980/215195192-7edfc29f-4290-49dc-a9c0-1a24240c1a65.png">

Looking at the graph above, we can see that Q1 was the best quarter to release a horror movie.


# My Recommendations
Based on my results I can three clear recommendations:

1. Create "cult classic" films, which are films with a small budget and high ROI

2. Release these "cult classic" films during Q1 (January, February and March)

3. Choose directors that have experience directly horror movies and a track record of produces high ROI movies on a small budget. The two directors that I would like to recommend are Gary Dauberman and David Gordan Green. 



# My Next Steps
In my next step I would look at data to find out more on the following:

1. The size (number of theatres) of our horror movie release

2. The ideal amount of time horror movies stay in theatres to maximize profits

3. If the gender identity of the lead actor impacts profits

4. If personifying evil through a monster or villain makes a horror movie more money or easier to franchise?

5. If the intersection of the horror genre and the mystery genre improves profits

6. Horror movies profits in international markets

7. If microsoft should bring back the 3D horror movie
