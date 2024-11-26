# Chat Application Project

This project is a chat application built using JavaFX. It provides a user-friendly interface for real-time communication between clients and a server.

## Class Overview: `ClientFormController`
The `ClientFormController` class is a core component of the chat application. It manages the client-side user interface and handles interactions with the server.

### Components and Functionality

#### 1. JavaFX Components
These are the UI elements that enable user interaction:

- **AnchorPane (`pane`)**: A layout container for organizing the overall interface.
- **ScrollPane (`scrollPain`)**: A scrollable area that displays the chat messages.
- **VBox (`vBox`)**: A vertical box layout used to hold individual chat messages.
- **JFXTextField (`txtMsg`)**: A text field where users can input their messages.
- **Text (`txtLabel`)**: Displays the client’s name.
- **JFXButton (`emojiButton`)**: A button for opening the emoji picker.

#### 2. Networking Components
These components manage the communication between the client and the server:

- **Socket (`socket`)**: Establishes a connection to the server.
- **DataInputStream (`dataInputStream`)**: Reads incoming data from the server.
- **DataOutputStream (`dataOutputStream`)**: Sends data from the client to the server.

### Features
1. **Real-time Messaging**: Clients can send and receive messages instantly.
2. **User-Friendly Interface**: A clean and simple layout for seamless communication.
3. **Emoji Picker**: Add fun to conversations with an integrated emoji picker.

### Requirements
- **Java 8 or later**
- **JavaFX SDK**
- A basic understanding of Java and networking concepts

### Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/chat-application.git
   ```
2. Import the project into your preferred IDE.
3. Ensure the JavaFX library is configured in your project.
4. Compile and run the `ClientFormController` class to start the application.

### How It Works
1. **Initialization**: The client connects to the server using the `Socket` class.
2. **Sending Messages**: Users type messages in the `JFXTextField` and press Enter to send them. The message is sent to the server via `DataOutputStream`.
3. **Receiving Messages**: The `DataInputStream` listens for messages from the server and displays them in the `VBox` within the `ScrollPane`.
4. **Emoji Integration**: Clicking the `emojiButton` opens the emoji picker to add emojis to messages.

### Future Enhancements
- Add file-sharing capabilities.
- Implement group chat functionality.
- Include message encryption for secure communication.

### License
This project is open-source and free to use under the MIT License. Feel free to contribute and enhance its functionality!

