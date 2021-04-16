pipeline {
    agent any
    environment { 
        VAR1 = 'clang'
        VAR2 = 'micsu di'
    }
    stages {
        stage('Example') {
            steps {
                echo "printenv"
            }
        }
    }
    post { 
        unsuccessful { 
            echo 'I will always say Hello again!'
        }
    }
}
