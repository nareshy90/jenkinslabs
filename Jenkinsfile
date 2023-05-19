pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''#!/bin/bash
echo "Hello World! from Jenkins pipeline"'''
        echo 'Hello'
      }
    }

    stage('release') {
      steps {
        build 'release'
      }
    }

  }
}