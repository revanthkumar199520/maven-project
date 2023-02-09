pipeline {
agent any
environment setup {
path = "/usr/share/maven/bin:$PATH"
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
stage('Build'){
steps {
echo "Starting build"
sh "mvn clean install"
''')
}
}
}
}
}
