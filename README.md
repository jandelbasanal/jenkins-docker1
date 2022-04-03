# jenkins-docker1
I have configured slave node server which is my docker host as well. Used docker containers as my agent job executor.
Each Jenkins file defines different agent method how to use the container.

Jenkinsfile1 - uses agent in top level that means all stages will use this container image

Jenkinsfile2 - it uses different agent container in every stages

Jenkinsfile3 - it uses dockerfile for the agent container
