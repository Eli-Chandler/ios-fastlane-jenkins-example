pipeline {
    agent { label 'fastlane-osx' }
    stages {
        stage('Install bundle') {
            steps {
                sh 'bundle install'
            }
        }
        stage('Run fastlane') {
            steps {
                sh 'bundle exec fastlane beta'
            }
        }
    }
}
