pipeline {
    agent any
    parameters {
        choice(name: 'dockerImage')
    } 
    stages {
        stage('build') {
            steps {
                script {
                  // Pull the specified Docker image tag
                    sh "docker pull nginx"
                       }
                    }
                }
            }
        }
        stage('deploy') {
            steps {
                script {
                    sh """
                        ls
                        echo "Hello"
                        """
                }
            }
        }
    }
}
