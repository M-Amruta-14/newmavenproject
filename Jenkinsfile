pipeline{
    agent any
    stages{
        stage("git scm checkout"){
        steps{
            git 'https://github.com/M-Amruta-14/newmavenproject.git'
        }
        }
        stage("level-2"){
        steps{
            sh 'echo level-2'
        }
        }
        stage("level-3"){
        steps{
            sh 'echo level-3'
        }
        }
    }
}
