# jenkins-docker


  docker run --restart=always --privileged --dns 8.8.8.8 -d --name jenkins -v /home/xavier/data:/var/jenkins_home -p 1080:8080 -u root anoochit/jenkins-dind
