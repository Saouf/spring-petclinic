pipeline{
agent any
tools{
        maven 'apache-maven-3.6.3-bin'
        jdk 'jdk-1.8.0_191'
}
stages{
      stage('Compilation du projet')
      {
        steps{
           bat 'mvn compile'
              }
      }
}

}
