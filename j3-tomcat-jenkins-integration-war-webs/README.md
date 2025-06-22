# jenkins-tomcat
First prepare the TOMCAT Server along with Jenkins Server in different EC2 at AWS Cloud.
In Jenkins we must have 

###############################################
Dashboard > Jenkins-Tomcat( Server Name ) > Pipeline ====> Points to remember
1. While adding agent any in Pipeline code - In tools maven name should be same as given in like Maven Tool
2. We are saving artifacts in war file
3. At Deploying Artifact > sshagent > Name should be same as given in Jenkins Dashboard > Credentials > User ID name
4. 
