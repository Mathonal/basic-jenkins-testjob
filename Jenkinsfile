node {
    stage('clone') {
    git branch: 'main', url: 'https://github.com/Mathonal/basic-jenkins-testjob.git'
    }
    stage('build') {
    sh '''javac Main.java'''
    }
    stage('run') {
    sh '''java Main'''
    }
}
