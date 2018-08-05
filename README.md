# Charging Break Frontend

[![NPM version](https://img.shields.io/npm/v/chargingbreak-frontend.svg?style=flat-square)](https://www.npmjs.com/package/chargingbreak-frontend)
[![Build](https://travis-ci.org/ChargingBreak/chargingbreak-frontend.svg?branch=master)](https://travis-ci.org/ChargingBreak/chargingbreak-frontend)

## Dependencies

Install JavaScript dependencies via npm after cloning the repository:

```
npm install
```

> **Note:** Makes sure to have `vue-cli` installed as well: `npm install -g vue-cli`

## Development

Run local webserver on port 8080

```
npm run serve
```

> Visit http://localhost:8080 to access the site

## Build

Generate production build

```
npm run build
```

## Deploy

Deploy assets to S3 and invalidate CloudFront cache entries

```
npm run deploy && npm run deploy:invalidate
```

Full deployment:

```
npm run build && npm run deploy && npm run deploy:invalidate
```
