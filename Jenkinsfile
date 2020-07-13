pipeline {
    agent any
	
    stages {
        stage('Build') {
		
			when{
#				changeset glob: "*.js", caseSensitive: true

				changeset glob: "*.js"
			}
		
            steps {                
                echo 'Hello World changeset JS'
            }
        }
    }
}
