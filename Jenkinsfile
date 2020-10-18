pipeline {
agent any
stages {
stage('Build Docket Image') {
steps {
sh 'docker build -t cyberfrat:$BUILD_NUMBER .'
}
}
}
}
