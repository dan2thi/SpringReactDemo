# SpringReactDemo
Sample skeleton project where frontend is served by react and backend with spring boot. 

- During the dev phase make sure to uncomment content of frontend/src/setupProxy.js (This will allow frontend to run on port 3000 while all the rest '/api' calls will be proxied to port 8080).
- Make sure to comment out content of 'frontend/src/setupProxy.js' when building the final production jar file which contains frontend js files. 

# Special Thanks
Special thanks goes to [yugabyte](https://github.com/yugabyte) in providing a clear and profound step by step explanation [here](https://github.com/yugabyte/yugastore-java/tree/master/react-ui) in setting up dev and prod environments for a webapplication where react serves front-end and spring boot serves back-end.

