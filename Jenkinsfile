pipeline {

 agent any
 
 tools {
   maven 'MyMaven'
   jdk 'MyJava'
 }

 stages {

    stage('Build')
{
  steps {

   sh 'mvn -B -DskipTests clean package'
}
}

 } 
}
