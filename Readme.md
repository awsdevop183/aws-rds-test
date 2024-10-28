# Node Application to check database connection

1. Install docker on Ubuntu
```sudo apt update -y && sudo curl https://get.docker.com | bash```
2. Make directory structure as per the project, create required files and paste the content

3. Update app.js file with appropriate DB credentials

4. Connect to your DB and Create Database and Table as per mysql.db file

5. Create Docker image with ```docker build -t testdb .```

6. Create a container from the image ```docker run -d --name db -p 90:3000 testdb```