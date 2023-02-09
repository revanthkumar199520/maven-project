pipeline{
agent any
environment setup{
path = "/usr/share/maven/bin:$PATH"
stages{
stage('Source download'){
steps{
sh('''
echo "Starting downloading source"
echo "Printing current working directory"
echo `pwd`
rm -rf*
git clone https://github.com/revanthkumar199520/maven-project.git/maven_Project
echo"Printing curent working directory"
echo"Source download completed"
''')
}
}
stage(Build){
steps{
sh('''
#!bin/bash
echo "Starting build"
echo `mvn clean install`
''')
}
}
}
}
