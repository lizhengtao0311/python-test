pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            sh 'echo "Hello World"'
            sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
          }
        }

        stage('') {
          steps {
            echo 'fasdfasdasdf'
          }
        }

      }
    }

    stage('3333') {
      steps {
        echo '22222222'
      }
    }

  }
}