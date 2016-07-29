`composer install`

#Bugs

* We are seeing some strange characters appearing on the page, where an apostrophe should be. We've checked our content source and it's definitely using an `’` character.
* The episodes should be listed in order of their season and episode number. At the moment "Behind The Laughter - s11e22" is appearing first in the list
* Sometimes we see errors appear on the page such as `Uncaught exception 'GuzzleHttp\Exception\ServerException'`. We know that the API doesn't always work, so please make sure this page can handle the errors gracefully. Perhaps you could tell the user "Sorry, there was an error. Please try again by reloading the page."
* There are some visual differences between the design and the page as we see it in Chrome. Please correct the CSS so that the page matches the design exactly.
