pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                echofhgfg 'Hello World'
            }
        }
    }
    post { 
        failure { 
            echo 'I will always say Hello again!'
        }
    }
}
