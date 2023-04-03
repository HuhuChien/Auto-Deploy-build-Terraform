pipeline {
   agent any
    stages {
        stage('use dir') {
            steps {
                dir('the_data_virtualenv'){
                    bat 'python3 main.py'
                }
            }
        }
    }
}