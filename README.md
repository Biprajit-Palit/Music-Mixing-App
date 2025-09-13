<img src="https://r2cdn.perplexity.ai/pplx-full-logo-primary-dark%402x.png" class="logo" width="120"/>

## Project Document: Collaborative Playlist Mixer

### 1. Introduction

- **Project Name:** Collaborative Playlist Mixer  
- **Developer:** Biprajit Palit (CSE Student, NIT Agartala)  
- **Project Goal:** To create a web application where multiple users can collaborate on creating and listening to a shared playlist in real-time.  
- **Target Audience:** Music lovers who enjoy sharing and discovering music with friends.  
- **Personal Goal:** To strengthen my portfolio with a real-world web project that demonstrates my skills in full-stack development, real-time systems, and API integration, as I work towards becoming an SDE at top tech companies.  

---

### 2. Requirements

#### 2.1. Functional Requirements

- **User Authentication:**
    - Users should be able to register and log in using Google OAuth (via Firebase or Supabase).  
    - Implement secure session management.  
- **Room Management:**
    - Users can create a room with a unique code.  
    - Users can join a room using the unique code.  
    - Store room details in the database.  
- **Playlist Management:**
    - Users can add and remove songs.  
    - Playlist should be scrollable and interactive.  
    - Songs should be playable within the room.  
- **Song Search:**
    - Integrate with Spotify/YouTube APIs.  
    - Search results should be displayed clearly for easy selection.  
- **Real-time Collaboration:**
    - Playlist updates should sync instantly across all members.  
    - WebSockets (Socket.IO) for real-time communication.  
- **Live Chat:**
    - Enable members to chat inside the room.  
    - Messages visible to all members with user info.  
- **User Interface (UI):**
    - Clean, modern design.  
    - Side navigation bar for easy access (search, rooms, create/join).  

#### 2.2. Non-Functional Requirements

- **Performance:** Low-latency, responsive updates.  
- **Scalability:** Support multiple rooms and users concurrently.  
- **Security:** Strong authentication and authorization.  
- **Usability:** Simple and intuitive UI.  
- **Reliability:** Minimal downtime with proper error handling.  

---

### 3. Use Cases

- **User Registration/Login** → Register/login with OAuth.  
- **Create a Room** → Generates unique code.  
- **Join a Room** → Enter a room code to join.  
- **Search for Songs** → Query Spotify/YouTube API.  
- **Add Song** → Add track to playlist.  
- **Delete Song** → Remove track from playlist.  
- **Play Song** → Play tracks directly in the room.  
- **Send Chat Message** → Exchange messages in real-time.  

---

### 4. Functionality

#### 4.1. Authentication
- Google OAuth via Firebase/Supabase.  
- Securely handle user sessions.  

#### 4.2. Room Creation
- Generate unique alphanumeric codes.  
- Store room metadata in database.  

#### 4.3. Room Joining
- Validate room codes.  
- Maintain active users list.  

#### 4.4. Song Search
- Spotify/YouTube API integration.  
- Display results with title, artist, thumbnail.  

#### 4.5. Playlist Management
- Structured playlist storage.  
- Add/remove track functions.  

#### 4.6. Real-time Updates
- WebSockets (Socket.IO).  
- Broadcast playlist changes, messages, join/leave events.  

#### 4.7. Live Chat
- Simple chat UI with user identity.  

---

### 5. Technology Stack

- **Frontend Framework:** Next.js  
- **Database:** Supabase/PostgreSQL  
- **Authentication:** Google OAuth 2.0  
- **Real-time Communication:** WebSockets (Socket.IO)  
- **Music API:** Spotify API / YouTube API  
- **Deployment (Future):** Vercel / Railway  

---

### 6. Project Milestones (Planned)

1. **Authentication & UI Setup** (1 day) → Google OAuth, basic layout.  
2. **Room Creation & Joining** (1-2 days) → Unique codes + validation.  
3. **Song Search & Playlist Management** (2-3 days) → API integration.  
4. **Real-time Updates** (1-2 days) → Socket.IO for live sync.  
5. **Live Chat** (1 day) → Add chat feature inside room.  
6. **Testing & Debugging** (1 day) → Fix edge cases and polish UI.  

---

### 7. Project Risks

- **API Rate Limits:** Spotify/YouTube rate limits. Solution → caching & error handling.  
- **WebSocket Complexity:** Handling concurrent real-time updates.  
- **Scalability:** Performance issues with multiple users/rooms.  
- **Security:** Protecting user data and room access.  

---

### 8. Conclusion

This project represents my effort to apply **full-stack development, API integration, and real-time system design** in a single application. As a CSE student at **NIT Agartala**, this is an important step in my journey to becoming a skilled software engineer.  

It will serve as a **portfolio project**, highlighting my ability to work with modern frameworks, authentication, real-time communication, and API-driven development.  

<div style="text-align: center">⁂</div>
