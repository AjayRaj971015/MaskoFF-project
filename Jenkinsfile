pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'checking'
                fileExists 'p1.sh'
                echo 'output'
                sh '.p1.sh'   
            
            }
            
        }
    }
}
