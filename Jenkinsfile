pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                checkout([$class: 'GitSCM', branches: [[name: '*/development']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/Anees2022/git-project.git']]])
            }
        }
    }
}
