# Car Rental App

## Description
This is a React-based car rental application that allows users to browse car models, view details, and mark cars as favorites using a star icon.

## Prerequisites
Ensure you have the following installed on your machine:
- Node.js (v14 or higher)
- npm (v6 or higher)

## Getting Started

### 1. Clone the Repository
Clone the project to your local machine:
```bash
git clone <repository-url>
cd <repository-folder>

### 2. Install Dependencies
Install the required dependencies:
npm install

### 3. Run the Application in Development Mode
npm run dev

The application will be available at `http://localhost:5713`.

### 4. Build for Production
To create a production build, run:
npm run build

This will generate a dist folder containing optimized files.

5. Serve the Production Build Locally
To test the production build locally:
1. Install the serve package globally:
npm install -g serve
2. Serve the dist folder:
serve -s dist
3. Open the provided URL in your browser.

Project Structure
- src/components: Contains reusable React components like CarCard, SearchBar, and Footer.
- src/pages: Contains page-specific components like Home and CarDetailsModal.
- src/styles: Contains shared styled-components for consistent styling.
- src/assets: Contains static assets like images and icons.
- src/App.js: Main application component that sets up routing and state management.

Deployment
To deploy the app, upload the contents of the dist folder to a static hosting service like Netlify, Vercel, or AWS S3.


Dependencies
React
Styled-components
React-icons
Vite

Install dependencies using npm:
npm install react styled-components react-icons vite
```

Features
- Car browsing: Users can view a list of car models with images and details.
- Car details: Users can click on a car to view more information in a modal.
- Favorites: Users can mark cars as favorites using a star icon.
- Search: Users can search for cars by name.
- Sorting: Users can sort cars by name or price.

To run locally, use the following command:
npm run dev
```