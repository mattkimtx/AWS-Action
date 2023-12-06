# Testing GitHub Action
- In this repo, I am testing how to use GitHub Action


### High Level plan to deploy code to EC2

1. Copy Django code from the previous repo to this current repo
2. Create a job in my action.yml file that connects to the AWS EC2 server
3. Once SSH is successful, copy files from GitHub to EC2 (only for files that were changed)
4. Check to make sure the files were copied successfully 
5. migrate files in Django and run server (activate python shell .env to run server)
6. Check to see if website is running. if not throw error
7. stop the server, deactivate the Python shell exit EC2.
