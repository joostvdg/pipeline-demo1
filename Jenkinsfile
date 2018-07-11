pipeline {
   agent any
libraries {
  lib('lib-demo1@master')
}
   stages {
	stage('Demo') {
          steps {
            hello 'Joost'
          }
        }
   }
}
