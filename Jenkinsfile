pipeline {
  agent any
  stages {
    stage('Pre-reqs') {
    }
    stage('Verify') {
      parallel {
        stage('Lint') {
        }
        stage('Syntax') {
        }
        stage('Unit') {
        }
      }
    }
    stage('Smoke') {
    }
    stage('Stage files') {
    }
    stage('Upload') {
      parallel {
        stage('Dev') {
        }
        stage('Prod') {

        }
      }
    }
    stage('Cleanup') {
    }
  }
}
