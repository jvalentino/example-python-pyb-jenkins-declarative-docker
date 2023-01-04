pipeline {
  agent { label 'pyb' }

  stages {
    
    stage('Install') {
      steps {
          sh 'pyb install_dependencies'
      }
    }

    stage('Build') {
      steps {
          sh 'pyb'
      }
    }

  }
}