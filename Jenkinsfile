pipeline {
    agent { label 'fastlane-osx' }
    stages {
        stage('Install bundle') {
            steps {
                bat 'bundle install'
            }
        }
        stage('Run fastlane') {
            steps {
                bat 'bundle exec fastlane beta'
            }
        }
    }
}
