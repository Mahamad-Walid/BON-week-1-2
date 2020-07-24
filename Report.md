# Battle of Neighbourhoods final- Report
## 1 Introduction/Business Problem
#### Discussion of the business problem and the audience who would be interested in this project.
##### Something about the tourist place - sharm el sheikh,Egypt
    it is an Egyptian city on the southern tip of the Sinai Peninsula, in South Sinai Governorate, on the coastal strip along the Red Sea. Its population is approximately 73,000 as of 2015. Sharm El Sheikh is the administrative hub of Egypt's South Sinai Governorate, which includes the smaller coastal towns of Dahab and Nuweiba as well as the mountainous interior, St. Catherine and Mount Sinai. The city and holiday resort is a significant centre for tourism in Egypt, while also attracting many international conferences and diplomatic meetings.
#### Opening of Hotel/Restaurant Shop
    Coming down to business problem,I would like to open a hotel/restaurant near beach side.As it is a famous tourist spot,there is already lots of attention towards it.I know there will be many competitors in terms of hotel and restauramt.But keeping them in mind,i need to locate my hotel in place where more people are attracted and comfortable for a stay and a good meal.I want to bring foreign and local peoples attention towards my new hotel.I would like to flavour my retaurant recipe with Italian,American,typical Egyptian foods to grab their taste.
    
    The challenge is to find a suitable location for opening a new hotel / restaurant attracted to all local and foreign people in the centre of all famous venues.
#### Expected / Interested Audience
    Well, almost every business man who wnats to open a hotel in sharm el sheikh and needs a good place srounded by lots of nice place that local people and tourists are interseted in it like parks, cafes, dive shops and etc.
## 2 Data Section
#### 2.a What data is used?
    We will be completely working on Foursquare data to explore and try to locate our new hotel where more venues like church, beach, museums, memorials that are present nearby.
#### How will we be solving using this data?
        We will look for midpoint area of venues to locate our new hotel.Before that our major focus will be on all venues present in and around the core place of sharm el sheikh.
        
    Just a heads up on how many hotels are distributed now around sharm el sheikh.We will perform some EDA on hotels & restaurants present in the tourist spot.On furthur notebook we will use Foursquare data to determine other venues as well.
#### the first map that represent sharm el sheikh and the hotels around core point
    red point is for core of sharm el sheikh
    blue points are hotel postion
![Map of sharm el sheikh](https://user-images.githubusercontent.com/62917455/88362056-6fe26180-cd7b-11ea-931e-d66ab4816d4e.png)

## 3 Methodology Section
    In this sections we will perform some data analysis and EDA to find insight from data.We will try to understand the current stats of all given data.Probably,clustering or centroid of all venues will help us to locate new hotel.\
#### this graph represents hotels and how far are they from core location
![Hotels](https://user-images.githubusercontent.com/62917455/88362043-68bb5380-cd7b-11ea-8d1d-b7ae49342c33.png)
#### as we study that graph we deduce that:
     -Il Caminetto Restaurant is so far from core point
    -Pool at Aida Hotel is super close from the core point
    -764 metres is average distance from all hotels to core location.
#### this map shows postion of all venues around the core point:
    red point represents sharm el sheikh core location
    black points represent venues location
![Map of Venues](https://user-images.githubusercontent.com/62917455/88362505-0cf1ca00-cd7d-11ea-9f05-ac3ae057195b.png)
#### this graph represents how far are venues from the core location
![Venues graph](https://user-images.githubusercontent.com/62917455/88362052-6e189e00-cd7b-11ea-85d2-6a32df4ff0bd.png)
#### as we study that graph we deduce that:
    -Metro Market and Magic Dive Club are close from our location.
    -Albatros Aqua Park is so far away from our location
#### this graph represents Venue Categories
![Venues categories](https://user-images.githubusercontent.com/62917455/88362038-66f19000-cd7b-11ea-9dff-70a605e3d713.png)
#### as we study that graph we deduce that:
    -park, dive shop and Italian restaurant are the most famous category at sharm el sheikh
#### the next photo we extract the rated venues
![Ratings](https://user-images.githubusercontent.com/62917455/88362907-6efeff00-cd7e-11ea-812f-b52c4badf990.png)
#### from this photo we deduce that:
    -Iberotel Palace Sharm El Sheikh has the best rating in all the venues
    -Layali El Helmiya and Golden Spa Turkish Bath have the lowest rating in all the venues
#### after doing some clustering we got the map where we should open our new hotel
    red point is sharm el sheikh core location
    green point is the place we should open the hotel
    the other colored points are venues
![Clustered map](https://user-images.githubusercontent.com/62917455/88362047-6bb64400-cd7b-11ea-911b-ae9133e6ca24.png)

## 4 Results Section
#### Hotel location
     -Final location is pointed at 27.865067817116596,34.29524703125478

    -This location is at front of Pizza Melodies restaurant

    -Located at a one way road which can give more attention to people who pass by.
#### Top Rated Venues
    -Abo Ali
    -Iberotel Palace Sharm El Sheikh
    -Fresh Fish Center
    -Metro Market
    -Brazilian Coffee Stores
    
#### Spot my hotel against others
    here is the photo of the combined map where the map has everything:
![Combined map](https://user-images.githubusercontent.com/62917455/88362044-6a851700-cd7b-11ea-94ef-1d03d4e57294.png)

#### Few more Stats
    -Most common categories of venues are parks, diveshops, italians restaurants
    -Average distance between hotels is 764 metres
    -Pool at Aida Hotel, and Aida hotel will be more our opponents
## 5 Discussion Section
From above reports,we could get an idea why the predicted one is pointed/clustered on the given spot.First most thing could be the center of attraction for the place.

KMeans have figured out the most common place for all the venues.This output was very adjacent to the core location.This proves the accurate spotting of our predicted algorithm.

Despite of the findings,there were some lack in data.ratings were missing for most of the venues.Also when I compared foursquare data with google map ,i could see there were many hotels and venues found missing in foursquare sadly.
## 6 Conclusion Section
As a business person,one would be able to set up a hotel/restaurant on given spot.This will bring revenue automatically as we have located in very near to core one.We proved this with Kmeans

#### Future Expectation:
As mentioned earlier,most of data needs to be extracted from googlemaps.Even though we got somewhat accurate prediction.To be very confident on concluding our output,we may need more data to analyse.

Research based on hotel reviews and restaurant menus could be used for future purpose.
#### My Experience:
I can say it was not that bad. the first first three courses were kinda easy but that last course specifically the 3rd, 4th and 5th weeks made me super depressed although i had fun trying to slove every problem faced me.thanks for everything you have done 
# Thanks for putting time to read this!