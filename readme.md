# Coindex CLI

Command line interface written in Node.js to check cryptocurrency prices

## Usage

```
npm install

npm link
```

## Commands

```
# Help & Commands
coindec -h

# Version
coindec -V

# API Key Commands
coindec key set
coindec key show
coindec key remove

# Crypto Check Commands
coindec check price

# Check Specific Coins (default: BTC,ETH,XRP,USDT,ADA)
coindec check --coin=BTC,ETH

# Choose Currency (Default: USD)
coindec check --cur=EUR
```

### Version

1.0.0

