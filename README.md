# ember-popover
> A simple popover component that integrates with bootstrap 3 but provides its own API in order to work well with ember.js

## The Story
I figured out it was incredibly hard to use the original Twitter Bootstrap Popover Plugin with real ember.js views/templates, because the popover plugin generates a new element every time the popover gets shown and therefore takes control over inserting/rendering the view's html.

This breaks any bindings, actions etc. and only works with static templates, but not with real™ ember views.

## The Solution
I had a look into the code of the Popover Plugin and its dependency, the Tooltip Plugin. Because of the amount of LOC I decided to write a popover plugin on my own, based on Ember.Component.

The result is pretty simple but works quite well:

```handlebars

exmple to come

```

## API