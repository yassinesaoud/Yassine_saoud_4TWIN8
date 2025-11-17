pipeline {
    agent any


    stages {

        stage('GIT') {
            steps {
                git branch: 'main',
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
