# dev
#Jenkinsfile
Pipeline {
 agent any 
 stages {
  stage ("build") {
   steps {
     echo 'building the application..'
        }
       }
  stage ("test") {
    steps {
     echo 'testing ther app..'
        }
       }
      }
    }
