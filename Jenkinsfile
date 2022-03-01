node {
  stage ("SCM checkout"){
  git credentialsId: 'github', url: 'https://github.com/cherukurisai451/JavaWebApplicationStepByStep.git'
  }
   stage ("sonarqube"){
  echo 'build'
  }
  stage ("build"){
  echo 'build'
  }
   stage ("blackduck scan"){
  echo 'build'
  }
   stage ("checkmarx"){
  echo 'build'
  }
  stage ("Integration-test") {
    echo 'Test'
  }
   stage ("acceptance test"){
  echo 'build'
  }
   stage ("performance test"){
  echo 'build'
  }
  
  stage ("deploy") {
    echo'Deploy'
  }
  
}
