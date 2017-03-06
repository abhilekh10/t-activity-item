# t-activity-item Specification

### Component Use

``` html

<t-activity-item
	resources="{{resources}}"
	settings="{{settings}}"
>
</t-activity-item>

```

### Options to Component

```javascript

	var resources = {
	    "buttons": {
	      "startsFrom": "Starting Price",
	      "showOptions": "Show Options"
	    }
	  }

```


```javascript

	  var settings = {
	    "imgPlaceholder": "http://cdn.xyz.com/images/placeholder.jpg",
		"onShowOptionClick": "_showOptions(item)"
	  }

```


## Important Information

- Misc items to be handled from CSS like:
1. List card background color
2. Mixin (to control text color, font etc)
3. Mixin (Button color, size etc.)


## Test Cases
- Basic validation for filter

## Steps to Start
- Set Github repository at your end for this project, we will merge them later
- APIs Integration - Use Tavisca's APIs for integration purpose.

## Performance standard
- Any component if opened via [web page tester](https://www.webpagetest.org/), it should load under 500ms (milli seconds).

## Documents
- Visual designs for search components - https://projects.invisionapp.com/share/6E9PJ7R4Q#/screens/212067485
- API access : Url - http://demo.travelnxt.com/dev
- Tavisca Elements - https://github.com/atomelements and https://github.com/travelnxtelements
- Vaadin elements - https://vaadin.com/docs/-/part/elements/elements-getting-started.html
- Google - https://elements.polymer-project.org/browse?package=google-web-components
- Tavisca Web component style Guide - https://drive.google.com/open?id=0B7BT_2nBFNYVR2tscE9pRnVJYmc

## Ballpark Estimates

5 Days / 25 Weeks
- Estimates are including above requrement with responsive design.
- Estimates are for single resourse.
- These are ballpark estimates and can be more/less while actual development.
