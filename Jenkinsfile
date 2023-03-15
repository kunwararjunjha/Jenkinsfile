pipeline {
    agent any
    stages {
        stage('build maven') {
            parallel {
                            stage('Build Docker Image') {
            steps {
                        script {
                    sh 'docker pull  httpd '
                    sh 'docker run -d -p 80:80 httpd'
                }
    }
}


}
}
}
}
