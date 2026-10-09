# Task 4: Badminton Court Booking System

## The Goal
The hunger games of campus amenities. Develop a time-slot reservation system for a shared campus resource. This evaluates your logic for handling dates, times, and preventing data conflicts on the backend. If two people book the court at the same time and your app allows it, you are responsible for the physical altercation that follows.

## The Tasks
1. **Slot Display:** Show a schedule for a single day, divided into 1-hour time slots.
2. **Availability Status:** Clearly differentiate between "Available" and "Booked" slots.
3. **Booking Action:** Allow a user to select an available slot and book it.
4. **Conflict Prevention (Backend):** The server MUST verify that a slot is not already taken before confirming a new booking. If two people try to book the exact same slot simultaneously, only one should succeed. 

## Constraints & Technical Details
* **Frontend:** React.
* **Backend/Database:** Required. Django or Ruby on Rails with SQLite3.
* **Time Handling:** Handle time slots cleanly in your database schema. Do not worry about global timezones for this task; assume IST. We are not booking courts in London.
* **Documentation:** Required. You must explicitly explain the logic you used to prevent double-booking in your submission file. 

## Design Rules
* **Visual Clarity:** Use color coding (green for available, gray/red for booked, disabled cursor on booked slots). Color code it so even a sleep-deprived engineering student can understand it.
* **Confirmation:** Provide a modal or an alert to confirm the booking details before finalizing.