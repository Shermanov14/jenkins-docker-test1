pipeline {
    agent {
        dockerfile true
        label 'generic'
    }//agent
    stages {
        stage ("Run helloworld.py") 
        stage ("Chech hostanem of docker container") {
            steps {
                sh """
                    python helloworld.py
                    mv helloworld.py goodbyeworld.py
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
