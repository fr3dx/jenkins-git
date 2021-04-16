pipeline {
    agent any
    environment { 
        VAR = 'clang'
    }
    stages {
        stage('Example') {
            steps {
                echo '$VAR'
            }
        }
    }
    post { 
        unsuccessful { 
            echo 'I will always say Hello again!'
        }
    }
}
