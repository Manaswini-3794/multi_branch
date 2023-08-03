pipeline {
  agent {
     node { 
        label 'lsv03259'
        } 
  }
    stages{
    stage('build') {
      steps {
        sh ''' python gcd.py
              echo 'this is the code to find gcd'
        '''
      }
    }
    }
}
