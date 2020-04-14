pipeline {
    agent {
        docker {
            image 'centos'
            label 'generic'
        }//docker
    }//agent
    stages {
        stage ("Chech hostanem of docker container") {
            steps {
                sh """
                    cat /etc/hostname
                    hostname
                """
            }//steps
        }//stage   
    }//stages
}//pipeline
