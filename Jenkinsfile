pipeline{
    agent any

        environment {
        BRANCH_NAME = "${env.BRANCH_NAME}"
    }



    stages{
        stage("Test"){
            steps{
              script {
              echo "branch name is "+ BRANCH_NAME
                if(BRANCH_NAME!='master' ){
                    echo "branch is not master"
                }
              }
            }
        }
    }
}
