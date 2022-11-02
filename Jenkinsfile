pipeline{
agent any
stages 
{
stage('Build') 
{
steps{
echo "Building the Code1.........."
sh "mvn clean"
}
}
stage('Test') 
{
steps{
echo "Testing the Code2.........."
sh "mvn test"
}
}
stage('Compile') 
{
steps{
echo "Compiling the Project3.........."
sh "mvn compile"
}
}
stage('Deploy') 
{
steps{
echo "Deploying the Project4.........."
}
}
}
}
