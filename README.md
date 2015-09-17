# taxi-trip-data-fargo
An anonymized dataset of trips by a taxi company operating in fargo from Jan 2013 to March 2014.

## The data
The [data.json](https://raw.githubusercontent.com/muhasaho/taxi-trip-data-fargo/master/data.json) is a json array of 12300 objects. Each object represents a **trip**. A trip has the following format:
```javascript
"dropoff": {
    "location": [
        46.87429245,    //dropoff latitude
        -96.79251132    //dropoff longitude
    ], 
    "utcTime": "2013-01-03T07:42:12.033Z"   //dropoff time in UTC
}, 
"pickup": {
    "location": [
        46.86238289,    //pickup latitude
        -96.83044631    //pickup longitude
    ], 
    "utcTime": "2013-01-03T07:33:19.089Z"   //pickup time in UTC
}
```

###License
MIT. See [License](https://github.com/muhasaho/taxi-trip-data-fargo/blob/master/LICENSE)
