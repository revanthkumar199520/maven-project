pipeline{
agent any
environment setup{
path = "/usr/share/maven/bin:$PATH"
stages{
stage('Source download'){
sh('''
echo "Starting downloading source"
echo "Printing current working directory"
echo 'pwd'
rm -rf*
git clone <Repo url>/maven_Project
echo"Printing curent working directory"
echo"Source download completed"
''')
}
stage(Build){
sh('''
#!bin/bash
echo "Starting build"
echo "mvn clean install
