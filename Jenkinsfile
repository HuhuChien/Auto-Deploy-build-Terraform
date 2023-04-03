pipeline {
   agent any
    stages {
        stage('use dir') {
            steps {
                dir('the_data_virtualenv'){
                    sh 'python main.py'
                }
            }
        }
    }
}