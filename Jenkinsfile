pipeline {
    agent any

    triggers {
        githubPush()
    }

    stages {
        stage('Notify on Commit') {
            steps {
                script {
                    // Telegram ¸޽Ãö¼Û                    sh "curl -s -X POST https://api.telegram.org/bot6897611448:AAGSYozfLZDhCKY12Y8umUbGogqT10oCq6c/sendMessage -d chat_id=-1002030069453 -d text='New commit detected on branch"
                }
            }
        }
    }
}
