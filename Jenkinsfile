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
        
    }
}
