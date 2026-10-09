# Task 1: ACM Member Directory

## The Goal
Welcome to the easiest task on the list. Your objective is to build a responsive directory to display club members, allowing users to search and filter through the roster easily. Think of it as a digital yearbook, but for people who actually know how to exit Vim.

## The Tasks
1. **Fetch & Display:** Render a grid of member cards containing their Name, Role (e.g., Executive Member, Web Team, Over-caffeinated Designer), and a profile placeholder.
2. **Search functionality:** Implement a text input that filters the displayed members by name in real-time. If they type "Abhi", they should instantly see everyone who might be Abhishek.
3. **Role Filtering:** Add a dropdown or toggle buttons to filter members by their specific roles. 
4. **Empty State:** Design a clean "No members found" state if a search yields no results. Do not just leave the screen blank and let the user question their life choices.

## Constraints & Technical Details
* **Frontend:** React (Vite/Next.js).
* **Backend/Database:** Backend & db are optional.
* **Documentation:** Required. Include a `README_SUBMISSION.md` explaining how to run your project and any wild assumptions you made.

## Design Rules
* **Mobile-Responsive:** The grid must collapse gracefully to a single column on mobile devices, because nobody opens links on their laptop anymore.
* **Styling:** Use Tailwind CSS or plain CSS. Make it look like we actually have a design team.