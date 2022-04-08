pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo "Hello World!"
            }
        }
      stage('UAT') {
            steps {
                echo "Hello from UAT environment!"
            }
        }
      stage('PROD') {
            steps {
              echo "Hello from PROD environment!"
            }
        }
    }
}
