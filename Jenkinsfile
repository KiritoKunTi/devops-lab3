pipeline {
    agent any

    stages {
        stage('Run Python Script') {
            steps {
                sh 'python greet.py' // For Linux/macOS
                // bat 'python script.py' // Uncomment for Windows
            }
        }
    }
}
