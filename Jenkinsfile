#!/usr/bin/env groovy
pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'gcc lala.c -o lala'
            }
        }
	stage('running') {
            steps {
                sh './lala'
            }
        }
    }
}
