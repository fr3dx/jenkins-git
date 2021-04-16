pipeline {
    agent any
    environment { 
        VAR = 'clang'
        VAR2 = 'micsu di'
    }
    stages {
        stage('Example') {
            steps {
                echo "$VAR"
            }
        }
    }
    post { 
        unsuccessful { 
            echo 'I will always say Hello again!'
        }
    }
}
