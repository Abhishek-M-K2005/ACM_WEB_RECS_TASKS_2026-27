# Task 5: ACM Merch Store

## The Goal
Capitalism at its finest. Build a simulated storefront for a highly anticipated club merch drop (example: 50 limited-edition hoodies). This is an advanced task that tests your ability to handle race conditions, database transactions, and component state under pressure. Selling 50 hoodies to 5000 students without blowing up the database is the true test of a backend developer.

## The Tasks
1. **Product Display:** Show the item, its price, and a live "Stock Remaining" counter.
2. **The Buy Button:** A button to purchase the item that disables itself immediately and ruthlessly when stock hits zero.
3. **Concurrency Handling (The Core Challenge):** Ensure that if 100 requests come in simultaneously for the last 5 hoodies, the database strictly halts at 0 and does not result in negative stock. Ghost inventory is a crime.
4. **Simulate Load:** Write a small script or button on the frontend that fires 10 concurrent "Buy" requests to prove your backend actually prevents overselling.

## Constraints & Technical Details
* **Frontend:** React.
* **Backend/Database:** Required. Django or Ruby on Rails. SQLite3 is acceptable, but you must utilize database transactions, atomic updates (like Django's F() expressions or Rails' update_counters), or row-level locking.
* **Documentation:** Required. You must deeply and clearly document how you achieved atomic transactions and prevented the race condition in your backend. If you just subtract 1 and pray, you will fail.

## Design Rules
* **Urgency:** Design the UI to look like a hype drop. Use a dark theme, countdown timers, or progress bars for the stock limit. Make them sweat for the merch.
* **Error Handling:** If a user clicks buy but the stock just ran out, show a graceful "Sold Out!" error message rather than a 500 Internal Server Error stack trace.