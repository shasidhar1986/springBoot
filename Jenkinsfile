node{
  git branch: "master", url: "https://github.com/shasidhar1986/springBoot" 

  stage ('Build and Deploy DSV image') {
    sh "docker build -t localhost:5000/jenkins-pipeline-example:dsv ."
    sh "docker push localhost:5000/jenkins-pipeline-example:dsv"
  }

}
