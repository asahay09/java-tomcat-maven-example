pipeline{
    agent any
    stages{
        stage('Initialize') {
            steps{
                sh '''
                echo "PATH = ${PATH}"
                echo "M2_HOME = ${M2_Home}"
                '''
            }
        }
        stage('Build')  {
            steps{
                echo 'Hello World'
            }
        }
    }
}