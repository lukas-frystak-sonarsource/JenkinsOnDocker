
docker exec jenkins-jenkins-1 keytool -importcert -file /usr/updates.jenkins.io.crt -alias jenkinsUpdateCenter -keystore /opt/java/openjdk/lib/security/cacerts -storepass changeit -trustcacerts -noprompt

/usr/updates.jenkins.io.crt

