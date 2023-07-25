##  Deploy-Simple-HTML-WebPage-Using-Nginx

- index.html 
- nginx

All components are docker-based

### With Git


Step 1: clone the repo

    git clone https://github.com/mahmoudsaleh74/Deploy-Simple-HTML-WebPage-Using-Nginx.git

### linux command
Step 2: change Directory 

   cd Deploy-Simple-HTML-WebPage-Using-Nginx
#### with docker To start the application

Step 3: start nginx
    
    docker run -it -d  --name html -v .:/usr/share/nginx/html/ -p 8080:80 nginx


