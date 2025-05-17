# Prometheus: Add README for JobIt

## Project Overview

JobIt is a comprehensive job search and exploration web application designed to simplify the job hunting process for professionals. The platform offers an intuitive and feature-rich interface that helps users discover, research, and understand job opportunities across various industries.

### Key Features
- Comprehensive Job Search: Explore job listings with advanced filtering options including location, employment type, job level, and salary range
- Detailed Job Insights: View in-depth information about job postings, including company details, job requirements, and responsibilities
- Company Exploration: Browse job openings for specific companies and discover similar companies based on search criteria
- Salary Estimation: Utilize an interactive tool to estimate salary ranges for different job roles
- Geolocation-Powered Results: Receive job recommendations and salary estimates tailored to the user's location
- Adaptive User Experience: Toggle between light and dark themes for comfortable browsing

### Core Benefits
- Streamlined Job Discovery: Centralized platform for finding and understanding job opportunities
- Informed Decision Making: Comprehensive job and company information at your fingertips
- Personalized Job Search: Flexible filtering and location-based recommendations
- User-Friendly Design: Intuitive interface with customizable viewing preferences

## Getting Started, Installation, and Setup

### Prerequisites

Before you begin, ensure you have the following installed:
- [Node.js](https://nodejs.org/) (version 18 or later recommended)
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

### Configuration

Create a `.env.local` file in the project root and add the following environment variables:
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

### Key Features to Explore
- Job search with advanced filters
- Company job listings
- Salary estimates
- Light and dark mode themes

### Browser Compatibility
- Modern browsers (Chrome, Firefox, Safari, Edge)
- Responsive design for mobile and desktop