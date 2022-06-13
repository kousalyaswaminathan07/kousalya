pipeline{
  agent any
  stages{
    stage("build"){
          steps{
            echo 'build an application..'
          }
            stage("test"){
          steps{
            echo 'test an application..'
          }
                    stage("deploy"){
          steps{
            echo 'deploy an application..'
          }
          }
          }
          } 
          node{
            //groovy scripts
          }
