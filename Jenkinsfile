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

         stage("Test 2"){
            steps{
              script {
              echo "branch name is "+ env.BRANCH_NAME
                if(env.BRANCH_NAME!='master' ){
                    echo "stageb 2 branch is not master"
                }
              }
            }
         }
    }
}
