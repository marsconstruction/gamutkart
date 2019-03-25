pipeline {
    agent node1
       stages {
           stage('checkout') {
             steps {
                 checkout scm
                }
            }
             stage("Build") {
                 steps {
                     sh '/packages/apache-maven-3.6.0/bin/mvn install'
                    }
                }
        }
    } 
