@Library('qclab-pipeline-library')
import org.qclab.*
def profile = new getProfileType()
echo profile
pipeline {
  agent any
  stages {
    stage('Demo') {
      steps {
        echo 'hello,demo'
        sayHello 'sean'
      }
    }

  }
}
