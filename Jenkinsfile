pipeline {
    agent none
    stages {

stage ('Building'){
   agent {label 'Linux_slave2'}
    steps{
        echo "Building............"
    }
   }   

stage ('Testing'){
   agent {label 'Linux_slave2'}
    steps{
        echo "Testing.................the Build and generating the war file for the same............"
    }
    }
}
}
