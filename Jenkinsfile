pipeline {
   agent any

   stages {
      stage('Hello') {
         steps {
            echo 'pipeline'
         }
      }
      stage('java path') {
          steps {
              sh label: '', script: '''$JAVA_HOME'''
          }
      }
   }
}
