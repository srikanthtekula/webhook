pipeline {
    agent any 
    stages {
        stage('Stage build') {
            steps {
                echo ' dev application!' 
		echo 'i have added webhook added '
            }
        }
		
      stage('Stage test') {
            steps {
                echo ' test application' 
		    echo 'i have added webhook at 2 '
            }
        }
		
        stage('Stage deploy') {
            steps {
                echo 'prod application' 
		    echo 'i have added webhook at 3'
            }
        }
    }
}
