node 
{
    stage('checkout')
    {
        checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: '85f080eb-02f2-4e6c-bcb8-9be6fb899f24', url: 'https://github.com/Velpulavenkatarao/JavaSample.git']]])
    }
    stage('static code analysis')
    {
        echo "static code analysis"
    }
    stage('build')
    {
        echo "Build the code"
    }
    stage('unit Testing')
    {
        echo "Unit Testing"
    }
    stage('Delivery')
    {
        echo "Deliver the code"
    }
    
}
