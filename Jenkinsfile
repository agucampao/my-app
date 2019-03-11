  node{
   stage('SCM Checkout'){
     #git credentialsId: 'build-docker', url: 'https://github.com/agucampao/my-app'
     git (credentialsId: 'build-docker', url: 'https://github.com/agucampao/my-app', branch: 'dev-branch')
   }

}