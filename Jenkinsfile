pipeline {
    agent {
        label "demoAgent"
    }

    stages {
        stage('Time') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                build 'SeleniumMaven'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
    post {
        always{
            echo 'pipeline done!!!!!!!!'
        }
    }
}
