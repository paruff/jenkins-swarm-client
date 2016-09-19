# jenkins-swarm-client

Tiny alpine-based image to run Jenkins swarm client.  
This image also includes a Docker client, allowing to trigger jobs as docker containers 
(just need to bind the **/var/run/docker.sock** Docker socket to get this working).  
  
The client working directory is set to **/jenkins/wks**; you may bind it to a local path if you want to persist workspaces.  
  
Please refer to <https://wiki.jenkins-ci.org/display/JENKINS/Swarm+Plugin> for other arguments.
