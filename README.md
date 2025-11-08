# solid-octo-broccoli
  
  |--Project Description and Purpose
  └──What problem does your project solve?
    └──It's a Event Planner (create events, holidays, RSVP, reminders)
|Who is the target user?
 
|What makes it interesting or unique?
└──Planned Backend
  └──Choose your stack:
    └──AWS Lambda + API Gateway + DynamoDB
|--List the main models/tables or DynamoDB items you’ll need.
  └──API Routes and Methods
     └──POST / Events → create a new events 
     └──PUT /Events/:id → edit a event
     └──DELETE /Events/:id → delete a event
|--Frontend Features and Pages
  └──What pages will your frontend include (one page minimum)?
     └──Home page with featured content
     └──Login page
     └──Dashboard (shows user data)
     └──Calender
|--Authentication Flow
Will users log in with email/password (JWT)?
Or will you use Amazon Cognito or another OIDC provider?
Which routes/pages will be protected?
└──Deployment Plan
  └──Where will you host your frontend and backend?
    └──Frontend → AWS S3 + CloudFront
    └──Backend → AWS Lambda + API Gateway
    └──Database → DynamoDB

Capstone-api/
  ├── capstone-plan.md
  ├── src/
   |-- Frontend
    |--Apps.jsx
    |--Apps.css
    |--index.css
    |--Main.jsx
  └── package.json
  ├──package-lock.json
  ├──Memes Setup 
  ├──package.json
  ├──Memes Setup 
  ├──postcss.config.js
  ├──tailwind.config.js
  ├──AWS set up
  ├──vite.config.js
