## Polution Level Service

## Demo Video: https://youtu.be/U6-V7QsPBrw

### What is it?
*Polution Level Service* is a Fluence Service that accepts a city name as parameter and outputs pollution data for that city. It can be used in any Sustainability Project that requires pollution data. It uses the API from [AQICN](https://aqicn.org) to fetch real-time pollution data all over the world.

### Compile and run

```
marine build --release
mrepl Config.toml
call pollution_level get ["paris"]
```

## Long-term goal

Our goal is to later use this new fluence service to create a Dynamic NFT that you can mint using a city name and that would automatically change its illustration based on the pollution level of that city.

We hired artist [Robson Teixeira](https://www.behance.net/robsonteixeira) to create the 3 illustrations representing 3 different levels of pollution.

Here is the first draft from the artist:
![](https://myairnft.com/screenshots/nfts-draft.png)

Here is the final version:
![](https://myairnft.com/screenshots/nfts-final.png)

The NFT will have metadata that redirects to our Polution Level Service in order to display one on 3 illustrations depending on the severity of the pollution level in that city. 

