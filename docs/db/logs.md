# Logs collection

## Data representation

```javascript
    {
        "rqId": UUID4,
        "rqDt": datetime,
        "request": json,
        "response": json
        "actions":[{
            "action": string,
            "request": json,
            "response": json
        }]
    }
```

## Example

```javascript
    {
        "rqId": "f821ebc7-0032-44fd-8dd8-c3f7e7e3e367",
        "rqDt": "2021-01-18T23:59:59+07:00",
        "request": {},
        "response": {},
        "actions"[{
            "action": "payment_paypal"
            "request": {},
            "response": {}
        }]
    }
```
