pipeline{
    agent any 
    stages{
        stage('Build') {
          steps{
           sh 'echo "this is my first groovy scrip"'
           sh '''
              export x=one
              echo "value of x: ${x}"
           
           '''
          }
        }
        
        stage('Build 1') {
          steps{
           sh 'echo "this is my second groovy script"'
           sh '''
              export x=two
              echo "value of x: ${x}"
           '''
           
          }
        }
        
    }
}
