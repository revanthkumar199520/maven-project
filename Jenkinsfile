<<<<<<< HEAD
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
=======
pipeline {
    agent any
    stages {
        stage('Source Download') {
            steps {
                sh('''
                echo "Starting Source Download step"
                echo "Printing current working directory"
                echo `pwd`
                rm -rf *
                echo "Downloading your git repository"
                git clone https://github.com/revanthkumar199520/maven-project.git
                echo `pwd`
                echo "Completed Source Download step"
                ''')
            }
        }




    }

}

>>>>>>> 7b07b5ffc0682988ba4dd720fbc404e8357f3a0a
