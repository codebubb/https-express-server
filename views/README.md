# https-express-server
## Basic Express server, set to run on secure https://localhost/

I originally created this to just test out Facebook logins whilst working locally.

I have kept the original 'Login With Facebook' page to be served when the Express server is running.

All the certs and keys have been pre-generated in the `keys` folder.

You will just need to make sure that you add the `rootCA.pem` key to your list of **Trusted Root CAs**.

Then just `npm start` and you can access your content at `https://localhost/`.