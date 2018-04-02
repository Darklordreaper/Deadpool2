node {
    stage('Git Checkout') { // for display purposes
     echo 'Checout Code and clone it inside jenkins workspace.'
     git 'https://github.com/BharathKh/Deadpool.git'
   }
   stage('Build Test & Package') {
      echo 'Build the package'
      sh 'mvn clean compile package'
   }
   stage('Results') {
       echo 'Test Results are reported..'
}
