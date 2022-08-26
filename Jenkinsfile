pipeline {
  agent any
  stages {
    stage('') {
      steps {
        git 'https://github.com/sangramrath/simple-java-maven-app.git'
        sh 'mvn -B -DskipTests clean package'
      }
    }

  }
}