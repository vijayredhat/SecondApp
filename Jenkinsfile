#!/usr/bin/env groovy 
@Library('s4sdk-pipeline-library') 
node {
    deleteDir()
    sh "git clone --depth 1 https://github.com/SAP/cloud-s4-sdk-pipeline.git pipelines"
    load './pipelines/s4sdk-pipeline.groovy'
}
