**Project Title**

A basic HTML website containerized with Docker

**Description**

This project showcases a simple HTML website built with HTML, CSS, and JS. To make it easily deployable and portable, I created a Dockerfile to containerize the website. With a single command, you can run the website in a Docker container.

**Technologies Used**

- HTML
- CSS
- JS
- Docker

**To Run This Project In Your Machine Follow the steps**
- Step 1: You Need A Docker In your machine:
   - If You are Using Linux run command **sudo apt install docker.io**
   - After Installation to Verify run commans **systemctl status docker**
   - It Will Show you something like this 
   ![image](https://github.com/user-attachments/assets/d37b8468-20c0-4b81-b056-46d03a318f7c)
   
   - If you are windows you can click here and install https://docs.docker.com/desktop/install/windows-install/

- Step 2: Clone this github repository to your local machine

- Step 3: Now you need to convert all these files into Docker images
   - For that Navigate to the cloned folder using terminal and run **docker build . -t my-website:latest**

- Step 4: Now you need to create container for the created docker image
   - For that run a command **docker run -d -p 80:80 my-website:latest**

<br>

**Now You can Able to see my website in you localhost:8080 !!!!** <br>
<br>
**If You Face Any Difficulties While Running This Project Feel Free to Ping me**
  
