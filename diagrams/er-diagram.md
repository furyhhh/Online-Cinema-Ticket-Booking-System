# ER Diagram

## Main Entities

- User
- Movie
- Theatre
- Screen
- Show
- Seat
- Booking
- Payment
- Ticket

## Relationships

- A user can make multiple bookings.
- A movie can have multiple shows.
- A theatre can contain multiple screens.
- A screen can contain multiple seats.
- A show is associated with a movie and a screen.
- A booking can contain one or more seats.
- A booking is associated with a payment.
- A confirmed booking generates a ticket.
