stage("stage 1"){
 node("cdPipelineLINUX"){
  dir("test"){
    sh "ls -latr"
  }
 }
}
stage("stage 2"){
  node("cdPipelineLINUX"){
    dir("test"){
      sh "ls -latr"
    }
  }
}
