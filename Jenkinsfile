// Powered by Infostretch 

timestamps {

node () {

	stage ('DiagnosticsApp - Checkout') {
 	 checkout([$class: 'GitSCM', branches: [[name: '*/develop']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: '3a50b6b4-b8df-4bd0-bf7f-4dea864dd2ed', url: 'https://github.com/sriten/diagnosticsApp']]]) 
	}
	stage ('DiagnosticsApp - Build') {
 	
// Unable to convert a build step referring to "hudson.plugins.build__timeout.BuildTimeoutWrapper". Please verify and convert manually if required.
// Unable to convert a build step referring to "hudson.plugins.timestamper.TimestamperBuildWrapper". Please verify and convert manually if required.		// Shell build step
sh """ 
echo "Build should start now..........."
pwd 
 """
// Unable to convert a build step referring to "com.cloudbees.jenkins.GitHubSetCommitStatusBuilder". Please verify and convert manually if required. 
	}
}
}