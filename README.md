Comment Service - SPAM & FURIOUS

**What Needs to Be Developed:**

-Comment Management: Allow users to post comments, reply to comments, and like/dislike comments.

-Database for Comments: Store comments in a database, associating them with the correct video and user.

-API for Comment Interaction: Endpoints like POST /videos/{id}/comments (to post), GET /videos/{id}/comments (to retrieve), and DELETE /comments/{id} (to delete a comment).


**Technologies to Use:**

-Spring Boot: For building the REST API.

-Spring Data JPA / MongoDB: For storing comments in a relational or NoSQL database.

-Redis: For caching the comments to improve performance, especially when dealing with large numbers of comments.
