pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '/usr/local/bin/gradle clean shadowJar'
      }
    }
  }
  environment {
    PATH = '/usr/local/bin:/bin:/usr/bin:/usr/local/sbin:/usr/sbin:/sbin:/opt/aws/bin:/home/ec2-user/.local/bin:/home/ec2-user/bin'
  }
}