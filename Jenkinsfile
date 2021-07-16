pipeline {
    agent any
    stages {
        stage('First') {
            steps {
                script {
                    env.EXECUTE=True
                   } 
                echo 'Updating Second Stage'
            }
        }
        stage('Second') {
            steps {
                echo 'Step Two'
            }
        }
        stage('Third') {
            steps {
                echo 'Step Three'
            }
        }
    }
}
