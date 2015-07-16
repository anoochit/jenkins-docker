# jenkins-docker

    docker run --restart=always --privileged -it -v /root/data:/var/jenkins_home \
            -p 8080:8080 -u root \
            anoochit/jenkins-dind
