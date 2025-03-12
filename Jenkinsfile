pipeline{
    agent any
    stages{
        stage("git scm checkout"){
        steps{
            git 'https://github.com/M-Amruta-14/newmavenproject.git'
        }
        }
        stage("validate the code"){
        steps{
            withMaven(globalMavenSettingsConfig: '', jdk: 'JDK_HOME', maven: 'MAVEN_HOME', mavenSettingsConfig: '', traceability: true) {
                sh 'mvn validate'
            }
        }
        } 
    }
}
