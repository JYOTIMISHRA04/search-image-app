# Image Search App

This is a React-based Image Search application that allows users to search for images using a search query. The application displays search results with pagination and shows detailed information about each image.

## Features

- Search for images using a query
- Display image results in a grid format
- Detailed view for selected images, including additional information and social media links
- Responsive design for different screen sizes
- Pagination for browsing through search results
- Clean and intuitive UI with Material-UI components

## Demo

A live demo of the app can be accessed [here](#).

## Technologies Used

- **React.js**: A JavaScript library for building user interfaces.
- **Material-UI**: A popular React UI framework for building modern and responsive web applications.
- **React Hooks**: For managing state and side effects.
- **Axios**: To fetch image data from the API.
- **Custom Hooks**: For handling data fetching and state management.
- **JavaScript (ES6+)**: For core functionality and logic.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/image-search-app.git
 Navigate to the project directory:

bash
Copy code
cd image-search-app
Install the dependencies:

bash
Copy code
npm install
Run the development server:

bash
Copy code
npm start
Open your browser and visit http://localhost:3000 to view the app.




## How It Works

1. Search Input: Users can enter a search term in the search bar, which triggers an API request to fetch relevant images.

2. Image Results: The images are displayed in a grid format. Clicking on an image opens a modal with detailed information.

3. Pagination: Users can navigate through different pages of results.

4. Detailed View: When an image is clicked, additional image information (e.g., title, description) is displayed in a modal.


## API Integration
This app fetches images using an external API (e.g., Unsplash or Pixabay). You can update the API_URL in the /data folder with your API endpoint.

