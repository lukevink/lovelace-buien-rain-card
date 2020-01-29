# home-assistant-buienradar-forecast-card
Graph of Buienradars rain forecast 

![Preview Image](https://github.com/lukevink/home-assistant-buienradar-forecast-card/blob/master/buien-card-screenshot1.png)
![Preview Image](https://github.com/lukevink/home-assistant-buienradar-forecast-card/blob/master/buien-card-screenshot2.png)

### Simple install

1. Download and copy `buien-rain-card.js` into your `config/www` directory.

2. Add a reference to `buien-rain-card.js` inside your `ui-lovelace.yaml`.

  ```yaml
  resources:
    - url: /local/buien-rain-card.js
      type: module
  ```
