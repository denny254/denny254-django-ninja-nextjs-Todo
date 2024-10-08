﻿# Django Ninja & Next.js - DaisyUI Components | Client Components | Form Submissions
This project integrates Django Ninja (a web framework for building APIs) with Next.js, utilizing DaisyUI components for a modern and responsive UI. The focus is on handling client components and form submissions efficiently.

Table of Contents
Project Overview
Technologies Used
Installation
Configuration
Running the Project
Features
API Documentation
Form Submissions
Troubleshooting
Contributing
License
Project Overview
This project is a full-stack web application that leverages Django Ninja for building APIs and Next.js for creating a dynamic and fast frontend. DaisyUI, a Tailwind CSS-based UI library, is used to design responsive and aesthetically pleasing components.

The application demonstrates how to handle form submissions from the client side using Next.js and how to process these submissions on the server side with Django Ninja.

Technologies Used
Backend: Django Ninja
Frontend: Next.js, DaisyUI
Styling: Tailwind CSS
API Documentation: Swagger/OpenAPI (integrated with Django Ninja)
JavaScript/TypeScript: Used for client-side scripting and API calls
Installation
Prerequisites
Python 3.x
Node.js and npm/yarn
PostgreSQL or any other preferred database
Django and Django Ninja
Next.js and Tailwind CSS
Backend Setup
Clone the repository:

git clone https://github.com/denny254/denny254-django-ninja-nextjs-Todo.git
cd denny254-django-ninja-nextjs-Todo
Install Python dependencies:

pip install -r requirements.txt
Set up the database:

python manage.py migrate
Run the Django development server:

python manage.py runserver
Frontend Setup
Navigate to the frontend directory:

cd frontend
Install Node.js dependencies:

npm install
Run the Next.js development server:

npm run dev
Configuration
Backend Configuration
Update the settings.py file with your database configurations.
Configure Django Ninja routes in urls.py.
Frontend Configuration
Modify the next.config.js file if needed.
Update API endpoint URLs in your frontend components to match your backend configuration.
Running the Project
Running in Development Mode
Start the Django server:

python manage.py runserver
Start the Next.js server:

npm run dev
Running in Production Mode
Build the Next.js application:

npm run build
Collect static files for Django:

python manage.py collectstatic
Deploy using your preferred method (e.g., Docker, Heroku, AWS, etc.).

Features
API Integration: Smooth integration of Django Ninja APIs with the Next.js frontend.
DaisyUI Components: Pre-styled components for building responsive and consistent UIs.
Form Handling: Efficient client-side form handling and validation with server-side processing.
API Documentation
API documentation is automatically generated and available at /api/docs/. You can access the interactive API documentation using Swagger UI.

Form Submissions
Forms are handled using client-side validation with Next.js. On submission, the data is sent to the Django Ninja backend for processing. The flow includes handling both successful submissions and error cases.

Troubleshooting
Ensure all environment variables are correctly configured.
Check for CORS issues when making API calls from the frontend to the backend.
If you encounter any errors, refer to the logs in the console for more details.
Contributing
Contributions are welcome! Please fork this repository, make your changes, and submit a pull request. Ensure your code adheres to the project's coding standards.

License
This project is licensed under the MIT License. See the LICENSE file for details.
