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

So, Socket.IO allows us to easily build real time applications, such as chat apps and multiplayer games.

## Project Setup

1. Clone the repository to the local machine by either downloading the ZIP File or using the following git command:
```
git clone https://github.com/aniru-dh21/Realtime-Chat-App-With-Rooms.git
```

2. Change your Present working directory to the client Folder and install the dependencies using npm:
```
npm install
```

3. Run the following command to boot up the frontend:
```
npm start
```

4. Webpack will build the React app and serve it to <ins>http://localhost:3000</ins>

5. Then change your Present working directory to the server Folder and install the dependencies using npm:
```
npm install
```

6. Now, let's boot up the server by running the following command:
```
npm run dev
```

7. Webpack will build the React app and server it to <ins>http://localhost:4000/</ins>

## How to set up HarperDB

1. First, <a href="https://studio.harperdb.io/">create an account with HarperDB</a>.

2. Click on the "Create New HarperDB Cloud Instance" button located in your HarperDB studio.

3. Choose the suitable instance type and then proceed by clicking on the button labled as AWS or verizon Wavelength HarperDB instance.

4. Select the cloud provider (I selected AWS), and click the instance to add the detail of your instance.

5. Enter the instance and click the Instance Details button and also create create your instance credentials.

6. HarperDB has a generous free tier that we can use for this project, so select that.

7. Check your details are correct, then create the instance.

## How to Set Up HarperDB Environment Variables ?

In order for you to be able to save messages in HarperDB, you'll need your HarperDB instance URL, and your API password.

In your HarperDB dashboard, click on your instance, then go to "config". You will find your instance URL, and your instance API Auth Header - that is, your "super_user" password that allows you to make any request to the database.

Create the following files and add your HarperDB URL and password as shown in file `Sample.env`.
