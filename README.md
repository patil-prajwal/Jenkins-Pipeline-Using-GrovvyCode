![Jenkins With Kubernetes](https://i0.wp.com/foxutech.com/wp-content/uploads/2019/01/How-to-run-groovy-script-in-Jenkins.png?resize=696%2C377&ssl=1)

# **Problem Statement :**

1. _Create container image that’s has Jenkins installed using Dockerfile Or You can use the Jenkins Server on RHEL 8/7._

2. _When we launch this image, it should automatically starts Jenkins service in the container._

3. _Create a **Job Chain** of Job1, Job2, Job3 and Job4 using Build Pipeline Plugin in Jenkins._

4. _**Job2** (Seed Job) : Pull the Github repo automatically when some developers push repo to Github._

5. _Further on jobs should be pipeline using written code using Groovy language by the developer_

6. **Job1** : 
   
	_**A.** By looking at the code or program file, Jenkins should automatically start the respective language interpreter installed image container to deploy code on top of Kubernetes (Eg. If code is of PHP, then Jenkins should start the container that has PHP already installed)_

	_**B.** Expose your pod so that testing team could perform the testing on the pod_

	_**C.** Make the data to remain persistent using PVC (If server collects some data like logs, other user information)_

7. **Job3** : 
   
    _Test your app if it is working or not._

8. **Job4** : 
   
    _If app is not working , then send email to developer with error messages and redeploy the application after code is being edited by the developer._

[For More Info Please Visit Here](https://docs.google.com/document/d/1jAwEo3egWn1_njjPLd2-yUUCndkCSvh7eZIQHXM1S3s/edit?usp=sharing)


<p align="center">
    <a href="#" alt="Jenkins"><img height="100" width="100" src="https://github.com/patil-prajwal/Tech-Stack-Icons/blob/main/Icons/jenkins.svg"></a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
    <a href="#" alt="Groovy"><img height="100" width="100" src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/36/Groovy-logo.svg/445px-Groovy-logo.svg.png"></a>
    
  </p>

DevOpsT/6