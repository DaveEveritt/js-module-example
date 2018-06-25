# Simple JavaScript ES6 module example

Just to get JavaScript ES6 modules up and running locally, without any other libraries.

**Note:** the script tag for the main JavaScript file (from which any module files are imported) needs a `type="module"` attribute e.g. `<script type="module" src="main.js"></script>`.

Although [ES6 module syntax is supported in most modern browsers](https://www.caniuse.com/#feat=es6-module), the same-origin policy applies, so can't run from your file system (i.e. by dragging your HTML file to the browser). Run a local server—any of these will do:

- [node](https://www.npmjs.com/package/http-server) (install globally with `npm install http-server -g` and run from your project directory with `http-server` on the command-line to view on http://localhost:8080)
- [Python](https://sweetme.at/2013/08/21/simple-local-http-server-with-python/) `python -m SimpleHTTPServer` Python3 `python -m http.server` (default port 8000)
- [Ruby](https://sweetme.at/2013/08/28/simple-local-http-server-with-ruby/) `ruby -run -e httpd . -p 8000`
- [PHP](https://secure.php.net/manual/en/features.commandline.webserver.php) `php -S localhost:8000`

## TO DO

- [ ] improve links to local servers
- [ ] document CommonJS, AMD and ES6
