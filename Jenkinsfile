pipeline{
agent any
environment setup{
path = "/usr/share/maven/bin:$PATH"
stages{
stage('Source download'){
steps{
echo "Starting downloading source"
echo "Printing current working directory"
echo `pwd`
rm -rf*
git clone `https://github.com/revanthkumar199520/maven-project.git`
echo"Printing curent working directory"
echo"Source download completed"
''')
}
}
stage('Build'){
steps{
echo "Starting build"
sh "mvn clean install"
''')
}
}
}
}
}
