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
        height: 300  
        
 (update interval is in seconds)
 (height is optional)

### An example in my own UI as a Picture Element:

![Preview Image](https://github.com/lukevink/home-assistant-buienradar-forecast-card/blob/master/buien-card-screenshot2.png)
