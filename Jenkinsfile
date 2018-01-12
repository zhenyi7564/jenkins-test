pipeline {
    agent any
    stages {

        stage('test'){
          steps{

                echo "test1"
                sh 'mkdir /Users/msuarez/Desktop/from-jenkins'
                sh 'touch /Users/msuarez/Desktop/from-jenkins/test.txt'
                }
        }
        stage('select')
        {
        steps{
            sh 'sqlcmd -S 209.45.48.90 -U sa -P 06220367 -Q "use dbedocsys; select * from documentos"'

        }

        }

}
}
