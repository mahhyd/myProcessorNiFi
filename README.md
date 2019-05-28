# myProcessorNiFi
## Requirements
    • JDK 1.8
    • Apache Maven 3.1.1 or newer 
    • Git Client (used during build process by 'bower' plugin)
    • Apache NiFi 1.9.2
		
## Build
mvn clean install

## Deployment
    1. Copy the nificustomprocessor/nifi-sumtwoint-nar/target/nifi-sumtwoint-nar-1.9.2.nar to $NIFI_HOME/lib 
    2. $NIFI_HOME/bin/nifi.sh stop 
    3. $NIFI_HOME/bin/nifi.sh start
