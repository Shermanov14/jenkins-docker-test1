pipeline {
    agent {
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
