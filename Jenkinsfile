@Library('qclab-pipeline-library')
import org.qclab.*
def profile = new GetProfileType().getProfileType()

pipeline {
  agent any
  stages {
    stage('Demo') {
      steps {
        echo 'hello,demo'
        sayHello 'sean'
        echo "mvn verify -P${profile}"
      }
    }

  }
}
