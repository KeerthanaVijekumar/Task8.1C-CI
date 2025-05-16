pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git branch: 'main', url: 'https://github.com/KeerthanaVijekumar/Task8.1C-CI.git'
      }
    }
    stage('Build') {
      steps {
        echo 'Building the code using Maven'
      }
    }
    stage('Unit and Integration Tests') {
      steps {
        echo 'Running tests using JUnit'
      }
    }
    stage('Code Analysis') {
      steps {
        echo 'Analyzing code with SonarQube'
      }
    }
    stage('Security Scan') {
      steps {
        echo 'Performing security audit with npm audit'
      }
    }
    stage('Deploy to Staging') {
      steps {
        echo 'Deploying to a staging environment using Ansible'
      }
    }
    stage('Integration Tests on Staging') {
      steps {
        echo 'Running integration tests on the staging server'
      }
    }
    stage('Deploy to Production') {
      steps {
        echo 'Deploying to production with Ansible'
      }
    }
  }
}