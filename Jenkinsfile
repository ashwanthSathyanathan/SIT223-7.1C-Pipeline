pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build stage: compiling and packaging the source code.'
                echo 'Tool: Maven (build automation to compile and package the code).'
            }
        }
        stage('Unit and Integration Tests') {
            steps {
                echo 'Test stage: running unit tests and integration tests.'
                echo 'Tools: JUnit for unit tests, Selenium for integration tests.'
            }
        }
        stage('Code Analysis') {
            steps {
                echo 'Code Analysis stage: checking the code against industry standards.'
                echo 'Tool: SonarQube (static code analysis).'
            }
        }
        stage('Security Scan') {
            steps {
                echo 'Security Scan stage: scanning the code for vulnerabilities.'
                echo 'Tool: OWASP Dependency-Check (scans dependencies for known CVEs).'
            }
        }
        stage('Deploy to Staging') {
            steps {
                echo 'Deploy to Staging stage: deploying the app to a staging server.'
                echo 'Tool: AWS CLI (deploy to an AWS EC2 staging instance).'
            }
        }
        stage('Integration Tests on Staging') {
            steps {
                echo 'Staging Tests stage: running integration tests in a production-like environment.'
                echo 'Tool: Postman with Newman (automated API integration testing).'
            }
        }
        stage('Deploy to Production') {
            steps {
                echo 'Deploy to Production stage: deploying the app to the production server.'
                echo 'Tool: AWS CLI (deploy to an AWS EC2 production instance).'
            }
        }
    }
}
