# CollabDocs

CollabDocs is a real-time collaborative document editor built with the MERN stack. It allows multiple users to create, edit, and collaborate on documents in real-time with rich text editing features.

## Features

- Real-Time Collaboration
- Rich Text Editing
- User Authentication
- Document Sharing
- Document Management
- Version History
- Export and Import

## Technology Stack

- **Frontend:** React, Redux, Quill.js, Tailwind CSS
- **Backend:** Node.js, Express.js, MongoDB, Mongoose, Socket.IO
- **Authentication:** JWT

## Getting Started

### Prerequisites

- Node.js
- MongoDB

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/CollabDocs.git
   cd CollabDocs
   ```

2. **Backend Setup:**
   ```bash
   cd backend
   npm install
   npm start
   ```

3. **Frontend Setup:**
   ```bash
   cd frontend
   npm install
   npm start
   ```

### Project Structure

```
CollabDocs/
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── sockets/
│   ├── utils/
│   ├── app.js
│   └── config/
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── store/
│   │   ├── App.js
│   │   └── index.js
├── .env
├── .gitignore
├── package.json
└── README.md
```

### Usage

1. **Start the Backend Server:**
   ```bash
   cd backend
   npm start
   ```

2. **Start the Frontend Development Server:**
   ```bash
   cd frontend
   npm start
   ```

3. Open your browser and navigate to `http://localhost:3000` to start using CollabDocs.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a pull request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [React](https://reactjs.org/)
- [Redux](https://redux.js.org/)
- [Quill.js](https://quilljs.com/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Node.js](https://nodejs.org/)
- [Express.js](https://expressjs.com/)
- [MongoDB](https://www.mongodb.com/)
- [Socket.IO](https://socket.io/)
