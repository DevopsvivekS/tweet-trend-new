pipeline {
        agent {
            node {
                label 'maven'
            }
        }
environment {
        PATH = "/opt/apache-maven-3.9.5/bin:$PATH"
}
        stages {
           stage ('build') {
                 steps {
                     sh 'mvn clean deploy'
                 }
            }
       }
}

