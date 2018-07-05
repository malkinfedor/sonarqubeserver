Wher run this container have to mount some dirs:
volumes:
  - $PWD/sonar:/opt/sonarqube/data:z
  - $PWD/qualityprofile:/qualityprofile:z
  - $PWD/extensions:/opt/sonarqube/extensions:z
