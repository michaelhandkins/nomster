Nomster
=======

Nomster is a Yelp clone that allows registered users to add places to the app's database that may then be reviewed with star-ratings and comments from any registered user.

Technologies Used
-----------------

  * Ruby, v. 2.5.3 (primary programming language)
  * Rails (framework)
  * Bootstrap (design elements)
  * Google Maps API (restaurant map placement)
  * Devise (user authentication)
  * Carrierwave (image and video uploading)
  * AWS (image and video storage)
  * will_paginate (pagination of index)

Interface
---------

After signing up to be a registered user of Nomster, users have the option to add a "New Place" to the application's index of eateries.

![](images/addplace.PNG)

After creating a place, a representation of where the place is located on a map is generated automatically thanks to Google Maps API integration.

![](images/whatamap.PNG)

Any registered user may add a photo or comment to any place shown in the app. 

![](images/addphoto.PNG) ![](images/addcomment.PNG)

Nomster is deployed at https://nomster-handkins.herokuapp.com/