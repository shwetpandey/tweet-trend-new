pipeline {
    agent {
        node{
            label 'maven'
        }
    }

    stages {
        stage('clone git code') {
            steps {
                git branch: 'main', url: 'https://github.com/shwetpandey/tweet-trend-new.git'
            }
        }
    }
}
