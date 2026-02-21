pipeline {
agent any
stages {
stage('clone') {
steps {
git branch:'main', url: 'https://github.com/Charan21-09/Calculator.git';
}
}
stage('compile') {
steps {
sh 'javac Calculator.java'
}
}
stage('build') {
steps {
sh 'java Calculator 25 5'
}
}
}
}
