node('master') 
{
    stage('Continuous Download_1221') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build_1221') 
	{
    sh label: '', script: 'mvn package'
	}
}
