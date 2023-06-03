pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                sh 'mvn clean package' // Збирання проекту з використанням Maven
            }
        }
        
        stage('Test') {
            steps {
                sh 'mvn test' // Виконання тестів з використанням Maven
            }
        }
    }
}
