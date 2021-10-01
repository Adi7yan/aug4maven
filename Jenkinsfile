pipeline {
    agent any

    stages {
      
        stage ('Build Stage') {
            steps {
               
                    sh 'mvn compile'
                
                
            }
        }
        stage ('Test stage') {
            steps {
               
                    sh 'mvn test'
                 
            }
        }
        stage ('Deployment Stage') {
            steps {
               
                    sh 'mvn package'
          
            }
        }
    }
}
