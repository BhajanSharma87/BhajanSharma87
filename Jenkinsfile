pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo " Building Phase Executed"
				javac Hello.java
				java Hello
				echo " Java Compiled and Executed"
            }
}

    stage('Test') {
            steps {
                echo " Testing Phase Executed"
            }
}
           
		       stage('Deploy') {
            steps {
                echo " Deploy Phase Executed"
            }
}
		   
        }
    }
}
