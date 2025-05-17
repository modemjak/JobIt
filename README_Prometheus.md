# Prometheus: Add README for JobIt

## Project Overview

JobIt is a comprehensive job search and exploration platform designed to simplify the job hunting process for professionals. The application provides an intuitive and feature-rich solution for discovering, analyzing, and understanding job opportunities across various industries.

### Key Features

- **Comprehensive Job Listings**: Browse the latest job posts from top and featured companies
- **Advanced Job Search**: Filter jobs by location, employment type, career level, and salary range
- **Detailed Job Insights**: Access in-depth information about job requirements, responsibilities, and company backgrounds
- **Salary Estimation**: Get estimated salary ranges for specific roles based on user input and location
- **Location-Based Results**: Utilize geolocation API to provide localized job recommendations
- **Responsive Design**: Seamless user experience with light and dark theme options

### Problem Solved

JobIt addresses the challenges job seekers face by consolidating job information, providing context-rich job details, and offering tools to make informed career decisions. The platform bridges the gap between job seekers and potential employers by presenting comprehensive, easily digestible job information.

## Getting Started, Installation, and Setup

### Prerequisites

Before you begin, ensure you have the following installed:
- [Node.js](https://nodejs.org/) (version 16 or later)
- [npm](https://www.npmjs.com/) (comes with Node.js)
- [Git](https://git-scm.com/)

### Installation Steps

1. Clone the repository:
```bash
git clone https://github.com/DevTaehong/Jobit.git
cd Jobit
```

2. Install dependencies:
```bash
npm install
```

3. Set up environment variables:
Create a `.env` file in the project root with the following keys:
```
X_RAPID_API_KEY=your_rapid_api_key
COMPANIES_API_KEY=your_companies_api_key
NEXT_PUBLIC_GEOCODE_API_KEY=your_geocode_api_key
```

### Running the Application

#### Development Mode
To run the application in development mode:
```bash
npm run dev
```
The application will be available at `http://localhost:3000`

#### Production Build
To create a production build:
```bash
npm run build
npm start
```

### Recommended Development Workflow
1. Start the development server
2. Open `http://localhost:3000` in your browser
3. Make changes to the code, and the page will automatically reload

### Supported Platforms
- Windows
- macOS
- Linux

### Additional Notes
- Ensure all environment variables are correctly configured
- The application requires an active internet connection for fetching job data