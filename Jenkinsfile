node('built-in') {
    stage('continuos download') {
    git branch: 'main', url: 'https://github.com/aashokrao/DevOpsAwsAA'
    }
    stage('continuos build') {
        sh 'mvn package'
    }
    //stage('continuos deployment') {
    //    sh 'scp /home/ubuntu/.jenkins/workspace/pipelineJob/target/WebApp.war ubuntu@172.31.31.110:/var/lib/tomcat9/webapps/qaenv.war'
    //}
    //stage('continuos testing') {
    //    sh '''echo "#########################################"
    //    echo "TESTING PASSED"
    //    echo "#########################################"'''
    //}
    //stage('continuos delivery') {
    //    sh 'scp /home/ubuntu/.jenkins/workspace/pipelineJob/target/WebApp.war ubuntu@172.31.88.230:/var/lib/tomcat9/webapps/prodenv.war'
    //}
}