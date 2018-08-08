### Run the application

**First**

Add file token.js in root project folder and add `const token = <Your Mapbox token>` to it.

**Second**

In a terminal, check the version of Python you have: `python -V`. If you have Python 2.x, spin up the server with `python -m SimpleHTTPServer 8000` (or some other port, if port 8000 is already in use.) For Python 3.x, you can use `python3 -m http.server 8000`. If you don't have Python installed, navigate to Python's [website](https://www.python.org/) to download and install the software.

**Third**

With your server running, visit the site: `http://localhost:8000`

### Accessibility

- add aria attributes
- change color contrast

### Offline Availability

Add Service Worker
