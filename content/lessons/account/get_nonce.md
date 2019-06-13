---
title: "Get Nonce"
---

Get the nonce of an Ethereum address. The nonce is the current transaction index of an account (an index representing the amount of transactions an address has submitted to the network).
The nonce is used for constructing transactions.

## Request

```javascript
curl -X GET \
  -H 'Content-Type: application/json' \
  https://api.cinder.cloud/api/ethereum/address/0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2/nonce
```

## Example Response

```json
{
    "nonce": 1,
    "address": "0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2"
}
```

