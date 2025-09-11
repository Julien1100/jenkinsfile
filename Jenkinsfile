pipeline {
  agent {
    label "${params.NODE}"
  }
  parameters {
    string(name: 'NODE', description: 'Nom du nœud cible')
  }
  stages {
    stage ('Test') {
      steps {
        sh 'echo test'
      }
    }
  }
}
