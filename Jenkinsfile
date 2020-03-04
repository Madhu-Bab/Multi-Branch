node{
   stage('Checkout Data From SCM to Jenkins'){
       git credentialsId: 'd551251e-cbe4-425e-9592-d502d244192e', url: 'https://github.com/Madhu-Bab/Multi-Branch.git'
   }
   stage('Compile Stage'){
       tool name: 'maven3', type: 'maven'
         sh 'mvn compile'
   }
   stage('Stest Stage'){
       tool name: 'maven3', type: 'maven'
         sh 'mvn test'
  }  
}
