# my-demo
first docker project
let's try to commit from VSCode
and edit from github.dev (just press '.' on any repo)
and modify with VSCode Local
and modify in Linux with nano

# build with (do not forget the final dot :-)
docker build -t hello:latest -f dockerfile-hello .

#Run your newly built image with 
docker run -p 8000:8000 hello:latest

#From your computer, open a browser and navigate to
http://localhost:8000

WOW server in Linux WSL e client in Windows !!!

#if necessary stop with
docker container ls -a
docker container stop <container name>
