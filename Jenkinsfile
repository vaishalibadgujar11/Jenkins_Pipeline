pipeline {
  agent none
  stages {
    stage('Apex Installstion') {
      steps {
        node(label: '214_Mars') {
          echo 'Copy and Install Apex build'
        }

      }
    }

    stage('Database Setup') {
      steps {
        echo 'DB Setup'
      }
    }

    stage('SVN Update') {
      steps {
        echo 'checkout code'
      }
    }

    stage('Batch Execution') {
      steps {
        echo 'Execute Sanity'
      }
    }

  }
}