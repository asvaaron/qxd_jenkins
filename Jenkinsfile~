#!/usr/bin/env groovy
pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'cd src'
		sh 'cmake ..'
		sh 'make'

            }
        }
	stage('running') {
            steps {
                sh './lala'
            }
        }
    }
}
