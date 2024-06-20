# Real-Time Code Editor

Welcome to the Real-Time Code Editor! This application allows multiple users to collaborate on coding projects in real-time. Users can join existing rooms or create new ones using unique room IDs and usernames.

## Features

- **Real-Time Collaboration:** Multiple users can code together in real-time.
- **Room IDs:** Join or create rooms using unique room IDs.
- **Usernames:** Identify users by their unique usernames.
- **Persistent Rooms:** Users can log back into previously created rooms to continue coding.

## Getting Started

Follow these instructions to get the Real-Time Code Editor up and running on your local machine.

### Prerequisites

- [Node.js](https://nodejs.org/) (v14.x or later)
- [npm](https://www.npmjs.com/)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/anim_2403/realtime-code-editor.git
   cd realtime-code-editor `

1.  Install dependencies:

    bash

    Copy code

    `npm install`

### Running the Application

1.  Start the server:

    bash

    Copy code

    `npm start`

2.  Open your browser and navigate to `http://localhost:3000`.

Usage
-----

1.  **Create a New Room:**

    -   On the homepage, enter a username and click on "Create Room".
    -   A unique room ID will be generated, which you can share with others.
2.  **Join an Existing Room:**

    -   On the homepage, enter your username and the room ID provided by your collaborator.
    -   Click on "Join Room" to start coding together.
3.  **Rejoin a Room:**

    -   To rejoin a room you previously created or joined, enter the same room ID and username.

Technologies Used
-----------------

-   **Frontend:** React.js
-   **Backend:** Node.js, Express.js
-   **Real-Time Communication:** Socket.io

Contributing
------------

We welcome contributions! Please read our [contributing guidelines](CONTRIBUTING.md) for more details.

License
-------

This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgements
----------------

-   [Socket.io](https://socket.io/)
-   [React.js](https://reactjs.org/)
-   [Express.js](https://expressjs.com/)

Contact
-------

For any inquiries, please contact us at [animeshsingh2403@gmail.com].
