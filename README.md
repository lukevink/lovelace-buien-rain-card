## *** THIS CARD IS NO LONGER IN DEVELOPMENT ***
I created this card out of desperation (there was no way to forecast) and its implimentation is pretty terrible.
Please try the [Neerslaag App](https://github.com/aex351/home-assistant-neerslag-app) from aex351 who did some awesome work and made a much better implimentation. [Visit on HAS Forum](https://community.home-assistant.io/t/neerslag-card-rain-forecast-buienalarm-and-or-buienradar/287512)


# Home Assistant Buienradar Forecast Card
Graph of Buienradars rain forecast 

![Preview Image](https://github.com/lukevink/home-assistant-buienradar-forecast-card/blob/master/buien-card-screenshot1.png)

### Simple install

1. Download and copy `buien-rain-card.js` into your `config/www` directory.

2. Add a reference to `buien-rain-card.js` inside your `ui-lovelace.yaml`.

  ```yaml
  resources:
    - url: /local/buien-rain-card.js
      type: module
  ```

### Add as a card to your UI

      - type: 'custom:buien-rain-forecast'
        long: 4.8945
        lat: 52.3667
        lineColor: 'rgba(89, 160, 238, 1)'
        fillColor: 'rgba(89, 160, 238, 0.2)'
        update_interval: 10
        icon: 'mdi:weather-rainy'
        
 (update interval is in seconds)

### An example in my own UI as a Picture Element:

![Preview Image](https://github.com/lukevink/home-assistant-buienradar-forecast-card/blob/master/buien-card-screenshot2.png)
