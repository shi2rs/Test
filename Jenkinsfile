pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        echo 'Step 1'
      }
      stage('Example') {
            steps {
                echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"
            }
        }
    }
    
  }
}
