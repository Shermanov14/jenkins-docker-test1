pipeline {
    agent {
        docker {
            image 'centos'
            label 'generic'
        }//step
    }//docker
    stages {
        stage ("Chech hostanem of docker container")
            steps {
                sh """
                    cat /etc/hostname
                    hostname
                """
            }//steps
        }//stage   
    }//stages
}//pipeline