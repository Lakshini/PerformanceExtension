# PerformanceExtension

1. Build using "mvn clean install" command.

2.After the successful build, you can find the jar file with all the dependencies inside siddhi-execution-performance/component/target folder

3. Convert that jar to OSGI bundled jar using <SP_HOME>/bin/jartobundle.sh

4. After the successful build, you can find the OSGI bundled jar file inside destination folder

5. Copy the converted jar file in to <SP_HOME>/lib folder

6. Start WSO2 SP server and run your siddhi app with the performance extension.
