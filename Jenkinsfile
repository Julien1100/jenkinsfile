pipeline {
  agent { label "${NODE_NAME}" }
  
  stages {
    stage('Test') {
      steps {
        sh '''
        #!/bin/bash
        echo "Job lancé sur le nœud : $NODE_NAME"
        '''
      }
    }
  }
}
