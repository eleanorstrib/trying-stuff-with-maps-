# How to run this file

1 - Using the terminal, clone this repo to your local machine

2 - Create a virtualenv - recommend a Python venv, `virtualenv -p python3 envname` (note there are no requirements to install to run the file)

3 - Get a [Mapbox](https://www.mapbox.com) access token and either add to your local file or create a file called `secret.js` in the project root - a file with that name is already sourced in the html

4 - Add the data file to the project root and change the name of the file/path at the `$.getJSON` command if needed

4 - Start your Python server `python3 -m http.server`

5 - Navigate to `localhost:8000` (or whichever port is specified in the terminal) and select `heatmap.html`
