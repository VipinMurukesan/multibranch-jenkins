node('built-in') 
{
    stage('Continuous Download_loans') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build_loans') 
	{
    sh label: '', script: 'mvn package'
	}
	stage('Continuous Test_loans') 
	{
    sh label: '', script: 'echo "Hello from loans"'
	}

}
