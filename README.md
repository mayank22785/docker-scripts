# docker-scripts
docker automated scripts
Jenkins Slave Docker container

Based on https://github.com/thaeli/docker-images

A Jenkins Slave for Jenkins Docker Plugin using Ubuntu 14.04 Trusty.

Usage

Pull this image on target slave of jenkins.
docker pull mayankrs/jenkins-slave-ubuntu
Setting jenkins.

Install Jenkins Docker Plugin.
Add Docker template to Cloud provider from System Setting.
Limit target job's execution node to Label of above template.
