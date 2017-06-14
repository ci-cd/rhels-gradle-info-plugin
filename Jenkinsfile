pipeline {
  agent any
  stages {
    stage('') {
      steps {
        sh ''' withSonarQubeEnv('My SonarQube Server') {
      sh 'mvn clean package sonar:sonar'
    }'''
        }
      }
    }
  }