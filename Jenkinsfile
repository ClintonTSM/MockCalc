#!groovy
pipeline {
agent any

stages {
stage('Checkout') {
steps {
checkout scm
}
}
stage('Deploy APIC Services') {
steps {
script {
sh "make deploy_api_service"
}
}
}
}
}
