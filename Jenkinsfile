pipeline 
     {
      agent {
           label 'S1'
      }
      stages
      {
       stage('git')
       {
        steps
            {
              git "https://github.com/varalakshmikonjeti/26Jenkins.git"
              }
}
        stage('run')
        {
         steps
            {
             sh "java Demo.java"
             sh "python3 main.py"
             }
        }
       
      }//stages
      }//pipeline
