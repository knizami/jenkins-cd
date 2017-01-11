# jenkins-cd

docker build -t jenkins-cd 

docker run --name myjenkins -p 8080:8080 -p 50000:50000 --env JAVA_OPTS=-Dhudson.footerURL=https://github.com/knizami/jenkins-cd jenkins


