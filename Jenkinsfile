pipeline {
    agent {
        docker {
            image 'bkimminich/juice-shop' 
            args '-p 3000:3000' 
        }
    }
    stages {
        stage('Build') { 
            steps {
                sh 'docker run --rm -p 3000:3000 bkimminich/juice-sho' 
            }
        }
    }
}