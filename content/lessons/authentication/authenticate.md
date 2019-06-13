---
title: "RapidAPI"
---

Cindercloud is free of use for everyone. However, by default unauthenticated requests are throttled at 4 req/min. 

Removing this restriction can be done by registering on RapidAPI. After registering and signing up for the free plan, you'll get an API key.

## Authentication Header

```javascript
curl --get --include 'https://cindercloud.p.rapidapi.com/api/ethereum/address/0xc0ffee145a59d2172971cde0f0b4959d51193a80/balance' \
  -H 'X-RapidAPI-Key: YOUR_API_KEY'
```

## Endpoint

The endpoint for unauthenticated requests is `https://api.cinder.cloud`

##  Endpoint with RapidAPI

When making use of RapidAPI, the base url changes from `https://api.cinder.cloud` to `https://cindercloud.p.rapidapi.com`