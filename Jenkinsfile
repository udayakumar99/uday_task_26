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
    "javac Demo.java"
    "java Demo.java"
    "python main.py"
   }
  }
 }
}
