pipeline {
agent any
statges {
stage('Build Docket Image') {
steps {
sh 'docker build -t cyberfrat:$BUILD_NUMBER .'
}
}
}
}
