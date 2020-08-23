

#  WeatherNow

A weather app that allows you to check the weather for any location based on GPS data of iPhone as well as searching any city manually. Uses Core Location get to current location of phone GPS. Incorporates Open Weather API and sends HTTP request to retrieve weather condition for particular city

## Finished App
<img src="https://github.com/GavinWon/WeatherNow/blob/master/weathernow.png" alt="Finished App" width=300>


##Condition Codes

```swift
switch (condition) {

    case 0...300 :
        return "tstorm1"

    case 301...500 :
        return "light_rain"

    case 501...600 :
        return "shower3"

    case 601...700 :
        return "snow4"

    case 701...771 :
        return "fog"

    case 772...799 :
        return "tstorm3"

    case 800 :
        return "sunny"

    case 801...804 :
        return "cloudy2"

    case 900...903, 905...1000  :
        return "tstorm3"

    case 903 :
        return "snow5"

    case 904 :
        return "sunny"

    default :
        return "dunno"
    }
```
