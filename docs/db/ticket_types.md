# ticketTypes collection

## Data representation

```javascript
    {
        "UID": UUID4,
        "name": string,
        "description": string,
        "createdDt": datetime,
        "status": string Enum, // avaliable, sold out
        "price": number,
        "quantity": number,
        "ticketSold": number,
        "eventId": UUID4,
        "fixedSeat": boolean
        "seats": [string] // can empty
    }
```

## Example

```javascript
    {
        "UID": "f765a8ec-de45-4fc9-91e4-133a9168b52f",
        "name": "early bird",
        "description": "lorem ipsum",
        "createdDt": "2021-01-18T22:30:00+07:00",
        "status": "avaliable"
        "price": 100.00,
        "quantity": 10,
        "ticketSold": 5,
        "eventId": "bdd8f769-ad4f-4be1-8dbd-d759043662c5",
        "fixedSeat": True
        "seats": ["A1", "B1", "B2"] // can empty
    }
```
