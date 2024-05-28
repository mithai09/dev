Building Your Image Cmd 
docker build -t docker-container-nodejs .

Confirm that the image has been created.
docker images

Run the image
docker run -d -p 8000:3000 -v address_to_app_locally:/app docker-container-nodejs 

Set up a multi stage jenkins pipeline where each stage is run on a unique agent. This is a very useful approach when you have multi language application or application that has conflicting dependencies.
