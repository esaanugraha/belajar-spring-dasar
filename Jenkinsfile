peline {
    agent {
        node {
            label "docker-esa"
        }
    }

    stages {
        stage('Hello') {
            steps {
                sh 'echo "test-jenkins" > index2.html'
            }
        }
    }
}

post {
    always {
        echo "I will always say hello again !"
    }
    success {
        echo "Yey, Sucsess"
    }
    failure {
        echo "Oh no, Failure"
    }
    cleanup {
        echo "Don't care success or error"
    }
}