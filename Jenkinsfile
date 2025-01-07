pipeline {
    agent any

    stages {
        stage('Version') {
            steps {
                sh 'python3 --version'
            }
        }
        stage('Deploy') {
            steps {
                sh 'streamlit run Current_price.py'
            }
        }
        
    }
}
