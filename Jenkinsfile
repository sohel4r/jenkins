#!groovy

stage 'Test'

node('slave') {

    env.NODE_ENV = "test"

    print "Environment will be : ${env.NODE_ENV}"

    sh 'node -v'
    sh 'npm prune'
    sh 'npm install'
    sh 'npm test'
}

stage 'deployment'

node('slave') {

    env.NODE_ENV = "test"

    print "Environment will be : ${env.NODE_ENV}"

    sh 'node -v'
    sh 'npm prune'
    sh 'npm install'
    sh 'npm test'
}
