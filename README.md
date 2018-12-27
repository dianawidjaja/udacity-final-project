# Restaurant Review App Project
This project is part of Udacity's Front-End Web Developer Nanodegree program. The goal is to make a static webpage into a responsive and accessible web app that supports offline availability.

## Installation

Clone the GitHub repository.

```
git clone https://github.com/dianawidjaja/udacity-final-project.git
```
The project runs on a simple HTTP server in [Python](https://www.python.org/). If you have Python 2.x, start the server using:

```
python -m SimpleHTTPServer 8000
```
 For Python 3.x, run:
 
 ```
 python3 -m http.server 8000
 ```

View the restaurant review app in a browser at `http://localhost:8000`.

## Project Features

The following features are implemented by [starter code](https://github.com/udacity/mws-restaurant-stage-1).

`index.html`

* Loads a map with location markers using [MapBox API](https://www.mapbox.com/) and [Leaflet](https://leafletjs.com/) 
* Filters restaurants based on neighborhood and cuisine
* Displays restaurant information with photo, name, location, and a View More button

`restaurant.html`
* Loads a map with a location marker for the restaurant
* Displays restaurant information, such as address and hours
* Lists reviews with reviewer's names, ratings, and comments

## Additional Features

The following features are implemented to meet project requirements.

### Responsive UI

* Makes UI compatible with mobile and desktop devices 
* Adapts filters to various screen sizes
* Implements the flex container for `restaurant-list`

### Accessibility

* Adds a skip link to navigate directly to main content
* Includes alternative text for images
* Manages focus using `tabindex` to improve navigation
* Implements ARIA attributes for filters
* Implements ARIA role for the `main` landmark

### Offline Availability

* Registers a service worker
* Adds assets to cache to enable app to load offline after the first use


### Accessibility

### Offline Availability

