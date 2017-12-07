#!/usr/bin/env groovy
properties([
    [$class: 'GithubProjectProperty',
    displayName: '',
    projectUrlStr: 'https://github.com/nareshorganiztion399/demo11.git/'],
    pipelineTriggers([githubPush()])])

node {
 stage 'build'
 echo 'hello world'
 stage 'test'
 echo 'hello veridic'
 stage 'Deploy'
 echo 'hello Georgia'
}
