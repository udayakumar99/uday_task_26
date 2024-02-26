pipeline
{
 agent any
 stages
 {
  stage("git")
  {
   steps
   {
    git "https://github.com/udayakumar99/uday_task_26.git"
   }
  }
  stage("run")
  {
   steps
   {
    sh "java Demo.java"
    sh "python main.py"
   }
  }
 }
}
