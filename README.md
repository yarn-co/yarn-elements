# yarn-elements
Polymer v1 elements for the yarniverse

[![Build Status](https://travis-ci.org/yarn-co/yarn-elements.svg?branch=master)](https://travis-ci.org/yarn-co/yarn-elements)

## Includes
### Elements
### Behaviors
  - `yarn-auth-behavior`
  - `yarn-state-behavior`
  - `yarn-view-behavior`

## Docs and Tests
The relative paths used in this project assume that `yarn-elements` will be included alongside its dependencies using bower.  So, to test this repo and view documentation, a small amount of massaging must be done.  Also, HTML imports require CORS support, so we must use a simple web server to view the tests and documentation.
```bash
bower install
ln -s .. bower_components/yarn-elements
python -m SimpleHTTPServer 8000
# Now navigate to, for example,
# http://localhost:8000/bower_components/yarn-elements/
```

### Documentation
To view the fancy documentation for this repo, follow the process above then navigate to **http://localhost:8000/bower_components/yarn-elements/**.

### Tests
Tests are placed inside the `test` folder within the individual element and behavior folders.
