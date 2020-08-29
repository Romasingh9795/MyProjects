pipeline {
   agent any
   stages {
      stae('Source') {
         git branch: 'test', url: 'git@diyvb:repos/gradle-greetings'
         stash name: 'test-sources', includes: 'build.gradle,/src/test'
      }
      stage('Build') {
         
      }
   }
}
