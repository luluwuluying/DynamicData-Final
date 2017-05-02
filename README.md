## Documentation
### What is it?
#### Travel Life is an itinerary website that provides one day itinerary for each destination. You can simply type in a random destination and get a perfect one day itinerary. Inside of each itinerary, the system will returns 4 places to have fun and 2 restaurants for meal.
#### ![alt text](http://url/to/background.png)

### How it works?
#### Here I used Google Place Api: Using google place type to query and get the name, address, rating from each destination. I attached the google place api node.js as follows.
#### ![alt text](http://url/to/api.png)
#### ![alt text](http://url/to/api2.png)

### My code
#### Since google place api doesn't have a specific place type called attractions or things to do, so I have to query those places by different place type, I am using restaurant, park ,church and mesume for my project. First I created a variable for location based on the input from user and then searching the places within the range of that location.



