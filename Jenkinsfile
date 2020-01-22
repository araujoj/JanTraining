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
	sh 'mv * /usr/share/nginx/html/' 
      }
    }
  }
}
