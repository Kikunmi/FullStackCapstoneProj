Capstone Project Proposal
Smart Travel Planner & Itinerary Builder
Stack Focus
This project will be an evenly focused full stack web application, balancing frontend user experience with backend API design, authentication, and data persistence.
Project Type
Web Application accessible through modern browsers.
Project Goal
The goal of this project is to help users plan and organize trips in one centralized platform. The application will allow users to search destinations and attractions, create trips, and build structured day by day itineraries with notes.
By combining external travel data with user specific planning data, the app aims to reduce the need to juggle multiple tools (notes apps, spreadsheets, bookmarks) during trip planning.
User Demographic
Primary users include:
•	Leisure travelers planning vacations or short trips
•	Users who prefer structured, organized itineraries
•	Travelers who want to save, revisit, and update trip plans over time
The application is designed for non technical users who value clarity, simplicity, and organization.
Data & API Strategy
The application will use a hybrid data approach:
•	External Data: A travel or places API (to be finalized in Step Three) to retrieve destination and attraction information such as names, categories, and basic descriptions.
•	Internal Data: A custom backend API and database to store user specific data, including users, trips, daily itineraries, saved attractions, and notes.
The specific API provider is not finalized at this stage, which aligns with Step Two guidelines; this proposal defines the type of data and usage rather than locking into an implementation prematurely.
Planned Tech Stack
•	Frontend: React
•	Backend: Node.js with Express
•	Database: MongoDB
•	Authentication: Secure user authentication with protected routes
•	Deployment: 
o	Application hosted on Render
o	Database hosted on MongoDB Atlas (free tier)
Project Approach
Database Schema (High Level)
Planned core entities include:
•	User – authentication and ownership of trips
•	Trip – destination details and metadata
•	TripDay – day by day organization within a trip
•	ItineraryItem – attractions, notes, and ordering per day
This schema supports structured itinerary building while remaining flexible for iteration.
Potential API Challenges
•	Inconsistent or incomplete data from external APIs
•	Rate limits on free API tiers
•	Network or API request failures
These will be mitigated through defensive data handling, graceful error messaging, and caching minimal data for saved itinerary items.
Sensitive Information
Sensitive data will include user credentials. Passwords will be securely handled, environment variables will be used for secrets, and authenticated routes will be protected.
Core Functionality (MVP)
•	User registration and login
•	Create, view, edit, and delete trips
•	Search destinations and attractions via external API
•	Build and edit day by day itineraries
•	Add notes to itinerary items
•	Persist trip data across sessions
User Flow
1.	User signs up or logs in
2.	User creates a new trip from the dashboard
3.	User searches attractions for the destination
4.	User adds attractions to specific trip days
5.	User views and edits the itinerary by day
6.	User returns later to revisit or update saved trips
Beyond CRUD & Stretch Goals
Beyond Basic CRUD:
•	Day by day itinerary structure with ordered items
•	Transformation of external data into persistent, user specific plans
Stretch Goals:
•	Map view for itinerary items (if location data is available)
•	Shareable, read only trip links
•	Saved attractions library reusable across trips
Stretch goals are optional and will only be implemented if time allows.
Summary
This project proposes a realistic yet challenging full stack application that emphasizes thoughtful data modeling, meaningful API integration, and clear user experience. The scope is intentionally designed to be achievable within the capstone timeframe while still producing a portfolio worthy project.

