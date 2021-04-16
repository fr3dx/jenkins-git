pipeline {
    agent any
    environment { 
        VAR1 = 'clang'
        VAR2 = 'micsu di'
    }
    stages {
        stage('Example') {
            steps {
                echo "$VAR1"
                echo "$VAR2"
            }
        }
    }
    post { 
        unsuccessful { 
            echo 'I will always say Hello again!'
        }
    }
}
