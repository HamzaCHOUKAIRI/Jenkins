node {
    stage('Clone') {
   git branch: 'main', url: 'https://github.com/HamzaCHOUKAIRI/Jenkins.git'
}
stage('Build') {
  sh 'javac Main.java'
}
stage('Run') {
sh 'java Main'
}
}
