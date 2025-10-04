ChatIO - a real time online chat application build using websockets.

**High Level Architecture Diagram**
<img width="1464" height="689" alt="image" src="https://github.com/user-attachments/assets/a5eb7cc0-f382-4f54-8aa5-2b4c7111c763" />

MVP:-
User signup/login using OAuth (Google)

Real-time 1-to-1 chat using WebSockets

Store recent chats in Redis

Store chat history in SQL

Upload images/videos via Cloudinary (store URLs in MongoDB)

Kafka queue for message reliability
