node('master') 
{
    stage('Continuous Download-Loans') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build_Loans') 
	{
    sh label: '', script: 'mvn package'
	}
    }

