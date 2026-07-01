# Personalized Networking Assistant

## Task 1: Description of the ER Diagram

### Overview
The Personalized Networking Assistant helps users discover and connect with professionals based on their interests, skills, goals, and networking preferences.

### Main Entities

1. User
   - User_ID
   - Name
   - Email
   - Skills
   - Interests

2. Profile
   - Profile_ID
   - User_ID
   - Bio
   - Experience
   - Education

3. Connection
   - Connection_ID
   - User1_ID
   - User2_ID
   - Status

4. Recommendation
   - Recommendation_ID
   - User_ID
   - Recommended_User_ID
   - Score

### Relationships

- One User has one Profile.
- One User can have many Connections.
- One User can receive many Recommendations.
- Recommendations connect users with similar interests and goals.
