pipeline {
agent any
stages {
stage('Checkout') { 
steps {
sh 'echo checkout'
}
}
stage('Test') { 
steps {
sh 'echo test'
}
}
stage('Deploy') { 
steps {
sh 'echo deploy'
}
}
}
}
checkout([$class: 'GitSCM', branches: [[name: '*/master']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/thouefab/DevOpsPath_GRPI_1']]])