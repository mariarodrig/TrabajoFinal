pipeline {
  agent any
  stages {
    stage('empaquetado') {
      steps {
        build 'EmpaquetadoProduccion'
      }
    }

    stage('Correo') {
      steps {
        mail(subject: 'produccionsita', body: 'esta es una producción', from: 'maria_rodriguez82182@elpoli.edu.co', to: 'maria_rodriguez82182@elpoli.edu.co')
      }
    }

  }
}