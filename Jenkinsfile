pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building My project'
            }
        }
		 stage('Test') {
            steps {
                echo 'Test My project'
            }
        }
		 stage('Deploy') {
            steps {
                echo 'Deploy My project'
            }
        }
    }
    post{
        always{
            emailext body: 'I am happy that I am learning', subject: 'Pipeline status', to: 'srivastava.vivekcs65@gmail.com'
        }
    }
}
