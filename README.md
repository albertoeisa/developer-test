#Developer Test

This test is designed to demonstrate your technical, analytical and communications skills.

##How to take this test

* Fork this project to your own repository
* Install the dependencies and get the code running (there is some advice below)
* Review the list of issues below. Read through each one and ensure you can replicate the problems on your development build
* Fix each issue as best you can. Each fix should be contained in its own branch and you should open a Pull Request for each one. Your Pull Requests should briefly describe how you've fixed the issue and what steps should be taken for a tester to check your work (advice on this is below)

##Running this code

Clone your fork of this project to a development environment that can run PHP 5.5+

`composer install`

##Notes on Pull Requests

Include guidance on:
any new build steps. even if it's just merge the code.
how to test this issue is fixed.
one issue, one branch, one pull request.


#Bugs

###ISSUE#1

We are seeing some strange characters appearing on the page, where an apostrophe should be. We've checked our content source and it's definitely using an `’` character.

###ISSUE#2

The episodes should be listed in order of their season and episode number. At the moment "Behind The Laughter - s11e22" is appearing first in the list

###ISSUE#3
Sometimes we see errors appear on the page such as `Uncaught exception 'GuzzleHttp\Exception\ServerException'`. We know that the API doesn't always work, so please make sure this page can handle the errors gracefully. Perhaps you could tell the user "Sorry, there was an error. Please try again by reloading the page."

###ISSUE#4
There are some visual differences between the design and the page as we see it in Chrome. Please correct the CSS so that the page matches the design exactly. You can find the design.png in the root of this project.
