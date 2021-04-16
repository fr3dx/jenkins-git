pipeline {
    agent docker
    stages         
        stage('Build') {

            steps {
                image 'maven:3-alpine'
                label 'my-defined-label'
                args  '-v /tmp:/tmp'


            }

        }
}
