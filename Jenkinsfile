pipeline {
    agent {
        node {
            label 'maven'
        }
    }

    stages {
        stage('Clone-repo') {
            steps {
                git branch: 'main', url: 'https://github.com/cosmicqbit/tweet-trend.git'
            }
        }
    }
}
