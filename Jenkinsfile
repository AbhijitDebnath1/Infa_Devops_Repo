env.dockerimagename="devopsinfacts/devops_repo:buildon"
node {
   stage ('Code Checkout') {
   //If some other Repository is to be given apart from current repo, provide git URL as below demo...
   // checkout scm
	git url:'https://github.com/lalithavinoth/Infa_Devops_Repo.git'
  }   
   stage ('Informatica Deployment') {
	sh '/var/jenkins/informaticaDeployment.sh $commitID'
	}

}
