pipeline {
    agent any

    stages {
        stage ('Compile Stage') {
          steps{
            sh 'make'
          }
          
        }

        stage ('Testing Stage') {

            steps {
                sh 'make check'
            }
        }


        stage ('Deployment Stage') {
            steps {
                sh 'make publish'
            }
        }
    }
}
