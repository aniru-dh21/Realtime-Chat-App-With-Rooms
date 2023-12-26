# Real-Time Chat App with React, Node, Socket.io, and HarperDB

Tools used to Build this App:
- **Frontend**: React (A frontend JavaScript framework for building interactibe applications)
- **Backend**: Node and Express (Express is very popular NodeJS framework that allows us to easily create APIs and backends)
- **Database**: HarperDB (a data + application platform that allows you to query data using either SQL or NoSQL. HarperDB also has a built-in API, saving us from having to write a lot of backend code)
- **Realtime Communication**: Socket.io

## What is Socket.IO?

Socket.IO allows the server to push information to the client in real time, when events occur on the server.

Without Socket.IO, the client would have to make multiple polling AJAX calls to verify that the event has occured on the server.

Socket.IO means that the client doesn't have to make multiple polling AJAX calls to verify if some event has occured on the server. Instead, the server sends the infor to the client as soon as it gets it.
