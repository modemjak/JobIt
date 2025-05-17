# Prometheus: Add README for JobIt

## Project Overview

JobIt is a comprehensive job search and exploration web application designed to simplify the job hunting process. The platform provides users with an intuitive and feature-rich experience for discovering, researching, and understanding job opportunities.

### Key Features
- Comprehensive Job Search: Explore job listings with advanced filtering options including location, employment type, job level, and salary range
- Detailed Job Insights: Access in-depth information about job postings, including company details, job requirements, and responsibilities
- Company Exploration: Browse job openings for specific companies and discover similar companies in the industry
- Salary Estimation: Utilize an interactive tool to estimate salary ranges for different job roles
- Location-Based Results: Leverage geolocation API to provide personalized job recommendations and salary estimates
- Responsive Design: Seamless user experience with light and dark theme options

### Core Functionality
The application empowers job seekers by providing a centralized platform that goes beyond traditional job listings. Users can not only search for jobs but also gain comprehensive insights into potential career opportunities, company cultures, and compensation expectations.

## Getting Started, Installation, and Setup

### Prerequisites

Before you begin, ensure you have the following installed:
- [Node.js](https://nodejs.org/) (version 18.x or later)
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
Create a `.env.local` file in the project root and add the following variables:
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

### Additional Configuration

- The application uses Next.js with TypeScript
- State management is handled with Redux
- Styling is done using Tailwind CSS
- Dark and light themes are supported via `next-themes`

### Recommended Development Environment

- Use Visual Studio Code with the following recommended extensions:
  - ESLint
  - Prettier
  - Tailwind CSS IntelliSense