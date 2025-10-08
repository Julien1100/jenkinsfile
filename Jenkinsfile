pipeline {
  agent { label "${NODE_NAME}" }
  tools {
    jdk 'JDK17'
  }
  
  stages {
    stage('Java Version') {
      steps {
        sh '''
        #!/bin/bash
        java --version
        '''
      }
    }
    
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
