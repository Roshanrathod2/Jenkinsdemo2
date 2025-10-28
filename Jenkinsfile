pipeline {
    agent any{

      stages {
           stage('Checkout') {
             steps {
                checkout scm
               }
            }

            stage('Extract') {
              steps {
                bat "C:\\Users\\Roshan Rathod\\AppData\\Local\\Microsoft\\WindowsApps\\python.exe extract.py"
             }
        }
      }
    }
}
