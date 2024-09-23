pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh 'echo 'Hello World' > sample.txt'
		    }
		}
	    stages('sandy'){
		    steps{
			    sh 'echo 'hello sandy' > sandy1.txt
		    }
	    }
	}
}
