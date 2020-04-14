pipeline {
    agent {
        docker {
            image 'python'
            label 'generic'
        }//step
    }//docker
    stages {
        stage ("Run helloworld.py") {
            steps {
                sh """
                    python helloworld.py
                    mv helloworld.py goodbyeworld.py
                """
            }//steps
        }//stage   
    }//stages
}//pipeline