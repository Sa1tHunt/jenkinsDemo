pipeline {
    agent {
        label "demoAgent"
    }

    stages {
        stage('Time') {
            steps {
                echo '2022-06-07-14-00'
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
