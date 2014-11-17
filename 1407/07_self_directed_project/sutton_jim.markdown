### Self Directed Project 

 **SELECTED** 

### Pitch

Denver's population has grown 17% since 2000. With a housing market this tight (96% occupancy rates), finding a house or an apartment means having to act quickly, which is hard to do without being able to make quick analyses and comparisons of different options. 

### Description

It's easy to compare two apartments when you have been given the information: rent, square footage, etc. My app is designed be a single repository for all the other information that a prospective relocator might want to know in order to have an overview of their options and a way to compare different rental locations. Instead of simply visiting a neighborhood or touring a couple of different apartments, my app is designed to give renters the ability to compare their potential options. For example, maybe I've just moved here, toured 2 apartments, and like them both reasonably well. How can I choose beyond just my gut feeling? Wouldn't knowing things like crime rates, distances to grocery stores, parks, and bike paths help me make a decision that will lead to longer-term satisfaction? Right now, to solve this problem, I'd have to spend a fair amount of time scouring Google Maps for each address, zooming in and out to look at what is around each location, and then try to find things like crime statistics by typing them into a search bar and hoping something good comes up. 

I want to provide a way for a user to enter the addresses of these potential rental locations, see this data side by side, and sort or filter it to compare the options that they believe will most impact their comfort or happiness with a given location. This app will also help its users save time. I might see a listing that looks great on Craigslist, but why waste my time touring the place if I can quickly enter the address and see immediately that there have been 12 burglaries and 15 car thefts there in the last year. Or maybe I like to walk my dog or go for a run in the morning--if there's not a park within a few blocks, I should probably look elsewhere. The basic idea is to make signing a lease less of a craps shoot and more of an informed decision--one I can make quickly since, in this market, there are lots of people in line to sign the same lease. 


### Target Audience

Anyone either moving to Denver or moving out of their current rental and needing to make an informed decision quickly, which is to say, anyone who wants to sign a lease in Denver and not get trapped between leases, stuck in a place they will probably hate for the duration of the lease.

### Integrations

* What OAuth provider makes sense for this audience?

 Facebook or Twitter AND Google

* What Data.gov data or API will you use?

-Google Maps API.
-Yelp API for quick querying of things like "park", "grocery", "bars".
-http://data.denvergov.org/dataset/city-and-county-of-denver-crime

* Any other integrations?
-possibly d3.js or Google Charts API for data comparison?


-heart of the app is ability to get lots of data for an address quickly
-ability to compare is the next step

###Week 1:
* Plan to have:
-name/branding
-wireframes
-basic UI/colors/layout theme (layout should account for second address display) 
-defined basic user stories (what a user can/will do on the site)
-user can sign in using OAuth (either Google or FB)
-user can enter a single address
-user can see crime data for a single address (chosen data set for crime)
-deploy to VPS

* Nice to have:
-placeholders for the second address (the 
-address showing up on google map
-user ability to change search radius from default ( e.g. change .5mi to .2mi )

* Uh oh:
-deploy to localhost
-allow UI to look a little shitty in service of delivering functionality


###Week 2:
* Plan to have:
-user can enter second address * (if this isn't complete from week 1) 
-user can see data for both addresses *
-user can see default list of "close by" amenities:
   -parks
   -grocery stores
   -restaurants
   -bars / liquor stores
   -coffee shops

###Week 3:

* Plan to have:
-user can customize their search (e.g. you can choose the 3 things you want to compare and that's all that will show up)
-use of background workers

