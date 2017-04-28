# icon-label-grid

A Polymer Element showing a grid of icon-label elements.

Example:
```html
<icon-label-grid data="[[array]]"></icon-label-grid>
```

### Styling

`<icon-label-grid>` provides the following custom properties and mixins for styling:

Custom property                | Description                         | Default
-------------------------------|-------------------------------------|--------
`--icon-label-grid-cell-width` | Grid cell width                     | 33%
`--icon-label-grid-link-color` | Icon label link text color on hover | --secondary-text-color
`--icon-label-grid-text-color` | Icon label text color               | --primary-text-color

### Dependencies

Dependencies are installed using [Bower](http://bower.io/):

    npm install -g bower

### Testing

    Tests are run using [web-component-tester](https://github.com/Polymer/web-component-tester):

        npm install -g web-component-tester
        wct

### Demonstration & Documentation

    Demonstration and documentation are viewed using [polyserve](https://github.com/PolymerLabs/polyserve):

        npm install -g polyserve
        polyserve

    bower install
