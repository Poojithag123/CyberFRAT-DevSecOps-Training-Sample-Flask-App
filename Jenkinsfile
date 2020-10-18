pipeline{
agent any
statges {
stage('Build Docket image') {
steps {
sh 'docker build -t cyberfrat:$BUILD_NUMBER .'
}
}
}
}
