pipeline{
  agent any
  
  stages{
    stage('Script'){
      steps{
        sh 'sh List.sh'
        sh 'sh folders.sh'
        sh 'sh sys-info.sh'
      }
    }
  }
}
