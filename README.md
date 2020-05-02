# Docker_Project
I have made one self-hosted file sync and share server in which I have used a cloud app such as OwnCloud and MySQL Database. The entire service can be Start/Stop by using just a single command using docker-compose.

# What is OwnCloud 
ownCloud is a self-hosted file sync and share server. It provides access to your data through a web interface, sync clients or WebDAV while providing a platform to view, sync and share across devices easily—all under your control. ownCloud’s open architecture is extensible via a simple but powerful API for applications and plugins and it works with any storage.

# To run 
Use the following command in the directory where the "docker-compose.yml" file is present

-- docker-compose up

To stop

-- docker-compose down

# Troubleshooting the errors
If you face any error while launching docker-compose then run this two commands in terminal
  
  -- systemctl stop firewalld
  
  -- systemctl restart docker
  
# Note
-- This project was build on Redhat 8

-- Please use Bridge Adapter in Networks if Running on Virtual Machine
