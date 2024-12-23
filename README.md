# ReviewBot

ReviewBot is a platform designed to enhance the user experience of evaluating products. Users can input a product to receive its pros and cons and interact with a chatbot that answers product-specific queries and reviews. The platform includes authentication, pricing, about us, and contact us pages.

---

## Features

1. **Product Review Analysis**
   - Enter a product to view its pros and cons.
2. **Chatbot**
   - Interact with a chatbot powered by Gemini 1.5B for product-specific queries and reviews.
3. **User Authentication**
   - Secure login and signup functionality.
4. **Pricing Page**
   - View subscription plans with detailed comparisons.
5. **About Us Page**
   - Learn about our mission and team.
6. **Contact Us Page**
   - Reach out to us using an integrated form.

---

## Tech Stack

- **Frontend**: React.js
- **Backend**: Express.js
- **Database**: MongoDB
- **Styling**: TailwindCSS
- **Chatbot**: Gemini 1.5B

---

## Installation

### Prerequisites
- Node.js installed on your system.
- MongoDB set up locally or a MongoDB Atlas account.

### Steps
1. **Clone the Repository**
   ```bash
   git clone https://github.com/Sohith-reddy/reviewbot.git
   cd reviewbot
   ```

2. **Install Backend Dependencies**
   ```bash
   cd backend
   npm install
   ```

3. **Install Frontend Dependencies**
   ```bash
   cd ../frontend
   npm install
   ```

4. **Set Up Environment Variables**
   - Create a `.env` file in the `backend` directory with the following:
     ```env
     PORT=5000
     MONGO_URI=your-mongo-db-connection-string
     JWT_SECRET=your-jwt-secret
     CHATBOT_API_KEY=your-gemini-api-key
     ```

5. **Run the Backend**
   ```bash
   cd backend
   npm start
   ```

6. **Run the Frontend**
   ```bash
   cd ../frontend
   npm start
   ```

7. **Access the Application**
   Open your browser and navigate to `http://localhost:3000`.

---

## Folder Structure

### Backend
- `routes/`: API routes for authentication, chatbot, and product operations.
- `models/`: MongoDB schemas for users, chat history, etc.
- `controllers/`: Handles backend logic for API routes.
- `middleware/`: Middleware for authentication and error handling.
- `server.js`: Entry point for the backend server.

### Frontend
- `src/components/`: Reusable React components for UI.
- `src/pages/`: Pages for home, login, signup, pricing, etc.
- `src/styles/`: TailwindCSS configurations and global styles.
- `src/api.js`: API service for connecting to the backend.

---

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

---

## Contact

For questions or feedback, reach out to us at [your-email@example.com].
