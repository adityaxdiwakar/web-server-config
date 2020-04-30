# nginx-config
Aditya Diwakar's Nginx Configuration to run on ``adi.wtf``.

## Files
This Nginx configuration is split up between 6 files all of which are different components.

### API
This is my personal API (known as the adinet), you can see all the code for the adinet [here](https://github.com/adityaxdiwakar/adinet-api).

### Blueberry
Blueberry is a market data provisioner that uses market data from the Chicago Mercantile Exchange to provide forward-facing quotes data (including best bid/ask), this is exposed to the world for the sake of ``md.aditya.diwakar.io/recent/`` which is the HTTP method to receive a quote. You can see all Blueberry code [here](https://github.com/adityaxdiwakar/blueberry).

### Driplet
Driplet is a systemctl and streamed file log system. This is exposed to the WAN for the sake of the [websocket](https://github.com/adityaxdiwakar/driplet-daemon), [API](https://github.com/adityaxdiwakar/driplet-api), and the [frontend](https://github.com/adityaxdiwakar/driplet-www). The code is linked.

### Others
All other configuration files do not have Github repositories, they are static components.

## Support
If you need support for any Nginx configurations, feel free to contact me ``aditya@diwakar.io`` or on Discord @ ``aditya#0001``. 
