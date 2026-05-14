// Updated pipelin
pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Building the code using Maven to compile and package the application'
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo 'Running unit tests using JUnit to ensure the code functions as expected'
                echo 'Running integration tests using Selenium to ensure components work together'
            }
        }

        stage('Code Analysis') {
            steps {
                echo 'Analysing the code using Checkstyle to ensure it meets industry standards'
            }
        }

        stage('Security Scan') {
            steps {
                echo 'Performing security scan using OWASP Dependency Check to identify vulnerabilities'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Deploying the application to staging server on AWS EC2 instance'
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo 'Running integration tests on staging environment to ensure the application functions as expected'
            }
        }

        stage('Deploy to Production') {
            steps {
                echo 'Deploying the application to production server on AWS EC2 instance'
            }
        }

    }
}
