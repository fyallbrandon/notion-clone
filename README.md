# React + TypeScript + Vite

![Notion clone](https://github.com/fyallbrandon/notion-clone/assets/156007704/d5e8ce62-52f3-47aa-99df-ca058ff8cb44)

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
