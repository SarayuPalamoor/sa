# sa

https://www.youtube.com/watch?v=GLZAyt3g2Dk

PROJECT DEPLOYMENT IN THE AWS CLOUD USING EC2 INSTANCE

sudo apt update
sudo apt-get  install docker.io
 sudo apt install git
 sudo apt install nano

 <html>
<head><title>My Webpage</title></head>
<body><h1>Hello from AWS !< /h1></body>
</html>

git bash:
git init
git add .
$ git commit -m "some comit"
git branch -M main
git remote add origin https://github.com/SarayuPalamoor/aws.git
git push -u origin main

in cmd 
git clone "the url of repo (https://github.com/SarayuPalamoor/aws.git)"
ls
cd aws
ls
nano Dockerfile 
(Paste this)
FROM nginx:alpine
COPY . /usr/share/nginx/html

sudo docker build -t mywebapp .
sudo docker run -d -p 80:80 mywebapp

go to instance and copy public ipv4
paste in browser

