# entprise-bot

Task Submission: Setting up Elasticsearch in Docker
Added Launch
Launched EC2 Instance in AWS:
o	Logged in to AWS Management Console.
o	Navigated to EC2 and clicked on "Launch Instance".
o	Chose an Amazon Machine Image (AMI) like Ubuntu.
o	Selected an Instance Type: t2.micro.
o	Configured Instance Details including network settings and storage requirements.
o	Created a Security Group with custom TCP rules for ports 9200 and 9300
 

Configured and Set Up
Configured and Set Up Elasticsearch with Docker:
o	Created a Dockerfile on the EC2 instance with Ubuntu 14.04 : dockerfile
o	Built the Docker image : docker build -t my-es-image .
o	Started the Elasticsearch container: docker run --rm -d -p 9200:9200 -p 9300:9300 my-es-image
Pushed and Verified
Pushed Dockerfile to GitHub:
o	Installed Git on the EC2 instance: sudo apt-get update , sudo apt-get install git
o	Pushed the Dockerfile and related files to GitHub repository named enterprise-bot.
Verified Elasticsearch Installation:
Accessed Elasticsearch at http://52.90.217.64:9200/ to confirm it's running.
 



