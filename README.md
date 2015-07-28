# yarn-elements
Polymer v1 elements for the yarniverse

[![Build Status](https://travis-ci.org/yarn-co/yarn-elements.svg?branch=master)](https://travis-ci.org/yarn-co/yarn-elements)

## Includes
### Elements
### Behaviors
  - [`yarn-auth-behavior`](https://github.com/yarn-co/yarn-auth-behavior)
  - [`yarn-endpoints-behavior`](https://github.com/yarn-co/yarn-endpoints-behavior)
  - [`yarn-state-behavior`](https://github.com/yarn-co/yarn-state-behavior)
  - [`yarn-view-behavior`](https://github.com/yarn-co/yarn-view-behavior)

## Docs and Tests
HTML imports require CORS support, so we must use a simple web server to view the tests and documentation.
```bash
bower install
python -m SimpleHTTPServer 8000
```

### Documentation
To view the fancy documentation for this repo, follow the process above then navigate to **http://localhost:8000/**.

### Tests
To run the tests for this repo, follow the process above then navigate to **http://localhost:8000/tests/**.
