# Egypt's Museums
-------

## Description:
This single page app uses Google maps and Foursquare's API to list all the available museums near by in Cairo and Giza, Egypt. 

## How to run:
Make sure that you have Node.js installed on your device and then clone the repository.
Navigate to the directory that contains the project and write:
`npm install`
then run:
`npm start`
The browser should automatically open the app.  If it doesn't, navigate to [http://localhost:3000](http://localhost:3000)

NOTE: Service worker for this app will only work when the app is in production mode.
## Loading the App in Production Mode:
To run the app in production mode run:
`npm run build`
Then navigate to the build directory and start a localhost with python
`python -m SimpleHTTPServer 8000`
After that navigate to [http://localhost:8000](http://localhost:8000) in your browser.
