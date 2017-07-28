
node (){

  stage ('Security Test'){

    @NonCPS
    def dockerFile = new FileNameFinder().getFileNames(env.WORKSPACE, 'Dockerfile')
    print "Dockerfile=${dockerFile}"
  }

}



