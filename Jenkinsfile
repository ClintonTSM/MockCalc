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
echo 'make deploy_api_service'
}
}
}
}
}
