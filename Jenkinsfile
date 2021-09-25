properties([pipelineTriggers([pollSCM('* * * * *')])])
node {
    stage("clone"){
        git branch: 'main', url: 'https://github.com/iliava/my-0607-project.git'
    }
    stage("show files"){
        bat "dir /w"
    }
}
