node
{ 
stage("Cloning from Git")
{
git branch: 'main', url: 'git@github.com:mhvarun3/pipeline3.git'
}
stage("Run a Shell Script")
{
  sh "chmod 755 abc.sh"
sh "./abc.sh"
}
}
