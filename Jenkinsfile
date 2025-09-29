pipeline {
agent any
  stages {
    stage('Build') {
      steps {
        git 'https://github.com/rcorsan/pipeline.git'
        bat 'mvn clean install' [cite: 94]
      }
    }
  stage('Test') {
    steps {
      bat 'mvn test' [cite: 99]
    }
  }
  stage('Deploy') {
    steps {
      bat 'echo "Desplegando..."' [cite: 104]
    }
  }
}
}
