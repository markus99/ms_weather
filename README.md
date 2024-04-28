# ms_weather
Home Assistant Weatherflow Tempest Forecast, Sensors, Template(s)

My take on a custom weather card for Home Assistant using Tempest Weatherflow data.  Provided excerpts from some files only - you'll have to copy/insert where necessary.  Also worth noting I'm using packages and have ms_weather.yaml in a /packages folder in my /config directory and include in via configuration.yaml using:

```
  packages: !include_dir_named packages
```

Results in something like this:

![image](https://github.com/markus99/ms_weather/assets/2835274/ce7d7b4a-2349-45a5-a5b7-9b5655e5a98e)

