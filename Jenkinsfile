pipeline {

    agent any

    environment {

        APP_NAME = "Test-App"
        APP_VERSION = "1.0.0"
        APP_ENV = "dev"
    }
    stages {
        stage("Build") {
            steps {
                echo "Building Application..."
                echo "Building App with name ${APP_NAME}"
                echo "App version is ${APP_VERSION}"
                echo "App Environment is ${APP_ENV}"
            }
        }
        stage("Test") {
            steps {
                echo "Test Application..."
                echo "Building App with name ${APP_NAME}"
                echo "App version is ${APP_VERSION}"
                echo "App Environment is ${APP_ENV}"
            }
        }
        stage("Deploy") {
            steps {
                echo "Deploy Application.."
                echo "Building App with name ${APP_NAME}"
                echo "App version is ${APP_VERSION}"
                echo "App Environment is ${APP_ENV}"
            }
        }
    }
       post {
        success {
            echo "Pipeline is successfull"
        }
        failure {
            echo "This pipeline is failed"
        }
        always {
            echo "Whether success or fail, you should run"
        }
    }
}
