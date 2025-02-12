pipeline {
    agent any

    stages {
        stage('Run Python Script') {
            steps {
                sh 'python3 greet.py' // For Linux/macOS
                // bat 'python script.py' // Uncomment for Windows
            }
        }
    }
}
