# Task 3: The Mess Management System

## The Goal
Democracy dies in the mess hall. Your goal is to build a dashboard to streamline hostel mess operations, bringing order to the chaos of weekly menus. This project evaluates your ability to model relational data, handle basic interactions like voting, and manage UI layouts that do not induce headaches.

## The Tasks
1. **Weekly Menu View:** Display the mess menu organized by days of the week (Breakfast, Lunch, Snacks, Dinner).
2. **Sunday Special Voting:** Implement a voting mechanism where users can upvote their preferred "Sunday Special" from a list of options. Let the people choose their paneer.
3. **Feedback Form:** A simple form attached to today's menu for students to rate the food (1-5 stars) and leave comments that the mess contractor will probably ignore.
4. **One Vote Per User:** Ensure a user can only cast one vote for the Sunday Special. Voter fraud is strictly prohibited.

## Constraints & Technical Details
* **Frontend:** React.
* **Backend/Database:** Required. Use Django or Ruby on Rails with SQLite3. 
* **Data Modeling:** You will need tables/models for MenuItem, Vote, and a mock User.
* **Authentication:** Mock it. You can hardcode a user ID in the frontend requests to simulate a logged-in student. 
* **Documentation:** Required. Include an entity-relationship diagram (ERD) or a simple text explanation of your database models, alongside setup instructions.

## Design Rules
* **Navigation:** Use a tabbed interface or an accordion to switch between days of the week smoothly.
* **Interactivity:** The voting button should provide immediate visual feedback. Make the UI look appetizing, even if the food on Thursday night is not.