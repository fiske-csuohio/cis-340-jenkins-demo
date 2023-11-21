pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'javac java/basic/Basic.java'
		sh 'cd java; printf "64\n" | java basic.Basic'
            }
        }
    }
}
