# Are you looking for a new place to live in Boston? #

Most people in Boston do not have a car.  Many would like to find an apartment close to reliable public transportation.  They need to be close enough to work to not have to commute more than 30 minutes one way.  Generally they want to have great services close to them.

When looking for a new apartment this type of information is not always easy to find.  We need a tool that will combine services type information (FourSquare) with transportation type information (Massachusetts Bay Transportation Authority).

## Data Information
Foursquare data will be used to get services information.  This will contain the types of venues available in a location.  Venue data includes ratings, stats (user counts and checking counts), likes, & price.  It also contains latitude and longitude data that can be used to calculate the exact distance from a given point.  

Massachusetts Bay Transportation Authority (https://www.mbta.com/developers) has information related to the transportation in Boston.  The V3 API contains Vehicle, Trip, Stop, Shape, Schedule, Route, Prediction, & Facility information.  The shape data contains latitude and longitude information which will be used to calculate the distance from various points of interest in your neighborhood.
