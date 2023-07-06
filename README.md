# studyNotion-Project
StudyNotion is a fully functional ed-tech platform that enables users to create, consume, and rate educational content.
The platform is built using the MERN stack, which includes ReactJS, NodeJS, MongoDB, and ExpressJS.

StudyNotion aims to provide:
A seamless and interactive learning experience for students, making education more accessible and engaging.
A platform for instructors to showcase their expertise and connect with learners across the globe.

The front end of StudyNotion has all the necessary pages that an ed-tech platform should have. Some of these pages are:

For Students:
Homepage: This page will have a brief introduction to the platform, as well as links to the course list and user details.
Course List: This page will have a list of all the courses available on the platform, along with their descriptions and ratings.
Wishlist: This page will display all the courses that a student has added to their wishlist.
Cart Checkout: This page will allow the user to complete the course purchase.
Course Content: This page will have the course content for a particular course, including videos, and other related material.
User Details: This page will have details about the student's account, including their name, email, and other relevant information.
User Edit Details: This page will allow the student to edit their account details.

For Instructors:
Dashboard: This page will have an overview of the instructor's courses, as well as the ratings and feedback for each course.
Insights: This page will have detailed insights into the instructor's courses, including the number of views, clicks, and other relevant metrics.
Course Management Pages: These pages will allow the instructor to create, update, and delete courses, as well as manage the course content and pricing.
View and Edit Profile Details: These pages will allow the instructor to view and edit their account details.

The back end of StudyNotion provides a range of features and functionalities, including:

User authentication and authorization: Students and instructors can sign up and log in to the platform using their email addresses and password. The platform also supports OTP (One-Time Password) verification and forgot password functionality for added security.
Course management: Instructors can create, read, update, and delete courses, as well as manage course content and media. Students can view and rate courses.
Payment Integration: Students will purchase and enrol on courses by completing the checkout flow that is followed by Razorpay integration for payment handling.
Cloud-based media management: StudyNotion uses Cloudinary, a cloud-based media management service, to store and manage all media content, including images, videos, and documents.
Markdown formatting: Course content in document format is stored in Markdown format, which allows for easier display and rendering on the front end.

Frameworks, Libraries, and Tools used:

The back end of StudyNotion uses a range of frameworks, libraries, and tools to ensure its functionality and performance, including:
Node.js: Node.js is used as the primary framework for the back end.
MongoDB: MongoDB is used as the primary database, providing a flexible and scalable data storage solution.
Express.js: Express.js is used as a web application framework, providing a range of features and tools for building web applications.
JWT: JWT (JSON Web Tokens) are used for authentication and authorization, providing a secure and reliable way to manage user credentials.
Bcrypt: Bcrypt is used for password hashing, adding an extra layer of security to user data.
Mongoose: Mongoose is used as an Object Data Modeling (ODM) library, providing a way to interact with MongoDB using JavaScript.

API Design:
The StudyNotion platform's API is designed following the REST architectural style. The API is implemented using Node.js and Express.js. 
It uses JSON for data exchange and follows standard HTTP request methods such as GET, POST, PUT, and DELETE.
Sample list of API endpoints and their functionalities:
/api/auth/signup (POST) - Create a new user (student or instructor) account.
/api/auth/login (POST) – Log in using existing credentials and generate a JWT token.
/api/auth/verify-otp (POST) - Verify the OTP sent to the user's registered email.
/api/auth/forgot-password (POST) - Send an email with a password reset link to the registered email.
/api/courses (GET) - Get a list of all available courses.
/api/courses/:id (GET) - Get details of a specific course by ID.
/api/courses (POST) - Create a new course.
/api/courses/:id (PUT) - Update an existing course by ID.
/api/courses/:id (DELETE) - Delete a course by ID.
/api/courses/:id/rate (POST) - Add a rating (out of 5) to a course.

Sample API requests and responses:
GET /api/courses: Get all courses
Response: A list of all courses in the database
GET /api/courses/:id: Get a single course by ID
Response: The course with the specified ID
POST /api/courses: Create a new course
Request: The course details in the request body
Response: The newly created course
PUT /api/courses/:id: Update an existing course by ID
Request: The updated course details in the request body
Response: The updated course
DELETE /api/courses/:id: Delete a course by ID
Response: A success message indicating that the course has been deleted.


Deployment:
The deployment process for the StudyNotion ed-tech platform will involve hosting the application on various cloud-based services. 
The front end will be deployed using Vercel, a popular hosting service for static sites built with React. The back-end will be hosted
on Render or Railway, two cloud-based hosting services for applications built with Node.js and MongoDB. Media files will be hosted on 
Cloudinary, a cloud-based media management platform, and the database will be hosted on MongoDB Atlas, a fully managed cloud database service.
The hosting environment and infrastructure for the StudyNotion platform will ensure scalability, security, and reliability. Vercel provides
a fast and scalable hosting environment for the front end, while Render or Railway provide a scalable and reliable infrastructure for the
back end. Cloudinary provides reliable storage for media files with features like automatic image optimization and transformation, while 
MongoDB Atlas provides a highly available and secure database environment with features like automatic scaling and disaster recovery. 
Overall, the deployment process for StudyNotion will ensure a stable and scalable hosting environment for the application, allowing users to
access the platform seamlessly from anywhere in the world.


Conclusion:
In conclusion, this document outlines the architecture, features, and functionalities of the StudyNotion ed-tech platform. It highlights the use 
of MERN stack technologies and REST API design and outlines the deployment process using free hosting services, Vercel for the front-end, Render.com or
Railway.app for the backend, and MongoDB Atlas for the database. Additionally, it lists potential future enhancements that could be implemented to improve 
the platform, along with their estimated timelines and priorities.
Throughout the development of the project, various achievements will be made in terms of implementing the desired functionalities and creating a user-friendly 
interface. However, there will be challenges to be faced during the development process, such as integrating different technologies and debugging errors.

