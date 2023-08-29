pipeline {
    agent any

    stages {

        stage('Hello') {
            steps {
                echo 'Hello World'
            
            }
        }
        stage('Print Top') {
            steps {

                sh"""
                set -x
                 ls

                """
            
            }
        }



    }


}
