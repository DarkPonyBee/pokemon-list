# Frontend Coding Interview Test

## Description

This repository implements a Pokémon data table with pagination and loading skeleton.

### Demo

https://github.com/user-attachments/assets/0031f08b-dceb-4e57-ba95-2ef0e6454408

### Key Features:

1. **Pokémon Data Fetching:**
   - Utilizes the PokeAPI to fetch Pokémon data
   - Implements data validation using Zod schemas

2. **Data Table:**
   - Displays Pokémon information in a responsive table
   - Shows name, image, and types for each Pokémon

3. **Pagination:**
   - Adds client-side pagination with "Previous" and "Next" buttons
   - Updates URL parameters for page navigation

4. **Loading State:**
   - Implements a skeleton loading component for better UX
   - Displays while data is being fetched

5. **Styling:**
   - Uses Tailwind CSS for responsive and clean design

### Technical Details:

- Built with Next.js 14 and React 18
- Utilizes TypeScript for type safety
- Implements server-side rendering for initial data fetch
- Configures Next.js Image component for optimized image loading

### Testing Instructions:

1. Clone the repository
2. Run `npm install` to install dependencies
3. Start the development server with `npm run dev`
4. Navigate to `http://localhost:3000` to view the application
5. Test pagination by clicking "Next" and "Previous" buttons
6. Verify that the loading state appears when changing pages
