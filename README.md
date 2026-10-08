# NestFinder — Property Search Frontend

A responsive React/Vite frontend prototype for a property discovery platform.

## Features
- Landing page with login/signup prompts and location search
- Login and signup forms
- Property search and filter UI
- Property cards and detailed property view
- Interactive map using React Leaflet + OpenStreetMap
- User dashboard with preferences and saved properties
- Modular components and React Router navigation
- Mock property data ready to replace with backend API calls

## Run locally
```bash
npm install
npm run dev
```
Then open the local URL shown by Vite.

## Build
```bash
npm run build
```

## Backend integration points
Replace the `properties` array in `src/App.jsx` with API requests. The UI expects property objects containing: `id`, `title`, `city`, `area`, `price`, `beds`, `baths`, `size`, `type`, `lat`, `lon`, `tag`, `desc`, and `amenities`.

## Submission
Suggested GitHub repository name: `nestfinder-property-ui`
Suggested PDF filename: `Wireframes_Prototype_Sanjeev.pdf`
Suggested source archive: `Frontend_Source_Code_Sanjeev.zip`
