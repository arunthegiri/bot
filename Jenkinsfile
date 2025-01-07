pipeline {
    agent any

    stages {
        stage('Version') {
            steps {
                sh 'python3 --version'
            }
        }
        stage('Getting requirements') {
            steps {
                sh '/usr/bin/pip3 install -r requirements.txt'
            }
        }
        stage('Deploy') {
            steps {
                sh 'streamlit run Current_price.py'
            }
        }
        
    }
}
