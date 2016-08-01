#Developer Test

This test is designed to demonstrate your technical, analytical and communication skills.

We have a built simple website that displays a list of TV episodes pulled from a remote API. There are a number of issues with this website that need to be fixed.

##How to take this test

* Fork this project to your own repository (https://help.github.com/articles/fork-a-repo/)
* Install the dependencies and get the code running (there is some advice below)
* Review the list of issues below. Read through each one and ensure you understand the problems before you dive into the code
* Fix each issue as best you can. Each fix should be contained in its own branch and you should open a Pull Request for each one. Instructions for how to format your Pull Request are below.

###Running this code

Clone your fork of this project to a development environment that can run PHP 5.5+

Navigate to the directory you've just created and run `composer install`. If you do not have composer on your machine, you can use the version of composer included in this repository - run `php composer.phar install`.

Start your server with the `public` directory as your document root. If you are using the built in PHP server you can navigate to `public` and run `php -S localhost:8000` to start a server.


###Notes on Pull Requests

* (https://help.github.com/articles/creating-a-pull-request/)[Creating a Pull Request]
* Each issue you work on should be in its own branch. The branch should be named sensibly so that the issue can be identified e.g. `issue1`
* Pull Requests should be opened against the Master branch of your own fork (not against 3ev/developer-test)
* Your Pull Request message should describe what has been fixed and include all the steps to test your work
* Your Pull Request message should be formatted as follows:

**Title**
>ISSUE#10 - fixed profile image

**Message**

>This PR updates the avatar image for Bobby Child so that it is less terrifying.
>
>---
>
>**Testing**
>
>In a browser verify that the avatar image has been replaced with the new image and that the dimensions have remained the same.
>
>---
>
>**Deployment steps**
>
>Merge branch `issue10` into `master`
>
>Compile assets: `./bin/node_modules/gulp`


#Issues to fix

###ISSUE#1

Some of the text on the page looks a bit strange. Please fix it.

###ISSUE#2

The episodes should be listed in order of their season and episode number. At the moment "Behind The Laughter - s11e22" is appearing first in the list

###ISSUE#3
Sometimes we see errors appear on the page such as `Uncaught exception 'GuzzleHttp\Exception\ServerException'`. Please show the user an error message such as "Sorry, there was an error. Please try again by reloading the page." and use one of the Bootstrap styles for displaying it.

###ISSUE#4
There are some visual differences between the design and the page as we see it in Chrome. Please correct the CSS so that the page matches the design exactly. You can find the design.png in the root of this project.
