pipeline {
  agent any
  stages {
    stage('Pre-reqs') {
      steps {
      }
    }
    stage('Verify') {
      parallel {
        stage('Lint') {
          steps {
          }
        }
        stage('Syntax') {
          steps {
          }
        }
        stage('Unit') {
          steps {
          }
        }
      }
    }
    stage('Smoke') {
      steps {
      }
    }
    stage('Stage files') {
      steps {
      }
    }
    stage('Upload') {
      parallel {
        stage('Dev') {
          steps {
          }
        }
        stage('Prod') {
          steps {
          }
        }
      }
    }
    stage('Cleanup') {
      steps {
      }
    }
  }
}
