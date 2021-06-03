pipeline {
      agent any
      stages {
            stage('Init') {
                  steps {
                        echo 'Hi, thifs is Anshul from LevelUp360'
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
            stage('Deploy Productions') {
                  steps {
                        echo "Deploying in Productidon Area"
                  }
            }
      }
}
