pipeline {
    agent {
        label "master"
    }
        //triggers {
          //  cron('H/15 * * * *')
        //}
            stages {
                    stage('echo') {
                                steps {
                                    echo 'hello from the trigger'
                                }
                    }
                    stage('after') {
                        //some commands
                    }
            }
}