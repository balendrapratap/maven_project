node{
    stage("SCM Checkout"){
        git 'https://github.com/balendrapratap/maven_project'
    }
    stage("compile-project"){

        def mvnHome = tool name: 'Mave3', type: 'maven'

        sh "${mvnHome}/bin/mvn package"
    }
}
