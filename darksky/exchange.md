# Dark Sky

The easiest, most advanced, weather API on the web.

## Full Description

Signup to get your own API key and start using 1000 calls per day for free. https://darksky.net/dev/register

## Capabilities

Forecasts and current conditions
Darksky.forecast{lat_and_long_or_time = '44.9772995,-93.2654692'} 

Global coverage
Darksky.forecast{lat_and_long_or_time = '25.0375198,121.5636796', lang = 'zh-tw'} 

Historical data
return Darksky.forecast{lat_and_long_or_time = '44.9772995,-93.2654692,2017-10-26T18:53:08+00:00'}

Severe weather alerts
Darksky.forecast{lat_and_long_or_time = '25.0375198,121.5636796'}.alerts 


## Schema

https://gist.githubusercontent.com/dominicletz/9d07d71755d0713031480733466c72d4/raw/b8b131c61c4e2a50d2f46498df9f1576711d2bd2/darksky.yaml

## Contact

developer@darksky.net

