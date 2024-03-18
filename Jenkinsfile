pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build Success'
            }
        }
 
        stage('Test') {
            steps {
                echo 'Test success1111111111111'
            }
        }
  
        stage('Deploy') {
            steps {
                echo 'Deployee success55555555555555555555'
            }
        }
    }
    post {
        always
        {
            emailext body: 'Build success', subject: 'Pipeline', to: 'vinaysoma8@gmail.com'
        }
    }
}
