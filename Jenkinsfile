pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Construcción del proyecto'
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
        echo 'Despliegue de la aplicación.'
      }
    }

  }
}