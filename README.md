# Treasure Map in Flask

This is an implementation of <a href="https://github.com/polypmer/freestuff-bot">freestuff-bot</a> using [Flask](www.flask.pocoo.org).

## Dependencies
* requests
* bs4
* python 3.x
* [see requirements.txt]


## Application Intereface
Something like this subject to change:
<ul>
<li>domain.com/location/quantity</li>
<li>domain.com/location/map for a quantity of 9
</li>
<li>domain.com/location>/map/quantity  - for more or less entries , geocoder crashes around 20
</li>
</ul>
## TODO: 
* A lot
* Navigation
* Make X's for mappify's Map creation
* Fancy Legend
* Loading screen

### Issues:
* Major location problem, only three cities work?
    - get list of cities names
    - create dict/key?
* Store stuffs list in a session??
    - pass it through a link?

