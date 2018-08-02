pipeline {
   agent any

   stages {
      stage('Build') {
        steps {
            echo 'Building..'
        }
    }

    stage('Test') {
        steps {
            echo 'Testing..'
            echo "${env.GIT_BRANCH}"
        }
    }

    stage('Deploy') {
        steps {
            echo 'Deploying....'
        }
     }
  }
}
