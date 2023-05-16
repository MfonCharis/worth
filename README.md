# Worth System
WORTH Cloud Engineer Tech Test

This sets out to acheive the following The site should be served to the public.

Two marketing users Alice & Malory should have access to only add to the /news section
Bobby the content editor needs to be able to edit the entire website.
Charlie works in HR and should be able to update /people.html
Add a custom error document.
Automation of testing & deployment of infrastructure.

# Why choose a mongo db
Flexible data model: MongoDB is a document-based database, which means that it can handle data in a more flexible and dynamic way than traditional relational databases. This makes it easier to store and retrieve data for applications with complex or changing data structures.

Mongo is highly scalable and effective for handling spikes in user traffic

Performance: MongoDB is optimized for fast read and write operations, which can improve the performance of applications that need to access data frequently.

Easy integration with nodejs. Mongo is also open source with good vendor support

# DockerFile
This Dockerfile assumes that your application code is in the same directory as the Dockerfile. It installs Node.js and MongoDB, sets up the MongoDB data directory, and exposes the ports for the web server and MongoDB. The CMD directive at the end starts MongoDB in the background and then starts the web server.

# JenkinsFile
Groovy pipeline script that automates the deployment of the website using Jenkins, the Dockerfile, and the Terraform plugin into a webserver
