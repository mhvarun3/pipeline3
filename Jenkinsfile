node
{ 
stage("Cloning from Git")
{
git "git@github.com:mhvarun3/pipeline3.git"
}
stage("Run a Shell Script")
{
  sh "chmod 755 shell"
sh "./shell"
}
}
