#!/usr/bin/groovy
@Library(['github.com/joostvdg/jenkins-pipeline-lib','github.com/joostvdg/jenkins-pipeline-go']) _

node {
    goBuild()
}
/*
def executeExample() { 
    def example = new Example(steps) 
    String name = 'Joost' 
    example.sayHello(name) 
}

@Library() 
import com.github.joostvdg.Utilities 

node { 
    executeExample() 
} 

def executeExample() { 
    def utils = new Utilities(steps) 
    String name = 'Joost' utils.sayHello(name) 
}



@Library('github.com/joostvdg/jenkins-pipeline-lib') 
import com.github.joostvdg.Utilities 

node { 
    timeout(1){
        timestamps {
            stage('Example') {
                executeExample() 
            }
        }
    }
} 

def executeExample() { 
    def utils = new Utilities(steps) 
    String name = 'Joost' 
    utils.sayHello(name) 
}
*/