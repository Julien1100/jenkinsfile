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
    stage('Deploy') {
      steps {
        sh '''
        #!/bin/bash
        echo "Deploy"
        pwd
        cd ..
        pwd
        '''
        sh '''
        #!/bin/bash
        echo "Deploy again"
        pwd
        '''
      }
}
}
}
