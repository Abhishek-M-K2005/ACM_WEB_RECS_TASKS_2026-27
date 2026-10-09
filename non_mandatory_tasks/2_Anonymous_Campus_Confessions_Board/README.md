# Task 2: Anonymous Campus Confessions Board

## The Goal
Create a public, real-time message board where students can post short text snippets anonymously. This is where hopes, dreams, and complaints about the OS professor go to die. This task evaluates your ability to handle forms, manage lists in React, and execute basic POST/GET API operations without breaking a sweat.

## The Tasks
1. **Submission Form:** Create a form with a text area for the confession and a "Submit" button. 
2. **Character Limit:** Enforce a strict 250-character limit. Show a live character counter that aggressively turns red when approaching the limit. 
3. **Confession Feed:** Display submitted confessions in reverse chronological order (newest first) below the form.
4. **Auto-update:** When a new confession is submitted, it should immediately appear at the top of the feed without requiring a page reload. We are not in 2008 anymore.

## Constraints & Technical Details
* **Frontend:** React.
* **Backend/Database:** You can use an in-memory array in your Django/Rails backend, or use SQLite3 to persist the data. If you refresh the server and the drama disappears, that is fine for this tier. You can hardcode or, just use simple database.
* **Authentication:** None required. The board is completely anonymous to protect the guilty.
* **Documentation:** Required. Briefly document your API endpoints (if built) and instructions to spin up the dev server.

## Design Rules
* **Layout:** Card-based UI for the feed. Keep it minimalist and focus on readable typography.
* **Feedback:** Show a brief success toast/notification when a confession is successfully posted so the user knows their rant made it to the void.