properties([[$class: 'GithubProjectProperty', 
             displayName: '', 
             projectUrlStr: 'https://github.com/manojkarrolla/Pipeline.git/'],
             pipelineTriggers([githubPush()])])

pipeline {
    agent any
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

