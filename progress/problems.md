# Problems Identified and Proposed Solutions

The following problems were identified during the analysis and design of the proposed Online Cinema Ticket Booking Management System. Since this project is an assignment and does not include a working implementation, these are proposed problems and solutions rather than actual software defects.

---

## Problem 1 – Seat Availability

### Problem

A user may try to select a seat that has already been booked for the selected movie show.

### Proposed Solution

The system should check the availability status of each seat before confirming the booking. Seats that are already booked should be displayed as unavailable and should not be selectable.

### Related Test Case

TC07 – Booked Seat

### Status

Identified – Solution Proposed

---

## Problem 2 – Invalid Booking Details

### Problem

A user may attempt to book a ticket without providing all the required booking information.

### Proposed Solution

The system should validate the booking details before confirmation. If any required information is missing or invalid, an appropriate validation message should be displayed.

### Related Test Case

TC12 – Invalid Booking

### Status

Identified – Solution Proposed

---

## Problem 3 – Conflicting Show Timings

### Problem

Two shows may be scheduled for the same screen at overlapping times.

### Proposed Solution

The system should check the existing show schedule before adding a new show. Conflicting show timings should not be allowed for the same screen.

### Related Test Case

TC13 – Show Timing

### Status

Identified – Solution Proposed

---

## Problem 4 – Invalid Data

### Problem

Users or administrators may enter invalid or incomplete information into the system.

### Proposed Solution

Input validation should be applied to important fields such as names, email addresses, dates, show timings and other required information. Invalid data should generate appropriate error messages.

### Related Test Case

TC14 – Database Validation

### Status

Identified – Solution Proposed

---

## Problem 5 – Payment Validation

### Problem

Incorrect or incomplete payment information may be entered during ticket booking.

### Proposed Solution

The system should validate the required payment information before confirming the booking. The ticket should only be confirmed after successful payment processing.

### Related Test Case

TC09 – Payment

### Status

Identified – Solution Proposed

---

## Problem 6 – Duplicate Booking

### Problem

A user may attempt to book the same seat more than once for the same movie show.

### Proposed Solution

The system should verify seat availability immediately before confirming the booking and prevent duplicate seat reservations.

### Related Test Case

TC07 – Booked Seat

### Status

Identified – Solution Proposed
