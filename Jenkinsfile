node{
  stage('GIT REMOTE PULL') {
    git 'https://github.com/parthidevops/devops_test'
  }
  stage('CLEAN') {
    sh 'mvn clean'
  }
  stage('COMPILE') {
    sh 'mvn compile'
  }
  stage('TEST') {
    sh 'mvn test'
  }
  stage('PACKAGE') {
    sh 'mvn package'
  }
}
