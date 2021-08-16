properties([pipelineTriggers([pollSCM('* * * * *')])])
node {
    stage("clone"){
        git branch: 'main', url: 'https://github.com/iliava/my-devops-project.git'
    }
    stage("show files"){
        bat "dir"
    }
}
