pipeline {
      agent any
      stages {
            stage('Init') {
                  steps {
                        echo 'Hi, this is DamiaNeoDon this time'
                        echo 'We are Starting the Testing'
                  }
            }
            stage('Build') {
                  steps {
                        echo 'Building Sample Maven Project'
                  }
            }
            stage('Deploy') {
                  steps {
                        echo "Deploying in Staging Area"
                  }
            }
            stage('Deploy Production') {
                  steps {
                        echo "Deploying in Production Area"
                  }

            }stage('Concluding step') {
                  steps {
                        echo "Concluding extra step in production"
                  }

            }
      }
}
