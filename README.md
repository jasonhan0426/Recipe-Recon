# Recipe Recon

## Description

This site provides basic function of web application for users to sign in, search for recipe from a 3rd party API (yummly.com), and favorite recipes

## Authors

* [dhoang1csuf](https://github.com/dhoang1csuf) - Daniel Hoang
* [gerardco](https://github.com/gerardco) - Gerard Cortes
* [jasonhan0426](https://github.com/jasonhan0426) - Jason Han
* [philipchungtech](https://github.com/philipchungtech) - Philip Chung
* [shelleypham](https://github.com/shelleypham) - Shelley Pham

## Installation

* `git clone <repository-url>` this repository
* `cd <repository>`
* `npm install`

### Build With Plugins

What things you need to install to run the software:

```
$ ember install emberfire
$ ember install torii
```

## Deployment

```
$ ember serve
```

once loaded, open browser and open up a page with link: http://localhost:4200/

The first thing you will see is a page like this where you can login at the top right corner and do a search of recipe at the bottom
<br>
<img height="250" src="https://github.com/cpsc473p2g/documentation/blob/master/home.PNG">
<br>
You can search recipe in the search box and that will pull data from a third part (yummly.com)
For example, when searching eggs, you will get a list of recipe that includes ingrediant eggs with that model that looks like this.
Note that the "Add to my Favorites" button which will be saving data to our database hosted on firebase
<br>
<img height="400" src="https://github.com/cpsc473p2g/documentation/blob/master/egg.PNG">
<br>
Once you are login, notice at top left corner there is an extra "My Favorite Recipes" button
<br>
<img height="50" src="https://github.com/cpsc473p2g/documentation/blob/master/favorite.PNG">
<br>
For every recipes you added to my Favorites will be shown here
<br>
<img height="400" src="https://github.com/cpsc473p2g/documentation/blob/master/MyFavorite.PNG">
<br>

## Acknowledgments

* [emberfire](https://github.com/firebase/emberfire)
* [torii](https://github.com/Vestorly/torii)
