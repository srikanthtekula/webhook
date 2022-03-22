pipeline {
    agent any 
    stages {
        stage('Stage build') {
            steps {
                echo ' dev application!' 
		echo 'i have added webhook '
            }
        }
		
      stage('Stage test') {
            steps {
                echo ' test application' 
            }
        }
		
        stage('Stage deploy') {
            steps {
                echo 'prod application' 
            }
        }
    }
}
