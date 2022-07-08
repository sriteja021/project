pipeline {
    agent any

    stages {
        stage('CheckOut') {
            steps {
                echo 'Hello World'
		git branch: 'main', url: 'https://github.com/sriteja124/myproject.git'
            }
        }
	stage("Build") {
           steps {
               sh './new.sh'
		  
	   }
	}
			
    }
}