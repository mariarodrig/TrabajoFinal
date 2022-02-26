pipeline {
  agent any
  stages {
    stage('empaquetado') {
      steps {
        build 'EmpaquetadoPruebas'
      }
    }

    stage('') {
      steps {
        emailext(subject: 'holi', body: 'prueba', from: 'marialej1505@gmail.com', to: 'marialej1505@gmail.com')
      }
    }

  }
}