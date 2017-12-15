## MEAN stack 
The components of the MEAN stack are as follows:
- MongoDB, a NoSQL database
- Express.js, a web application framework that runs on Node.js
- Angular.js or Angular, JavaScript MVC frameworks that run in browser JavaScript engines
- Node.js, an execution environment for event-driven server-side and networking applications
Because all components of the MEAN stack support programs are written in JavaScript, MEAN applications can be written in one language for both server-side and client-side execution environments.

## How to run system
You can run the project directly in our workspace. The github authorization 
module is only work in our workspace (because github OAuth apps needs a fixed 
authorization callback URL). Our URL is https://project22-zhangqx.c9users.io/login

You can also download the project and open it on your workspace. 
To run the project in your own workspace, follow the steps: 
1. install mongodb
sudo apt-get install -y mongodb-org

2. start mongodb
mongod --smallfiles --syslog --fork

3. install all dependencies 
npm install

4. start the server
node server.js

5. open a new windows and use the URL to visit the page:
https://"your project name"-"your user name".c9users.io/login
