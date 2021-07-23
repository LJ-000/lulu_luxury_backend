# Welcome to the Lulu Luxury Database!

<img height="400" src="https://www.bjtonline.com/sites/bjtonline.com/files/styles/bjt30_article_large/public/time_tide-miavana-web.jpg?itok=itMq8Bd9&timestamp=1524495882"></img>

## About Lulu Luxury

Lulu Luxury is a (fictional) vacation planning app for every person’s (or penguin’s) needs! This app is dedicated to Lulu the penguin from the Georgia aquarium.

This app is a single page application that houses a React front end, and a Ruby backend.

Be sure to check out the front-end repo <a href="http://github.com/bwennuh/luxury/lulu-app-frontend">here</a>!


## Database Info

### Patrons

Patron information includes the patron names, ages, phone numbers, emails, and a boolean check to see whether or not they've paid for the resort stay yet.

### Resorts

Resort information includes the resort names, locations, availability dates, images of the resort, and the resort's current rating.

### Excursions

Excursion information includes the excursion names, excursion types, popularity ratings, excursion descriptions, images of the excursions, reservation dates, and the associated resort ID's (to be linked to their associated resorts).

### Bookings

Patrons, resorts, and excursions are linked via bookings.

Booking information includes the patron ID (to get the associated patron), the resort ID (to get the associated resort), the excursion ID (to get the associated excursion, if applicable), the room type at the resort, and the start date & end date of the reservation stay.
