pipeline {
    agent any
    tools {
        maven 'maven-3.6.0' 
          }
    stages 
    {
        stage('compile')
          {
            steps {
                sh 'mvn clean compile'
                  }
           }
   
    
        stage('Testing stage')
          {
            steps {
                sh 'mvn test'
                 }
            }
   
        stage('Build the package')
          {
            steps {
                sh 'mvn package'
                 }
            }
    }
}
