pipeline {
    agent docker
3
    stages         
4
        stage('Build') {
5
​
6
            steps {
7
                image 'maven:3-alpine'
8
                label 'my-defined-label'
9
                args  '-v /tmp:/tmp'
10
​
11
​
12
            }
13
​
14
        }
}
