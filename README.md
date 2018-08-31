A basic framework to get started with a Web App with a front-end and back-end component all in one place, to be deployed to the GCP App Engine.

The front-end component is located in the /client directory, and is a vanilla create-react-app with an additional proxy setting so that it can communicate with the server.

The server is located in the /server directory, and is a very basic Node.js server using Express.js (though you can use anything you like).

Credit to the following tutorials for setting this up:

https://medium.freecodecamp.org/how-to-make-create-react-app-work-with-a-node-backend-api-7c5c48acb1b0
https://developer.mozilla.org/en-US/docs/Learn/Common_questions/How_do_you_host_your_website_on_Google_App_Engine
