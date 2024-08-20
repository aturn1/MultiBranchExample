pipeline
  {
   agent any
   stages
   {
   stage("checkout source code")
   {
     steps
     {
      git branch: 'feature3', url: 'https://github.com/aturn1/MultiBranchExample.git'
     }
    }
   stage("checkforakeyword")
   {
    steps
    {
     sh 'cat contact.html | grep -i wealth'
    }
   }
  }
}
