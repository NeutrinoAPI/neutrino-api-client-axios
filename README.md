# NeutrinoAPI Node Axios SDK

Node client using the Axios HTTP client

The official API client and SDK built by [NeutrinoAPI](https://www.neutrinoapi.com/)

| Feature          |       |
|------------------|-------|
| Platform Version | >= 10 |
| HTTP Library     |       |
| JSON Library     |       |
| HTTP/2           | false |
| HTTP/3           | false |
| CodeGen Version  | 4.6.8 |

## Getting started

First you will need a user ID and API key pair: [SignUp](https://www.neutrinoapi.com/signup/)

## To Initialize
```js
const NeutrinoAPIClient = require('../client/neutrino-api-client')

const neutrinoAPIClient = new NeutrinoAPIClient('<your-user-id>', '<your-api-key');
```

## Running Examples

```sh
$ node src/examples/bad-word-filter.js
```
You can find examples of all APIs in _src/examples/_

## For Support
[Contact us](https://www.neutrinoapi.com/contact-us/)