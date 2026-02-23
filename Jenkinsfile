node {
  stage('Build image') {
    bat 'docker build -t primeiroapp:%BUILD_NUMBER% .'
  }

  stage('Run container') {
    bat 'docker run --rm primeiroapp:%BUILD_NUMBER%'
  }
}