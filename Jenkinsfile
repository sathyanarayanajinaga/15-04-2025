node {
    //Declare aglobal variable for mvn Home
    
    stage('version') {
        
    //build job: 'version check'
        
    } 

    stage('Environment'){
    
        //build job: 'Enviro-check'       
    }
    
    stage('Document'){
    
        //build job: 'Generate-JavaDoc', parametersa: [booleanparam(name: 'generate_javadoc', value: false), stringparam(name: 'javadoc_location', value:'C:\\_javadoc00')]
    }
    
    stage('compile') {
    
        //build job: 'compile-RPS'
    }
    
    stage('Acceptance') {
    
        //def response = input meaasge:'UAT Tests', Parameters:[choice(choice: 'Pass\nFail', description: 'Proceed or Abort?', name: 'Pass or Fail?')]
    }
    
    stage('Conclusion'){
            
        def response = input message: 'whatcha think?', parameters: [choice(choices: 'Yes\nNo', description: 'Procees or Abort?', name: 'Yes or No?')]
    
    if (response=="Yes") {
    echo "I agree!"
    } else {
    echo "you are hard to please."
    }
    }
    }
          
