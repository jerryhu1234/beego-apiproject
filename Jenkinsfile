pipeline {
  agent {
    dockerfile {
      filename 'DockerFile'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'docker build -t beego-apiproject ./'
      }
    }
  }
}