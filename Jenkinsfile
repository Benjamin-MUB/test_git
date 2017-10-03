pipeline {
  agent any
  stages {
    stage('begin') {
      steps {
        echo 'hello world'
      }
    }
    stage('Test') {
      steps {
        catchError() {
          sh 'echo \'CHAMEAU\''
        }
        
      }
    }
  }
  post {
    always {
      echo 'finish'
      
    }
    
  }
}