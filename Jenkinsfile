pipeline {
agent any
  stages {
    stage('Build') {
      steps {
        git 'https://github.com/rcorsan/pipeline.git'
        bat 'echo Construyendo...' [cite: 94]
      }
    }
  stage('Test') {
    steps {
      bat 'echo Probando...' [cite: 99]
    }
  }
  stage('Deploy') {
    steps {
      bat 'echo "Desplegando..."' [cite: 104]
    }
  }
}
}
