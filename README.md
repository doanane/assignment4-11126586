Job Portal Application
Overview
The Job Portal Application is designed to streamline the job search process for users by providing an intuitive interface for exploring job opportunities. It includes essential features such as user login, personalized home screen, and categorized job listings.

Features
1. Login Screen
User Input: The login screen allows users to enter their name and email address. These details are essential for personalizing the user experience on the Home screen.
Login Functionality: When the user presses the login button, the application captures the entered name and email. This information is then passed to the Home screen to personalize the content and welcome message.
2. Home Screen
Personalized Greeting: The Home screen displays a welcome message that includes the user's name and email, making the experience more personalized and engaging.
Job Listings:
Popular Jobs: This section features job cards for jobs that are currently trending or highly sought after. The section displays at least 8 different job cards.
Featured Jobs: This section highlights job cards for jobs that are specially promoted or significant opportunities. It also displays at least 8 different job cards.
3. Job Cards
Component Design: The JobCard component is a custom functional component that encapsulates the job details in a visually appealing and informative layout.
Props Handling: The JobCard component accepts various props, including:
jobTitle: The title of the job position.
companyName: The name of the company offering the job.
location: The location of the job.
jobType: The type of job (e.g., full-time, part-time).
description: A brief description of the job.
Display: The JobCard component ensures that all relevant information is displayed in a clear and accessible manner, allowing users to quickly scan and identify suitable job opportunities.
4. UI Design
Styling Consistency: The application is styled to closely match the provided UI design specifications. This includes consistent use of colors, fonts, and layout structures.
Custom Components: Custom components are used throughout the application to maintain a cohesive look and feel, ensuring a seamless user experience.
