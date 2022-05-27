pipeline {
    agent any
    
    stages{
        stage('cloning ...'){
            steps{
                sh 'rm -r flaskandjenkins'
                sh 'git clone https://github.com/lidorse/flaskandjenkins'
            }
        }
        stage('build'){
            steps{
                sh 'echo building'
            }
        }
        stage('Testing'){
            steps{
                sh 'echo testing'

            }
        }
    }
    
    
    
}
