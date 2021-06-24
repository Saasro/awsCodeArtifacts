# Gradle library to publish and fetch libraries form AWS code artifact.

How to use
* Setup AWS cmd utils 
* update "aws_access_key_id" and "aws_secret_access_key"

To publish library to AWS codeartifact add the below line to build.gradle

apply from: 'https://raw.githubusercontent.com/Saasro/awsCodeArtifacts/main/publishLibrary.gradle'

To fetch library form AWS code artifact, add the below line to build.gradle

apply form: 'https://raw.githubusercontent.com/Saasro/awsCodeArtifacts/main/syncAwsArtifact.gradle'


