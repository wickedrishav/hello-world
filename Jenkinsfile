pipeline{
  agent any() {
    environment{
    PATH="/opt/maven3/bin:$PATH"
    }
    stages{
    stage("git checkout")
      steps{
        git 'https://github.com/wickedrishav/hello-world'
      }
    }
  }
}
