# learn-groovy-development

Instructions to Install groovy on Linux. Prequisite for Groovy is Java. make sure you have java-11 installed on your machine.

1. Download from below link on Ec2 instance and run the below commands to install groovy 
```````````````````````````````````````````````
  $ cd /home/rocky
  $ wget  https://groovy.jfrog.io/ui/native/dist-release-local/groovy-zips/apache-groovy-sdk-4.0.10.zip
  $ unzip apache-groovy-sdk-4.0.10.zip
  $ mv apache-groovy-sdk-4.0.10 groovy4
  $ export PATH=$PATH:/home/rocky/grrovy4/bin
  $ groovy --version
```````````````````````````````````````````````

2. Go to Each folder and try to run grrovy scripts as below. verify the Output 

````````````````````````````````````````
 $ groovy < name of the script > 
 
````````````````````````````````````````
