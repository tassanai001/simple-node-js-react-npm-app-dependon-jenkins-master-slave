node('master') {
  stage ('Build on master'){
    echo 'Running on master'
    sh 'ifconfig'
  }
}

node('jenkins-slave-1') {
  stage ('Build on master'){
    echo 'Running on jenkins-slave-1'
    sh 'sleep 5s'
    sh 'ifconfig'
  }
}
