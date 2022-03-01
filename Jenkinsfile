node {
  stage ("SCM checkout"){
  git credentialsId: 'github', url: 'https://github.com/cherukurisai451/JavaWebApplicationStepByStep.git'
  }
  stage ("build"){
  sh 'mvn clean package'
  }
  stage ("test") {
    echo 'Test'
  }
  
  stage ("deploy") {
    echo'Deploy'
  }
  
}
