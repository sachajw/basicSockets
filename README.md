# basicSockets

clone the repo
cd into the server folder and run "npm install"
launch server "npm run start"
go to the client folder and open the index.html in your browser
if you can type in a message and see the same message on the screen you have a working socket. (edited) 

next deploy the server to Azure and change the line
const socket = io('http://localhost:3000');
in the index.html to point to the new application
then put the gateway in place and change this line again to the new gateway url and it should still work (edited) 

without the server running you should see the connection errors in the browser console
after the server is started you should see application running at ...
and the connection (this means the client is connected)

type something in the box, like "hello ruan" and press send. You will see on the server that it has
server received chat hello ruan
an on the top of the screen it shows the message you typed
