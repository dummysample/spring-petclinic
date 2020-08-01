node {
    stage("scm"){
       
        git url:' https://github.com/dummysample/spring-petclinic.git'   
    }
       stage("build"){
        sh 'mvn package'

    }
}
