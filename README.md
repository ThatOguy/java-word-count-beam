This project was me folling the apache beam quick start for java see link below

https://beam.apache.org/get-started/quickstart-java/

comands used:

PS> mvn compile exec:java -D exec.mainClass=org.apache.beam.examples.WordCount `
 -D exec.args="--inputFile=sample.txt --output=counts" -P direct-runner