node('built-in')

{

stage('ContinuousDownload_master')
         {
    git 'https://github.com/jtaku4/optclab.git'
        }

stage('Continuousbuild_master')
         {
   sh label: '', script: 'mvn package'
        }

}
 
