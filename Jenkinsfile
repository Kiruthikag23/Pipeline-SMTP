pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }

        stage('Build') {
            steps {
                echo 'This is the first build'
                  
            }
        }

        stage('Test') {
            steps {
                echo 'This is the first Test'
                echo 'This is the Second Test'
            }
        }

        stage('Deploy') {
            steps {
                echo 'This is the first deploy'
                echo 'This is the second deploy'
                echo 'This is the third deploy'
            }
        }

        stage('Success') {
            steps {
                echo 'This is the first Build'
                echo 'This is the Second Test'
                echo 'This is the third deploy'
                echo 'Build,test,deploy has been completed successfully'
            
            }
        }

        stage('Failiure') {
            steps {
                echo 'This is the first Build'
                echo 'This is the Second Test'
                echo 'This is the second deploy'
                echo 'This is the third deploy'
                echo 'build,test.deploy has been failed'
            
            }
        }
    }
}
