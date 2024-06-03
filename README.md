# Morning News (frontend)
## Presentation
MorningNews is an application that allows you to display the latest news from The Verge. You can also save your favorite articles and find them by logging into your account.
You can have a complete preview of the application by using this link:
```
https://morningnews-frontend-blush.vercel.app/
```
![MorningNews](https://github.com/PalomaAubeau/morningnews-backend/assets/154338327/06610301-7e11-414c-98f0-6b30ad11ecb4)

## Features
Latest News Display: View the most recent articles from The Verge with headlines, summaries, and author.\
Save Favorites: Save your favorite articles to easily find them later, and hide the ones you don't want to see.\
User Accounts: Log in to your account to access your saved articles.\

## Technologies Used
### Frontend:
CSS, JavaScript
Framework: React.js

### Backend:
Node.js
Express.js

### API:
The Verge API

### Database:
MongoDB


## Installation
### Prerequisites
Node.js and npm (or yarn) should be installed on your machine.

### Installation Steps
Create a folder with two separated folders into it: one for the backend part, and the other one for the frontend part.
### 1. Clone repositories into  separated folders:

BACKEND:
```
https://github.com/PalomaAubeau/morningnews-backend.git
```
FRONTEND:
```
https://github.com/PalomaAubeau/morningnews-frontend.git
```
Open two terminals to retrieve the backend and frontend parts in parallel.
### 2. Install dependencies for both frontend and backend:

```
cd backend
npm (or yarn) install
```
```
cd ../frontend
npm (or yarn) install
```

### 3. Configure environment variables:
Create a .env file in the backend folder.
Add your required keys and configurations.
Example:
```
NEWS_API_KEY=your_api_key
```
```
CONNECTION_STRING=your_connection_string_for_mongoDB
```
### 4. Start the application:
Backend (you can use npm or yarn):
```
cd backend
yarn start
```
Frontend (you can use npm or yarn):
```
cd frontend
yarn dev
```

## Acknowledgements
Thanks to The Verge for their content.
