pipeline {
    agent {
		label 'raj'
	}

    tools {
       
        maven 'maven-3.9.3'
    }

    stages {
      	 stage('compile') {
            steps {
               
                // Run Maven on a Unix agent.
                sh "mvn compile"

               
            }

          
        }
		stage('Test') {
            steps {
               
                // Run Maven on a Unix agent.
                sh "mvn test"

               
            }

          
        }
		stage('package') {
            steps {
               
                // Run Maven on a Unix agent.
                sh "mvn package"

               
            }

          
        }
    }
}
