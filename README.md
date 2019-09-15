## Details

+ The template is made with by Colorlib.
+ The RSVP is made with Rsvpify.

## Nginx Custom Runtime for App Engine

+ `app.yaml` - Configuration file for App Engine. This just declares the runtime is custom and to use the Dockerfile to run the application.
+ `Dockerfile` - Defines your docker image. It extends from the official nginx Docker image and adds the configuration and static files.
+ `nginx.conf` - A basic nginx configuration file.
+ `www/index.html` - Root page to be served by nginx.
