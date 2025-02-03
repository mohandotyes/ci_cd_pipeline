pipeline {
    agent any
    tools {
        jdk 'jdk17'
        
    }
    stages {
        stage ("clean workspace") {
            steps {
                cleanWs()
            }
        }
        stage ("Git Checkout") {
            steps {
                git 'https://github.com/mohandotyes/ci_cd_pipeline.git'
            }
        }

    }
