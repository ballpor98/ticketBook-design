# ticketBook-design

repo for ticket booking system design

## Task

Design the software system TicketBook having these requirements
Ticket booking system for event

* Tickets have multiple prices based on ticket types
* Some events have seating (fixed seat), some don't
* The number of tickets is limited and must not be overbooked  
* Support both synchronous payment methods and asynchronous payment methods  
* Can handle the consistent traffic of 20k req/sec and peak traffic of 40k req/sec

Expected Output

* Tech Stack
* System Diagram
* API Documentation
* Database Design

## Result

### Tech stack

![alt text](https://raw.githubusercontent.com/ballpor98/ticketBook-design/cb8706b8611b2c2985498c7e0d87b273f3ab4ced/assets/tech_stack.jpeg "tech stack")

### System Diagram

![alt text](https://raw.githubusercontent.com/ballpor98/ticketBook-design/cb8706b8611b2c2985498c7e0d87b273f3ab4ced/assets/system_architecture.jpeg "tech stack")

### API Documentation

API Documentation [Here](https://htmlpreview.github.io/?https://github.com/ballpor98/ticketBook-design/blob/main/docs/api/api_spec.html)  
 `*` **Not finish**

### Database Design

[Attendees collection](./docs/db/attendees.md)  
[Event collection](./docs/db/event.md)  
[Tickets collection](./docs/db/ticket_types.md)  
[Orders collection](./docs/db/orders.md)  
[Logs collection](./docs/db/logs.md)  
