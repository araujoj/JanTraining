pipeline {
  agent any
  stages {
    stage('myStage'){
      steps {
        sh 'ls -la' 
      }
    }
    stage('Build') {
      steps { 
        sh 'ls'
	sh 'cp * /usr/share/nginx/html/' 
      }
    }
  }
}
