# Welcome to WhatIf!

### WhatIf is a comprehensive and user-friendly web-based platform that provides investors with valuable insights into the potential returns of their hypothetical cryptocurrency investments.

The app's intuitive interface allows users to easily select from a range of popular cryptocurrencies and specify a starting date, enabling them to see the estimated profits or losses they would have made if they had invested on that date and held until the present.

WhatIf leverages historical market data to provide accurate calculations of investment returns, allowing users to make informed investment decisions based on historical market trends and patterns. The app's sophisticated algorithm takes into account various factors, such as market volatility and price fluctuations, to provide users with a comprehensive analysis of their potential returns. 


Whether you're an experienced cryptocurrency investor or just starting out, WhatIf provides you with the tools to realize how much money you could have had. With its easy-to-use interface and advanced calculation algorithms, WhatIf is the fun tool for anyone looking to explore the world of cryptocurrency investment. 

## To get WhatIf working on your machine:

### You must have [Go](https://go.dev), and [Docker](https://www.docker.com) installed.

### To verify installation, run the following commands:
```zsh
go version
docker -v
```
### Use your preferred method of cloning the repository to get the WhatIf project within your go/src folder.

## Initalizing back-end server

### Navigate to the `server` folder
```zsh
cd server
```

### Run Docker compose to setup back-end server and Air live-reload

```zsh
docker compose up
``` 

### The back end will serve on http://localhost:8008.
