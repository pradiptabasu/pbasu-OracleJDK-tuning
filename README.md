# pbasu-OracleJDK-tuning
pbasu-OracleJDK-tuning

* http://jvmmemory.com/
* http://karunsubramanian.com/wp-content/uploads/2014/07/Java8-heap.jpg
* https://www.oracle.com/technetwork/articles/java/vmoptions-jsp-140102.html
* https://dzone.com/articles/g1gcgarbage-first-garbage-collector-tuning-flags-1
* https://www.oracle.com/technetwork/java/visualgc-136680.html
* https://blogs.oracle.com/nbprofiler/visual-gc-plugin-20-for-visualvm





C:\Java\jdk1.8.0_181\bin\java -XX:+HeapDumpOnOutOfMemoryError -Xms2g -Xmx2g -XX:MetaspaceSize=1g -XX:MaxMetaspaceSize=1g -XX:MinHeapFreeRatio=50 -XX:MaxHeapFreeRatio=70 -XX:NewRatio=8 -XX:SurvivorRatio=32 -XX:+UseG1GC -XX:MaxGCPauseMillis=100 -XX:G1ReservePercent=20 -jar "wiremock-standalone-2.18.0.jar" --port 8810 --record-mappings --verbose --proxy-all="https://catalog-services-depcd12vw.mdv.mmo.de:9443" --root-dir "D:\Workspace\WireMockRoot\WireMock_Recordings_Home




-XX:+HeapDumpOnOutOfMemoryError
-Xms1g
-Xmx1g
-XX:MaxMetaspaceSize=256m
-XX:+UseG1GC
-XX:MaxGCPauseMillis=100
-XX:G1ReservePercent=20
-Djava.security.egd=file:/dev/urandom
-Duser.language=en
-Duser.region=EN




C:\Java\jdk1.8.0_181\bin\java -XX:+HeapDumpOnOutOfMemoryError -Xms2g -Xmx2g -XX:MetaspaceSize=1g -XX:MaxMetaspaceSize=1g -XX:+UseG1GC -XX:MaxGCPauseMillis=100 -XX:G1ReservePercent=20 -XX:+UnlockCommercialFeatures -XX:+FlightRecorder -jar "wiremock-standalone-2.18.0.jar" --port 8810 --record-mappings --verbose --proxy-all="https://catalog-services-depcd12vw.mdv.mmo.de:9443" --root-dir "D:\Workspace\WireMockRoot\WireMock_Recordings_Home


