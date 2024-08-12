node('built-in') 
{
    stage('Continuous Download_master') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build_master') 
	{
    sh label: '', script: 'mvn package'
	}
stage('Continuous Build_test') 
	{
    sh label: '', script: 'echo `pwd` is working directory'
	}

}
