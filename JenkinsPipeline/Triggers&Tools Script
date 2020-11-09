pipeline {
    agent any
    triggers {
        cron('H/2 * * * *')
    }
    stages {
        stage('Example') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
