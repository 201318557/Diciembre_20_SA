pipeline {
    agent any

    stages {
        stage ('Compile Stage') {
          steps{
            echo 'make'
          }
          
        }

        stage ('Testing Stage') {

            steps {
                echo 'make check'
            }
        }


        stage ('Deployment Stage') {
            steps {
                echo 'make publish'
            }
        }
    }
}
