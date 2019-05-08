
# Blockchain Wallet API V2

## Installation

[`nodejs`](https://nodejs.org) and [`npm`](https://npmjs.com) are required to install and use this API service. Installation:

```sh
$ npm install -g blockchain-wallet-service
```

For the best stability and performance, make sure you are always using the latest version.

To check your version:

```sh
$ blockchain-wallet-service -V
```

To update to the latest version:

```sh
$ npm update -g blockchain-wallet-service
```

Requires:

  * node >= 6.0.0
  * npm >= 3.0.0

If you have issues with the installation process, see the troubleshooting section below.
t an API code [here](https://blockchain.info/api/api_create_code).

### Examples

To start the Wallet API service on port 3000:

```sh
$ blockchain-wallet-service start --port 3000
```

## Development

  1. Clone this repo
  2. Run `yarn --ignore-engines`
  3. Run `yarn start`
  4. Dev server is now running on port 3000

### Configuration

Optional parameters can be configured in a `.env` file:

  * `PORT` - port number for running dev server (default: `3000`)
  * `BIND` - ip address to bind the service to (default: `127.0.0.1`)

