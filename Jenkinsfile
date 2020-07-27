node{
  stage('SCM checkout') {
    git 'https://github.com/parthidevops/devops_test/mvn_demo'
  }
  stage('compile-package') {
    sh 'mvn package'
  }
}
