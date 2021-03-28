# Quality-Match
Quality Match Coding Task

Description:  
The main purpose is to view the historical hourly air temperature data of the city the user enter.

How it works:  
-User enter the city name and submit it.  
-The app retreive the city data from an API [nominatim](https://nominatim.openstreetmap.org/ui/search.html).  
-The app find the nearest weather station (from a list of station already retrieved from [dwd](http://ftp-cdc.dwd.de/) API) using coordination of both.  
-The user click on nearest weather station and the app fetch the data for this station from the dwd API.  

To download and use, simply run the following commands on your machine:

```bash
git clone https://github.com/EhabAlmardoud/Quality-Match.git
cd Quality-Match
npm install
```

To start the project run:
```bash
npm start
```

Note:  
If you are having problem retrieving data from the DWD website due to CORS policy: No 'Access-Control-Allow-Origin', 
You can download the Chrome extension [Moesif Origin & CORS Changer](https://chrome.google.com/webstore/detail/moesif-origin-cors-change/digfbfaphojjndkpccljibejjbppifbc)
