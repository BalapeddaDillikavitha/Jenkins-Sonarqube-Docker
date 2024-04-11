pipeline{
    agent any
    stages{
        stage('BUILD TEST'){
            steps{
                sh 'echo "Build completed."'
            }
        }
    }
    stage('UNIT TEST'){
        steps {
            sh 'mvn test'
        }

    }
    
    }
