# nasa-apod
Incorporating Nasa API to get random Astronomy Picture of the Day.

### [Live Site](https://saketkothari.github.io/nasa-apod/)
<img style="text-align:center" src="https://user-images.githubusercontent.com/81709725/132088052-d4a334f7-2453-4df7-bbef-8b5fef51e997.png" />

#

#### API Reliability :-
A very large number of people use the instance of this API that NASA has set up. If you need a extremely reliable version of this API, you likely want to stand up your own version of the API. You can do that with this code! All information that this API returns is actually just grabbed from the <a href='https://apod.nasa.gov/apod/astropix.html'>Astronomy Photo of the Day Website</a> (APOD).

#

#### Features :- 
* Result is formatted into cards with an image, title add to favorites, description, date and copyright information
* Ability to add images to favorite of our page this is accomplished using local storage
* Also have option to remove from favorite
* These images are lazy loaded in order to improve performance, only load when it comes to scroll.
