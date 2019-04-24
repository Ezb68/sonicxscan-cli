<h1 align="center">
  SonicXscan Client
  <br>
</h1>

<h4 align="center">
  Node Client for the <a href="https://api.sonicxscan.com">SonicXscan.com API</a>
</h4>

<p align="center">
  <a href="#how-to-use">How to Use</a>
</p>

# How to use

## Requirements

* Node v9.8.0

## Running tests

```bash
> npm test
```

## Usage

Install the package

```bash
> npm install @sonicxchain/sonicxscan-cli
```

Use the HTTP Client

```javascript
import {Client} from "@sonicxchain/sonicxscan-cli";

const client = new Client();

let recentBlocks = await client.getBlocks({
  sort: '-number',
  limit: 10,
});
```
