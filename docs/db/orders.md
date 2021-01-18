# Orders collection


## Data representation

```javascript
    {
        "UID": UUID4,
        "createdDt": datetime,
        "changedDt": datetime,
        "status": string Enum, // created, expired, success, fail
        "email": email,
        "costs":{
            "amount": number,
            "items": [{
                "ticketTypeId": UUID4,
                "name": string,
                "seat": string,
                "price": number
            }]
        },
        "eventId": UUID4,
        "expiryDt": datetime
    }
```

## Example

```javascript
    {
        "UID": "80c7c98b-a0c7-460b-829b-6a210c4d3a7b",
        "createdDt": "2021-01-18T22:00:00+07:00",
        "changedDt": "2021-01-18T23:59:59+07:00",
        "status": "created"
        "email": "nine.a@gmail.com",
        "costs":{
            "amount": 100.00,
            "items": [{
                "ticketTypeId": "f765a8ec-de45-4fc9-91e4-133a9168b52f",
                "name": "early bird",
                "seat": "A1",
                "price": 100.00
            }]
        },
        "eventId": "bdd8f769-ad4f-4be1-8dbd-d759043662c5",
        "expiryDt": "2021-01-19T22:30:00+07:00"
    }
```
