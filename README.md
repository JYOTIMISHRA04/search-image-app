# Image Search App

This is a React-based Image Search application that allows users to search for images using a search query. The application displays search results with pagination and shows detailed information about each image.

## Access App here - https://search-image-app-phi.vercel.app/

## Features

- Search for images using a query
- Display image results in a grid format
- Detailed view for selected images, including additional information and social media links
- Responsive design for different screen sizes
- Pagination for browsing through search results
- Clean and intuitive UI with Material-UI components

## Technologies Used

- **React.js**: A JavaScript library for building user interfaces.
- **Material-UI**: A popular React UI framework for building modern and responsive web applications.
- **React Hooks**: For managing state and side effects.
- **Axios**: To fetch image data from the API.
- **Custom Hooks**: For handling data fetching and state management.
- **JavaScript (ES6+)**: For core functionality and logic.

## Getting Started

Follow these instructions to set up the project locally.

### Prerequisites

Make sure you have the following installed:

- **Node.js** (>= 14.x)
- **npm** or **yarn**

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/JYOTIMISHRA04/search-image-app
   ```

2. **Navigate to the project directory:**

   ```bash
   cd search-image-app
   ```

3. **Install the dependencies:**

   Using npm:

   ```bash
   npm install
   ```

   Or using yarn:

   ```bash
   yarn install
   ```

### Running the App

1. **Start the development server:**

   Using npm:

   ```bash
   npm start
   ```

   Or using yarn:

   ```bash
   yarn start
   ```

2. **Open the app in your browser:**

   ```bash
   http://localhost:3000
   ```

### Deployment

The app is deployed on Vercel. To deploy your own version, follow these steps:

1. **Install the Vercel CLI:**

   ```bash
   npm install -g vercel
   ```

2. **Deploy the app:**

   ```bash
   vercel
   ```

## How It Works

1. Search Input: Users can enter a search term in the search bar, which triggers an API request to fetch relevant images.

2. Image Results: The images are displayed in a grid format. Clicking on an image opens a modal with detailed information.

3. Pagination: Users can navigate through different pages of results.

4. Detailed View: When an image is clicked, additional image information (e.g., title, description) is displayed in a modal.


## API Integration
This app fetches images using an external API (e.g., Unsplash or Pixabay). You can update the API_URL in the /data folder with your API endpoint.


##  GIFs:
```bash
![Demo GIF](public\assests\search-image-app.gif)
```


