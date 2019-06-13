---
title: "Listen For Events"
---

Listen for live events which are emitted from a contract. **Authentication for this endpoint isn't necessary.**

## Request Endpoint
```javascript
wss://api.cinder.cloud/ws/app/contract/event
```

## Request body 

| argument| description             |
|---------|-------------------------|
| abi     | ABI of the contract     |
| address | Address of the contract |
| event   | name of the event       |

## Subscribe Topic
```javascript
wss://api.cinder.cloud/ws/user/queue/contract-events
```

## Subscription Topic Response Example:

```json
{
  "values": {
        "from":"0xf3c461ecc55239776e026efa0ca2405e681ac7ef",
        "to":"0xee37f338220479c8f652e3557f02513bdb11c160",
        "value":1002009990000000000000
    }
}
```
