env.dockerimagename="devopsinfacts/devops_repo:buildon"
node {
   stage ('Code Checkout') {
   //If some other Repository is to be given apart from current repo, provide git URL as below demo...
    checkout scm
  }   
   stage ('Infomatica Deployment') {
	sh '/var/jenkins/informaticaDeployment.sh $commitID'
	}

}
