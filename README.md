Pre-requisite

    Docker  

    On Windows
    https://docs.docker.com/desktop/install/windows-install/


    On Ubuntu
    https://docs.docker.com/engine/install/ubuntu/#install-using-the-repository


Run Jenkins docker liter version

    1) docker run -p 8080:8080 -p 50000:50000 --restart=on-failure -v jenkins_home:/var/jenkins_home jenkins/jenkins:lts-jdk17

    2) Save Password samewhere safe "3d7f319d9f61425d876ab0478f62fc5a"
    3) http://localhost:8080/
    4) Enter Password from step 2
    5) Install "Suggested Plugin"
    6) Optional Step to create admin user
    7) Continue as Admin
    8) Save and Continue


   