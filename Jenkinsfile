pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Construcci�n del proyecto'
          }
        }

        stage('Test') {
          steps {
            echo 'Testeo del proyecto'
          }
        }

      }
    }

    stage('Deploy') {
      steps {
        echo 'Despliegue de la aplicaci�n.'
      }
    }

  }
}