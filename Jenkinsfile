pipeline {
    agent any

    stages {
        stage ('Compile and checkout .Stage') {

            steps {
           
                    sh ' compile stage ' 
                    echo "hello world"
                }
            }
        stage ('deploy Stage') {

            steps {
           
                    sh ' deploy stage ' 
                    echo "helloworld"
                }
            }
        }
}
