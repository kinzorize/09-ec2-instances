pipeline {
  agent any
  stages {
    stage('Git Checkout') {
      steps {
        git(url: 'https://github.com/kinzorize/09-ec2-instances.git', branch: 'main')
        echo 'Successfully checkout from Github'
      }
    }

  }
}