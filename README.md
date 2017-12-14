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