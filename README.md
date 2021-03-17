# docker configuration using ansible
🔰An Ansible PlayBook that does the following operations in the managed nodes: 🔹 Configure Docker 🔹 Start and enable Docker services 🔹 Pull the httpd server image from the Docker Hub 🔹 Run the docker container and expose it to the public 🔹 Copy the html code in /var/www/html directory and start the web server

In import.yml file I have imported two files i.e yum.yml and docker.yml
