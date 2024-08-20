pipeline
  {
   agent any
   stages
   {
   stage("checkout source code")
   {
     steps
     {
      git branch: 'feature2', url: 'https://github.com/aturn1/MultiBranchExample.git'
     }
    }
   stage("checkforakeyword")
   {
    steps
    {
     sh 'cat about.html | grep -i healthcare'
    }
   }
  }
}
