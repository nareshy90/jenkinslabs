pipeline {
  agent any
  stages {
    stage('Deploy') {
      steps {
        sh '''#!/bin/bash
aws cloudformation deploy --template-file ./ec2-demo.yml --stack-name test-cfn-jenkins-pipeline --region ap-southeast-2'''
      }
    }

  }
}
