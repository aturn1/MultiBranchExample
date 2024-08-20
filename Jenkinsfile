pipeline
  {
   agent any
   stages
   {
   stage("checkout source code")
   {
     steps
     {
      git branch: 'feature1', url: 'https://github.com/aturn1/MultiBranchExample.git'
     }
    }
   stage("checkforakeyword")
   {
    steps
    {
     sh 'cat index.html | grep -i healthcare' 
    }
   }
  }
}


