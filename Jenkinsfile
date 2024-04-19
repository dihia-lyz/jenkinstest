pipeline{
    agent any

    stages{
        stage("Test"){
            steps{
              script {
              echo "branch name is "+ env.BRANCH_NAME
                if(env.BRANCH_NAME!='master' ){
                    echo "branch is not master"
                }
              }
            }
        }
    }
}
