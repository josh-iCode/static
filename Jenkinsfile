pipeline {
      agent any
      stages {
          stage('Build') {
              steps {
                  sh 'echo "HELLO WORLD"'
                  sh '''
                      echo "Multiline shell steps works too"
                      ls -lah
                  '''
              }
          }
      }
}
