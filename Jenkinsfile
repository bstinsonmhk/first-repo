@Library('github.com/CentOS/cico-pipeline-library@master')

stage('Testing') {
    node('fedora-docs') {
        deleteDir()
        cicoPipeline{
            echo 'Build the asciibinder thing'
        }
    }
}
