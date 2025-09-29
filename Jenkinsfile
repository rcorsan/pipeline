pipeline {
agent any
  stages {
    stage('Build') {
      steps {
        git branch: 'main'. url: 'https://github.com/rcorsan/pipeline.git'
        bat 'echo Construyendo...'
      }
    }
  stage('Test') {
    steps {
      bat 'echo Probando...'
    }
  }
  stage('Deploy') {
    steps {
      bat 'echo "Desplegando..."'
    }
  }
}
}
