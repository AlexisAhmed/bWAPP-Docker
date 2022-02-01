<img src="https://www.ehacking.net/wp-content/uploads/2014/02/bwapp.jpg"
     alt="bWAPP"
     style="float: left; margin-right: 10px;" />


# bWAPP-Docker
As the title suggests, this is a simple Docker image for the OWASP bWAPP application designed to teach and demonstrate various web app vulnerabilities.

# Why?
Installing and configuring PHP based web apps can be quite time consuming as you need to install various packages like PHP, Apache, MySQL etc...
This Docker image eliminates(automates;)) this tedious process and provides you with a click and run solution that will provide you with a bWAPP instance in a few seconds.

# Setup
## Build your own Docker image
- Feel free to clone the repository and modify the bWAPP app as required.

## Pull the Docker image
- This repo provides you with a prebuilt Docker image that you can pull and run in seconds.
```
docker pull hackersploit/bwapp-docker
```

## Running the bWAPP container
```
docker run -d -p 80:80 hackersploit/bwapp-docker
```

## Installing bWAPP
- After running the bWAPP container, navigate to http://127.0.0.1/install.php to complete the bWAPP setup process.




