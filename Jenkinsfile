pipeline {
  agent any
  stages {
    stage('poll vcs') {
      steps {
        git(url: 'https://github.com/AdamRate/BOTEST.git', branch: 'master', poll: true)
      }
    }
    stage('confirm') {
      steps {
        echo 'DONE!'
      }
    }
  }
}