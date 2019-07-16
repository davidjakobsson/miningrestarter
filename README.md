# miningrestarter
Supposed to restart at cryptomining software and change connection settings if any errors occurs

I have created this project since my mining on the nicehash servers keeps loosing conenction to the servers after about half an hour. 
When I change the server it immediately works again, but it never recovers unless I change the server. 

My intention is to build a simple application that starts the miner and listens for errors. When an error occur it should restart the application, 
if the error is a connection error it should also change the server to which the miner is connected.
