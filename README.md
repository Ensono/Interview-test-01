Amido Front End Technical Test

Using a framework of your choice (or no framework if you like) create a server-side-rendered application that meets the following specification, using the following API:

https://developer.apple.com/library/archive/documentation/AudioVideo/Conceptual/iTuneSearchAPI/Searching.html#//apple_ref/doc/uid/TP40017632-CH5-SW1

Spec:

As a user
I want to be able perform a search query about an artist, album or song
So that I can see a list of artists, albums and/or songs related to my query

Given I am using the search form
When I conduct a search
Then I should be able to see the results returning matching Artists, Albums, and/or Songs
And it should limit to 10 items at a time
(optional) And when I scroll down, another 10 items should be revealed.

Given I am using the search form
When I conduct a search
And there are no results
Then I should be notified that there are no results

(optional)
Given I have a list of results
When I 'favorite' an artist, song or album
Then the favorited item should appear in another list (favorites section).
