pipeline {
    agent {
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
    }//stages
}//pipeline
