# node-todo-cicd
I use azure virtual machine with linux OS to setup jenkins and install docker on it. Build a simple node js app from a Dockerfile in which base image is node:alpine and copy current files in workdir app and expose 8000 port to map on host system which runs CMD["node","app.js"] in daemon mode. We configured github to connect system via ssh-keygen and add shh key to github. Then, install github integration plug-in and configure github-webhook to trigger jenkins via GitSCM polling to apply the committed changes.

sudo apt install nodejs
sudo apt install npm


npm install

node app.js

