# events collection

## Data representation

```javascript
    {
        "UID": UUID4,
        "name": string,
        "description": string,
        "createdDt": datetime,
        "changedDt": datetime,
        "status": string Enum, // created, start, end, cancel
        "startDt": datetime,
        "ticketTypes":[{
            "UID": UUID4,
            "name": string,
            "status": string Enum,
            "quantity": number,
            "ticketSold": number
        }],
        "capacity": number
    }
```

## Example

```javascript
    {
        "UID": "bdd8f769-ad4f-4be1-8dbd-d759043662c5",
        "name": "event101",
        "description": "lorem ipsum",
        "createdDt": "2021-01-18T22:00:00+07:00",
        "changedDt": "2021-01-18T23:59:59+07:00",
        "status": "created"
        "startDt": "2021-01-22T18:00:00+07:00",
        "ticketTypes":[{ 
            "UID": "f765a8ec-de45-4fc9-91e4-133a9168b52f",
            "name": "early bird",
            "status": "avaliable",
            "quantity": 10,
            "ticketSold": 5,
        }],
        "capacity": 100
    }
```
