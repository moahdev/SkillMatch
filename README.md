# SkillMatch
This project implements a real-time task challenge platform


🧩 Project Description:

SkillMatch is a full-stack web application that connects admins and players through a real-time category-based challenge system.

Admins manage categories and challenges, while players select which categories they want to follow.
Once a player selects categories, they automatically receive all associated challenges — including an expiration date — in real time.

✅ Admin Dashboard

* The admin dashboard provides full control over the content and structure of the challenge system.

Main Features

Manage Categories:

* Create, edit, delete categories  (e.g., “Coding” , "swiming","running", “Fitness”, “Photography”).

* Challenges should contain - name , description , image(optional), exparation date and related category

* When a challenge is created or updated in a category, all players who follow that category receive it instantly.

* Player Statistics - table that shows for each user how many challenges he completed, and how many for each category.

✅ Player Dashboard

* The player interface focuses on receiving and completing challenges in real time.

Main Features:

* Login and Sign up page
  
* When user sign up he chooses between 3 to 5 favoured categories for which he wants to receive challenges about.

* Automatically receive all challenges from selected categories.

* Mark challenges as completed

* Progress Tracking - View challenge history and completion status

✅ Technical Requirements

* Frontend -  React (Vite)

* Responsive, clean UI (Recommended MUI)

* Real-time updates for users when challenges expired / created (the challenegs must appear for each user if their selected categories overlap with the ones of the challenges)

* Backend - NestJS (TypeScript)

* show toast/ alert notifications
# Note:

Think about which information need to be saved in a DB , if so which DB is the most suitble here.

