pipeline {
    agent any

    stages {
        stag('build') {
            steps {
                echo 'build the file'
            }
        }
	stage('test') {
            steps {
                echo 'test the file'
            }
        }
	stage('deploy') {
            steps {
                echo 'file deploy'
            }
        }
    }
}
