

# Building Python with PyBuilder using a Jenkins Declarative Pipeline running on a Docker-based Build Agent

This project is used to demonstrate that:

1. The build agent of https://github.com/jvalentino/jenkins-agent-pyb (Docker Hub as `jvalentino2/jenkins-agent-pyb`) works
2. The Jenkins project of https://github.com/jvalentino/example-jenkins-docker-jcasc-2 is able to run this pipeline on the build agent

The basis of this project is https://github.com/jvalentino/example-python-pyb-lib-1, which had a Jenkinsfile added referencing the agent of `pyb` that is then setup as a Docker Build agent mapping to `jvalentino2/jenkins-agent-pyb`.

