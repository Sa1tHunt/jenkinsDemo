pipeline {
    agent {
        label "demoAgent"
    }

    stages {
        stage('Hello') {
            steps {
                echo 'Hello Hongik!'
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
