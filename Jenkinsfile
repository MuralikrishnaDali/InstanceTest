Pipeline
{
 agent{label 'SlaveNode'}
 Tools{
   maven 'mvn'
    jdk 'jdk'
    }

stages
{

stage ('Build')
{

    steps{

            echo 'building'
            sh 'mvn clean'
            sh 'mvn install'     
    }
}

}
}
