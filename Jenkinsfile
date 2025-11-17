pipeline {
    agent any


    stages {

        stage('GIT') {
            steps {
                git branch: 'master',
                    url: 'https://github.com/yassinesaoud/Yassine_saoud_4TWIN8.git'
            }
        }

        stage('Compile Stage') {
            steps {
                sh 'mvn clean compile'
            }
        }
    }
}
