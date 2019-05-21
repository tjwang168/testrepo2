
pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
		echo "building.."
		echo "2nd echo line"
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}

