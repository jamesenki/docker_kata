pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World from Jenkins File'
                hangoutsNotify message: "James Cloud Guru", token: "8TAhr5dP97wKtVlaaWya6Hn5l", threadByJob: true
            }
        }
    }
}
