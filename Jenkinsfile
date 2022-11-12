pipeline {
    agent any
           catchError(message: 'Hello') {
    // some block
}

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }

        }
       
    }
}

