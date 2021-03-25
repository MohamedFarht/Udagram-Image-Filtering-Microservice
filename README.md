# Udagram Image Filtering Microservice

###Endpoint on Elastic Beanstalk
try this: http://udagram-image-filtering-microservice-dev.eu-central-1.elasticbeanstalk.com/

###Test it with 
http://udagram-image-filtering-microservice-dev.eu-central-1.elasticbeanstalk.com/filteredimage?image_url=https://images.pexels.com/photos/414612/pexels-photo-414612.jpeg



### Setup Node Environment

You'll need to create a new node server. Open a new terminal within the project directory and run:

1. Initialize a new project: `npm i`
2. run the development server with `npm run dev`


### Deploying your system

Follow the process described in the course to `eb init` a new application and `eb create` a new environment to deploy your image-filter service! Don't forget you can use `eb deploy` to push changes.


### Custom Domain Name

Add your own domain name and have it point to the running services (try adding a subdomain name to point to the processing server)
> !NOTE: Domain names are not included in AWS’ free tier and will incur a cost.
