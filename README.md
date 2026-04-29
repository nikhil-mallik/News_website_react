# News Taja Khabar - News App

A modern news application built with React that fetches and displays latest news headlines across multiple categories using the NewsAPI.

## Features

- **Multiple News Categories**: Browse news by Business, Entertainment, General, Health, Science, Sports, and Technology
- **Infinite Scroll**: Automatically load more articles as you scroll down
- **Real-time Updates**: Fetches latest news headlines from NewsAPI
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Navigation**: Easy-to-use navigation bar to switch between categories
- **Loading Indicator**: Smooth loading experience with spinner animation
- **Progress Tracking**: Visual progress indicator while fetching data

## Tech Stack

- **React 19.2.5**: Frontend framework
- **React Router DOM 7.14.2**: Client-side routing
- **React Infinite Scroll Component 7.2.0**: Infinite scrolling functionality
- **Bootstrap 5**: Responsive UI components
- **NewsAPI**: Real-time news data

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm (v6 or higher)
- NewsAPI key (Get it free from [newsapi.org](https://newsapi.org))

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd newsapp
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the project root and add your NewsAPI key:
```env
REACT_APP_API_KEY=your_newsapi_key_here
```

4. Start the development server:
```bash
npm start
```

The app will open at [http://localhost:3000](http://localhost:3000)

## Available Scripts

### `npm start`
Runs the app in development mode. Open [http://localhost:3000](http://localhost:3000) to view it in your browser. The page reloads when you make changes.

### `npm run build`
Builds the app for production to the `build` folder. The build is optimized for the best performance.

### `npm test`
Launches the test runner in interactive watch mode.

## Project Structure

```
src/
├── components/
│   ├── NavBar.js         # Navigation bar component
│   ├── News.js           # Main news display component
│   ├── NewsItem.js       # Individual news item card
│   ├── Spinner.js        # Loading spinner component
│   └── Constant.js       # Constants and default values
├── App.js                # Main app component with routing
├── App.css               # App styles
├── index.js              # React entry point
└── index.css             # Global styles
```

## Usage

1. Navigate to different news categories using the navigation bar
2. Browse through articles on the current page
3. Scroll down to load more articles automatically
4. Click "Read More" to view the full article on the news source website

## Environment Variables

Create a `.env` file in the root directory:

```env
REACT_APP_API_KEY=your_newsapi_key_here
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is open source and available under the MIT License.

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
