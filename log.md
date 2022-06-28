```
/Library/Java/JavaVirtualMachines/jdk-11.0.13.jdk/Contents/Home/bin/java -Dmaven.multiModuleProjectDirectory=/Users/.../Downloads/pinot-0.10.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar -Dmaven.home=/Applications/IntelliJ IDEA CE.app/Contents/plugins/maven/lib/maven3 -Dclassworlds.conf=/Applications/IntelliJ IDEA CE.app/Contents/plugins/maven/lib/maven3/bin/m2.conf -Dmaven.ext.class.path=/Applications/IntelliJ IDEA CE.app/Contents/plugins/maven/lib/maven-event-listener.jar -javaagent:/Applications/IntelliJ IDEA CE.app/Contents/lib/idea_rt.jar=51496:/Applications/IntelliJ IDEA CE.app/Contents/bin -Dfile.encoding=UTF-8 -classpath /Applications/IntelliJ IDEA CE.app/Contents/plugins/maven/lib/maven3/boot/plexus-classworlds.license:/Applications/IntelliJ IDEA CE.app/Contents/plugins/maven/lib/maven3/boot/plexus-classworlds-2.6.0.jar org.codehaus.classworlds.Launcher -Didea.version=2022.1 clean install -DskipTests -Pbin-dist -P apple-silicon
[INFO] Scanning for projects...
[INFO] ------------------------------------------------------------------------
[INFO] Detecting the operating system and CPU architecture
[INFO] ------------------------------------------------------------------------
[INFO] os.detected.name: osx
[INFO] os.detected.arch: x86_64
[INFO] os.detected.version: 11.3
[INFO] os.detected.version.major: 11
[INFO] os.detected.version.minor: 3
[INFO] os.detected.classifier: osx-x86_64
[INFO] 
[INFO] -------------------< org.apache.pinot:pinot-pulsar >--------------------
[INFO] Building Pinot Pulsar 0.10.0-SNAPSHOT
[INFO] --------------------------------[ jar ]---------------------------------
Downloading from maven-default-http-blocker: http://0.0.0.0/io/grpc/grpc-core/maven-metadata.xml
[WARNING] Could not transfer metadata io.grpc:grpc-core/maven-metadata.xml from/to maven-default-http-blocker (http://0.0.0.0/): transfer failed for http://0.0.0.0/io/grpc/grpc-core/maven-metadata.xml
[INFO] 
[INFO] --- maven-clean-plugin:3.1.0:clean (default-clean) @ pinot-pulsar ---
[INFO] Deleting /Users/.../Downloads/pinot-0.10.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target
[INFO] 
[INFO] --- maven-checkstyle-plugin:3.1.2:check (checkstyle) @ pinot-pulsar ---
[INFO] You have 0 Checkstyle violations.
[INFO] 
[INFO] --- buildnumber-maven-plugin:1.3:create (default) @ pinot-pulsar ---
[INFO] Executing: /bin/sh -c cd /Users/.../Downloads/pinot-0.10.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar && git rev-parse --verify HEAD
[INFO] Working directory: /Users/.../Downloads/pinot-0.10.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar
[INFO] Storing buildNumber: 8633d8c996e6c5b81f03d8b08fb90d4608f41d6a at timestamp: 1656384913577
[INFO] Storing buildScmBranch: feature/condition_optimize_equal_220620
[INFO] 
[INFO] --- maven-enforcer-plugin:3.0.0-M2:enforce (enforce-dependency-convergence) @ pinot-pulsar ---
[INFO] 
[INFO] --- maven-enforcer-plugin:3.0.0-M2:enforce (enforce-maven-version) @ pinot-pulsar ---
[INFO] 
[INFO] --- jacoco-maven-plugin:0.8.6:prepare-agent (default) @ pinot-pulsar ---
[INFO] argLine set to -javaagent:/Users/.../.m2/repository/org/jacoco/org.jacoco.agent/0.8.6/org.jacoco.agent-0.8.6-runtime.jar=destfile=/Users/.../Downloads/pinot-0.10.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/jacoco.exec -Xms4g -Xmx4g
[INFO] 
[INFO] --- maven-remote-resources-plugin:1.6.0:process (process-resource-bundles) @ pinot-pulsar ---
[INFO] Preparing remote bundle org.apache:apache-jar-resource-bundle:1.4
[INFO] Copying 3 resources from 1 bundle.
[INFO] 
[INFO] --- maven-remote-resources-plugin:1.6.0:process (default) @ pinot-pulsar ---
[INFO] Preparing remote bundle org.apache:apache-jar-resource-bundle:1.4
[INFO] Copying 3 resources from 1 bundle.
[INFO] 
[INFO] --- maven-resources-plugin:2.6:resources (default-resources) @ pinot-pulsar ---
[INFO] Using 'UTF-8' encoding to copy filtered resources.
[INFO] skip non existing resourceDirectory /Users/.../Downloads/pinot-0.10.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/src/main/resources
[INFO] Copying 3 resources
[INFO] Copying 3 resources
[INFO] 
[INFO] --- maven-compiler-plugin:3.8.0:compile (default-compile) @ pinot-pulsar ---
[INFO] Changes detected - recompiling the module!
[INFO] Compiling 10 source files to /Users/.../Downloads/pinot-0.10.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/classes
[INFO] 
[INFO] --- maven-resources-plugin:2.6:testResources (default-testResources) @ pinot-pulsar ---
[INFO] Using 'UTF-8' encoding to copy filtered resources.
[INFO] Copying 1 resource
[INFO] Copying 3 resources
[INFO] Copying 3 resources
[INFO] 
[INFO] --- maven-compiler-plugin:3.8.0:testCompile (default-testCompile) @ pinot-pulsar ---
[INFO] Changes detected - recompiling the module!
[INFO] Compiling 2 source files to /Users/.../Downloads/pinot-0.10.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/test-classes
[INFO] 
[INFO] --- maven-surefire-plugin:3.0.0-M5:test (default-test) @ pinot-pulsar ---
[INFO] Tests are skipped.
[INFO] 
[INFO] --- jacoco-maven-plugin:0.8.6:report-aggregate (report) @ pinot-pulsar ---
[INFO] 
[INFO] --- maven-jar-plugin:3.2.0:jar (default-jar) @ pinot-pulsar ---
[INFO] Building jar: /Users/.../Downloads/pinot-0.10.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/pinot-pulsar-0.10.0-SNAPSHOT.jar
[INFO] 
[INFO] --- maven-shade-plugin:3.2.1:shade (default) @ pinot-pulsar ---
[INFO] Including org.eclipse.jetty:jetty-server:jar:9.4.39.v20210325 in the shaded jar.
[INFO] Including org.eclipse.jetty:jetty-http:jar:9.4.39.v20210325 in the shaded jar.
[INFO] Including org.eclipse.jetty:jetty-util:jar:9.4.39.v20210325 in the shaded jar.
[INFO] Including org.eclipse.jetty:jetty-io:jar:9.4.39.v20210325 in the shaded jar.
[INFO] Including org.apache.pulsar:pulsar-client-original:jar:2.7.2 in the shaded jar.
[INFO] Including org.apache.pulsar:pulsar-client-api:jar:2.7.2 in the shaded jar.
[INFO] Including org.apache.pulsar:pulsar-common:jar:2.7.2 in the shaded jar.
[INFO] Including io.netty:netty-handler:jar:4.1.54.Final in the shaded jar.
[INFO] Including io.netty:netty-transport-native-epoll:jar:linux-x86_64:4.1.54.Final in the shaded jar.
[INFO] Including org.apache.bookkeeper:bookkeeper-common-allocator:jar:4.12.0 in the shaded jar.
[INFO] Including io.airlift:aircompressor:jar:0.16 in the shaded jar.
[INFO] Including org.apache.bookkeeper:circe-checksum:jar:4.12.0 in the shaded jar.
[INFO] Including io.netty:netty-codec-haproxy:jar:4.1.60.Final in the shaded jar.
[INFO] Including com.fasterxml.jackson.dataformat:jackson-dataformat-yaml:jar:2.10.0 in the shaded jar.
[INFO] Including org.apache.pulsar:pulsar-transaction-common:jar:2.7.2 in the shaded jar.
[INFO] Including com.google.protobuf:protobuf-java-util:jar:3.11.4 in the shaded jar.
[INFO] Including org.apache.pulsar:bouncy-castle-bc:jar:pkg:2.7.2 in the shaded jar.
[INFO] Including io.netty:netty-codec-http:jar:4.1.54.Final in the shaded jar.
[INFO] Including io.netty:netty-resolver-dns:jar:4.1.60.Final in the shaded jar.
[INFO] Including io.netty:netty-codec-dns:jar:4.1.60.Final in the shaded jar.
[INFO] Including org.apache.commons:commons-lang3:jar:3.5 in the shaded jar.
[INFO] Including org.asynchttpclient:async-http-client:jar:2.12.1 in the shaded jar.
[INFO] Including org.asynchttpclient:async-http-client-netty-utils:jar:2.12.1 in the shaded jar.
[INFO] Including org.reactivestreams:reactive-streams:jar:1.0.3 in the shaded jar.
[INFO] Including com.typesafe.netty:netty-reactive-streams:jar:2.0.4 in the shaded jar.
[INFO] Including org.slf4j:slf4j-api:jar:1.7.25 in the shaded jar.
[INFO] Including com.yahoo.datasketches:sketches-core:jar:0.8.3 in the shaded jar.
[INFO] Including com.yahoo.datasketches:memory:jar:0.8.3 in the shaded jar.
[INFO] Including com.google.code.gson:gson:jar:2.2.4 in the shaded jar.
[INFO] Including org.apache.avro:avro:jar:1.9.2 in the shaded jar.
[INFO] Including com.fasterxml.jackson.core:jackson-core:jar:2.10.0 in the shaded jar.
[INFO] Including org.apache.commons:commons-compress:jar:1.20 in the shaded jar.
[INFO] Including org.apache.avro:avro-protobuf:jar:1.9.1 in the shaded jar.
[INFO] Including com.fasterxml.jackson.module:jackson-module-jsonSchema:jar:2.11.1 in the shaded jar.
[INFO] Including net.jcip:jcip-annotations:jar:1.0 in the shaded jar.
[INFO] Including org.apache.pulsar:pulsar-client-admin-original:jar:2.7.2 in the shaded jar.
[INFO] Including org.glassfish.jersey.core:jersey-client:jar:2.28 in the shaded jar.
[INFO] Including org.glassfish.jersey.media:jersey-media-json-jackson:jar:2.28 in the shaded jar.
[INFO] Including org.glassfish.jersey.ext:jersey-entity-filtering:jar:2.28 in the shaded jar.
[INFO] Including com.fasterxml.jackson.module:jackson-module-jaxb-annotations:jar:2.10.0 in the shaded jar.
[INFO] Including jakarta.xml.bind:jakarta.xml.bind-api:jar:2.3.2 in the shaded jar.
[INFO] Including jakarta.activation:jakarta.activation-api:jar:1.2.1 in the shaded jar.
[INFO] Including org.glassfish.jersey.media:jersey-media-multipart:jar:2.28 in the shaded jar.
[INFO] Including org.jvnet.mimepull:mimepull:jar:1.9.11 in the shaded jar.
[INFO] Including com.fasterxml.jackson.jaxrs:jackson-jaxrs-json-provider:jar:2.10.0 in the shaded jar.
[INFO] Including com.fasterxml.jackson.jaxrs:jackson-jaxrs-base:jar:2.10.0 in the shaded jar.
[INFO] Including org.glassfish.jersey.inject:jersey-hk2:jar:2.28 in the shaded jar.
[INFO] Including org.glassfish.hk2:hk2-locator:jar:2.5.0 in the shaded jar.
[INFO] Including org.glassfish.hk2.external:aopalliance-repackaged:jar:2.5.0 in the shaded jar.
[INFO] Including org.glassfish.hk2:hk2-api:jar:2.5.0 in the shaded jar.
[INFO] Including org.glassfish.hk2:hk2-utils:jar:2.5.0 in the shaded jar.
[INFO] Including javax.xml.bind:jaxb-api:jar:2.3.0 in the shaded jar.
[INFO] Including com.sun.activation:javax.activation:jar:1.2.0 in the shaded jar.
[INFO] Including org.slf4j:jul-to-slf4j:jar:1.7.25 in the shaded jar.
[INFO] Including com.google.guava:guava:jar:20.0 in the shaded jar.
[INFO] Including commons-collections:commons-collections:jar:3.2.1 in the shaded jar.
[INFO] Including io.netty:netty-transport:jar:4.1.54.Final in the shaded jar.
[INFO] Including org.apache.pulsar:protobuf-shaded:jar:2.1.0-incubating in the shaded jar.
[INFO] Including com.google.protobuf:protobuf-java:jar:3.12.0 in the shaded jar.
[INFO] Including org.checkerframework:checker-compat-qual:jar:2.5.2 in the shaded jar.
[INFO] Including io.grpc:grpc-core:jar:1.18.0 in the shaded jar.
[INFO] Including javax.servlet:javax.servlet-api:jar:3.1.0 in the shaded jar.
[INFO] Including javax.ws.rs:javax.ws.rs-api:jar:2.1 in the shaded jar.
[INFO] Including org.glassfish.jersey.containers:jersey-container-grizzly2-http:jar:2.28 in the shaded jar.
[INFO] Including org.glassfish.hk2.external:jakarta.inject:jar:2.5.0 in the shaded jar.
[INFO] Including org.glassfish.grizzly:grizzly-http-server:jar:2.4.4 in the shaded jar.
[INFO] Including org.glassfish.grizzly:grizzly-http:jar:2.4.4 in the shaded jar.
[INFO] Including org.glassfish.grizzly:grizzly-framework:jar:2.4.4 in the shaded jar.
[INFO] Including org.glassfish.jersey.core:jersey-common:jar:2.28 in the shaded jar.
[INFO] Including org.glassfish.hk2:osgi-resource-locator:jar:1.0.1 in the shaded jar.
[INFO] Including jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.5 in the shaded jar.
[INFO] Including org.glassfish.jersey.core:jersey-server:jar:2.28 in the shaded jar.
[INFO] Including org.glassfish.jersey.media:jersey-media-jaxb:jar:2.28 in the shaded jar.
[INFO] Including jakarta.annotation:jakarta.annotation-api:jar:1.3.4 in the shaded jar.
[INFO] Including javax.validation:validation-api:jar:2.0.1.Final in the shaded jar.
[INFO] Including org.glassfish.jersey.containers:jersey-container-servlet-core:jar:2.28 in the shaded jar.
[INFO] Including io.netty:netty-resolver:jar:4.1.54.Final in the shaded jar.
[INFO] Including io.netty:netty-common:jar:4.1.54.Final in the shaded jar.
[INFO] Including io.prometheus:simpleclient_common:jar:0.8.1 in the shaded jar.
[INFO] Including com.google.api.grpc:proto-google-common-protos:jar:1.12.0 in the shaded jar.
[INFO] Including io.grpc:grpc-context:jar:1.14.0 in the shaded jar.
[INFO] Including io.netty:netty-tcnative-boringssl-static:jar:2.0.36.Final in the shaded jar.
[INFO] Including commons-codec:commons-codec:jar:1.11 in the shaded jar.
[INFO] Including com.google.errorprone:error_prone_annotations:jar:2.3.4 in the shaded jar.
[INFO] Including io.prometheus:simpleclient:jar:0.8.1 in the shaded jar.
[INFO] Including org.eclipse.jetty:jetty-servlet:jar:9.4.39.v20210325 in the shaded jar.
[INFO] Including org.eclipse.jetty:jetty-security:jar:9.4.39.v20210325 in the shaded jar.
[INFO] Including org.eclipse.jetty:jetty-util-ajax:jar:9.4.39.v20210325 in the shaded jar.
[INFO] Including com.squareup.okio:okio:jar:1.6.0 in the shaded jar.
[INFO] Including io.prometheus:simpleclient_hotspot:jar:0.8.1 in the shaded jar.
[INFO] Including io.swagger:swagger-annotations:jar:1.5.21 in the shaded jar.
[INFO] Including io.grpc:grpc-protobuf-lite:jar:1.19.0 in the shaded jar.
[INFO] Including com.google.protobuf:protobuf-lite:jar:3.0.1 in the shaded jar.
[INFO] Including org.apache.commons:commons-collections4:jar:4.1 in the shaded jar.
[INFO] Including javax.annotation:javax.annotation-api:jar:1.2 in the shaded jar.
[INFO] Including org.codehaus.mojo:animal-sniffer-annotations:jar:1.17 in the shaded jar.
[INFO] Including com.github.ben-manes.caffeine:caffeine:jar:2.6.2 in the shaded jar.
[INFO] Including io.netty:netty-codec-socks:jar:4.1.54.Final in the shaded jar.
[INFO] Including io.netty:netty-buffer:jar:4.1.54.Final in the shaded jar.
[INFO] Including io.netty:netty-codec:jar:4.1.54.Final in the shaded jar.
[INFO] Including io.netty:netty-transport-native-unix-common:jar:4.1.54.Final in the shaded jar.
[INFO] Including org.bouncycastle:bcpkix-jdk15to18:jar:1.68 in the shaded jar.
[INFO] Including org.bouncycastle:bcprov-ext-jdk15to18:jar:1.68 in the shaded jar.
[INFO] Including org.bouncycastle:bcprov-jdk15to18:jar:1.68 in the shaded jar.
[INFO] Including org.apache.pinot:pinot-spi:jar:0.10.0-SNAPSHOT in the shaded jar.
[INFO] Including commons-configuration:commons-configuration:jar:1.10 in the shaded jar.
[INFO] Including commons-io:commons-io:jar:2.4 in the shaded jar.
[INFO] Including commons-lang:commons-lang:jar:2.6 in the shaded jar.
[INFO] Including commons-logging:commons-logging:jar:1.2 in the shaded jar.
[INFO] Including com.google.code.findbugs:jsr305:jar:3.0.0 in the shaded jar.
[INFO] Including org.apache.logging.log4j:log4j-slf4j-impl:jar:2.17.0 in the shaded jar.
[INFO] Including org.apache.logging.log4j:log4j-api:jar:2.17.0 in the shaded jar.
[INFO] Including org.apache.logging.log4j:log4j-core:jar:2.17.0 in the shaded jar.
[INFO] Including com.lmax:disruptor:jar:3.3.4 in the shaded jar.
[INFO] Including org.apache.logging.log4j:log4j-1.2-api:jar:2.17.0 in the shaded jar.
[INFO] Including joda-time:joda-time:jar:2.10.5 in the shaded jar.
[INFO] Including com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0 in the shaded jar.
[INFO] Including org.yaml:snakeyaml:jar:1.16 in the shaded jar.
[INFO] Including com.fasterxml.jackson.core:jackson-databind:jar:2.10.0 in the shaded jar.
[INFO] Including org.codehaus.groovy:groovy-all:jar:2.4.21 in the shaded jar.
[INFO] Including org.reflections:reflections:jar:0.9.9 in the shaded jar.
[INFO] Including org.javassist:javassist:jar:3.19.0-GA in the shaded jar.
[INFO] Including com.google.code.findbugs:annotations:jar:2.0.1 in the shaded jar.
[INFO] Including com.tdunning:t-digest:jar:3.2 in the shaded jar.
[WARNING] Discovered module-info.class. Shading will break its strong encapsulation.
[WARNING] Discovered module-info.class. Shading will break its strong encapsulation.
[WARNING] Discovered module-info.class. Shading will break its strong encapsulation.
[WARNING] Discovered module-info.class. Shading will break its strong encapsulation.
[WARNING] Discovered module-info.class. Shading will break its strong encapsulation.
[WARNING] Discovered module-info.class. Shading will break its strong encapsulation.
[WARNING] Discovered module-info.class. Shading will break its strong encapsulation.
[WARNING] Discovered module-info.class. Shading will break its strong encapsulation.
[WARNING] Discovered module-info.class. Shading will break its strong encapsulation.
[WARNING] Discovered module-info.class. Shading will break its strong encapsulation.
[WARNING] Discovered module-info.class. Shading will break its strong encapsulation.
[WARNING] Discovered module-info.class. Shading will break its strong encapsulation.
[WARNING] jakarta.activation-api-1.2.1.jar, javax.activation-1.2.0.jar define 31 overlapping classes: 
[WARNING]   - javax.activation.CommandInfo$Beans$1
[WARNING]   - javax.activation.ObjectDataContentHandler
[WARNING]   - javax.activation.DataContentHandlerFactory
[WARNING]   - javax.activation.DataContentHandler
[WARNING]   - javax.activation.CommandObject
[WARNING]   - javax.activation.SecuritySupport$2
[WARNING]   - javax.activation.FileTypeMap
[WARNING]   - javax.activation.CommandInfo
[WARNING]   - javax.activation.MailcapCommandMap
[WARNING]   - javax.activation.DataHandler$1
[WARNING]   - 21 more...
[WARNING] jaxb-api-2.3.0.jar, jakarta.xml.bind-api-2.3.2.jar define 111 overlapping classes: 
[WARNING]   - javax.xml.bind.annotation.XmlValue
[WARNING]   - javax.xml.bind.annotation.XmlElement
[WARNING]   - javax.xml.bind.annotation.adapters.XmlJavaTypeAdapter
[WARNING]   - javax.xml.bind.ContextFinder
[WARNING]   - javax.xml.bind.ContextFinder$3
[WARNING]   - javax.xml.bind.annotation.XmlElementRefs
[WARNING]   - javax.xml.bind.helpers.DefaultValidationEventHandler
[WARNING]   - javax.xml.bind.ParseConversionEvent
[WARNING]   - javax.xml.bind.annotation.XmlSchema
[WARNING]   - javax.xml.bind.ValidationException
[WARNING]   - 101 more...
[WARNING] annotations-2.0.1.jar, jsr305-3.0.0.jar define 34 overlapping classes: 
[WARNING]   - javax.annotation.RegEx
[WARNING]   - javax.annotation.concurrent.Immutable
[WARNING]   - javax.annotation.meta.TypeQualifierDefault
[WARNING]   - javax.annotation.meta.TypeQualifier
[WARNING]   - javax.annotation.Syntax
[WARNING]   - javax.annotation.CheckForNull
[WARNING]   - javax.annotation.Nonnull
[WARNING]   - javax.annotation.CheckReturnValue
[WARNING]   - javax.annotation.meta.TypeQualifierNickname
[WARNING]   - javax.annotation.MatchesPattern
[WARNING]   - 24 more...
[WARNING] jakarta.ws.rs-api-2.1.5.jar, javax.ws.rs-api-2.1.jar define 137 overlapping classes: 
[WARNING]   - javax.ws.rs.ext.RuntimeDelegate$HeaderDelegate
[WARNING]   - javax.ws.rs.DefaultValue
[WARNING]   - javax.ws.rs.core.StreamingOutput
[WARNING]   - javax.ws.rs.HEAD
[WARNING]   - javax.ws.rs.core.Request
[WARNING]   - javax.ws.rs.ext.WriterInterceptor
[WARNING]   - javax.ws.rs.ext.Providers
[WARNING]   - javax.ws.rs.container.Suspended
[WARNING]   - javax.ws.rs.container.ConnectionCallback
[WARNING]   - javax.ws.rs.client.FactoryFinder
[WARNING]   - 127 more...
[WARNING] bcprov-ext-jdk15to18-1.68.jar, bcprov-jdk15to18-1.68.jar define 3604 overlapping classes: 
[WARNING]   - org.bouncycastle.crypto.modes.gcm.Tables8kGCMMultiplier
[WARNING]   - org.bouncycastle.pqc.jcajce.provider.qtesla.SignatureSpi
[WARNING]   - org.bouncycastle.jcajce.provider.asymmetric.ecgost.KeyFactorySpi
[WARNING]   - org.bouncycastle.jcajce.provider.symmetric.AES$AlgParamsCCM
[WARNING]   - org.bouncycastle.asn1.cmc.CMCStatusInfoV2
[WARNING]   - org.bouncycastle.pqc.crypto.sphincs.SPHINCSKeyParameters
[WARNING]   - org.bouncycastle.jcajce.provider.digest.SHA384$Mappings
[WARNING]   - org.bouncycastle.asn1.x509.CRLNumber
[WARNING]   - org.bouncycastle.jcajce.provider.digest.SM3
[WARNING]   - org.bouncycastle.asn1.x509.TBSCertList$1
[WARNING]   - 3594 more...
[WARNING] protobuf-java-3.12.0.jar, protobuf-lite-3.0.1.jar define 135 overlapping classes: 
[WARNING]   - com.google.protobuf.CodedOutputStream$AbstractBufferedEncoder
[WARNING]   - com.google.protobuf.MessageLiteOrBuilder
[WARNING]   - com.google.protobuf.LazyField$LazyEntry
[WARNING]   - com.google.protobuf.AbstractMessageLite
[WARNING]   - com.google.protobuf.UnsafeUtil
[WARNING]   - com.google.protobuf.Utf8
[WARNING]   - com.google.protobuf.LazyStringArrayList$ByteArrayListView
[WARNING]   - com.google.protobuf.GeneratedMessageLite$ExtensionDescriptor
[WARNING]   - com.google.protobuf.SmallSortedMap$EntrySet
[WARNING]   - com.google.protobuf.CodedOutputStream$1
[WARNING]   - 125 more...
[WARNING] jcip-annotations-1.0.jar, annotations-2.0.1.jar define 4 overlapping classes: 
[WARNING]   - net.jcip.annotations.GuardedBy
[WARNING]   - net.jcip.annotations.NotThreadSafe
[WARNING]   - net.jcip.annotations.ThreadSafe
[WARNING]   - net.jcip.annotations.Immutable
[WARNING] jakarta.annotation-api-1.3.4.jar, javax.annotation-api-1.2.jar define 15 overlapping classes: 
[WARNING]   - javax.annotation.ManagedBean
[WARNING]   - javax.annotation.PreDestroy
[WARNING]   - javax.annotation.Resource$AuthenticationType
[WARNING]   - javax.annotation.Generated
[WARNING]   - javax.annotation.security.DeclareRoles
[WARNING]   - javax.annotation.Priority
[WARNING]   - javax.annotation.Resource
[WARNING]   - javax.annotation.security.DenyAll
[WARNING]   - javax.annotation.security.RunAs
[WARNING]   - javax.annotation.sql.DataSourceDefinitions
[WARNING]   - 5 more...
[WARNING] maven-shade-plugin has detected that some class files are
[WARNING] present in two or more JARs. When this happens, only one
[WARNING] single version of the class is copied to the uber jar.
[WARNING] Usually this is not harmful and you can skip these warnings,
[WARNING] otherwise try to manually exclude artifacts based on
[WARNING] mvn dependency:tree -Ddetail=true and the above output.
[WARNING] See http://maven.apache.org/plugins/maven-shade-plugin/
[INFO] Attaching shaded artifact.
[INFO] 
[INFO] --- maven-site-plugin:3.7.1:attach-descriptor (attach-descriptor) @ pinot-pulsar ---
[INFO] Skipping because packaging 'jar' is not pom.
[INFO] 
[INFO] --- maven-jar-plugin:3.2.0:test-jar (default) @ pinot-pulsar ---
[INFO] Building jar: /Users/.../Downloads/pinot-0.10.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/pinot-pulsar-0.10.0-SNAPSHOT-tests.jar
[INFO] 
[INFO] --- maven-surefire-plugin:3.0.0-M5:test (integration-tests) @ pinot-pulsar ---
[INFO] Tests are skipped.
[INFO] 
[INFO] --- spotless-maven-plugin:2.9.0:check (default) @ pinot-pulsar ---
[INFO] 
[INFO] --- license-maven-plugin:4.0:check (default) @ pinot-pulsar ---
[INFO] Checking licenses...
[INFO] 
[INFO] --- apache-rat-plugin:0.13:check (default) @ pinot-pulsar ---
[INFO] Enabled default license matchers.
[INFO] Will parse SCM ignores for exclusions...
[INFO] Finished adding exclusions from SCM ignore files.
[INFO] 62 implicit excludes (use -debug for more details).
[INFO] 40 explicit excludes (use -debug for more details).
[INFO] 14 resources included (use -debug for more details)
[INFO] Rat check: Summary over all files. Unapproved: 0, unknown: 0, generated: 0, approved: 14 licenses.
[INFO] 
[INFO] --- maven-install-plugin:2.5.2:install (default-install) @ pinot-pulsar ---
[INFO] Installing /Users/.../Downloads/pinot-0.10.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/pinot-pulsar-0.10.0-SNAPSHOT.jar to /Users/.../.m2/repository/org/apache/pinot/pinot-pulsar/0.10.0-SNAPSHOT/pinot-pulsar-0.10.0-SNAPSHOT.jar
[INFO] Installing /Users/.../Downloads/pinot-0.10.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/pom.xml to /Users/.../.m2/repository/org/apache/pinot/pinot-pulsar/0.10.0-SNAPSHOT/pinot-pulsar-0.10.0-SNAPSHOT.pom
[INFO] Installing /Users/.../Downloads/pinot-0.10.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/pinot-pulsar-0.10.0-SNAPSHOT-shaded.jar to /Users/.../.m2/repository/org/apache/pinot/pinot-pulsar/0.10.0-SNAPSHOT/pinot-pulsar-0.10.0-SNAPSHOT-shaded.jar
[INFO] Installing /Users/.../Downloads/pinot-0.10.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/pinot-pulsar-0.10.0-SNAPSHOT-tests.jar to /Users/.../.m2/repository/org/apache/pinot/pinot-pulsar/0.10.0-SNAPSHOT/pinot-pulsar-0.10.0-SNAPSHOT-tests.jar
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  38.876 s
[INFO] Finished at: 2022-06-28T10:55:44+08:00
[INFO] ------------------------------------------------------------------------
[WARNING] The requested profile "bin-dist" could not be activated because it does not exist.

Process finished with exit code 0
```
