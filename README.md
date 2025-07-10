# Real-Time Chat App

A modern, real-time chat application built with **Node.js**, **Express**, and **Socket.io**. This project demonstrates expertise in full-stack JavaScript development, real-time communication, modular code structure, and clean UI/UX design. Users can join chat rooms, send messages, share their location, and see who else is online—all in real time.

![Chat App Screenshot](public/img/chat.png)

---

## 🚀 Features

- **Real-Time Messaging:** Instant message delivery using WebSockets.
- **Room-Based Chats:** Users can join specific rooms and chat with others.
- **User List Sidebar:** See who is online in each room.
- **Profanity Filter:** Prevents offensive language using the `bad-words` package.
- **Location Sharing:** Share your current location with a single click.
- **Responsive UI:** Clean, modern, and mobile-friendly interface.
- **Modular Codebase:** Well-structured and maintainable code with clear separation of concerns.

---

## 🛠️ Tech Stack

- **Backend:** Node.js, Express, Socket.io
- **Frontend:** HTML5, CSS3, JavaScript (ES6+), Mustache.js, Moment.js
- **Utilities:** [bad-words](https://www.npmjs.com/package/bad-words), [nodemon](https://www.npmjs.com/package/nodemon) (for development)

---

## 📦 Project Structure

```
chat-app/
├── public/               # Static assets (HTML, CSS, JS, images)
│   ├── [`public/chat.html`](public/chat.html )
│   ├── [`public/index.html`](public/index.html )
│   ├── css/
│   ├── img/
│   └── js/
├── src/                  # Server-side code
│   ├── [`src/index.js`](src/index.js )
│   └── utils/
│       ├── [`src/utils/messages.js`](src/utils/messages.js )
│       └── [`src/utils/users.js`](src/utils/users.js )
├── [`package.json`](package.json )
└── .gitignore
```

---

## 🖥️ Getting Started

### 1. Clone the Repository

```sh
git clone https://github.com/ali-roshanbin/chat-app.git
cd chat-app
```

### 2. Install Dependencies

```sh
npm install
```

### 3. Run the Application

- **Development mode (with auto-reload):**
  ```sh
  npm run dev
  ```
- **Production mode:**
  ```sh
  npm start
  ```

### 4. Open in Browser

Visit [http://localhost:3000](http://localhost:3000) and join a chat room!

---

## ✨ Usage

1. **Join a Room:**  
   Enter a display name and room name on the home page.

2. **Chat:**  
   Send messages, see others join/leave, and view the live user list.

3. **Share Location:**  
   Click "Send Location" to share your current location with the room.

---

## 🧩 Code Highlights

- **User Management:**  
  Modular user management with add, remove, and query functions ([`src/utils/users.js`](src/utils/users.js)).

- **Message Generation:**  
  Consistent message formatting and timestamping ([`src/utils/messages.js`](src/utils/messages.js)).

- **Socket.io Integration:**  
  Real-time events for joining, messaging, location sharing, and disconnects ([`src/index.js`](src/index.js)).

- **Frontend Templates:**  
  Dynamic rendering with Mustache.js and moment.js for time formatting ([`public/chat.html`](public/chat.html), [`public/js/chat.js`](public/js/chat.js)).

---

## 📸 Screenshots

| Join Room | Chat Room |
|-----------|-----------|
| ![Join](public/img/chat.png) | ![Chat](public/img/chat.png) |

---

## 🧑‍💻 Author

- **Ali Roshanbin**  
  [GitHub](https://github.com/ali-roshanbin) | [GitLab](https://gitlab.com/ali.roshanbin) | [LinkedIn](https://linkedin.com/in/roshanbin)

---

## 📄 License

This project is licensed under the [ISC License](LICENSE).

---

## ⭐️ Why This Project?

This chat app is a showcase of:

- Real-time web development skills
- Clean, maintainable, and modular code
- Responsive and user-friendly UI
- Practical use of modern JavaScript libraries and frameworks

If you're looking for a developer who can build robust, scalable, and user-centric applications—let's connect!
