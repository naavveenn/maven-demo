pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git(url: 'https://github.com/naavveenn/maven-demo.git', branch: 'master')
      }
    }

    stage('Test1') {
      steps {
        echo 'test 1 passed'
      }
    }

    stage('Test2') {
      steps {
        sh '''#!/bin/bash
echo "Hello world..test2"'''
      }
    }

  }
}