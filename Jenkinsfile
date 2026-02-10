pipeline {
agent any
stages {
stage('chckout scm') {
steps {
checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/salimakthar22/javadocker.git']])
}
}
}
}
