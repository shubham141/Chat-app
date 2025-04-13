
# 🗨️ Real-Time Chat App with Python & Sockets

A simple yet powerful real-time chat application built using Python and socket programming. This project demonstrates the core concepts of real-time communication, including user name customization and group chatting capabilities.

## 🚀 Features

- 🔌 Real-time messaging using Python sockets
- 👥 Group chat functionality
- ✏️ Users can change their display name
- 💬 Lightweight and easy to use
- 🧠 Built with core Python – no external frameworks required

## 📸 Screenshots
*<img width="906" alt="Screenshot 2025-04-13 at 4 06 42 PM" src="https://github.com/user-attachments/assets/53b3e531-0efd-45c9-86a4-4d0832e3ae72" />
*

## 🛠️ Technologies Used

- Python 3
- Socket module (built-in)
- Threading (for handling multiple clients simultaneously)

## 📦 How It Works

The app follows a client-server architecture:
- The **server** listens for incoming connections and relays messages to all connected clients.
- The **clients** connect to the server, send messages, and receive updates in real-time.
- Each client can choose a custom name when joining the chat.

## 📁 File Structure

```
chat-app/
├── app.py        # Runs the chat server
├── index.py        # Runs the chat client
└── README.md        # This file
```

## 🚴‍♂️ Getting Started

1. **Clone the repository**

```bash
git clone https://github.com/shubham141/Chat-app.git
cd chat-app
```

2. **Run the server**

```bash
python server.py
```

3. **Run one or more clients (in separate terminals)**

```bash
python client.py
```

4. **Start chatting!**
   - You’ll be prompted to enter your name.
   - Messages will be broadcasted to all connected clients.

## 🔄 Future Improvements

- Add a GUI (e.g., using Tkinter or PyQt)
- Encrypt messages for secure communication
- Add private chat / direct messages
- Add timestamps to messages
- Deploy the server to the cloud for global access

## 🙌 Contributing

Feel free to fork this repo and submit pull requests. Feedback and suggestions are always welcome!

## 📄 License

This project is open source and available under the Apache License.

---
 
Happy chatting! 💬✨
```

---

Let me know if you'd like to add GUI setup instructions, Docker support, or a badge section at the top!
