pipeline {
  agent {
    dockerfile {
      filename 'Dockerfile'
    }

  }
  stages {
    stage('run') {
      steps {
        sh 'docker run --rm $Image.id hostname'
      }
    }
  }
}