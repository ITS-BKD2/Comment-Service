User Service - Spam&Furious 

What Needs to Be Developed:
-User Management: Handle user registration, login, profile management, and authentication.

-JWT Authentication: Provide authentication using JSON Web Tokens (JWT) for secure access to other services.

-User Profile: Allow users to manage their profiles (e.g., avatars, bio).

-API for User Management: Endpoints like POST /users/register, POST /users/login, GET /users/{id}/profile.


Technologies to Use:

-Spring Boot: For building the REST API.

-Spring Security: For securing endpoints and managing JWT authentication.

-Spring Data JPA: For user data storage in a relational database (PostgreSQL/MySQL).

-Redis: For caching user sessions and improving performance.



Interactions with Other Services:

-Video Upload & Metadata Service: Ensure that only authenticated users can upload videos and associate video metadata with the user.

-Video Streaming & Playback Service: Secure access to streaming, ensuring users can only access videos they are authorized to view.

-Comment Service: Ensure that only authenticated users can comment on videos.
