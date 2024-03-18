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
                echo 'Test success'
            }
        }
  
        stage('Deploy') {
            steps {
                echo 'Deployee success'
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
