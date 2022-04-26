pipeline { 
    agent any  
    stages { 
        stage('COURSES') {
          steps {
            echo 'COURSES'
          }
        }
        stage('CREDITS') { 
            steps { 
               echo 'CREDITS...' 
               sh 'python3 ritvik.py'
              //bat 'mvn package'
            }
        }
   
}
    }
