#!groovy

stage 'Test'

node('master') {

    env.NODE_ENV = "test"

    print "Environment will be : ${env.NODE_ENV}"

    sh 'node -v'
    sh 'npm prune'
    sh 'npm install'
    sh 'npm test'
}
