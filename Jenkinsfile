pipeline {
    agent {
        dockerfile true
        label 'generic'
    }//agent
    stages {
        stage ("Run helloworld.py") {
            steps {
                sh """
                   python helloworld.py
                   mv helloworld.py goodbyeworld.py 
                """
            }//steps
        }//stage
        stage("Test request"){
            steps {
                sh """
                    python requestgoogle.py
                """
            }//steps
        }//stages    
    }//stages
}//pipeline
