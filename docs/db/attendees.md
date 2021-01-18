# Attendees collection

## Data representation

```javascript
    {
        "UID": UUID4,
        "createdDt": datetime,
        "changedDt": datetime,
        "status": string Enum, // created, attended
        "eventId": UUID4,
        "orderId": UUID4,
        "ticket":{ 
            "UID": UUID4,
            "name": string,
            "seat": string
        },
        "profile": {
            "name": string,
            "email": email,
            ...
        }
    }
```

## Example

```javascript
    {
        "UID": "89c18d96-8e34-4866-a3e5-69f6a6edfff8",
        "createdDt": "2021-01-18T22:00:00+07:00",
        "changedDt": "2021-01-18T23:59:59+07:00",
        "status": "created"
        "eventId": "bdd8f769-ad4f-4be1-8dbd-d759043662c5",
        "orderId": "80c7c98b-a0c7-460b-829b-6a210c4d3a7b",
        "ticket":{ 
            "name": "early bird",
            "seat": "A1"
        },
        "profile": {
            "name": "nine a",
            "email": "nine.a@gmail.com",
            ...
        }
    }
```
