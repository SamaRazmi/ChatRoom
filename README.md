Chat Room Readme

Description:

This chat room application enables real-time communication between users connected to the same room. Developed by Samaneh Razmi, the application utilizes web sockets for seamless and instantaneous message exchange.

Getting Started:

    Clone the Repository:
        Clone this repository to your local machine using the following command:

        bash

    git clone https://github.com/SamaRazmi/ChatRoom.git

Installation:

    Navigate to the project directory and install dependencies for both server and client:

    bash

    cd ChatRoom
    npm install
    cd client
    npm install

Starting the Server:

    Start the server by running the following command from the project root directory:

    npm start

Starting the Client:

    Open another terminal window/tab, navigate to the client directory, and start the client:

    bash

        cd client
        npm start

    Joining a Room:
        Open your web browser and navigate to the address where the client is running (by default, it should be http://localhost:3000/).
        You will be prompted to enter a username and choose a room to join. Enter the same room name on both browser instances to join the same room.

    Chatting:
        Once you have joined the same room on both browser instances, you can start chatting.
        Messages typed in one browser will instantly appear in the other browser, facilitating real-time communication.

Notes:

    Ensure that both the server and client are running simultaneously to establish a connection and enable chat functionality.
    Any message sent in the chat room will be visible to all users present in the same room.

Credits:

    Designed and developed by Samaneh Razmi.

Support:

    For any inquiries or support, please contact Samaneh Razmi at samane.flower69@gmail.com.
