# PlantBot Plant Care Chatbot

## Project Description
PlantBot is a static HTML website designed to provide users with plant care tips and advice through an interactive chatbot interface. The website is optimized for deployment on Vercel, allowing for seamless updates and scalability.

## Features
- Interactive chatbot for plant care advice
- Responsive design for mobile and desktop
- Easy deployment on Vercel
- Static HTML for fast loading times

## Setup Instructions

### Prerequisites
- Ensure you have [Node.js](https://nodejs.org/) and [Vercel CLI](https://vercel.com/download) installed on your machine.

### Steps
1. **Clone the Repository**: Clone the project repository from GitHub to your local machine.
2. **Navigate to the Project Directory**: Use the terminal to navigate to the project directory.
3. **Install Dependencies**: Run `npm install` to install any necessary dependencies.
4. **Deploy to Vercel**: Use `vercel` command to deploy the site.

## Deployment Instructions
To deploy the PlantBot Plant Care Chatbot on Vercel, follow these steps:
1. **Install Vercel CLI**: Ensure you have the Vercel CLI installed by running `npm install -g vercel`.
2. **Login to Vercel**: Use `vercel login` to authenticate your Vercel account.
3. **Deploy the Project**: Navigate to the project directory and run `vercel` to deploy the site.

## Configuration Details
The project uses a `vercel.json` file for configuration:
- **Builds**: Uses `@vercel/static` for serving static HTML files.
- **Routes**: Redirects all requests to `index.html` for SPA behavior.
- **Headers**: Sets cache control headers for performance optimization.

## Project Information
- **Repository**: [GitHub Repository URL]
- **License**: MIT License
- **Author**: Your Name
