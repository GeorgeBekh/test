#!/usr/bin/env groovy

node('docker') {
    stage('Checkout') {
        checkout scm
    }

    stage('Publish') {
        sh "git rev-parse --abbrev-ref HEAD"
    }
}
