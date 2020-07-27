node{
  stage('SCM checkout') {
    git 'https://github.com/parthidevops/devops_test'
  }
  stage('compile-package') {
    sh 'mvn package'
  }
}
