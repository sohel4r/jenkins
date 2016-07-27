#!groovy

stage 'Test'

node('node') {

    env.NODE_ENV = "test"

    print "Environment will be : ${env.NODE_ENV}"

    sh 'node -v'
    sh 'npm prune'
    sh 'npm install'
    sh 'npm test'
}
