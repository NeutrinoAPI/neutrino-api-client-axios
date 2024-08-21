# NeutrinoAPI Node Axios SDK

Neutrino API Node.js client using the Axios HTTP library

The official API client and SDK built by [NeutrinoAPI](https://www.neutrinoapi.com/)

| Feature          |        |
|------------------|--------|
| Platform Version | >= 10  |
| HTTP Library     | Axios  |
| JSON Library     | Native |
| HTTP/2           | No     |
| HTTP/3           | No     |
| CodeGen Version  | 4.6.15 |

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

Set the __'your-user-id'__ and __'your-api-key'__ values in the example to retrieve real API responses

## For Support
[Contact us](https://www.neutrinoapi.com/contact-us/)
