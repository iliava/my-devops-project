properties([pipelineTriggers([pollSCM('* * * * *')])])
node {
    stage("clone"){
        git branch: 'main', url: 'https://github.com/avielb/my-0507-project.git'
    }
    stage("show files"){a
        bat "dir"
    }
}
