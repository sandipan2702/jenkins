pipeline{
agent{
label 'linux-agent'}

stages{

stage('Build'){
steps{
echo "Building the app"
sh 'echo"Build running on-"'
sh 'hostname'
}
}

stage('Test'){
steps{
echo"Testing"
sh 'echo"Tests ran successfully"'
}
}


}

}
