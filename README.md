# web-api
Public Market Data API documentation for Brave New Coin.

## Install ReDoc CLI
```
npm i -g redoc-cli
```

## Build documentation
```
redoc-cli bundle openapi.yaml --output build/index.html --title "Brave New Coin API documentation" --template template.hbs --options.theme.colors.primary.main=#333F48 --options.theme.typography.links.color=#32329f --options.theme.typography.links.visited=#32329f --options.theme.typography.headings.fontFamily='Lato, sans-serif' --options.noAutoAuth --options.expandResponses=all
```

## Run locally
```
redoc-cli serve openapi.yaml --output build/index.html --title "Brave New Coin API documentation" --template template.hbs --options.theme.colors.primary.main=#333F48 --options.theme.typography.links.color=#32329f --options.theme.typography.links.visited=#32329f --options.theme.typography.headings.fontFamily='Lato, sans-serif' --options.noAutoAuth --options.expandResponses=all --watch
```

## ReDoc Documentation
* https://github.com/Rebilly/ReDoc
* https://github.com/Rebilly/ReDoc/blob/master/cli/README.md
