pipeline {
    agent any

    stages {
      
        stage ('Build Stage') {
            steps {
               
                    sh 'mvn compile'
                    script {
                           error "This pipeline stops here!"
                           }
                
            }
        }
        stage ('Test stage') {
            steps {
               
                    sh 'mvn tet'
                    script {
                           error "This pipeline stops here!"
                           }
            }
        }
        stage ('Deployment Stage') {
            steps {
               
                    sh 'mvn package'
                    script {
                           error "This pipeline stops here!"
                           }
            }
        }
    }
}
