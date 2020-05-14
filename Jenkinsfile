pipeline {
      agent any
      stages {
          stage('Upload to AWS') {
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
