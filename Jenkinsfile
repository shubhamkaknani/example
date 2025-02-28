pipeline
{
agent any
stages{
stage('clone repo') {
steps {
git url: 'https://github.com/shubhamkaknani/example.git', branch: 'main'
}
}
stage('Build'){
steps {
sh 'javac Devopsexam.java'
}
}
stage('run'){
steps
{
sh 'java Devopsexam'
}
}
}
}

