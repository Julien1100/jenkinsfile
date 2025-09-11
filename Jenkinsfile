pipeline {
  agent { label maple-jenkins-node }
  // parameters {
    // string(
      // name: 'NODE_NAME',
      // defaultValue: 'node',
      // description: 'Nom du nœud cible'
    // )
  // }
  
  stages {
    stage('Test') {
      steps {
        sh 'echo "Job lancé sur le nœud : $NODE_NAME"'
      }
    }
  }
}
