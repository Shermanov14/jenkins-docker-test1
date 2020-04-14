pipeline {
    agent {
<<<<<<< HEAD
        dockerfile true
        label 'generic'
    }//agent
    stages {
<<<<<<< HEAD
        stage ("Run helloworld.py") {
=======
        stage ("Chech hostanem of docker container") {
>>>>>>> ed045ede81548a780c8ce862e42869760f715f28
            steps {
                sh """
                    python helloworld.py
                    mv helloworld.py goodbyeworld.py
=======
        docker {
            image 'python'
            label 'generic'
        }//docker
    }//agent
    stages {
        stage ("Run .py") {
            steps {
                sh """
                   python helloworld.py
                   mv helloworld.py goodbyeworld.py 
>>>>>>> 6c16a9a80983eeaeef2a9b95a33bd986e050c6f5
                """
            }//steps
        }//stage
        stage("Test request")
            steps {
                sh """
                    python requestgoogle.py
                """
            }   
    }//stages
}//pipeline
