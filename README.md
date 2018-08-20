# web-api
Public API documentation for Brave New Coin.

## Install ReDoc CLI
```
npm i -g redoc-cli
```

## Build documentation
```
redoc-cli bundle openapi.yaml --output build/index.html --cdn --title "Brave New Coin API documentation" --template template.hbs
```

## ReDoc Documentation
* https://github.com/Rebilly/ReDoc
* https://github.com/Rebilly/ReDoc/blob/master/cli/README.md
