pipeline{
  agent any
  stages {
    stage ('Build') {
      steps {
        echo 'Running build automatioin'
        sh './gradlew build --no-deamon'
        archiveArtifacts artfifacts: 'distr/trainSchedule.zip'
      }
    }
  }
}
  
