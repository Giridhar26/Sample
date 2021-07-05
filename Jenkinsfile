/*pipeline {
      agent any
       stages{
       stage ("Hello world ")
            {
            steps{
            echo "Hello world"
            }
            }
            }
            }
*/
pipeline{
 agent any
 stages{
 stage('batch'){
 steps{
 bat "dir"
 bat "cd"
 bat "ping www.google.com"
 }
 }
 }
}
