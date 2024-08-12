# Queue - Notion Clone App

<img width="1272" alt="Screen Shot 2024-08-11 at 7 41 26 PM" src="https://github.com/user-attachments/assets/19f9bc73-8ca4-43f0-a151-cb0c55a76f28">


## Features

- Authentication
- Create, update and delete notes
- Create, update and delete images
- Reorder notes
- Change page title
- Change page cover image
- Create, update and delete pages


## Tech Stack
The app is generated with Vite and uses the following technologies:

- React
- TypeScript
- DndKit (drag and drop)
- CSS Modules
- Supabase (database, authentication, storage)
- Netlify (hosting)


## Running the app
To run the app locally, you need to create a Supabase project and add the following environment variables to your `.env` file:

```
VITE_SUPABASE_URL=""
VITE_SUPABASE_API_KEY=""
```

Then run the following commands:

```
npm install
npm run dev
```
