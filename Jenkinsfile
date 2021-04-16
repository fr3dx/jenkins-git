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
        unsuccessful { 
            echo 'I will always say Hello again!'
        }
    }
}
