pipeline {
    agent any

    stages {
        stage('welcome to jenkins') {
            steps {
                echo 'creating a folder'
                sh '''
                mkdir company.txt
                '''
            }
        }
        stage('second stage in jenkins') {
            steps {
                echo 'printing the echo statement'
            }
        }
        stage('third on jenkins') {
            steps {
                echo 'creating a file'
                sh '''
                touch depdetails.txt
                '''
            }
        }
        stage('fourth on jenkins') {
            steps {
                echo 'rename the file'
sh '''
mv depdetails.txt staffdetails.txt
'''
            }
        }
    }
}
