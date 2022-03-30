# A Real Time Chat App using React and Socket IO with E2E Encryption

A simple chat application with Node.js and React, where the exchanged messages will have end-to-end encryption using secret keys.
How the app works
We’ll create a secret key and store it in the frontend for demonstration purposes. The key is saved in a .ENV variable where the frontend has been deployed in a server.

Whenever a user sends or receives a message, the message will be encrypted or decrypted using an aes256 npm package with the same secret key.

## Backend
For the backend, we’ll use Node.js and the Express framework. Socket.io is needed to provide real-time, two-way communication between the backend server and the frontend.

## Frontend
We will use React, Redux library, the socket.io-client, and aes256 for encrypting and decrypting the messages for the frontend.
