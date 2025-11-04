# SkillMatch
This project implements a real-time task challenge platform


🧩 Project Description:

SkillQuest is a full-stack web application that connects admins and players through a real-time challenge system.

Admins can create tasks in various categories and assign them to selected players.
Players can log in, choose which categories they’re interested in, and receive challenges instantly — in real time — directly in their dashboard.

The platform includes two main portals:

Admin Panel – for managing users, categories, and challenges.

Player Dashboard – for receiving, completing, and tracking challenges.

🚀 Core Features
 Admin Panel

Login / authentication.

Create, edit, and delete challenges.

Define categories (e.g., “Coding”, “Fitness”, “Photography”).

Assign challenges to specific players or to category groups.

Send challenges in real time.

View players ompletion stats/rate on a table or chart.

Player Dashboard

Login / registration.

Select preferred categories.

Receive challenges in real time as soon as the admin sends them.

Accept or decline a challenge.

Mark challenges as completed .

View progress and history of challenges 

⚙️ Technical Requirements:

React (with Vite).

Real-time communication

Responsive and clear UI design

NestJS (TypeScript).

REST API for authentication, challenge management, etc.

Real-time events for challenge delivery and updates.

Note:
Think about which information need to be saved in a DB , if so which DB is the most suitble here.

Think about the request that need a real time manegment and which does not .
