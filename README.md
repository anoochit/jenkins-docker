# Jenkins with Docker in Docker

    docker run --restart=always --privileged --dns 8.8.8.8 -d --name jenkins \
        -v /data:/var/jenkins_home -p 8080:8080 -u root \
        anoochit/jenkins-dind
