```
/Library/Java/JavaVirtualMachines/jdk-11.0.13.jdk/Contents/Home/bin/java -Dmaven.multiModuleProjectDirectory=/Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar -Dmaven.home=/Applications/IntelliJ IDEA CE.app/Contents/plugins/maven/lib/maven3 -Dclassworlds.conf=/Applications/IntelliJ IDEA CE.app/Contents/plugins/maven/lib/maven3/bin/m2.conf -Dmaven.ext.class.path=/Applications/IntelliJ IDEA CE.app/Contents/plugins/maven/lib/maven-event-listener.jar -javaagent:/Applications/IntelliJ IDEA CE.app/Contents/lib/idea_rt.jar=52165:/Applications/IntelliJ IDEA CE.app/Contents/bin -Dfile.encoding=UTF-8 -classpath /Applications/IntelliJ IDEA CE.app/Contents/plugins/maven/lib/maven3/boot/plexus-classworlds.license:/Applications/IntelliJ IDEA CE.app/Contents/plugins/maven/lib/maven3/boot/plexus-classworlds-2.6.0.jar org.codehaus.classworlds.Launcher -Didea.version=2022.1 clean install package -DskipTests -Pbin-dist -X -P apple-silicon,other-jdk-maven-compiler-plugin
Apache Maven 3.8.1 (05c21c65bdfed0f71a2f2ada8b84da59348c4c5d)
Maven home: /Applications/IntelliJ IDEA CE.app/Contents/plugins/maven/lib/maven3
Java version: 11.0.13, vendor: Oracle Corporation, runtime: /Library/Java/JavaVirtualMachines/jdk-11.0.13.jdk/Contents/Home
Default locale: zh_CN_#Hans, platform encoding: UTF-8
OS name: "mac os x", version: "11.3", arch: "x86_64", family: "mac"
[DEBUG]   Included /Applications/IntelliJ IDEA CE.app/Contents/plugins/maven/lib/maven-event-listener.jar
[DEBUG] Populating class realm maven.ext
[DEBUG]   Included /Applications/IntelliJ IDEA CE.app/Contents/plugins/maven/lib/maven-event-listener.jar
[DEBUG] Created new class realm maven.api
[DEBUG] Importing foreign packages into class realm maven.api
[DEBUG]   Imported: javax.annotation.* < maven.ext
[DEBUG]   Imported: javax.annotation.security.* < maven.ext
[DEBUG]   Imported: javax.enterprise.inject.* < maven.ext
[DEBUG]   Imported: javax.enterprise.util.* < maven.ext
[DEBUG]   Imported: javax.inject.* < maven.ext
[DEBUG]   Imported: org.apache.maven.* < maven.ext
[DEBUG]   Imported: org.apache.maven.artifact < maven.ext
[DEBUG]   Imported: org.apache.maven.classrealm < maven.ext
[DEBUG]   Imported: org.apache.maven.cli < maven.ext
[DEBUG]   Imported: org.apache.maven.configuration < maven.ext
[DEBUG]   Imported: org.apache.maven.exception < maven.ext
[DEBUG]   Imported: org.apache.maven.execution < maven.ext
[DEBUG]   Imported: org.apache.maven.execution.scope < maven.ext
[DEBUG]   Imported: org.apache.maven.lifecycle < maven.ext
[DEBUG]   Imported: org.apache.maven.model < maven.ext
[DEBUG]   Imported: org.apache.maven.monitor < maven.ext
[DEBUG]   Imported: org.apache.maven.plugin < maven.ext
[DEBUG]   Imported: org.apache.maven.profiles < maven.ext
[DEBUG]   Imported: org.apache.maven.project < maven.ext
[DEBUG]   Imported: org.apache.maven.reporting < maven.ext
[DEBUG]   Imported: org.apache.maven.repository < maven.ext
[DEBUG]   Imported: org.apache.maven.rtinfo < maven.ext
[DEBUG]   Imported: org.apache.maven.settings < maven.ext
[DEBUG]   Imported: org.apache.maven.toolchain < maven.ext
[DEBUG]   Imported: org.apache.maven.usability < maven.ext
[DEBUG]   Imported: org.apache.maven.wagon.* < maven.ext
[DEBUG]   Imported: org.apache.maven.wagon.authentication < maven.ext
[DEBUG]   Imported: org.apache.maven.wagon.authorization < maven.ext
[DEBUG]   Imported: org.apache.maven.wagon.events < maven.ext
[DEBUG]   Imported: org.apache.maven.wagon.observers < maven.ext
[DEBUG]   Imported: org.apache.maven.wagon.proxy < maven.ext
[DEBUG]   Imported: org.apache.maven.wagon.repository < maven.ext
[DEBUG]   Imported: org.apache.maven.wagon.resource < maven.ext
[DEBUG]   Imported: org.codehaus.classworlds < maven.ext
[DEBUG]   Imported: org.codehaus.plexus.* < maven.ext
[DEBUG]   Imported: org.codehaus.plexus.classworlds < maven.ext
[DEBUG]   Imported: org.codehaus.plexus.component < maven.ext
[DEBUG]   Imported: org.codehaus.plexus.configuration < maven.ext
[DEBUG]   Imported: org.codehaus.plexus.container < maven.ext
[DEBUG]   Imported: org.codehaus.plexus.context < maven.ext
[DEBUG]   Imported: org.codehaus.plexus.lifecycle < maven.ext
[DEBUG]   Imported: org.codehaus.plexus.logging < maven.ext
[DEBUG]   Imported: org.codehaus.plexus.personality < maven.ext
[DEBUG]   Imported: org.codehaus.plexus.util.xml.Xpp3Dom < maven.ext
[DEBUG]   Imported: org.codehaus.plexus.util.xml.pull.XmlPullParser < maven.ext
[DEBUG]   Imported: org.codehaus.plexus.util.xml.pull.XmlPullParserException < maven.ext
[DEBUG]   Imported: org.codehaus.plexus.util.xml.pull.XmlSerializer < maven.ext
[DEBUG]   Imported: org.eclipse.aether.* < maven.ext
[DEBUG]   Imported: org.eclipse.aether.artifact < maven.ext
[DEBUG]   Imported: org.eclipse.aether.collection < maven.ext
[DEBUG]   Imported: org.eclipse.aether.deployment < maven.ext
[DEBUG]   Imported: org.eclipse.aether.graph < maven.ext
[DEBUG]   Imported: org.eclipse.aether.impl < maven.ext
[DEBUG]   Imported: org.eclipse.aether.installation < maven.ext
[DEBUG]   Imported: org.eclipse.aether.internal.impl < maven.ext
[DEBUG]   Imported: org.eclipse.aether.metadata < maven.ext
[DEBUG]   Imported: org.eclipse.aether.repository < maven.ext
[DEBUG]   Imported: org.eclipse.aether.resolution < maven.ext
[DEBUG]   Imported: org.eclipse.aether.spi < maven.ext
[DEBUG]   Imported: org.eclipse.aether.transfer < maven.ext
[DEBUG]   Imported: org.eclipse.aether.version < maven.ext
[DEBUG]   Imported: org.fusesource.jansi.* < maven.ext
[DEBUG]   Imported: org.slf4j.* < maven.ext
[DEBUG]   Imported: org.slf4j.event.* < maven.ext
[DEBUG]   Imported: org.slf4j.helpers.* < maven.ext
[DEBUG]   Imported: org.slf4j.spi.* < maven.ext
[DEBUG] Populating class realm maven.api
[INFO] Error stacktraces are turned on.
[DEBUG] Message scheme: color
[DEBUG] Message styles: debug info warning error success failure strong mojo project
[DEBUG] Reading global settings from /Applications/IntelliJ IDEA CE.app/Contents/plugins/maven/lib/maven3/conf/settings.xml
[DEBUG] Reading user settings from /Users/.../.m2/settings.xml
[DEBUG] Reading global toolchains from /Applications/IntelliJ IDEA CE.app/Contents/plugins/maven/lib/maven3/conf/toolchains.xml
[DEBUG] Reading user toolchains from /Users/.../.m2/toolchains.xml
[DEBUG] Using local repository at /Users/.../.m2/repository
[DEBUG] Using manager EnhancedLocalRepositoryManager with priority 10.0 for /Users/.../.m2/repository
[INFO] Scanning for projects...
[DEBUG] Using mirror maven-default-http-blocker (http://0.0.0.0/) for repository.jboss.org (http://repository.jboss.org/maven2).
[DEBUG] Using mirror maven-default-http-blocker (http://0.0.0.0/) for snapshots.jboss.org (http://snapshots.jboss.org/maven2).
[DEBUG] Using mirror maven-default-http-blocker (http://0.0.0.0/) for oss.sonatype.org/jboss-snapshots (http://oss.sonatype.org/content/repositories/jboss-snapshots).
[DEBUG] Dependency collection stats {ConflictMarker.analyzeTime=484167, ConflictMarker.markTime=220875, ConflictMarker.nodeCount=20, ConflictIdSorter.graphTime=246208, ConflictIdSorter.topsortTime=147708, ConflictIdSorter.conflictIdCount=14, ConflictIdSorter.conflictIdCycleCount=0, ConflictResolver.totalTime=2143500, ConflictResolver.conflictItemCount=20, DefaultDependencyCollector.collectTime=346918083, DefaultDependencyCollector.transformTime=5405375}
[DEBUG] kr.motd.maven:os-maven-plugin:jar:1.6.2
[DEBUG]    org.apache.maven:maven-plugin-api:jar:3.5.3:compile
[DEBUG]       org.apache.maven:maven-model:jar:3.5.3:compile
[DEBUG]          org.apache.commons:commons-lang3:jar:3.5:compile
[DEBUG]       org.apache.maven:maven-artifact:jar:3.5.3:compile
[DEBUG]       org.eclipse.sisu:org.eclipse.sisu.plexus:jar:0.3.3:compile
[DEBUG]          javax.enterprise:cdi-api:jar:1.0:compile
[DEBUG]             javax.annotation:jsr250-api:jar:1.0:compile
[DEBUG]             javax.inject:javax.inject:jar:1:compile
[DEBUG]          org.eclipse.sisu:org.eclipse.sisu.inject:jar:0.3.3:compile
[DEBUG]          org.codehaus.plexus:plexus-component-annotations:jar:1.5.5:compile
[DEBUG]       org.codehaus.plexus:plexus-classworlds:jar:2.5.2:compile
[DEBUG]    org.codehaus.plexus:plexus-utils:jar:3.1.0:compile
[DEBUG]    com.google.code.findbugs:jsr305:jar:3.0.2:compile
[DEBUG] Created new class realm extension>kr.motd.maven:os-maven-plugin:1.6.2
[DEBUG] Importing foreign packages into class realm extension>kr.motd.maven:os-maven-plugin:1.6.2
[DEBUG]   Imported:  < maven.api
[DEBUG] Populating class realm extension>kr.motd.maven:os-maven-plugin:1.6.2
[DEBUG]   Included: kr.motd.maven:os-maven-plugin:jar:1.6.2
[DEBUG]   Included: org.apache.commons:commons-lang3:jar:3.5
[DEBUG]   Included: javax.enterprise:cdi-api:jar:1.0
[DEBUG]   Included: org.eclipse.sisu:org.eclipse.sisu.inject:jar:0.3.3
[DEBUG]   Included: org.codehaus.plexus:plexus-component-annotations:jar:1.5.5
[DEBUG]   Included: org.codehaus.plexus:plexus-utils:jar:3.1.0
[DEBUG]   Included: com.google.code.findbugs:jsr305:jar:3.0.2
[DEBUG] Extension realms for project org.apache.pinot:pinot-pulsar:jar:0.11.0-SNAPSHOT: [ClassRealm[extension>kr.motd.maven:os-maven-plugin:1.6.2, parent: jdk.internal.loader.ClassLoaders$AppClassLoader@2c13da15]]
[DEBUG] Created new class realm project>org.apache.pinot:pinot-pulsar:0.11.0-SNAPSHOT
[DEBUG] Populating class realm project>org.apache.pinot:pinot-pulsar:0.11.0-SNAPSHOT
[DEBUG] Looking up lifecycle mappings for packaging jar from ClassRealm[project>org.apache.pinot:pinot-pulsar:0.11.0-SNAPSHOT, parent: ClassRealm[maven.api, parent: null]]
[DEBUG] Extension realms for project org.apache.pinot:pinot-stream-ingestion:pom:0.11.0-SNAPSHOT: [ClassRealm[extension>kr.motd.maven:os-maven-plugin:1.6.2, parent: jdk.internal.loader.ClassLoaders$AppClassLoader@2c13da15]]
[DEBUG] Looking up lifecycle mappings for packaging pom from ClassRealm[project>org.apache.pinot:pinot-pulsar:0.11.0-SNAPSHOT, parent: ClassRealm[maven.api, parent: null]]
[DEBUG] Extension realms for project org.apache.pinot:pinot-plugins:pom:0.11.0-SNAPSHOT: [ClassRealm[extension>kr.motd.maven:os-maven-plugin:1.6.2, parent: jdk.internal.loader.ClassLoaders$AppClassLoader@2c13da15]]
[DEBUG] Looking up lifecycle mappings for packaging pom from ClassRealm[project>org.apache.pinot:pinot-pulsar:0.11.0-SNAPSHOT, parent: ClassRealm[maven.api, parent: null]]
[DEBUG] Extension realms for project org.apache.pinot:pinot:pom:0.11.0-SNAPSHOT: [ClassRealm[extension>kr.motd.maven:os-maven-plugin:1.6.2, parent: jdk.internal.loader.ClassLoaders$AppClassLoader@2c13da15]]
[DEBUG] Looking up lifecycle mappings for packaging pom from ClassRealm[project>org.apache.pinot:pinot-pulsar:0.11.0-SNAPSHOT, parent: ClassRealm[maven.api, parent: null]]
[DEBUG] Extension realms for project org.apache:apache:pom:21: (none)
[DEBUG] Looking up lifecycle mappings for packaging pom from ClassRealm[maven.ext, parent: ClassRealm[plexus.core, parent: null]]
[INFO] ------------------------------------------------------------------------
[INFO] Detecting the operating system and CPU architecture
[INFO] ------------------------------------------------------------------------
[INFO] os.detected.name: osx
[INFO] os.detected.arch: x86_64
[INFO] os.detected.version: 11.3
[INFO] os.detected.version.major: 11
[INFO] os.detected.version.minor: 3
[INFO] os.detected.classifier: osx-x86_64
[DEBUG] === REACTOR BUILD PLAN ================================================
[DEBUG] Project: org.apache.pinot:pinot-pulsar:jar:0.11.0-SNAPSHOT
[DEBUG] Tasks:   [clean, install, package]
[DEBUG] Style:   Regular
[DEBUG] =======================================================================
[INFO] 
[INFO] -------------------< org.apache.pinot:pinot-pulsar >--------------------
[INFO] Building Pinot Pulsar 0.11.0-SNAPSHOT
[INFO] --------------------------------[ jar ]---------------------------------
[DEBUG] Lifecycle default -> [validate, initialize, generate-sources, process-sources, generate-resources, process-resources, compile, process-classes, generate-test-sources, process-test-sources, generate-test-resources, process-test-resources, test-compile, process-test-classes, test, prepare-package, package, pre-integration-test, integration-test, post-integration-test, verify, install, deploy]
[DEBUG] Lifecycle clean -> [pre-clean, clean, post-clean]
[DEBUG] Lifecycle site -> [pre-site, site, post-site, site-deploy]
[DEBUG] Lifecycle default -> [validate, initialize, generate-sources, process-sources, generate-resources, process-resources, compile, process-classes, generate-test-sources, process-test-sources, generate-test-resources, process-test-resources, test-compile, process-test-classes, test, prepare-package, package, pre-integration-test, integration-test, post-integration-test, verify, install, deploy]
[DEBUG] Lifecycle clean -> [pre-clean, clean, post-clean]
[DEBUG] Lifecycle site -> [pre-site, site, post-site, site-deploy]
[DEBUG] Lifecycle default -> [validate, initialize, generate-sources, process-sources, generate-resources, process-resources, compile, process-classes, generate-test-sources, process-test-sources, generate-test-resources, process-test-resources, test-compile, process-test-classes, test, prepare-package, package, pre-integration-test, integration-test, post-integration-test, verify, install, deploy]
[DEBUG] Lifecycle clean -> [pre-clean, clean, post-clean]
[DEBUG] Lifecycle site -> [pre-site, site, post-site, site-deploy]
[DEBUG] Using mirror maven-default-http-blocker (http://0.0.0.0/) for codehaus-snapshots (http://nexus.codehaus.org/snapshots/).
[DEBUG] Using mirror maven-default-http-blocker (http://0.0.0.0/) for apache.snapshots (http://repository.apache.org/snapshots).
[DEBUG] Lifecycle default -> [validate, initialize, generate-sources, process-sources, generate-resources, process-resources, compile, process-classes, generate-test-sources, process-test-sources, generate-test-resources, process-test-resources, test-compile, process-test-classes, test, prepare-package, package, pre-integration-test, integration-test, post-integration-test, verify, install, deploy]
[DEBUG] Lifecycle clean -> [pre-clean, clean, post-clean]
[DEBUG] Lifecycle site -> [pre-site, site, post-site, site-deploy]
[DEBUG] Lifecycle default -> [validate, initialize, generate-sources, process-sources, generate-resources, process-resources, compile, process-classes, generate-test-sources, process-test-sources, generate-test-resources, process-test-resources, test-compile, process-test-classes, test, prepare-package, package, pre-integration-test, integration-test, post-integration-test, verify, install, deploy]
[DEBUG] Lifecycle clean -> [pre-clean, clean, post-clean]
[DEBUG] Lifecycle site -> [pre-site, site, post-site, site-deploy]
[DEBUG] Lifecycle default -> [validate, initialize, generate-sources, process-sources, generate-resources, process-resources, compile, process-classes, generate-test-sources, process-test-sources, generate-test-resources, process-test-resources, test-compile, process-test-classes, test, prepare-package, package, pre-integration-test, integration-test, post-integration-test, verify, install, deploy]
[DEBUG] Lifecycle clean -> [pre-clean, clean, post-clean]
[DEBUG] Lifecycle site -> [pre-site, site, post-site, site-deploy]
[DEBUG] Lifecycle default -> [validate, initialize, generate-sources, process-sources, generate-resources, process-resources, compile, process-classes, generate-test-sources, process-test-sources, generate-test-resources, process-test-resources, test-compile, process-test-classes, test, prepare-package, package, pre-integration-test, integration-test, post-integration-test, verify, install, deploy]
[DEBUG] Lifecycle clean -> [pre-clean, clean, post-clean]
[DEBUG] Lifecycle site -> [pre-site, site, post-site, site-deploy]
[DEBUG] Lifecycle default -> [validate, initialize, generate-sources, process-sources, generate-resources, process-resources, compile, process-classes, generate-test-sources, process-test-sources, generate-test-resources, process-test-resources, test-compile, process-test-classes, test, prepare-package, package, pre-integration-test, integration-test, post-integration-test, verify, install, deploy]
[DEBUG] Lifecycle clean -> [pre-clean, clean, post-clean]
[DEBUG] Lifecycle site -> [pre-site, site, post-site, site-deploy]
[DEBUG] Lifecycle default -> [validate, initialize, generate-sources, process-sources, generate-resources, process-resources, compile, process-classes, generate-test-sources, process-test-sources, generate-test-resources, process-test-resources, test-compile, process-test-classes, test, prepare-package, package, pre-integration-test, integration-test, post-integration-test, verify, install, deploy]
[DEBUG] Lifecycle clean -> [pre-clean, clean, post-clean]
[DEBUG] Lifecycle site -> [pre-site, site, post-site, site-deploy]
[DEBUG] Lifecycle default -> [validate, initialize, generate-sources, process-sources, generate-resources, process-resources, compile, process-classes, generate-test-sources, process-test-sources, generate-test-resources, process-test-resources, test-compile, process-test-classes, test, prepare-package, package, pre-integration-test, integration-test, post-integration-test, verify, install, deploy]
[DEBUG] Lifecycle clean -> [pre-clean, clean, post-clean]
[DEBUG] Lifecycle site -> [pre-site, site, post-site, site-deploy]
[DEBUG] Lifecycle default -> [validate, initialize, generate-sources, process-sources, generate-resources, process-resources, compile, process-classes, generate-test-sources, process-test-sources, generate-test-resources, process-test-resources, test-compile, process-test-classes, test, prepare-package, package, pre-integration-test, integration-test, post-integration-test, verify, install, deploy]
[DEBUG] Lifecycle clean -> [pre-clean, clean, post-clean]
[DEBUG] Lifecycle site -> [pre-site, site, post-site, site-deploy]
[DEBUG] Lifecycle default -> [validate, initialize, generate-sources, process-sources, generate-resources, process-resources, compile, process-classes, generate-test-sources, process-test-sources, generate-test-resources, process-test-resources, test-compile, process-test-classes, test, prepare-package, package, pre-integration-test, integration-test, post-integration-test, verify, install, deploy]
[DEBUG] Lifecycle clean -> [pre-clean, clean, post-clean]
[DEBUG] Lifecycle site -> [pre-site, site, post-site, site-deploy]
[DEBUG] Lifecycle default -> [validate, initialize, generate-sources, process-sources, generate-resources, process-resources, compile, process-classes, generate-test-sources, process-test-sources, generate-test-resources, process-test-resources, test-compile, process-test-classes, test, prepare-package, package, pre-integration-test, integration-test, post-integration-test, verify, install, deploy]
[DEBUG] Lifecycle clean -> [pre-clean, clean, post-clean]
[DEBUG] Lifecycle site -> [pre-site, site, post-site, site-deploy]
[DEBUG] Lifecycle default -> [validate, initialize, generate-sources, process-sources, generate-resources, process-resources, compile, process-classes, generate-test-sources, process-test-sources, generate-test-resources, process-test-resources, test-compile, process-test-classes, test, prepare-package, package, pre-integration-test, integration-test, post-integration-test, verify, install, deploy]
[DEBUG] Lifecycle clean -> [pre-clean, clean, post-clean]
[DEBUG] Lifecycle site -> [pre-site, site, post-site, site-deploy]
[DEBUG] Lifecycle default -> [validate, initialize, generate-sources, process-sources, generate-resources, process-resources, compile, process-classes, generate-test-sources, process-test-sources, generate-test-resources, process-test-resources, test-compile, process-test-classes, test, prepare-package, package, pre-integration-test, integration-test, post-integration-test, verify, install, deploy]
[DEBUG] Lifecycle clean -> [pre-clean, clean, post-clean]
[DEBUG] Lifecycle site -> [pre-site, site, post-site, site-deploy]
[DEBUG] Lifecycle default -> [validate, initialize, generate-sources, process-sources, generate-resources, process-resources, compile, process-classes, generate-test-sources, process-test-sources, generate-test-resources, process-test-resources, test-compile, process-test-classes, test, prepare-package, package, pre-integration-test, integration-test, post-integration-test, verify, install, deploy]
[DEBUG] Lifecycle clean -> [pre-clean, clean, post-clean]
[DEBUG] Lifecycle site -> [pre-site, site, post-site, site-deploy]
[DEBUG] === PROJECT BUILD PLAN ================================================
[DEBUG] Project:       org.apache.pinot:pinot-pulsar:0.11.0-SNAPSHOT
[DEBUG] Dependencies (collect): [test]
[DEBUG] Dependencies (resolve): [compile, runtime, test]
[DEBUG] Repositories (dependencies): [apache.snapshots (https://repository.apache.org/snapshots, default, snapshots), central (https://repo.maven.apache.org/maven2, default, releases)]
[DEBUG] Repositories (plugins)     : [central (https://repo.maven.apache.org/maven2, default, releases)]
[DEBUG] -----------------------------------------------------------------------
[DEBUG] Goal:          org.apache.maven.plugins:maven-clean-plugin:3.1.0:clean (default-clean)
[DEBUG] Style:         Regular
[DEBUG] Configuration: <?xml version="1.0" encoding="UTF-8"?>
<configuration>
  <directory default-value="${project.build.directory}"/>
  <excludeDefaultDirectories default-value="false">${maven.clean.excludeDefaultDirectories}</excludeDefaultDirectories>
  <failOnError default-value="true">${maven.clean.failOnError}</failOnError>
  <followSymLinks default-value="false">${maven.clean.followSymLinks}</followSymLinks>
  <outputDirectory default-value="${project.build.outputDirectory}"/>
  <reportDirectory default-value="${project.build.outputDirectory}"/>
  <retryOnError default-value="true">${maven.clean.retryOnError}</retryOnError>
  <skip default-value="false">${maven.clean.skip}</skip>
  <testOutputDirectory default-value="${project.build.testOutputDirectory}"/>
  <verbose>${maven.clean.verbose}</verbose>
</configuration>
[DEBUG] -----------------------------------------------------------------------
[DEBUG] Goal:          org.apache.maven.plugins:maven-checkstyle-plugin:3.1.2:check (checkstyle)
[DEBUG] Style:         Regular
[DEBUG] Configuration: <?xml version="1.0" encoding="UTF-8"?>
<configuration>
  <cacheFile default-value="${project.build.directory}/checkstyle-cachefile"/>
  <checkstyleRulesHeader default-value="&lt;?xml version=&quot;1.0&quot;?&gt;&#10;&lt;!DOCTYPE module PUBLIC &quot;-//Checkstyle//DTD Checkstyle Configuration 1.3//EN&quot;&#10;        &quot;https://checkstyle.org/dtds/configuration_1_3.dtd&quot;&gt;&#10;"/>
  <configLocation default-value="sun_checks.xml">/Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/../../../config/checkstyle.xml</configLocation>
  <consoleOutput default-value="false">${checkstyle.consoleOutput}</consoleOutput>
  <encoding default-value="${project.build.sourceEncoding}">${encoding}</encoding>
  <excludes>${checkstyle.excludes}</excludes>
  <failOnViolation default-value="true">true</failOnViolation>
  <failsOnError default-value="false"/>
  <headerLocation default-value="LICENSE.txt">${checkstyle.header.file}</headerLocation>
  <includeResources default-value="true">${checkstyle.includeResources}</includeResources>
  <includeTestResources default-value="true">${checkstyle.includeTestResources}</includeTestResources>
  <includeTestSourceDirectory default-value="false">true</includeTestSourceDirectory>
  <includes default-value="**\/*.java">${checkstyle.includes}</includes>
  <logViolationCountToConsole default-value="true">${checkstyle.logViolationCount}</logViolationCountToConsole>
  <logViolationsToConsole default-value="true">true</logViolationsToConsole>
  <maxAllowedViolations default-value="0">${checkstyle.maxAllowedViolations}</maxAllowedViolations>
  <omitIgnoredModules default-value="false"/>
  <outputFile default-value="${project.build.directory}/checkstyle-result.xml">${checkstyle.output.file}</outputFile>
  <outputFileFormat default-value="xml">${checkstyle.output.format}</outputFileFormat>
  <plugin default-value="${plugin}"/>
  <project default-value="${project}"/>
  <propertiesLocation>${checkstyle.properties.location}</propertiesLocation>
  <propertyExpansion>config_loc=/Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/../../../config</propertyExpansion>
  <resourceExcludes>${checkstyle.resourceExcludes}</resourceExcludes>
  <resourceIncludes default-value="**/*.properties">${checkstyle.resourceIncludes}</resourceIncludes>
  <resources default-value="${project.resources}"/>
  <rulesFiles default-value="${project.build.directory}/checkstyle-rules.xml">${checkstyle.output.rules.file}</rulesFiles>
  <skip default-value="false">${checkstyle.skip}</skip>
  <skipExec default-value="false">${checkstyle.skipExec}</skipExec>
  <suppressionsFileExpression default-value="checkstyle.suppressions.file">${checkstyle.suppression.expression}</suppressionsFileExpression>
  <suppressionsLocation>/Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/../../../config/suppressions.xml</suppressionsLocation>
  <testResources default-value="${project.testResources}"/>
  <violationIgnore>${checkstyle.violation.ignore}</violationIgnore>
  <violationSeverity default-value="error">warning</violationSeverity>
</configuration>
[DEBUG] -----------------------------------------------------------------------
[DEBUG] Goal:          org.codehaus.mojo:buildnumber-maven-plugin:1.3:create (default)
[DEBUG] Style:         Regular
[DEBUG] Configuration: <?xml version="1.0" encoding="UTF-8"?>
<configuration>
  <buildNumberPropertiesFileLocation default-value="${basedir}/buildNumber.properties"/>
  <buildNumberPropertyName default-value="buildNumber">${maven.buildNumber.buildNumberPropertyName}</buildNumberPropertyName>
  <doCheck default-value="false">${maven.buildNumber.doCheck}</doCheck>
  <doUpdate default-value="false">${maven.buildNumber.doUpdate}</doUpdate>
  <format>${maven.buildNumber.format}</format>
  <getRevisionOnlyOnce default-value="false">${maven.buildNumber.getRevisionOnlyOnce}</getRevisionOnlyOnce>
  <locale>${maven.buildNumber.locale}</locale>
  <password>${password}</password>
  <project default-value="${project}"/>
  <reactorProjects default-value="${reactorProjects}"/>
  <readUrlScm default-value="${project.scm.connection}"/>
  <revisionOnScmFailure>${maven.buildNumber.revisionOnScmFailure}</revisionOnScmFailure>
  <scmBranchPropertyName default-value="scmBranch">${maven.buildNumber.scmBranchPropertyName}</scmBranchPropertyName>
  <scmDirectory default-value="${basedir}">${maven.buildNumber.scmDirectory}</scmDirectory>
  <session default-value="${session}"/>
  <skip default-value="false">${maven.buildNumber.skip}</skip>
  <timestampFormat>${maven.buildNumber.timestampFormat}</timestampFormat>
  <timestampPropertyName default-value="timestamp">${maven.buildNumber.timestampPropertyName}</timestampPropertyName>
  <urlScm default-value="${project.scm.developerConnection}"/>
  <useLastCommittedRevision default-value="false">${maven.buildNumber.useLastCommittedRevision}</useLastCommittedRevision>
  <username>${username}</username>
</configuration>
[DEBUG] -----------------------------------------------------------------------
[DEBUG] Goal:          org.apache.maven.plugins:maven-enforcer-plugin:3.0.0-M2:enforce (enforce-dependency-convergence)
[DEBUG] Style:         Regular
[DEBUG] Configuration: <?xml version="1.0" encoding="UTF-8"?>
<configuration>
  <fail default-value="true">${enforcer.fail}</fail>
  <failFast default-value="false">${enforcer.failFast}</failFast>
  <ignoreCache default-value="false">${enforcer.ignoreCache}</ignoreCache>
  <mojoExecution default-value="${mojoExecution}"/>
  <project default-value="${project}"/>
  <rules>
    <dependencyConvergence/>
  </rules>
  <session default-value="${session}"/>
  <skip default-value="false">${enforcer.skip}</skip>
</configuration>
[DEBUG] -----------------------------------------------------------------------
[DEBUG] Goal:          org.apache.maven.plugins:maven-enforcer-plugin:3.0.0-M2:enforce (enforce-maven-version)
[DEBUG] Style:         Regular
[DEBUG] Configuration: <?xml version="1.0" encoding="UTF-8"?>
<configuration>
  <fail default-value="true">${enforcer.fail}</fail>
  <failFast default-value="false">${enforcer.failFast}</failFast>
  <ignoreCache default-value="false">${enforcer.ignoreCache}</ignoreCache>
  <mojoExecution default-value="${mojoExecution}"/>
  <project default-value="${project}"/>
  <rules>
    <requireMavenVersion>
      <version>3.0.5</version>
    </requireMavenVersion>
    <dependencyConvergence/>
  </rules>
  <session default-value="${session}"/>
  <skip default-value="false">${enforcer.skip}</skip>
</configuration>
[DEBUG] -----------------------------------------------------------------------
[DEBUG] Goal:          org.jacoco:jacoco-maven-plugin:0.8.6:prepare-agent (default)
[DEBUG] Style:         Regular
[DEBUG] Configuration: <?xml version="1.0" encoding="UTF-8"?>
<configuration>
  <address>${jacoco.address}</address>
  <append>${jacoco.append}</append>
  <classDumpDir>${jacoco.classDumpDir}</classDumpDir>
  <destFile default-value="${project.build.directory}/jacoco.exec">${jacoco.destFile}</destFile>
  <dumpOnExit>${jacoco.dumpOnExit}</dumpOnExit>
  <exclClassLoaders>${jacoco.exclClassLoaders}</exclClassLoaders>
  <inclBootstrapClasses>${jacoco.inclBootstrapClasses}</inclBootstrapClasses>
  <inclNoLocationClasses>${jacoco.inclNoLocationClasses}</inclNoLocationClasses>
  <includes>
    <include>org/apache/pinot/**/*</include>
  </includes>
  <jmx>${jacoco.jmx}</jmx>
  <output>${jacoco.output}</output>
  <pluginArtifactMap>${plugin.artifactMap}</pluginArtifactMap>
  <port>${jacoco.port}</port>
  <project>${project}</project>
  <propertyName>${jacoco.propertyName}</propertyName>
  <sessionId>${jacoco.sessionId}</sessionId>
  <skip default-value="false">${jacoco.skip}</skip>
</configuration>
[DEBUG] -----------------------------------------------------------------------
[DEBUG] Goal:          org.apache.maven.plugins:maven-remote-resources-plugin:1.6.0:process (process-resource-bundles)
[DEBUG] Style:         Regular
[DEBUG] Configuration: <?xml version="1.0" encoding="UTF-8"?>
<configuration>
  <appendedResourcesDirectory default-value="${basedir}/src/main/appended-resources"/>
  <attachToMain default-value="true">${attachToMain}</attachToMain>
  <attachToTest default-value="true">${attachToTest}</attachToTest>
  <basedir default-value="${basedir}"/>
  <encoding default-value="${project.build.sourceEncoding}">${encoding}</encoding>
  <excludeArtifactIds default-value="">${excludeArtifactIds}</excludeArtifactIds>
  <excludeGroupIds default-value="">${excludeGroupIds}</excludeGroupIds>
  <excludeScope default-value="">${excludeScope}</excludeScope>
  <excludeTransitive default-value="false">${excludeTransitive}</excludeTransitive>
  <includeArtifactIds default-value="">${includeArtifactIds}</includeArtifactIds>
  <includeGroupIds default-value="">${includeGroupIds}</includeGroupIds>
  <includeProjectProperties default-value="false"/>
  <includeScope default-value="runtime">${includeScope}</includeScope>
  <localRepository default-value="${localRepository}"/>
  <mavenSession default-value="${session}"/>
  <outputDirectory default-value="${project.build.directory}/maven-shared-archive-resources"/>
  <project default-value="${project}"/>
  <remoteArtifactRepositories default-value="${project.remoteArtifactRepositories}"/>
  <resourceBundles>
    <resourceBundle>org.apache:apache-jar-resource-bundle:1.4</resourceBundle>
  </resourceBundles>
  <resources default-value="${project.resources}"/>
  <runOnlyAtExecutionRoot default-value="false"/>
  <skip default-value="false">${remoteresources.skip}</skip>
  <useDefaultFilterDelimiters default-value="true"/>
  <velocityFilterInMemoryThreshold default-value="5242880"/>
</configuration>
[DEBUG] -----------------------------------------------------------------------
[DEBUG] Goal:          org.apache.maven.plugins:maven-remote-resources-plugin:1.6.0:process (default)
[DEBUG] Style:         Regular
[DEBUG] Configuration: <?xml version="1.0" encoding="UTF-8"?>
<configuration>
  <appendedResourcesDirectory default-value="${basedir}/src/main/appended-resources"/>
  <attachToMain default-value="true">${attachToMain}</attachToMain>
  <attachToTest default-value="true">${attachToTest}</attachToTest>
  <basedir default-value="${basedir}"/>
  <encoding default-value="${project.build.sourceEncoding}">${encoding}</encoding>
  <excludeArtifactIds default-value="">${excludeArtifactIds}</excludeArtifactIds>
  <excludeGroupIds default-value="">${excludeGroupIds}</excludeGroupIds>
  <excludeScope default-value="">${excludeScope}</excludeScope>
  <excludeTransitive default-value="false">${excludeTransitive}</excludeTransitive>
  <includeArtifactIds default-value="">${includeArtifactIds}</includeArtifactIds>
  <includeGroupIds default-value="">${includeGroupIds}</includeGroupIds>
  <includeProjectProperties default-value="false"/>
  <includeScope default-value="runtime">${includeScope}</includeScope>
  <localRepository default-value="${localRepository}"/>
  <mavenSession default-value="${session}"/>
  <outputDirectory default-value="${project.build.directory}/maven-shared-archive-resources"/>
  <project default-value="${project}"/>
  <properties>
    <projectName>Apache Pinot</projectName>
  </properties>
  <remoteArtifactRepositories default-value="${project.remoteArtifactRepositories}"/>
  <resourceBundles>
    <resourceBundle>org.apache:apache-jar-resource-bundle:1.4</resourceBundle>
  </resourceBundles>
  <resources default-value="${project.resources}"/>
  <runOnlyAtExecutionRoot default-value="false"/>
  <skip default-value="false">${remoteresources.skip}</skip>
  <useDefaultFilterDelimiters default-value="true"/>
  <velocityFilterInMemoryThreshold default-value="5242880"/>
</configuration>
[DEBUG] -----------------------------------------------------------------------
[DEBUG] Goal:          org.apache.maven.plugins:maven-resources-plugin:2.6:resources (default-resources)
[DEBUG] Style:         Regular
[DEBUG] Configuration: <?xml version="1.0" encoding="UTF-8"?>
<configuration>
  <buildFilters default-value="${project.build.filters}"/>
  <encoding default-value="${project.build.sourceEncoding}">${encoding}</encoding>
  <escapeString>${maven.resources.escapeString}</escapeString>
  <escapeWindowsPaths default-value="true">${maven.resources.escapeWindowsPaths}</escapeWindowsPaths>
  <includeEmptyDirs default-value="false">${maven.resources.includeEmptyDirs}</includeEmptyDirs>
  <outputDirectory default-value="${project.build.outputDirectory}"/>
  <overwrite default-value="false">${maven.resources.overwrite}</overwrite>
  <project default-value="${project}"/>
  <resources default-value="${project.resources}"/>
  <session default-value="${session}"/>
  <supportMultiLineFiltering default-value="false">${maven.resources.supportMultiLineFiltering}</supportMultiLineFiltering>
  <useBuildFilters default-value="true"/>
  <useDefaultDelimiters default-value="true"/>
</configuration>
[DEBUG] -----------------------------------------------------------------------
[DEBUG] Goal:          org.apache.maven.plugins:maven-compiler-plugin:3.8.0:compile (default-compile)
[DEBUG] Style:         Regular
[DEBUG] Configuration: <?xml version="1.0" encoding="UTF-8"?>
<configuration>
  <basedir default-value="${basedir}"/>
  <buildDirectory default-value="${project.build.directory}"/>
  <compilePath default-value="${project.compileClasspathElements}"/>
  <compileSourceRoots default-value="${project.compileSourceRoots}"/>
  <compilerId default-value="javac">${maven.compiler.compilerId}</compilerId>
  <compilerReuseStrategy default-value="${reuseCreated}">${maven.compiler.compilerReuseStrategy}</compilerReuseStrategy>
  <compilerVersion>${maven.compiler.compilerVersion}</compilerVersion>
  <debug default-value="true">${maven.compiler.debug}</debug>
  <debuglevel>${maven.compiler.debuglevel}</debuglevel>
  <encoding default-value="${project.build.sourceEncoding}">UTF-8</encoding>
  <executable>${maven.compiler.executable}</executable>
  <failOnError default-value="true">${maven.compiler.failOnError}</failOnError>
  <failOnWarning default-value="false">${maven.compiler.failOnWarning}</failOnWarning>
  <forceJavacCompilerUse default-value="false">${maven.compiler.forceJavacCompilerUse}</forceJavacCompilerUse>
  <fork default-value="false">true</fork>
  <generatedSourcesDirectory default-value="${project.build.directory}/generated-sources/annotations"/>
  <maxmem>${maven.compiler.maxmem}</maxmem>
  <meminitial>${maven.compiler.meminitial}</meminitial>
  <mojoExecution default-value="${mojoExecution}"/>
  <optimize default-value="false">${maven.compiler.optimize}</optimize>
  <outputDirectory default-value="${project.build.outputDirectory}"/>
  <parameters default-value="false">${maven.compiler.parameters}</parameters>
  <project default-value="${project}"/>
  <projectArtifact default-value="${project.artifact}"/>
  <release>11</release>
  <session default-value="${session}"/>
  <showDeprecation default-value="false">${maven.compiler.showDeprecation}</showDeprecation>
  <showWarnings default-value="false">${maven.compiler.showWarnings}</showWarnings>
  <skipMain>${maven.main.skip}</skipMain>
  <skipMultiThreadWarning default-value="false">${maven.compiler.skipMultiThreadWarning}</skipMultiThreadWarning>
  <source default-value="1.6">11</source>
  <staleMillis default-value="0">${lastModGranularityMs}</staleMillis>
  <target default-value="1.6">11</target>
  <useIncrementalCompilation default-value="true">${maven.compiler.useIncrementalCompilation}</useIncrementalCompilation>
  <verbose default-value="false">${maven.compiler.verbose}</verbose>
</configuration>
[DEBUG] -----------------------------------------------------------------------
[DEBUG] Goal:          org.apache.maven.plugins:maven-resources-plugin:2.6:testResources (default-testResources)
[DEBUG] Style:         Regular
[DEBUG] Configuration: <?xml version="1.0" encoding="UTF-8"?>
<configuration>
  <buildFilters default-value="${project.build.filters}"/>
  <encoding default-value="${project.build.sourceEncoding}">${encoding}</encoding>
  <escapeString>${maven.resources.escapeString}</escapeString>
  <escapeWindowsPaths default-value="true">${maven.resources.escapeWindowsPaths}</escapeWindowsPaths>
  <includeEmptyDirs default-value="false">${maven.resources.includeEmptyDirs}</includeEmptyDirs>
  <outputDirectory default-value="${project.build.testOutputDirectory}"/>
  <overwrite default-value="false">${maven.resources.overwrite}</overwrite>
  <project default-value="${project}"/>
  <resources default-value="${project.testResources}"/>
  <session default-value="${session}"/>
  <skip>${maven.test.skip}</skip>
  <supportMultiLineFiltering default-value="false">${maven.resources.supportMultiLineFiltering}</supportMultiLineFiltering>
  <useBuildFilters default-value="true"/>
  <useDefaultDelimiters default-value="true"/>
</configuration>
[DEBUG] -----------------------------------------------------------------------
[DEBUG] Goal:          org.apache.maven.plugins:maven-compiler-plugin:3.8.0:testCompile (default-testCompile)
[DEBUG] Style:         Regular
[DEBUG] Configuration: <?xml version="1.0" encoding="UTF-8"?>
<configuration>
  <basedir default-value="${basedir}"/>
  <buildDirectory default-value="${project.build.directory}"/>
  <compilePath default-value="${project.compileClasspathElements}"/>
  <compileSourceRoots default-value="${project.testCompileSourceRoots}"/>
  <compilerId default-value="javac">${maven.compiler.compilerId}</compilerId>
  <compilerReuseStrategy default-value="${reuseCreated}">${maven.compiler.compilerReuseStrategy}</compilerReuseStrategy>
  <compilerVersion>${maven.compiler.compilerVersion}</compilerVersion>
  <debug default-value="true">${maven.compiler.debug}</debug>
  <debuglevel>${maven.compiler.debuglevel}</debuglevel>
  <encoding default-value="${project.build.sourceEncoding}">UTF-8</encoding>
  <executable>${maven.compiler.executable}</executable>
  <failOnError default-value="true">${maven.compiler.failOnError}</failOnError>
  <failOnWarning default-value="false">${maven.compiler.failOnWarning}</failOnWarning>
  <forceJavacCompilerUse default-value="false">${maven.compiler.forceJavacCompilerUse}</forceJavacCompilerUse>
  <fork default-value="false">true</fork>
  <generatedTestSourcesDirectory default-value="${project.build.directory}/generated-test-sources/test-annotations"/>
  <maxmem>${maven.compiler.maxmem}</maxmem>
  <meminitial>${maven.compiler.meminitial}</meminitial>
  <mojoExecution default-value="${mojoExecution}"/>
  <optimize default-value="false">${maven.compiler.optimize}</optimize>
  <outputDirectory default-value="${project.build.testOutputDirectory}"/>
  <parameters default-value="false">${maven.compiler.parameters}</parameters>
  <project default-value="${project}"/>
  <release>11</release>
  <session default-value="${session}"/>
  <showDeprecation default-value="false">${maven.compiler.showDeprecation}</showDeprecation>
  <showWarnings default-value="false">${maven.compiler.showWarnings}</showWarnings>
  <skip>${maven.test.skip}</skip>
  <skipMultiThreadWarning default-value="false">${maven.compiler.skipMultiThreadWarning}</skipMultiThreadWarning>
  <source default-value="1.6">11</source>
  <staleMillis default-value="0">${lastModGranularityMs}</staleMillis>
  <target default-value="1.6">11</target>
  <testPath default-value="${project.testClasspathElements}"/>
  <testRelease>${maven.compiler.testRelease}</testRelease>
  <testSource>${maven.compiler.testSource}</testSource>
  <testTarget>${maven.compiler.testTarget}</testTarget>
  <useIncrementalCompilation default-value="true">${maven.compiler.useIncrementalCompilation}</useIncrementalCompilation>
  <verbose default-value="false">${maven.compiler.verbose}</verbose>
</configuration>
[DEBUG] -----------------------------------------------------------------------
[DEBUG] Goal:          org.apache.maven.plugins:maven-surefire-plugin:3.0.0-M5:test (default-test)
[DEBUG] Style:         Regular
[DEBUG] Configuration: <?xml version="1.0" encoding="UTF-8"?>
<configuration>
  <additionalClasspathElements>${maven.test.additionalClasspath}</additionalClasspathElements>
  <argLine>${argLine}</argLine>
  <basedir default-value="${basedir}"/>
  <childDelegation default-value="false">${childDelegation}</childDelegation>
  <classesDirectory default-value="${project.build.outputDirectory}"/>
  <classpathDependencyExcludes>${maven.test.dependency.excludes}</classpathDependencyExcludes>
  <debugForkedProcess>${maven.surefire.debug}</debugForkedProcess>
  <dependenciesToScan>${dependenciesToScan}</dependenciesToScan>
  <disableXmlReport default-value="false">${disableXmlReport}</disableXmlReport>
  <enableAssertions default-value="true">${enableAssertions}</enableAssertions>
  <enableProcessChecker>${surefire.enableProcessChecker}</enableProcessChecker>
  <encoding default-value="${project.reporting.outputEncoding}">${surefire.encoding}</encoding>
  <excludedEnvironmentVariables>${surefire.excludedEnvironmentVariables}</excludedEnvironmentVariables>
  <excludedGroups>${excludedGroups}</excludedGroups>
  <excludes>
    <exclude>**/*IT.java</exclude>
  </excludes>
  <excludesFile>${surefire.excludesFile}</excludesFile>
  <failIfNoSpecifiedTests>${surefire.failIfNoSpecifiedTests}</failIfNoSpecifiedTests>
  <failIfNoTests>${failIfNoTests}</failIfNoTests>
  <forkCount default-value="1">1</forkCount>
  <forkMode default-value="once">${forkMode}</forkMode>
  <forkNode>${surefire.forkNode}</forkNode>
  <forkedProcessExitTimeoutInSeconds default-value="30">${surefire.exitTimeout}</forkedProcessExitTimeoutInSeconds>
  <forkedProcessTimeoutInSeconds>3600</forkedProcessTimeoutInSeconds>
  <groups>${groups}</groups>
  <includesFile>${surefire.includesFile}</includesFile>
  <junitArtifactName default-value="junit:junit">${junitArtifactName}</junitArtifactName>
  <jvm>${jvm}</jvm>
  <localRepository default-value="${localRepository}"/>
  <objectFactory>${objectFactory}</objectFactory>
  <parallel>${parallel}</parallel>
  <parallelMavenExecution default-value="${session.parallel}"/>
  <parallelOptimized default-value="true">${parallelOptimized}</parallelOptimized>
  <parallelTestsTimeoutForcedInSeconds>${surefire.parallel.forcedTimeout}</parallelTestsTimeoutForcedInSeconds>
  <parallelTestsTimeoutInSeconds>${surefire.parallel.timeout}</parallelTestsTimeoutInSeconds>
  <perCoreThreadCount default-value="true">${perCoreThreadCount}</perCoreThreadCount>
  <pluginArtifactMap>${plugin.artifactMap}</pluginArtifactMap>
  <pluginDescriptor default-value="${plugin}"/>
  <printSummary default-value="true">${surefire.printSummary}</printSummary>
  <project default-value="${project}"/>
  <projectArtifactMap>${project.artifactMap}</projectArtifactMap>
  <projectBuildDirectory default-value="${project.build.directory}"/>
  <projectRemoteRepositories default-value="${project.remoteArtifactRepositories}"/>
  <redirectTestOutputToFile default-value="false">${maven.test.redirectTestOutputToFile}</redirectTestOutputToFile>
  <remoteRepositories default-value="${project.pluginArtifactRepositories}"/>
  <reportFormat default-value="brief">plain</reportFormat>
  <reportNameSuffix default-value="">${surefire.reportNameSuffix}</reportNameSuffix>
  <reportsDirectory default-value="${project.build.directory}/surefire-reports"/>
  <rerunFailingTestsCount default-value="0">${surefire.rerunFailingTestsCount}</rerunFailingTestsCount>
  <reuseForks default-value="true">false</reuseForks>
  <runOrder default-value="filesystem">${surefire.runOrder}</runOrder>
  <session default-value="${session}"/>
  <shutdown default-value="exit">${surefire.shutdown}</shutdown>
  <skip default-value="false">${maven.test.skip}</skip>
  <skipAfterFailureCount default-value="0">${surefire.skipAfterFailureCount}</skipAfterFailureCount>
  <skipExec>${maven.test.skip.exec}</skipExec>
  <skipTests default-value="false">${skipTests}</skipTests>
  <suiteXmlFiles>${surefire.suiteXmlFiles}</suiteXmlFiles>
  <systemPropertiesFile>${surefire.systemPropertiesFile}</systemPropertiesFile>
  <systemPropertyVariables>
    <zookeeper.forceSync>no</zookeeper.forceSync>
  </systemPropertyVariables>
  <tempDir default-value="surefire">${tempDir}</tempDir>
  <test>${test}</test>
  <testClassesDirectory default-value="${project.build.testOutputDirectory}"/>
  <testFailureIgnore default-value="false">false</testFailureIgnore>
  <testNGArtifactName default-value="org.testng:testng">${testNGArtifactName}</testNGArtifactName>
  <testSourceDirectory default-value="${project.build.testSourceDirectory}"/>
  <threadCount>${threadCount}</threadCount>
  <threadCountClasses default-value="0">${threadCountClasses}</threadCountClasses>
  <threadCountMethods default-value="0">${threadCountMethods}</threadCountMethods>
  <threadCountSuites default-value="0">${threadCountSuites}</threadCountSuites>
  <trimStackTrace default-value="true">false</trimStackTrace>
  <useFile default-value="true">${surefire.useFile}</useFile>
  <useManifestOnlyJar default-value="true">${surefire.useManifestOnlyJar}</useManifestOnlyJar>
  <useModulePath default-value="true">${surefire.useModulePath}</useModulePath>
  <useSystemClassLoader default-value="true">${surefire.useSystemClassLoader}</useSystemClassLoader>
  <useUnlimitedThreads default-value="false">${useUnlimitedThreads}</useUnlimitedThreads>
  <workingDirectory>${basedir}</workingDirectory>
</configuration>
[DEBUG] -----------------------------------------------------------------------
[DEBUG] Goal:          org.jacoco:jacoco-maven-plugin:0.8.6:report-aggregate (report)
[DEBUG] Style:         Regular
[DEBUG] Configuration: <?xml version="1.0" encoding="UTF-8"?>
<configuration>
  <includes>
    <include>org/apache/pinot/**/*</include>
  </includes>
  <outputDirectory default-value="${project.reporting.outputDirectory}/jacoco-aggregate"/>
  <outputEncoding default-value="UTF-8">${project.reporting.outputEncoding}</outputEncoding>
  <project>${project}</project>
  <reactorProjects>${reactorProjects}</reactorProjects>
  <skip default-value="false">${jacoco.skip}</skip>
  <sourceEncoding default-value="UTF-8">${project.build.sourceEncoding}</sourceEncoding>
  <title default-value="${project.name}"/>
</configuration>
[DEBUG] -----------------------------------------------------------------------
[DEBUG] Goal:          org.apache.maven.plugins:maven-jar-plugin:3.2.0:jar (default-jar)
[DEBUG] Style:         Regular
[DEBUG] Configuration: <?xml version="1.0" encoding="UTF-8"?>
<configuration>
  <archive>
    <manifestEntries>
      <Build-Time>2022-06-28T03:29:52Z</Build-Time>
      <Implementation-Branch>${scmBranch}</Implementation-Branch>
      <Implementation-Title>pinot-pulsar</Implementation-Title>
      <Implementation-Version>0.11.0-SNAPSHOT-${buildNumber}</Implementation-Version>
      <Implementation-Vendor-Id>org.apache.pinot</Implementation-Vendor-Id>
      <Implementation-Vendor>Apache Software Foundation</Implementation-Vendor>
    </manifestEntries>
    <manifest>
      <addDefaultSpecificationEntries>true</addDefaultSpecificationEntries>
      <addDefaultImplementationEntries>true</addDefaultImplementationEntries>
    </manifest>
  </archive>
  <classesDirectory default-value="${project.build.outputDirectory}"/>
  <finalName default-value="${project.build.finalName}"/>
  <forceCreation default-value="false">${maven.jar.forceCreation}</forceCreation>
  <outputDirectory default-value="${project.build.directory}"/>
  <outputTimestamp default-value="${project.build.outputTimestamp}"/>
  <project default-value="${project}"/>
  <session default-value="${session}"/>
  <skipIfEmpty default-value="false"/>
  <useDefaultManifestFile default-value="false">${jar.useDefaultManifestFile}</useDefaultManifestFile>
</configuration>
[DEBUG] -----------------------------------------------------------------------
[DEBUG] Goal:          org.apache.maven.plugins:maven-shade-plugin:3.2.1:shade (default)
[DEBUG] Style:         Regular
[DEBUG] Configuration: <?xml version="1.0" encoding="UTF-8"?>
<configuration>
  <createDependencyReducedPom default-value="true"/>
  <dependencyReducedPomLocation default-value="${basedir}/dependency-reduced-pom.xml"/>
  <filters>
    <filter>
      <artifact>*:*</artifact>
      <excludes>
        <exclude>META-INF/*.SF</exclude>
        <exclude>META-INF/*.DSA</exclude>
        <exclude>META-INF/*.RSA</exclude>
      </excludes>
    </filter>
  </filters>
  <generateUniqueDependencyReducedPom default-value="false"/>
  <localRepository default-value="${localRepository}"/>
  <outputDirectory default-value="${project.build.directory}"/>
  <project default-value="${project}"/>
  <relocations>
    <relocation>
      <pattern>com.google.common</pattern>
      <shadedPattern>shaded.com.google.common</shadedPattern>
    </relocation>
    <relocation>
      <pattern>com.fasterxml.jackson</pattern>
      <shadedPattern>shaded.com.fasterxml.jackson</shadedPattern>
    </relocation>
    <relocation>
      <pattern>org.apache.http</pattern>
      <shadedPattern>shaded.org.apache.http</shadedPattern>
    </relocation>
    <relocation>
      <pattern>software.amazon</pattern>
      <shadedPattern>shaded.software.amazon</shadedPattern>
    </relocation>
    <relocation>
      <pattern>org.reflections</pattern>
      <shadedPattern>shaded.org.reflections</shadedPattern>
    </relocation>
    <relocation>
      <pattern>io.netty</pattern>
      <shadedPattern>shaded.io.netty</shadedPattern>
    </relocation>
    <relocation>
      <pattern>org.apache.parquet</pattern>
      <shadedPattern>shaded.org.apache.parquet</shadedPattern>
    </relocation>
    <relocation>
      <pattern>org.apache.kafka</pattern>
      <shadedPattern>shaded.org.apache.kafka</shadedPattern>
    </relocation>
  </relocations>
  <remoteArtifactRepositories default-value="${project.remoteArtifactRepositories}"/>
  <session default-value="${session}"/>
  <shadeSourcesContent default-value="false">${shadeSourcesContent}</shadeSourcesContent>
  <shadeTestJar default-value="false"/>
  <shadedArtifactAttached>true</shadedArtifactAttached>
  <shadedArtifactId default-value="${project.artifactId}"/>
  <shadedClassifierName default-value="shaded"/>
  <transformers>
    <transformer implementation="org.apache.maven.plugins.shade.resource.ApacheLicenseResourceTransformer"/>
  </transformers>
  <useBaseVersion default-value="false"/>
</configuration>
[DEBUG] -----------------------------------------------------------------------
[DEBUG] Goal:          org.apache.maven.plugins:maven-site-plugin:3.7.1:attach-descriptor (attach-descriptor)
[DEBUG] Style:         Regular
[DEBUG] Configuration: <?xml version="1.0" encoding="UTF-8"?>
<configuration>
  <basedir>${basedir}</basedir>
  <localRepository default-value="${localRepository}"/>
  <locales default-value="en">${locales}</locales>
  <pomPackagingOnly default-value="true"/>
  <project default-value="${project}"/>
  <reactorProjects default-value="${reactorProjects}"/>
  <relativizeDecorationLinks default-value="true">${relativizeDecorationLinks}</relativizeDecorationLinks>
  <repositories default-value="${project.remoteArtifactRepositories}"/>
  <siteDirectory default-value="${basedir}/src/site"/>
  <skip default-value="false">${maven.site.skip}</skip>
</configuration>
[DEBUG] -----------------------------------------------------------------------
[DEBUG] Goal:          org.apache.maven.plugins:maven-jar-plugin:3.2.0:test-jar (default)
[DEBUG] Style:         Regular
[DEBUG] Configuration: <?xml version="1.0" encoding="UTF-8"?>
<configuration>
  <archive>
    <manifestEntries>
      <Build-Time>2022-06-28T03:29:52Z</Build-Time>
      <Implementation-Branch>${scmBranch}</Implementation-Branch>
      <Implementation-Title>pinot-pulsar</Implementation-Title>
      <Implementation-Version>0.11.0-SNAPSHOT-${buildNumber}</Implementation-Version>
      <Implementation-Vendor-Id>org.apache.pinot</Implementation-Vendor-Id>
      <Implementation-Vendor>Apache Software Foundation</Implementation-Vendor>
    </manifestEntries>
    <manifest>
      <addDefaultSpecificationEntries>true</addDefaultSpecificationEntries>
      <addDefaultImplementationEntries>true</addDefaultImplementationEntries>
    </manifest>
  </archive>
  <classifier default-value="tests"/>
  <finalName default-value="${project.build.finalName}"/>
  <forceCreation default-value="false">${maven.jar.forceCreation}</forceCreation>
  <outputDirectory default-value="${project.build.directory}"/>
  <outputTimestamp default-value="${project.build.outputTimestamp}"/>
  <project default-value="${project}"/>
  <session default-value="${session}"/>
  <skip>${maven.test.skip}</skip>
  <skipIfEmpty default-value="false"/>
  <testClassesDirectory default-value="${project.build.testOutputDirectory}"/>
  <useDefaultManifestFile default-value="false">${jar.useDefaultManifestFile}</useDefaultManifestFile>
</configuration>
[DEBUG] -----------------------------------------------------------------------
[DEBUG] Goal:          org.apache.maven.plugins:maven-surefire-plugin:3.0.0-M5:test (integration-tests)
[DEBUG] Style:         Regular
[DEBUG] Configuration: <?xml version="1.0" encoding="UTF-8"?>
<configuration>
  <additionalClasspathElements>${maven.test.additionalClasspath}</additionalClasspathElements>
  <argLine>${argLine}</argLine>
  <basedir default-value="${basedir}"/>
  <childDelegation default-value="false">${childDelegation}</childDelegation>
  <classesDirectory default-value="${project.build.outputDirectory}"/>
  <classpathDependencyExcludes>${maven.test.dependency.excludes}</classpathDependencyExcludes>
  <debugForkedProcess>${maven.surefire.debug}</debugForkedProcess>
  <dependenciesToScan>${dependenciesToScan}</dependenciesToScan>
  <disableXmlReport default-value="false">${disableXmlReport}</disableXmlReport>
  <enableAssertions default-value="true">${enableAssertions}</enableAssertions>
  <enableProcessChecker>${surefire.enableProcessChecker}</enableProcessChecker>
  <encoding default-value="${project.reporting.outputEncoding}">${surefire.encoding}</encoding>
  <excludedEnvironmentVariables>${surefire.excludedEnvironmentVariables}</excludedEnvironmentVariables>
  <excludedGroups>${excludedGroups}</excludedGroups>
  <excludes>
    <exclude>none</exclude>
  </excludes>
  <excludesFile>${surefire.excludesFile}</excludesFile>
  <failIfNoSpecifiedTests>${surefire.failIfNoSpecifiedTests}</failIfNoSpecifiedTests>
  <failIfNoTests>${failIfNoTests}</failIfNoTests>
  <forkCount default-value="1">1</forkCount>
  <forkMode default-value="once">${forkMode}</forkMode>
  <forkNode>${surefire.forkNode}</forkNode>
  <forkedProcessExitTimeoutInSeconds default-value="30">${surefire.exitTimeout}</forkedProcessExitTimeoutInSeconds>
  <forkedProcessTimeoutInSeconds>3600</forkedProcessTimeoutInSeconds>
  <groups>${groups}</groups>
  <includes>
    <include>**/*IT.java</include>
  </includes>
  <includesFile>${surefire.includesFile}</includesFile>
  <junitArtifactName default-value="junit:junit">${junitArtifactName}</junitArtifactName>
  <jvm>${jvm}</jvm>
  <localRepository default-value="${localRepository}"/>
  <objectFactory>${objectFactory}</objectFactory>
  <parallel>${parallel}</parallel>
  <parallelMavenExecution default-value="${session.parallel}"/>
  <parallelOptimized default-value="true">${parallelOptimized}</parallelOptimized>
  <parallelTestsTimeoutForcedInSeconds>${surefire.parallel.forcedTimeout}</parallelTestsTimeoutForcedInSeconds>
  <parallelTestsTimeoutInSeconds>${surefire.parallel.timeout}</parallelTestsTimeoutInSeconds>
  <perCoreThreadCount default-value="true">${perCoreThreadCount}</perCoreThreadCount>
  <pluginArtifactMap>${plugin.artifactMap}</pluginArtifactMap>
  <pluginDescriptor default-value="${plugin}"/>
  <printSummary default-value="true">${surefire.printSummary}</printSummary>
  <project default-value="${project}"/>
  <projectArtifactMap>${project.artifactMap}</projectArtifactMap>
  <projectBuildDirectory default-value="${project.build.directory}"/>
  <projectRemoteRepositories default-value="${project.remoteArtifactRepositories}"/>
  <redirectTestOutputToFile default-value="false">${maven.test.redirectTestOutputToFile}</redirectTestOutputToFile>
  <remoteRepositories default-value="${project.pluginArtifactRepositories}"/>
  <reportFormat default-value="brief">plain</reportFormat>
  <reportNameSuffix default-value="">${surefire.reportNameSuffix}</reportNameSuffix>
  <reportsDirectory default-value="${project.build.directory}/surefire-reports"/>
  <rerunFailingTestsCount default-value="0">${surefire.rerunFailingTestsCount}</rerunFailingTestsCount>
  <reuseForks default-value="true">false</reuseForks>
  <runOrder default-value="filesystem">${surefire.runOrder}</runOrder>
  <session default-value="${session}"/>
  <shutdown default-value="exit">${surefire.shutdown}</shutdown>
  <skip default-value="false">true</skip>
  <skipAfterFailureCount default-value="0">${surefire.skipAfterFailureCount}</skipAfterFailureCount>
  <skipExec>${maven.test.skip.exec}</skipExec>
  <skipTests default-value="false">${skipTests}</skipTests>
  <suiteXmlFiles>${surefire.suiteXmlFiles}</suiteXmlFiles>
  <systemPropertiesFile>${surefire.systemPropertiesFile}</systemPropertiesFile>
  <systemPropertyVariables>
    <zookeeper.forceSync>no</zookeeper.forceSync>
  </systemPropertyVariables>
  <tempDir default-value="surefire">${tempDir}</tempDir>
  <test>${test}</test>
  <testClassesDirectory default-value="${project.build.testOutputDirectory}"/>
  <testFailureIgnore default-value="false">false</testFailureIgnore>
  <testNGArtifactName default-value="org.testng:testng">${testNGArtifactName}</testNGArtifactName>
  <testSourceDirectory default-value="${project.build.testSourceDirectory}"/>
  <threadCount>${threadCount}</threadCount>
  <threadCountClasses default-value="0">${threadCountClasses}</threadCountClasses>
  <threadCountMethods default-value="0">${threadCountMethods}</threadCountMethods>
  <threadCountSuites default-value="0">${threadCountSuites}</threadCountSuites>
  <trimStackTrace default-value="true">false</trimStackTrace>
  <useFile default-value="true">${surefire.useFile}</useFile>
  <useManifestOnlyJar default-value="true">${surefire.useManifestOnlyJar}</useManifestOnlyJar>
  <useModulePath default-value="true">${surefire.useModulePath}</useModulePath>
  <useSystemClassLoader default-value="true">${surefire.useSystemClassLoader}</useSystemClassLoader>
  <useUnlimitedThreads default-value="false">${useUnlimitedThreads}</useUnlimitedThreads>
  <workingDirectory>${basedir}</workingDirectory>
</configuration>
[DEBUG] -----------------------------------------------------------------------
[DEBUG] Goal:          com.diffplug.spotless:spotless-maven-plugin:2.9.0:check (default)
[DEBUG] Style:         Regular
[DEBUG] Configuration: <?xml version="1.0" encoding="UTF-8"?>
<configuration>
  <baseDir default-value="${project.basedir}"/>
  <buildDir default-value="${project.build.directory}"/>
  <encoding default-value="UTF-8"/>
  <filePatterns>${spotlessFiles}</filePatterns>
  <java>
    <includes>
      <include>src/main/java/**/*.java</include>
      <include>src/test/java/**/*.java</include>
    </includes>
    <importOrder>
      <order>,\#</order>
    </importOrder>
    <removeUnusedImports/>
  </java>
  <lineEndings default-value="GIT_ATTRIBUTES"/>
  <repositories default-value="${project.remotePluginRepositories}"/>
  <repositorySystemSession default-value="${repositorySystemSession}"/>
  <setLicenseHeaderYearsFromGitHistory>${spotlessSetLicenseHeaderYearsFromGitHistory}</setLicenseHeaderYearsFromGitHistory>
  <skip default-value="false">${spotless.check.skip}</skip>
</configuration>
[DEBUG] -----------------------------------------------------------------------
[DEBUG] Goal:          com.mycila:license-maven-plugin:4.0:check (default)
[DEBUG] Style:         Regular
[DEBUG] Configuration: <?xml version="1.0" encoding="UTF-8"?>
<configuration>
  <aggregate default-value="false">${license.aggregate}</aggregate>
  <concurrencyFactor default-value="1.5">${license.concurrencyFactor}</concurrencyFactor>
  <defaultBasedir default-value="${basedir}">${license.basedir}</defaultBasedir>
  <defaultHeaderDefinitions>
    <headerDefinition>/Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/../../../headerdefinition.xml</headerDefinition>
  </defaultHeaderDefinitions>
  <defaultUseDefaultExcludes default-value="true">${license.useDefaultExcludes}</defaultUseDefaultExcludes>
  <dryRun default-value="false">${license.dryRun}</dryRun>
  <encoding default-value="${project.build.sourceEncoding}">${license.encoding}</encoding>
  <errorMessage default-value="Some files do not have the expected license header">${license.errorMessage}</errorMessage>
  <failIfMissing default-value="true">${license.failIfMissing}</failIfMissing>
  <failIfUnknown default-value="false">${license.failIfUnknown}</failIfUnknown>
  <legacyConfigExcludes>
    <exclude>**/*.txt</exclude>
    <exclude>**/*.log</exclude>
    <exclude>**/*.list</exclude>
    <exclude>**/*.out</exclude>
    <exclude>**/*.generated</exclude>
    <exclude>**/*.json</exclude>
    <exclude>**/*.schema</exclude>
    <exclude>**/java.sql.*</exclude>
    <exclude>**/org.apache.spark.sql.sources.DataSourceRegister</exclude>
    <exclude>**/*.avro</exclude>
    <exclude>**/*.avsc</exclude>
    <exclude>**/*.csv</exclude>
    <exclude>**/*.desc</exclude>
    <exclude>**/*.parquet</exclude>
    <exclude>**/*.gz</exclude>
    <exclude>**/*.orc</exclude>
    <exclude>**/*.dict</exclude>
    <exclude>**/*.raw</exclude>
    <exclude>**/*.mapping</exclude>
    <exclude>**/*.ser</exclude>
    <exclude>**/*.v1</exclude>
    <exclude>**/*.v2</exclude>
    <exclude>target/**</exclude>
    <exclude>pinot-*/target/**</exclude>
    <exclude>kubernetes/**</exclude>
    <exclude>docker/**</exclude>
    <exclude>contrib/**</exclude>
    <exclude>HEADER</exclude>
    <exclude>LICENSE*</exclude>
    <exclude>NOTICE*</exclude>
    <exclude>**/node_modules/**</exclude>
    <exclude>**/dist/**</exclude>
    <exclude>**/src/main/resources/*.*rc</exclude>
    <exclude>**/maven-eclipse.xml</exclude>
    <exclude>.externalToolBuilders/**</exclude>${license.excludes}</legacyConfigExcludes>
  <legacyConfigHeader>/Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/../../../HEADER</legacyConfigHeader>
  <legacyConfigIncludes>${license.includes}</legacyConfigIncludes>
  <legacyConfigInlineHeader>${license.inlineHeader}</legacyConfigInlineHeader>
  <mapping>
    <java>JAVADOC_STYLE</java>
    <scala>JAVADOC_STYLE</scala>
    <thrift>JAVADOC_STYLE</thrift>
    <g4>JAVADOC_STYLE</g4>
    <ts>JAVADOC_STYLE</ts>
    <tsx>JAVADOC_STYLE</tsx>
    <config>SCRIPT_STYLE</config>
    <queries>SCRIPT_STYLE</queries>
    <results>SCRIPT_STYLE</results>
    <fmpp>SCRIPT_STYLE</fmpp>
    <ftl>FTL_STYLE</ftl>
    <MockMaker>SCRIPT_STYLE</MockMaker>
    <appAssemblerScriptTemplate>SCRIPT_STYLE</appAssemblerScriptTemplate>
    <sql>SCRIPT_STYLE</sql>
    <conf>DOUBLESLASH_STYLE</conf>
    <cfg>DOUBLESLASH_STYLE</cfg>
    <proto>DOUBLESLASH_STYLE</proto>
    <rst>RST_STYLE</rst>
    <readme>RST_STYLE</readme>
  </mapping>
  <nThreads default-value="0">${license.nThreads}</nThreads>
  <quiet default-value="false">${license.quiet}</quiet>
  <skip default-value="false">${license.skip}</skip>
  <skipExistingHeaders default-value="false">${license.skipExistingHeaders}</skipExistingHeaders>
  <strictCheck default-value="true">${license.strictCheck}</strictCheck>
  <useDefaultMapping default-value="true">${license.useDefaultMapping}</useDefaultMapping>
  <project default-value="${project}"/>
  <settings default-value="${settings}"/>
</configuration>
[DEBUG] -----------------------------------------------------------------------
[DEBUG] Goal:          org.apache.rat:apache-rat-plugin:0.13:check (default)
[DEBUG] Style:         Regular
[DEBUG] Configuration: <?xml version="1.0" encoding="UTF-8"?>
<configuration>
  <addDefaultLicenseMatchers default-value="true">${rat.addDefaultLicenseMatchers}</addDefaultLicenseMatchers>
  <addLicenseHeaders default-value="false">${rat.addLicenseHeaders}</addLicenseHeaders>
  <basedir default-value="${basedir}">${rat.basedir}</basedir>
  <consoleOutput default-value="false">${rat.consoleOutput}</consoleOutput>
  <copyrightMessage>${rat.copyrightMessage}</copyrightMessage>
  <excludeSubProjects default-value="true">${rat.excludeSubprojects}</excludeSubProjects>
  <excludes>
    <exclude>licenses/**</exclude>
    <exclude>licenses-binary/**</exclude>
    <exclude>**/target/**</exclude>
    <exclude>**/*.txt</exclude>
    <exclude>**/*.log</exclude>
    <exclude>**/*.list</exclude>
    <exclude>**/*.out</exclude>
    <exclude>**/*.generated</exclude>
    <exclude>**/*.json</exclude>
    <exclude>**/*.schema</exclude>
    <exclude>**/java.sql.*</exclude>
    <exclude>**/org.apache.spark.sql.sources.DataSourceRegister</exclude>
    <exclude>**/*.avro</exclude>
    <exclude>**/*.avsc</exclude>
    <exclude>**/*.csv</exclude>
    <exclude>**/*.desc</exclude>
    <exclude>**/*.parquet</exclude>
    <exclude>**/*.gz</exclude>
    <exclude>**/*.orc</exclude>
    <exclude>**/*.dict</exclude>
    <exclude>**/*.raw</exclude>
    <exclude>**/*.mapping</exclude>
    <exclude>**/*.ser</exclude>
    <exclude>**/*.v1</exclude>
    <exclude>**/*.v2</exclude>
    <exclude>**/appAssemblerScriptTemplate</exclude>
    <exclude>**/node_modules/**</exclude>
    <exclude>**/dist/**</exclude>
    <exclude>**/*.*rc</exclude>
    <exclude>**/src/main/resources/*.*rc</exclude>
    <exclude>**/*.iml</exclude>
    <exclude>**/maven-eclipse.xml</exclude>
    <exclude>**/.settings/**</exclude>
    <exclude>**/.project</exclude>
    <exclude>.externalToolBuilders/**</exclude>
    <exclude>kubernetes/**</exclude>
    <exclude>docker/**</exclude>
    <exclude>contrib/**</exclude>
    <exclude>.github/*.md</exclude>
    <exclude>**/test-output/**</exclude>
    <exclude>**/.factorypath</exclude>
  </excludes>
  <excludesFile>${rat.excludesFile}</excludesFile>
  <excludesFileCharset default-value="${project.build.sourceEncoding}">${rat.excludesFileCharset}</excludesFileCharset>
  <ignoreErrors default-value="false">${rat.ignoreErrors}</ignoreErrors>
  <includesFile>${rat.includesFile}</includesFile>
  <includesFileCharset default-value="${project.build.sourceEncoding}">${rat.includesFileCharset}</includesFileCharset>
  <numUnapprovedLicenses default-value="0">${rat.numUnapprovedLicenses}</numUnapprovedLicenses>
  <parseSCMIgnoresAsExcludes default-value="true">${rat.parseSCMIgnoresAsExcludes}</parseSCMIgnoresAsExcludes>
  <project default-value="${project}"/>
  <reportFile default-value="${project.build.directory}/rat.txt">${rat.outputFile}</reportFile>
  <reportStyle default-value="plain">${rat.outputStyle}</reportStyle>
  <skip default-value="false">${rat.skip}</skip>
  <useDefaultExcludes default-value="true">${rat.useDefaultExcludes}</useDefaultExcludes>
  <useEclipseDefaultExcludes default-value="true">${rat.useEclipseDefaultExcludes}</useEclipseDefaultExcludes>
  <useIdeaDefaultExcludes default-value="true">${rat.useIdeaDefaultExcludes}</useIdeaDefaultExcludes>
  <useMavenDefaultExcludes default-value="true">${rat.useMavenDefaultExcludes}</useMavenDefaultExcludes>
</configuration>
[DEBUG] -----------------------------------------------------------------------
[DEBUG] Goal:          org.apache.maven.plugins:maven-install-plugin:2.5.2:install (default-install)
[DEBUG] Style:         Regular
[DEBUG] Configuration: <?xml version="1.0" encoding="UTF-8"?>
<configuration>
  <artifact default-value="${project.artifact}"/>
  <attachedArtifacts default-value="${project.attachedArtifacts}"/>
  <createChecksum default-value="false">${createChecksum}</createChecksum>
  <installAtEnd default-value="false">${installAtEnd}</installAtEnd>
  <localRepository>${localRepository}</localRepository>
  <packaging default-value="${project.packaging}"/>
  <pomFile default-value="${project.file}"/>
  <project default-value="${project}"/>
  <reactorProjects default-value="${reactorProjects}"/>
  <skip default-value="false">${maven.install.skip}</skip>
  <updateReleaseInfo default-value="false">${updateReleaseInfo}</updateReleaseInfo>
</configuration>
[DEBUG] -----------------------------------------------------------------------
[DEBUG] Goal:          org.apache.maven.plugins:maven-checkstyle-plugin:3.1.2:check (checkstyle)
[DEBUG] Style:         Regular
[DEBUG] Configuration: <?xml version="1.0" encoding="UTF-8"?>
<configuration>
  <cacheFile default-value="${project.build.directory}/checkstyle-cachefile"/>
  <checkstyleRulesHeader default-value="&lt;?xml version=&quot;1.0&quot;?&gt;&#10;&lt;!DOCTYPE module PUBLIC &quot;-//Checkstyle//DTD Checkstyle Configuration 1.3//EN&quot;&#10;        &quot;https://checkstyle.org/dtds/configuration_1_3.dtd&quot;&gt;&#10;"/>
  <configLocation default-value="sun_checks.xml">/Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/../../../config/checkstyle.xml</configLocation>
  <consoleOutput default-value="false">${checkstyle.consoleOutput}</consoleOutput>
  <encoding default-value="${project.build.sourceEncoding}">${encoding}</encoding>
  <excludes>${checkstyle.excludes}</excludes>
  <failOnViolation default-value="true">true</failOnViolation>
  <failsOnError default-value="false"/>
  <headerLocation default-value="LICENSE.txt">${checkstyle.header.file}</headerLocation>
  <includeResources default-value="true">${checkstyle.includeResources}</includeResources>
  <includeTestResources default-value="true">${checkstyle.includeTestResources}</includeTestResources>
  <includeTestSourceDirectory default-value="false">true</includeTestSourceDirectory>
  <includes default-value="**\/*.java">${checkstyle.includes}</includes>
  <logViolationCountToConsole default-value="true">${checkstyle.logViolationCount}</logViolationCountToConsole>
  <logViolationsToConsole default-value="true">true</logViolationsToConsole>
  <maxAllowedViolations default-value="0">${checkstyle.maxAllowedViolations}</maxAllowedViolations>
  <omitIgnoredModules default-value="false"/>
  <outputFile default-value="${project.build.directory}/checkstyle-result.xml">${checkstyle.output.file}</outputFile>
  <outputFileFormat default-value="xml">${checkstyle.output.format}</outputFileFormat>
  <plugin default-value="${plugin}"/>
  <project default-value="${project}"/>
  <propertiesLocation>${checkstyle.properties.location}</propertiesLocation>
  <propertyExpansion>config_loc=/Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/../../../config</propertyExpansion>
  <resourceExcludes>${checkstyle.resourceExcludes}</resourceExcludes>
  <resourceIncludes default-value="**/*.properties">${checkstyle.resourceIncludes}</resourceIncludes>
  <resources default-value="${project.resources}"/>
  <rulesFiles default-value="${project.build.directory}/checkstyle-rules.xml">${checkstyle.output.rules.file}</rulesFiles>
  <skip default-value="false">${checkstyle.skip}</skip>
  <skipExec default-value="false">${checkstyle.skipExec}</skipExec>
  <suppressionsFileExpression default-value="checkstyle.suppressions.file">${checkstyle.suppression.expression}</suppressionsFileExpression>
  <suppressionsLocation>/Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/../../../config/suppressions.xml</suppressionsLocation>
  <testResources default-value="${project.testResources}"/>
  <violationIgnore>${checkstyle.violation.ignore}</violationIgnore>
  <violationSeverity default-value="error">warning</violationSeverity>
</configuration>
[DEBUG] -----------------------------------------------------------------------
[DEBUG] Goal:          org.codehaus.mojo:buildnumber-maven-plugin:1.3:create (default)
[DEBUG] Style:         Regular
[DEBUG] Configuration: <?xml version="1.0" encoding="UTF-8"?>
<configuration>
  <buildNumberPropertiesFileLocation default-value="${basedir}/buildNumber.properties"/>
  <buildNumberPropertyName default-value="buildNumber">${maven.buildNumber.buildNumberPropertyName}</buildNumberPropertyName>
  <doCheck default-value="false">${maven.buildNumber.doCheck}</doCheck>
  <doUpdate default-value="false">${maven.buildNumber.doUpdate}</doUpdate>
  <format>${maven.buildNumber.format}</format>
  <getRevisionOnlyOnce default-value="false">${maven.buildNumber.getRevisionOnlyOnce}</getRevisionOnlyOnce>
  <locale>${maven.buildNumber.locale}</locale>
  <password>${password}</password>
  <project default-value="${project}"/>
  <reactorProjects default-value="${reactorProjects}"/>
  <readUrlScm default-value="${project.scm.connection}"/>
  <revisionOnScmFailure>${maven.buildNumber.revisionOnScmFailure}</revisionOnScmFailure>
  <scmBranchPropertyName default-value="scmBranch">${maven.buildNumber.scmBranchPropertyName}</scmBranchPropertyName>
  <scmDirectory default-value="${basedir}">${maven.buildNumber.scmDirectory}</scmDirectory>
  <session default-value="${session}"/>
  <skip default-value="false">${maven.buildNumber.skip}</skip>
  <timestampFormat>${maven.buildNumber.timestampFormat}</timestampFormat>
  <timestampPropertyName default-value="timestamp">${maven.buildNumber.timestampPropertyName}</timestampPropertyName>
  <urlScm default-value="${project.scm.developerConnection}"/>
  <useLastCommittedRevision default-value="false">${maven.buildNumber.useLastCommittedRevision}</useLastCommittedRevision>
  <username>${username}</username>
</configuration>
[DEBUG] -----------------------------------------------------------------------
[DEBUG] Goal:          org.apache.maven.plugins:maven-enforcer-plugin:3.0.0-M2:enforce (enforce-dependency-convergence)
[DEBUG] Style:         Regular
[DEBUG] Configuration: <?xml version="1.0" encoding="UTF-8"?>
<configuration>
  <fail default-value="true">${enforcer.fail}</fail>
  <failFast default-value="false">${enforcer.failFast}</failFast>
  <ignoreCache default-value="false">${enforcer.ignoreCache}</ignoreCache>
  <mojoExecution default-value="${mojoExecution}"/>
  <project default-value="${project}"/>
  <rules>
    <dependencyConvergence/>
  </rules>
  <session default-value="${session}"/>
  <skip default-value="false">${enforcer.skip}</skip>
</configuration>
[DEBUG] -----------------------------------------------------------------------
[DEBUG] Goal:          org.apache.maven.plugins:maven-enforcer-plugin:3.0.0-M2:enforce (enforce-maven-version)
[DEBUG] Style:         Regular
[DEBUG] Configuration: <?xml version="1.0" encoding="UTF-8"?>
<configuration>
  <fail default-value="true">${enforcer.fail}</fail>
  <failFast default-value="false">${enforcer.failFast}</failFast>
  <ignoreCache default-value="false">${enforcer.ignoreCache}</ignoreCache>
  <mojoExecution default-value="${mojoExecution}"/>
  <project default-value="${project}"/>
  <rules>
    <requireMavenVersion>
      <version>3.0.5</version>
    </requireMavenVersion>
    <dependencyConvergence/>
  </rules>
  <session default-value="${session}"/>
  <skip default-value="false">${enforcer.skip}</skip>
</configuration>
[DEBUG] -----------------------------------------------------------------------
[DEBUG] Goal:          org.jacoco:jacoco-maven-plugin:0.8.6:prepare-agent (default)
[DEBUG] Style:         Regular
[DEBUG] Configuration: <?xml version="1.0" encoding="UTF-8"?>
<configuration>
  <address>${jacoco.address}</address>
  <append>${jacoco.append}</append>
  <classDumpDir>${jacoco.classDumpDir}</classDumpDir>
  <destFile default-value="${project.build.directory}/jacoco.exec">${jacoco.destFile}</destFile>
  <dumpOnExit>${jacoco.dumpOnExit}</dumpOnExit>
  <exclClassLoaders>${jacoco.exclClassLoaders}</exclClassLoaders>
  <inclBootstrapClasses>${jacoco.inclBootstrapClasses}</inclBootstrapClasses>
  <inclNoLocationClasses>${jacoco.inclNoLocationClasses}</inclNoLocationClasses>
  <includes>
    <include>org/apache/pinot/**/*</include>
  </includes>
  <jmx>${jacoco.jmx}</jmx>
  <output>${jacoco.output}</output>
  <pluginArtifactMap>${plugin.artifactMap}</pluginArtifactMap>
  <port>${jacoco.port}</port>
  <project>${project}</project>
  <propertyName>${jacoco.propertyName}</propertyName>
  <sessionId>${jacoco.sessionId}</sessionId>
  <skip default-value="false">${jacoco.skip}</skip>
</configuration>
[DEBUG] -----------------------------------------------------------------------
[DEBUG] Goal:          org.apache.maven.plugins:maven-remote-resources-plugin:1.6.0:process (process-resource-bundles)
[DEBUG] Style:         Regular
[DEBUG] Configuration: <?xml version="1.0" encoding="UTF-8"?>
<configuration>
  <appendedResourcesDirectory default-value="${basedir}/src/main/appended-resources"/>
  <attachToMain default-value="true">${attachToMain}</attachToMain>
  <attachToTest default-value="true">${attachToTest}</attachToTest>
  <basedir default-value="${basedir}"/>
  <encoding default-value="${project.build.sourceEncoding}">${encoding}</encoding>
  <excludeArtifactIds default-value="">${excludeArtifactIds}</excludeArtifactIds>
  <excludeGroupIds default-value="">${excludeGroupIds}</excludeGroupIds>
  <excludeScope default-value="">${excludeScope}</excludeScope>
  <excludeTransitive default-value="false">${excludeTransitive}</excludeTransitive>
  <includeArtifactIds default-value="">${includeArtifactIds}</includeArtifactIds>
  <includeGroupIds default-value="">${includeGroupIds}</includeGroupIds>
  <includeProjectProperties default-value="false"/>
  <includeScope default-value="runtime">${includeScope}</includeScope>
  <localRepository default-value="${localRepository}"/>
  <mavenSession default-value="${session}"/>
  <outputDirectory default-value="${project.build.directory}/maven-shared-archive-resources"/>
  <project default-value="${project}"/>
  <remoteArtifactRepositories default-value="${project.remoteArtifactRepositories}"/>
  <resourceBundles>
    <resourceBundle>org.apache:apache-jar-resource-bundle:1.4</resourceBundle>
  </resourceBundles>
  <resources default-value="${project.resources}"/>
  <runOnlyAtExecutionRoot default-value="false"/>
  <skip default-value="false">${remoteresources.skip}</skip>
  <useDefaultFilterDelimiters default-value="true"/>
  <velocityFilterInMemoryThreshold default-value="5242880"/>
</configuration>
[DEBUG] -----------------------------------------------------------------------
[DEBUG] Goal:          org.apache.maven.plugins:maven-remote-resources-plugin:1.6.0:process (default)
[DEBUG] Style:         Regular
[DEBUG] Configuration: <?xml version="1.0" encoding="UTF-8"?>
<configuration>
  <appendedResourcesDirectory default-value="${basedir}/src/main/appended-resources"/>
  <attachToMain default-value="true">${attachToMain}</attachToMain>
  <attachToTest default-value="true">${attachToTest}</attachToTest>
  <basedir default-value="${basedir}"/>
  <encoding default-value="${project.build.sourceEncoding}">${encoding}</encoding>
  <excludeArtifactIds default-value="">${excludeArtifactIds}</excludeArtifactIds>
  <excludeGroupIds default-value="">${excludeGroupIds}</excludeGroupIds>
  <excludeScope default-value="">${excludeScope}</excludeScope>
  <excludeTransitive default-value="false">${excludeTransitive}</excludeTransitive>
  <includeArtifactIds default-value="">${includeArtifactIds}</includeArtifactIds>
  <includeGroupIds default-value="">${includeGroupIds}</includeGroupIds>
  <includeProjectProperties default-value="false"/>
  <includeScope default-value="runtime">${includeScope}</includeScope>
  <localRepository default-value="${localRepository}"/>
  <mavenSession default-value="${session}"/>
  <outputDirectory default-value="${project.build.directory}/maven-shared-archive-resources"/>
  <project default-value="${project}"/>
  <properties>
    <projectName>Apache Pinot</projectName>
  </properties>
  <remoteArtifactRepositories default-value="${project.remoteArtifactRepositories}"/>
  <resourceBundles>
    <resourceBundle>org.apache:apache-jar-resource-bundle:1.4</resourceBundle>
  </resourceBundles>
  <resources default-value="${project.resources}"/>
  <runOnlyAtExecutionRoot default-value="false"/>
  <skip default-value="false">${remoteresources.skip}</skip>
  <useDefaultFilterDelimiters default-value="true"/>
  <velocityFilterInMemoryThreshold default-value="5242880"/>
</configuration>
[DEBUG] -----------------------------------------------------------------------
[DEBUG] Goal:          org.apache.maven.plugins:maven-resources-plugin:2.6:resources (default-resources)
[DEBUG] Style:         Regular
[DEBUG] Configuration: <?xml version="1.0" encoding="UTF-8"?>
<configuration>
  <buildFilters default-value="${project.build.filters}"/>
  <encoding default-value="${project.build.sourceEncoding}">${encoding}</encoding>
  <escapeString>${maven.resources.escapeString}</escapeString>
  <escapeWindowsPaths default-value="true">${maven.resources.escapeWindowsPaths}</escapeWindowsPaths>
  <includeEmptyDirs default-value="false">${maven.resources.includeEmptyDirs}</includeEmptyDirs>
  <outputDirectory default-value="${project.build.outputDirectory}"/>
  <overwrite default-value="false">${maven.resources.overwrite}</overwrite>
  <project default-value="${project}"/>
  <resources default-value="${project.resources}"/>
  <session default-value="${session}"/>
  <supportMultiLineFiltering default-value="false">${maven.resources.supportMultiLineFiltering}</supportMultiLineFiltering>
  <useBuildFilters default-value="true"/>
  <useDefaultDelimiters default-value="true"/>
</configuration>
[DEBUG] -----------------------------------------------------------------------
[DEBUG] Goal:          org.apache.maven.plugins:maven-compiler-plugin:3.8.0:compile (default-compile)
[DEBUG] Style:         Regular
[DEBUG] Configuration: <?xml version="1.0" encoding="UTF-8"?>
<configuration>
  <basedir default-value="${basedir}"/>
  <buildDirectory default-value="${project.build.directory}"/>
  <compilePath default-value="${project.compileClasspathElements}"/>
  <compileSourceRoots default-value="${project.compileSourceRoots}"/>
  <compilerId default-value="javac">${maven.compiler.compilerId}</compilerId>
  <compilerReuseStrategy default-value="${reuseCreated}">${maven.compiler.compilerReuseStrategy}</compilerReuseStrategy>
  <compilerVersion>${maven.compiler.compilerVersion}</compilerVersion>
  <debug default-value="true">${maven.compiler.debug}</debug>
  <debuglevel>${maven.compiler.debuglevel}</debuglevel>
  <encoding default-value="${project.build.sourceEncoding}">UTF-8</encoding>
  <executable>${maven.compiler.executable}</executable>
  <failOnError default-value="true">${maven.compiler.failOnError}</failOnError>
  <failOnWarning default-value="false">${maven.compiler.failOnWarning}</failOnWarning>
  <forceJavacCompilerUse default-value="false">${maven.compiler.forceJavacCompilerUse}</forceJavacCompilerUse>
  <fork default-value="false">true</fork>
  <generatedSourcesDirectory default-value="${project.build.directory}/generated-sources/annotations"/>
  <maxmem>${maven.compiler.maxmem}</maxmem>
  <meminitial>${maven.compiler.meminitial}</meminitial>
  <mojoExecution default-value="${mojoExecution}"/>
  <optimize default-value="false">${maven.compiler.optimize}</optimize>
  <outputDirectory default-value="${project.build.outputDirectory}"/>
  <parameters default-value="false">${maven.compiler.parameters}</parameters>
  <project default-value="${project}"/>
  <projectArtifact default-value="${project.artifact}"/>
  <release>11</release>
  <session default-value="${session}"/>
  <showDeprecation default-value="false">${maven.compiler.showDeprecation}</showDeprecation>
  <showWarnings default-value="false">${maven.compiler.showWarnings}</showWarnings>
  <skipMain>${maven.main.skip}</skipMain>
  <skipMultiThreadWarning default-value="false">${maven.compiler.skipMultiThreadWarning}</skipMultiThreadWarning>
  <source default-value="1.6">11</source>
  <staleMillis default-value="0">${lastModGranularityMs}</staleMillis>
  <target default-value="1.6">11</target>
  <useIncrementalCompilation default-value="true">${maven.compiler.useIncrementalCompilation}</useIncrementalCompilation>
  <verbose default-value="false">${maven.compiler.verbose}</verbose>
</configuration>
[DEBUG] -----------------------------------------------------------------------
[DEBUG] Goal:          org.apache.maven.plugins:maven-resources-plugin:2.6:testResources (default-testResources)
[DEBUG] Style:         Regular
[DEBUG] Configuration: <?xml version="1.0" encoding="UTF-8"?>
<configuration>
  <buildFilters default-value="${project.build.filters}"/>
  <encoding default-value="${project.build.sourceEncoding}">${encoding}</encoding>
  <escapeString>${maven.resources.escapeString}</escapeString>
  <escapeWindowsPaths default-value="true">${maven.resources.escapeWindowsPaths}</escapeWindowsPaths>
  <includeEmptyDirs default-value="false">${maven.resources.includeEmptyDirs}</includeEmptyDirs>
  <outputDirectory default-value="${project.build.testOutputDirectory}"/>
  <overwrite default-value="false">${maven.resources.overwrite}</overwrite>
  <project default-value="${project}"/>
  <resources default-value="${project.testResources}"/>
  <session default-value="${session}"/>
  <skip>${maven.test.skip}</skip>
  <supportMultiLineFiltering default-value="false">${maven.resources.supportMultiLineFiltering}</supportMultiLineFiltering>
  <useBuildFilters default-value="true"/>
  <useDefaultDelimiters default-value="true"/>
</configuration>
[DEBUG] -----------------------------------------------------------------------
[DEBUG] Goal:          org.apache.maven.plugins:maven-compiler-plugin:3.8.0:testCompile (default-testCompile)
[DEBUG] Style:         Regular
[DEBUG] Configuration: <?xml version="1.0" encoding="UTF-8"?>
<configuration>
  <basedir default-value="${basedir}"/>
  <buildDirectory default-value="${project.build.directory}"/>
  <compilePath default-value="${project.compileClasspathElements}"/>
  <compileSourceRoots default-value="${project.testCompileSourceRoots}"/>
  <compilerId default-value="javac">${maven.compiler.compilerId}</compilerId>
  <compilerReuseStrategy default-value="${reuseCreated}">${maven.compiler.compilerReuseStrategy}</compilerReuseStrategy>
  <compilerVersion>${maven.compiler.compilerVersion}</compilerVersion>
  <debug default-value="true">${maven.compiler.debug}</debug>
  <debuglevel>${maven.compiler.debuglevel}</debuglevel>
  <encoding default-value="${project.build.sourceEncoding}">UTF-8</encoding>
  <executable>${maven.compiler.executable}</executable>
  <failOnError default-value="true">${maven.compiler.failOnError}</failOnError>
  <failOnWarning default-value="false">${maven.compiler.failOnWarning}</failOnWarning>
  <forceJavacCompilerUse default-value="false">${maven.compiler.forceJavacCompilerUse}</forceJavacCompilerUse>
  <fork default-value="false">true</fork>
  <generatedTestSourcesDirectory default-value="${project.build.directory}/generated-test-sources/test-annotations"/>
  <maxmem>${maven.compiler.maxmem}</maxmem>
  <meminitial>${maven.compiler.meminitial}</meminitial>
  <mojoExecution default-value="${mojoExecution}"/>
  <optimize default-value="false">${maven.compiler.optimize}</optimize>
  <outputDirectory default-value="${project.build.testOutputDirectory}"/>
  <parameters default-value="false">${maven.compiler.parameters}</parameters>
  <project default-value="${project}"/>
  <release>11</release>
  <session default-value="${session}"/>
  <showDeprecation default-value="false">${maven.compiler.showDeprecation}</showDeprecation>
  <showWarnings default-value="false">${maven.compiler.showWarnings}</showWarnings>
  <skip>${maven.test.skip}</skip>
  <skipMultiThreadWarning default-value="false">${maven.compiler.skipMultiThreadWarning}</skipMultiThreadWarning>
  <source default-value="1.6">11</source>
  <staleMillis default-value="0">${lastModGranularityMs}</staleMillis>
  <target default-value="1.6">11</target>
  <testPath default-value="${project.testClasspathElements}"/>
  <testRelease>${maven.compiler.testRelease}</testRelease>
  <testSource>${maven.compiler.testSource}</testSource>
  <testTarget>${maven.compiler.testTarget}</testTarget>
  <useIncrementalCompilation default-value="true">${maven.compiler.useIncrementalCompilation}</useIncrementalCompilation>
  <verbose default-value="false">${maven.compiler.verbose}</verbose>
</configuration>
[DEBUG] -----------------------------------------------------------------------
[DEBUG] Goal:          org.apache.maven.plugins:maven-surefire-plugin:3.0.0-M5:test (default-test)
[DEBUG] Style:         Regular
[DEBUG] Configuration: <?xml version="1.0" encoding="UTF-8"?>
<configuration>
  <additionalClasspathElements>${maven.test.additionalClasspath}</additionalClasspathElements>
  <argLine>${argLine}</argLine>
  <basedir default-value="${basedir}"/>
  <childDelegation default-value="false">${childDelegation}</childDelegation>
  <classesDirectory default-value="${project.build.outputDirectory}"/>
  <classpathDependencyExcludes>${maven.test.dependency.excludes}</classpathDependencyExcludes>
  <debugForkedProcess>${maven.surefire.debug}</debugForkedProcess>
  <dependenciesToScan>${dependenciesToScan}</dependenciesToScan>
  <disableXmlReport default-value="false">${disableXmlReport}</disableXmlReport>
  <enableAssertions default-value="true">${enableAssertions}</enableAssertions>
  <enableProcessChecker>${surefire.enableProcessChecker}</enableProcessChecker>
  <encoding default-value="${project.reporting.outputEncoding}">${surefire.encoding}</encoding>
  <excludedEnvironmentVariables>${surefire.excludedEnvironmentVariables}</excludedEnvironmentVariables>
  <excludedGroups>${excludedGroups}</excludedGroups>
  <excludes>
    <exclude>**/*IT.java</exclude>
  </excludes>
  <excludesFile>${surefire.excludesFile}</excludesFile>
  <failIfNoSpecifiedTests>${surefire.failIfNoSpecifiedTests}</failIfNoSpecifiedTests>
  <failIfNoTests>${failIfNoTests}</failIfNoTests>
  <forkCount default-value="1">1</forkCount>
  <forkMode default-value="once">${forkMode}</forkMode>
  <forkNode>${surefire.forkNode}</forkNode>
  <forkedProcessExitTimeoutInSeconds default-value="30">${surefire.exitTimeout}</forkedProcessExitTimeoutInSeconds>
  <forkedProcessTimeoutInSeconds>3600</forkedProcessTimeoutInSeconds>
  <groups>${groups}</groups>
  <includesFile>${surefire.includesFile}</includesFile>
  <junitArtifactName default-value="junit:junit">${junitArtifactName}</junitArtifactName>
  <jvm>${jvm}</jvm>
  <localRepository default-value="${localRepository}"/>
  <objectFactory>${objectFactory}</objectFactory>
  <parallel>${parallel}</parallel>
  <parallelMavenExecution default-value="${session.parallel}"/>
  <parallelOptimized default-value="true">${parallelOptimized}</parallelOptimized>
  <parallelTestsTimeoutForcedInSeconds>${surefire.parallel.forcedTimeout}</parallelTestsTimeoutForcedInSeconds>
  <parallelTestsTimeoutInSeconds>${surefire.parallel.timeout}</parallelTestsTimeoutInSeconds>
  <perCoreThreadCount default-value="true">${perCoreThreadCount}</perCoreThreadCount>
  <pluginArtifactMap>${plugin.artifactMap}</pluginArtifactMap>
  <pluginDescriptor default-value="${plugin}"/>
  <printSummary default-value="true">${surefire.printSummary}</printSummary>
  <project default-value="${project}"/>
  <projectArtifactMap>${project.artifactMap}</projectArtifactMap>
  <projectBuildDirectory default-value="${project.build.directory}"/>
  <projectRemoteRepositories default-value="${project.remoteArtifactRepositories}"/>
  <redirectTestOutputToFile default-value="false">${maven.test.redirectTestOutputToFile}</redirectTestOutputToFile>
  <remoteRepositories default-value="${project.pluginArtifactRepositories}"/>
  <reportFormat default-value="brief">plain</reportFormat>
  <reportNameSuffix default-value="">${surefire.reportNameSuffix}</reportNameSuffix>
  <reportsDirectory default-value="${project.build.directory}/surefire-reports"/>
  <rerunFailingTestsCount default-value="0">${surefire.rerunFailingTestsCount}</rerunFailingTestsCount>
  <reuseForks default-value="true">false</reuseForks>
  <runOrder default-value="filesystem">${surefire.runOrder}</runOrder>
  <session default-value="${session}"/>
  <shutdown default-value="exit">${surefire.shutdown}</shutdown>
  <skip default-value="false">${maven.test.skip}</skip>
  <skipAfterFailureCount default-value="0">${surefire.skipAfterFailureCount}</skipAfterFailureCount>
  <skipExec>${maven.test.skip.exec}</skipExec>
  <skipTests default-value="false">${skipTests}</skipTests>
  <suiteXmlFiles>${surefire.suiteXmlFiles}</suiteXmlFiles>
  <systemPropertiesFile>${surefire.systemPropertiesFile}</systemPropertiesFile>
  <systemPropertyVariables>
    <zookeeper.forceSync>no</zookeeper.forceSync>
  </systemPropertyVariables>
  <tempDir default-value="surefire">${tempDir}</tempDir>
  <test>${test}</test>
  <testClassesDirectory default-value="${project.build.testOutputDirectory}"/>
  <testFailureIgnore default-value="false">false</testFailureIgnore>
  <testNGArtifactName default-value="org.testng:testng">${testNGArtifactName}</testNGArtifactName>
  <testSourceDirectory default-value="${project.build.testSourceDirectory}"/>
  <threadCount>${threadCount}</threadCount>
  <threadCountClasses default-value="0">${threadCountClasses}</threadCountClasses>
  <threadCountMethods default-value="0">${threadCountMethods}</threadCountMethods>
  <threadCountSuites default-value="0">${threadCountSuites}</threadCountSuites>
  <trimStackTrace default-value="true">false</trimStackTrace>
  <useFile default-value="true">${surefire.useFile}</useFile>
  <useManifestOnlyJar default-value="true">${surefire.useManifestOnlyJar}</useManifestOnlyJar>
  <useModulePath default-value="true">${surefire.useModulePath}</useModulePath>
  <useSystemClassLoader default-value="true">${surefire.useSystemClassLoader}</useSystemClassLoader>
  <useUnlimitedThreads default-value="false">${useUnlimitedThreads}</useUnlimitedThreads>
  <workingDirectory>${basedir}</workingDirectory>
</configuration>
[DEBUG] -----------------------------------------------------------------------
[DEBUG] Goal:          org.jacoco:jacoco-maven-plugin:0.8.6:report-aggregate (report)
[DEBUG] Style:         Regular
[DEBUG] Configuration: <?xml version="1.0" encoding="UTF-8"?>
<configuration>
  <includes>
    <include>org/apache/pinot/**/*</include>
  </includes>
  <outputDirectory default-value="${project.reporting.outputDirectory}/jacoco-aggregate"/>
  <outputEncoding default-value="UTF-8">${project.reporting.outputEncoding}</outputEncoding>
  <project>${project}</project>
  <reactorProjects>${reactorProjects}</reactorProjects>
  <skip default-value="false">${jacoco.skip}</skip>
  <sourceEncoding default-value="UTF-8">${project.build.sourceEncoding}</sourceEncoding>
  <title default-value="${project.name}"/>
</configuration>
[DEBUG] -----------------------------------------------------------------------
[DEBUG] Goal:          org.apache.maven.plugins:maven-jar-plugin:3.2.0:jar (default-jar)
[DEBUG] Style:         Regular
[DEBUG] Configuration: <?xml version="1.0" encoding="UTF-8"?>
<configuration>
  <archive>
    <manifestEntries>
      <Build-Time>2022-06-28T03:29:52Z</Build-Time>
      <Implementation-Branch>${scmBranch}</Implementation-Branch>
      <Implementation-Title>pinot-pulsar</Implementation-Title>
      <Implementation-Version>0.11.0-SNAPSHOT-${buildNumber}</Implementation-Version>
      <Implementation-Vendor-Id>org.apache.pinot</Implementation-Vendor-Id>
      <Implementation-Vendor>Apache Software Foundation</Implementation-Vendor>
    </manifestEntries>
    <manifest>
      <addDefaultSpecificationEntries>true</addDefaultSpecificationEntries>
      <addDefaultImplementationEntries>true</addDefaultImplementationEntries>
    </manifest>
  </archive>
  <classesDirectory default-value="${project.build.outputDirectory}"/>
  <finalName default-value="${project.build.finalName}"/>
  <forceCreation default-value="false">${maven.jar.forceCreation}</forceCreation>
  <outputDirectory default-value="${project.build.directory}"/>
  <outputTimestamp default-value="${project.build.outputTimestamp}"/>
  <project default-value="${project}"/>
  <session default-value="${session}"/>
  <skipIfEmpty default-value="false"/>
  <useDefaultManifestFile default-value="false">${jar.useDefaultManifestFile}</useDefaultManifestFile>
</configuration>
[DEBUG] -----------------------------------------------------------------------
[DEBUG] Goal:          org.apache.maven.plugins:maven-shade-plugin:3.2.1:shade (default)
[DEBUG] Style:         Regular
[DEBUG] Configuration: <?xml version="1.0" encoding="UTF-8"?>
<configuration>
  <createDependencyReducedPom default-value="true"/>
  <dependencyReducedPomLocation default-value="${basedir}/dependency-reduced-pom.xml"/>
  <filters>
    <filter>
      <artifact>*:*</artifact>
      <excludes>
        <exclude>META-INF/*.SF</exclude>
        <exclude>META-INF/*.DSA</exclude>
        <exclude>META-INF/*.RSA</exclude>
      </excludes>
    </filter>
  </filters>
  <generateUniqueDependencyReducedPom default-value="false"/>
  <localRepository default-value="${localRepository}"/>
  <outputDirectory default-value="${project.build.directory}"/>
  <project default-value="${project}"/>
  <relocations>
    <relocation>
      <pattern>com.google.common</pattern>
      <shadedPattern>shaded.com.google.common</shadedPattern>
    </relocation>
    <relocation>
      <pattern>com.fasterxml.jackson</pattern>
      <shadedPattern>shaded.com.fasterxml.jackson</shadedPattern>
    </relocation>
    <relocation>
      <pattern>org.apache.http</pattern>
      <shadedPattern>shaded.org.apache.http</shadedPattern>
    </relocation>
    <relocation>
      <pattern>software.amazon</pattern>
      <shadedPattern>shaded.software.amazon</shadedPattern>
    </relocation>
    <relocation>
      <pattern>org.reflections</pattern>
      <shadedPattern>shaded.org.reflections</shadedPattern>
    </relocation>
    <relocation>
      <pattern>io.netty</pattern>
      <shadedPattern>shaded.io.netty</shadedPattern>
    </relocation>
    <relocation>
      <pattern>org.apache.parquet</pattern>
      <shadedPattern>shaded.org.apache.parquet</shadedPattern>
    </relocation>
    <relocation>
      <pattern>org.apache.kafka</pattern>
      <shadedPattern>shaded.org.apache.kafka</shadedPattern>
    </relocation>
  </relocations>
  <remoteArtifactRepositories default-value="${project.remoteArtifactRepositories}"/>
  <session default-value="${session}"/>
  <shadeSourcesContent default-value="false">${shadeSourcesContent}</shadeSourcesContent>
  <shadeTestJar default-value="false"/>
  <shadedArtifactAttached>true</shadedArtifactAttached>
  <shadedArtifactId default-value="${project.artifactId}"/>
  <shadedClassifierName default-value="shaded"/>
  <transformers>
    <transformer implementation="org.apache.maven.plugins.shade.resource.ApacheLicenseResourceTransformer"/>
  </transformers>
  <useBaseVersion default-value="false"/>
</configuration>
[DEBUG] -----------------------------------------------------------------------
[DEBUG] Goal:          org.apache.maven.plugins:maven-site-plugin:3.7.1:attach-descriptor (attach-descriptor)
[DEBUG] Style:         Regular
[DEBUG] Configuration: <?xml version="1.0" encoding="UTF-8"?>
<configuration>
  <basedir>${basedir}</basedir>
  <localRepository default-value="${localRepository}"/>
  <locales default-value="en">${locales}</locales>
  <pomPackagingOnly default-value="true"/>
  <project default-value="${project}"/>
  <reactorProjects default-value="${reactorProjects}"/>
  <relativizeDecorationLinks default-value="true">${relativizeDecorationLinks}</relativizeDecorationLinks>
  <repositories default-value="${project.remoteArtifactRepositories}"/>
  <siteDirectory default-value="${basedir}/src/site"/>
  <skip default-value="false">${maven.site.skip}</skip>
</configuration>
[DEBUG] -----------------------------------------------------------------------
[DEBUG] Goal:          org.apache.maven.plugins:maven-jar-plugin:3.2.0:test-jar (default)
[DEBUG] Style:         Regular
[DEBUG] Configuration: <?xml version="1.0" encoding="UTF-8"?>
<configuration>
  <archive>
    <manifestEntries>
      <Build-Time>2022-06-28T03:29:52Z</Build-Time>
      <Implementation-Branch>${scmBranch}</Implementation-Branch>
      <Implementation-Title>pinot-pulsar</Implementation-Title>
      <Implementation-Version>0.11.0-SNAPSHOT-${buildNumber}</Implementation-Version>
      <Implementation-Vendor-Id>org.apache.pinot</Implementation-Vendor-Id>
      <Implementation-Vendor>Apache Software Foundation</Implementation-Vendor>
    </manifestEntries>
    <manifest>
      <addDefaultSpecificationEntries>true</addDefaultSpecificationEntries>
      <addDefaultImplementationEntries>true</addDefaultImplementationEntries>
    </manifest>
  </archive>
  <classifier default-value="tests"/>
  <finalName default-value="${project.build.finalName}"/>
  <forceCreation default-value="false">${maven.jar.forceCreation}</forceCreation>
  <outputDirectory default-value="${project.build.directory}"/>
  <outputTimestamp default-value="${project.build.outputTimestamp}"/>
  <project default-value="${project}"/>
  <session default-value="${session}"/>
  <skip>${maven.test.skip}</skip>
  <skipIfEmpty default-value="false"/>
  <testClassesDirectory default-value="${project.build.testOutputDirectory}"/>
  <useDefaultManifestFile default-value="false">${jar.useDefaultManifestFile}</useDefaultManifestFile>
</configuration>
[DEBUG] =======================================================================
[DEBUG] Using mirror maven-default-http-blocker (http://0.0.0.0/) for confluent (http://packages.confluent.io/maven/).
[DEBUG] Using mirror maven-default-http-blocker (http://0.0.0.0/) for glassfish-repository (http://download.java.net/maven/glassfish).
[DEBUG] Using mirror maven-default-http-blocker (http://0.0.0.0/) for ossrh-snapshots (http://oss.sonatype.org/content/repositories/snapshots).
[DEBUG] Skipped remote request for org.apache.pinot:pinot-spi:0.11.0-SNAPSHOT/maven-metadata.xml locally installed metadata up-to-date
[DEBUG] Skipped remote request for org.apache.pinot:pinot-spi:0.11.0-SNAPSHOT/maven-metadata.xml locally installed metadata up-to-date
[DEBUG] Skipped remote request for org.apache.pinot:pinot:0.11.0-SNAPSHOT/maven-metadata.xml locally installed metadata up-to-date
[DEBUG] Dependency collection stats {ConflictMarker.analyzeTime=1173250, ConflictMarker.markTime=486834, ConflictMarker.nodeCount=442, ConflictIdSorter.graphTime=410875, ConflictIdSorter.topsortTime=132625, ConflictIdSorter.conflictIdCount=143, ConflictIdSorter.conflictIdCycleCount=0, ConflictResolver.totalTime=20100334, ConflictResolver.conflictItemCount=271, DefaultDependencyCollector.collectTime=1373577541, DefaultDependencyCollector.transformTime=22418000}
[DEBUG] org.apache.pinot:pinot-pulsar:jar:0.11.0-SNAPSHOT
[DEBUG]    org.eclipse.jetty:jetty-server:jar:9.4.45.v20220203:compile
[DEBUG]       org.eclipse.jetty:jetty-http:jar:9.4.45.v20220203:compile
[DEBUG]          org.eclipse.jetty:jetty-util:jar:9.4.45.v20220203:compile
[DEBUG]       org.eclipse.jetty:jetty-io:jar:9.4.45.v20220203:compile
[DEBUG]    org.testcontainers:pulsar:jar:1.17.1:test
[DEBUG]       org.testcontainers:testcontainers:jar:1.17.1:test
[DEBUG]          junit:junit:jar:4.13.2:test
[DEBUG]             org.hamcrest:hamcrest-core:jar:1.3:test
[DEBUG]          org.apache.commons:commons-compress:jar:1.21:compile (version managed from 1.21)
[DEBUG]          org.rnorth.duct-tape:duct-tape:jar:1.0.8:test
[DEBUG]             org.jetbrains:annotations:jar:17.0.0:test
[DEBUG]          com.github.docker-java:docker-java-api:jar:3.2.13:test
[DEBUG]          com.github.docker-java:docker-java-transport-zerodep:jar:3.2.13:test
[DEBUG]             com.github.docker-java:docker-java-transport:jar:3.2.13:test
[DEBUG]             net.java.dev.jna:jna:jar:5.8.0:test
[DEBUG]    org.apache.pulsar:pulsar-client-original:jar:2.7.2:compile
[DEBUG]       org.apache.pulsar:pulsar-client-api:jar:2.7.2:compile
[DEBUG]       org.apache.pulsar:pulsar-common:jar:2.7.2:compile
[DEBUG]          org.apache.pulsar:protobuf-shaded:jar:2.1.0-incubating:compile
[DEBUG]          io.netty:netty-handler:jar:4.1.74.Final:compile (version managed from 4.1.60.Final)
[DEBUG]             io.netty:netty-tcnative-classes:jar:2.0.48.Final:compile (version managed from 2.0.48.Final)
[DEBUG]          io.netty:netty-transport-native-epoll:jar:linux-x86_64:4.1.74.Final:compile (version managed from 4.1.60.Final)
[DEBUG]             io.netty:netty-transport-classes-epoll:jar:4.1.74.Final:compile (version managed from 4.1.74.Final)
[DEBUG]          org.apache.bookkeeper:bookkeeper-common-allocator:jar:4.12.0:compile
[DEBUG]          io.airlift:aircompressor:jar:0.16:compile
[DEBUG]          org.apache.bookkeeper:circe-checksum:jar:4.12.0:compile
[DEBUG]          io.netty:netty-tcnative-boringssl-static:jar:2.0.48.Final:compile (version managed from 2.0.36.Final)
[DEBUG]          io.netty:netty-codec-haproxy:jar:4.1.74.Final:compile (version managed from 4.1.60.Final)
[DEBUG]          com.fasterxml.jackson.dataformat:jackson-dataformat-yaml:jar:2.10.0:compile (version managed from 2.11.1)
[DEBUG]       org.apache.pulsar:pulsar-transaction-common:jar:2.7.2:compile
[DEBUG]          com.google.protobuf:protobuf-java-util:jar:3.11.4:compile
[DEBUG]       org.apache.pulsar:bouncy-castle-bc:jar:pkg:2.7.2:compile
[DEBUG]       io.netty:netty-codec-http:jar:4.1.74.Final:compile (version managed from 4.1.60.Final)
[DEBUG]       io.netty:netty-resolver-dns:jar:4.1.74.Final:compile (version managed from 4.1.60.Final)
[DEBUG]          io.netty:netty-codec-dns:jar:4.1.74.Final:compile (version managed from 4.1.74.Final)
[DEBUG]       org.apache.commons:commons-lang3:jar:3.5:compile (version managed from 3.6)
[DEBUG]       org.asynchttpclient:async-http-client:jar:2.12.3:compile (version managed from 2.12.1)
[DEBUG]          org.asynchttpclient:async-http-client-netty-utils:jar:2.12.3:compile
[DEBUG]          org.reactivestreams:reactive-streams:jar:1.0.3:compile (version managed from 1.0.3)
[DEBUG]          com.typesafe.netty:netty-reactive-streams:jar:2.0.4:compile
[DEBUG]          com.sun.activation:jakarta.activation:jar:1.2.2:compile
[DEBUG]       org.slf4j:slf4j-api:jar:1.7.25:compile (version managed from 1.7.25)
[DEBUG]       com.yahoo.datasketches:sketches-core:jar:0.8.3:compile
[DEBUG]          com.yahoo.datasketches:memory:jar:0.8.3:compile
[DEBUG]       com.google.code.gson:gson:jar:2.2.4:compile (version managed from 2.8.6)
[DEBUG]       org.apache.avro:avro:jar:1.9.2:compile (version managed from 1.9.1)
[DEBUG]          com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile (version managed from 2.10.2)
[DEBUG]       org.apache.avro:avro-protobuf:jar:1.9.1:compile
[DEBUG]       com.fasterxml.jackson.module:jackson-module-jsonSchema:jar:2.11.1:compile
[DEBUG]          javax.validation:validation-api:jar:2.0.1.Final:compile (version managed from 1.1.0.Final)
[DEBUG]       net.jcip:jcip-annotations:jar:1.0:compile
[DEBUG]    org.apache.pulsar:pulsar-client-admin-original:jar:2.7.2:compile
[DEBUG]       org.glassfish.jersey.core:jersey-client:jar:2.35:compile (version managed from 2.31)
[DEBUG]       org.glassfish.jersey.media:jersey-media-json-jackson:jar:2.35:compile (version managed from 2.31)
[DEBUG]          org.glassfish.jersey.ext:jersey-entity-filtering:jar:2.35:compile
[DEBUG]          com.fasterxml.jackson.module:jackson-module-jaxb-annotations:jar:2.10.0:compile (version managed from 2.12.2)
[DEBUG]             jakarta.xml.bind:jakarta.xml.bind-api:jar:2.3.2:compile
[DEBUG]             jakarta.activation:jakarta.activation-api:jar:1.2.1:compile
[DEBUG]       org.glassfish.jersey.media:jersey-media-multipart:jar:2.35:compile (version managed from 2.31)
[DEBUG]          org.jvnet.mimepull:mimepull:jar:1.9.13:compile
[DEBUG]       com.fasterxml.jackson.jaxrs:jackson-jaxrs-json-provider:jar:2.10.0:compile (version managed from 2.11.1)
[DEBUG]          com.fasterxml.jackson.jaxrs:jackson-jaxrs-base:jar:2.10.0:compile (version managed from 2.10.0)
[DEBUG]       org.glassfish.jersey.inject:jersey-hk2:jar:2.35:compile (version managed from 2.31)
[DEBUG]          org.glassfish.hk2:hk2-locator:jar:2.6.1:compile (version managed from 2.6.1) (exclusions managed from [jakarta.annotation:jakarta.annotation-api:*:*, org.javassist:javassist:*:*])
[DEBUG]             org.glassfish.hk2.external:aopalliance-repackaged:jar:2.6.1:compile
[DEBUG]             org.glassfish.hk2:hk2-api:jar:2.6.1:compile
[DEBUG]             org.glassfish.hk2:hk2-utils:jar:2.6.1:compile
[DEBUG]          org.javassist:javassist:jar:3.19.0-GA:compile (version managed from 3.25.0-GA)
[DEBUG]       javax.xml.bind:jaxb-api:jar:2.3.0:compile (version managed from 2.3.1)
[DEBUG]       com.sun.activation:javax.activation:jar:1.2.0:runtime
[DEBUG]       org.slf4j:jul-to-slf4j:jar:1.7.25:compile
[DEBUG]       com.google.guava:guava:jar:20.0:compile (version managed from 30.1-jre)
[DEBUG]    javax.servlet:javax.servlet-api:jar:3.1.0:compile
[DEBUG]    javax.ws.rs:javax.ws.rs-api:jar:2.1:compile
[DEBUG]    org.glassfish.jersey.containers:jersey-container-grizzly2-http:jar:2.35:compile
[DEBUG]       org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]       org.glassfish.grizzly:grizzly-http-server:jar:2.4.4:compile (version managed from 2.4.4)
[DEBUG]          org.glassfish.grizzly:grizzly-http:jar:2.4.4:compile
[DEBUG]             org.glassfish.grizzly:grizzly-framework:jar:2.4.4:compile
[DEBUG]       org.glassfish.jersey.core:jersey-common:jar:2.35:compile (version managed from 2.35)
[DEBUG]          org.glassfish.hk2:osgi-resource-locator:jar:1.0.3:compile
[DEBUG]       jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile
[DEBUG]    org.glassfish.jersey.core:jersey-server:jar:2.35:compile (exclusions managed from [org.javassist:javassist:*:*])
[DEBUG]       jakarta.annotation:jakarta.annotation-api:jar:1.3.5:compile
[DEBUG]       jakarta.validation:jakarta.validation-api:jar:2.0.2:compile
[DEBUG]    org.glassfish.jersey.containers:jersey-container-servlet-core:jar:2.35:compile
[DEBUG]    io.netty:netty-resolver:jar:4.1.74.Final:compile
[DEBUG]       io.netty:netty-common:jar:4.1.74.Final:compile (version managed from 4.1.74.Final)
[DEBUG]    io.prometheus:simpleclient_common:jar:0.8.1:compile
[DEBUG]    com.google.api.grpc:proto-google-common-protos:jar:1.12.0:compile
[DEBUG]       com.google.protobuf:protobuf-java:jar:3.19.2:compile (version managed from 3.5.1)
[DEBUG]    io.grpc:grpc-context:jar:1.14.0:compile
[DEBUG]    commons-codec:commons-codec:jar:1.11:compile
[DEBUG]    com.google.errorprone:error_prone_annotations:jar:2.3.4:compile
[DEBUG]    io.prometheus:simpleclient:jar:0.8.1:compile
[DEBUG]    org.eclipse.jetty:jetty-servlet:jar:9.4.45.v20220203:compile
[DEBUG]       org.eclipse.jetty:jetty-security:jar:9.4.45.v20220203:compile
[DEBUG]       org.eclipse.jetty:jetty-util-ajax:jar:9.4.45.v20220203:compile
[DEBUG]    com.squareup.okio:okio:jar:1.6.0:compile
[DEBUG]    io.prometheus:simpleclient_hotspot:jar:0.8.1:compile
[DEBUG]    io.swagger:swagger-annotations:jar:1.5.21:compile
[DEBUG]    io.grpc:grpc-protobuf-lite:jar:1.19.0:compile
[DEBUG]       io.grpc:grpc-core:jar:1.19.0:compile
[DEBUG]          io.opencensus:opencensus-api:jar:0.19.2:compile
[DEBUG]          io.opencensus:opencensus-contrib-grpc-metrics:jar:0.19.2:compile
[DEBUG]       com.google.protobuf:protobuf-lite:jar:3.0.1:compile
[DEBUG]    org.apache.commons:commons-collections4:jar:4.1:compile
[DEBUG]    javax.annotation:javax.annotation-api:jar:1.2:compile
[DEBUG]    org.codehaus.mojo:animal-sniffer-annotations:jar:1.17:compile
[DEBUG]    com.github.ben-manes.caffeine:caffeine:jar:2.6.2:compile
[DEBUG]    io.netty:netty-codec-socks:jar:4.1.74.Final:compile
[DEBUG]       io.netty:netty-buffer:jar:4.1.74.Final:compile (version managed from 4.1.74.Final)
[DEBUG]       io.netty:netty-transport:jar:4.1.74.Final:compile (version managed from 4.1.74.Final)
[DEBUG]       io.netty:netty-codec:jar:4.1.74.Final:compile (version managed from 4.1.74.Final)
[DEBUG]    org.bouncycastle:bcpkix-jdk15to18:jar:1.68:compile
[DEBUG]    org.bouncycastle:bcprov-ext-jdk15to18:jar:1.68:compile
[DEBUG]    org.bouncycastle:bcprov-jdk15to18:jar:1.68:compile
[DEBUG]    org.apache.pinot:pinot-spi:jar:0.11.0-SNAPSHOT:compile
[DEBUG]       commons-configuration:commons-configuration:jar:1.10:compile (version managed from 1.10)
[DEBUG]       commons-io:commons-io:jar:2.11.0:compile (version managed from 2.11.0)
[DEBUG]       commons-lang:commons-lang:jar:2.6:compile (version managed from 2.6)
[DEBUG]       commons-logging:commons-logging:jar:1.2:compile (version managed from 1.2)
[DEBUG]       commons-collections:commons-collections:jar:3.2.2:compile (version managed from 3.2.2)
[DEBUG]       com.google.code.findbugs:jsr305:jar:3.0.0:compile (version managed from 3.0.0)
[DEBUG]       org.apache.logging.log4j:log4j-slf4j-impl:jar:2.17.1:compile (version managed from 2.17.1)
[DEBUG]          org.apache.logging.log4j:log4j-api:jar:2.17.1:compile (version managed from 2.17.1)
[DEBUG]          org.apache.logging.log4j:log4j-core:jar:2.17.1:runtime (version managed from 2.17.1)
[DEBUG]       com.lmax:disruptor:jar:3.3.4:compile (version managed from 3.3.4)
[DEBUG]       org.apache.logging.log4j:log4j-1.2-api:jar:2.17.1:compile (version managed from 2.17.1)
[DEBUG]       joda-time:joda-time:jar:2.10.5:compile (version managed from 2.10.5)
[DEBUG]       com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile (version managed from 2.10.0)
[DEBUG]       org.yaml:snakeyaml:jar:1.30:compile (version managed from 1.30)
[DEBUG]       com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile (version managed from 2.10.0)
[DEBUG]       org.codehaus.groovy:groovy-all:jar:2.4.21:compile (version managed from 2.4.21)
[DEBUG]       org.reflections:reflections:jar:0.9.9:compile (version managed from 0.9.9)
[DEBUG]          com.google.code.findbugs:annotations:jar:2.0.1:compile
[DEBUG]    org.testng:testng:jar:6.11:test
[DEBUG]       com.beust:jcommander:jar:1.64:test
[INFO] 
[INFO] --- maven-clean-plugin:3.1.0:clean (default-clean) @ pinot-pulsar ---
[DEBUG] Dependency collection stats {ConflictMarker.analyzeTime=5290792, ConflictMarker.markTime=95833, ConflictMarker.nodeCount=14, ConflictIdSorter.graphTime=2392667, ConflictIdSorter.topsortTime=35917, ConflictIdSorter.conflictIdCount=12, ConflictIdSorter.conflictIdCycleCount=0, ConflictResolver.totalTime=6302458, ConflictResolver.conflictItemCount=14, DefaultDependencyCollector.collectTime=92019083, DefaultDependencyCollector.transformTime=14171083}
[DEBUG] org.apache.maven.plugins:maven-clean-plugin:jar:3.1.0
[DEBUG]    org.apache.maven:maven-plugin-api:jar:3.0:compile
[DEBUG]       org.apache.maven:maven-model:jar:3.0:compile
[DEBUG]          org.codehaus.plexus:plexus-utils:jar:2.0.4:compile
[DEBUG]       org.apache.maven:maven-artifact:jar:3.0:compile
[DEBUG]       org.sonatype.sisu:sisu-inject-plexus:jar:1.4.2:compile
[DEBUG]          org.codehaus.plexus:plexus-component-annotations:jar:1.7.1:compile (version managed from default)
[DEBUG]          org.codehaus.plexus:plexus-classworlds:jar:2.2.3:compile
[DEBUG]          org.sonatype.sisu:sisu-inject-bean:jar:1.4.2:compile
[DEBUG]             org.sonatype.sisu:sisu-guice:jar:noaop:2.1.7:compile
[DEBUG]    org.apache.maven.shared:maven-shared-utils:jar:3.2.1:compile
[DEBUG]       commons-io:commons-io:jar:2.5:compile
[DEBUG] Created new class realm plugin>org.apache.maven.plugins:maven-clean-plugin:3.1.0
[DEBUG] Importing foreign packages into class realm plugin>org.apache.maven.plugins:maven-clean-plugin:3.1.0
[DEBUG]   Imported:  < project>org.apache.pinot:pinot-pulsar:0.11.0-SNAPSHOT
[DEBUG] Populating class realm plugin>org.apache.maven.plugins:maven-clean-plugin:3.1.0
[DEBUG]   Included: org.apache.maven.plugins:maven-clean-plugin:jar:3.1.0
[DEBUG]   Included: org.codehaus.plexus:plexus-utils:jar:2.0.4
[DEBUG]   Included: org.codehaus.plexus:plexus-component-annotations:jar:1.7.1
[DEBUG]   Included: org.sonatype.sisu:sisu-inject-bean:jar:1.4.2
[DEBUG]   Included: org.sonatype.sisu:sisu-guice:jar:noaop:2.1.7
[DEBUG]   Included: org.apache.maven.shared:maven-shared-utils:jar:3.2.1
[DEBUG]   Included: commons-io:commons-io:jar:2.5
[DEBUG] Configuring mojo org.apache.maven.plugins:maven-clean-plugin:3.1.0:clean from plugin realm ClassRealm[plugin>org.apache.maven.plugins:maven-clean-plugin:3.1.0, parent: jdk.internal.loader.ClassLoaders$AppClassLoader@2c13da15]
[DEBUG] Configuring mojo 'org.apache.maven.plugins:maven-clean-plugin:3.1.0:clean' with basic configurator -->
[DEBUG]   (f) directory = /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target
[DEBUG]   (f) excludeDefaultDirectories = false
[DEBUG]   (f) failOnError = true
[DEBUG]   (f) followSymLinks = false
[DEBUG]   (f) outputDirectory = /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/classes
[DEBUG]   (f) reportDirectory = /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/classes
[DEBUG]   (f) retryOnError = true
[DEBUG]   (f) skip = false
[DEBUG]   (f) testOutputDirectory = /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/test-classes
[DEBUG] -- end configuration --
[INFO] Deleting /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target
[INFO] Deleting file /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/checkstyle-checker.xml
[INFO] Deleting file /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/.plxarc
[INFO] Deleting file /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/checkstyle-suppressions.xml
[INFO] Deleting file /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/maven-status/maven-compiler-plugin/compile/default-compile/createdFiles.lst
[INFO] Deleting file /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/maven-status/maven-compiler-plugin/compile/default-compile/inputFiles.lst
[INFO] Deleting directory /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/maven-status/maven-compiler-plugin/compile/default-compile
[INFO] Deleting directory /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/maven-status/maven-compiler-plugin/compile
[INFO] Deleting directory /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/maven-status/maven-compiler-plugin
[INFO] Deleting directory /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/maven-status
[INFO] Deleting file /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/checkstyle-result.xml
[INFO] Deleting file /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/checkstyle-cachefile
[INFO] Deleting file /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/classes/META-INF/NOTICE
[INFO] Deleting file /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/classes/META-INF/DEPENDENCIES
[INFO] Deleting file /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/classes/META-INF/LICENSE
[INFO] Deleting directory /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/classes/META-INF
[INFO] Deleting file /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/classes/org.codehaus.plexus.compiler.javac.JavacCompiler8175930637545898046arguments
[INFO] Deleting file /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/classes/javac.sh
[INFO] Deleting directory /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/classes
[INFO] Deleting file /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/maven-shared-archive-resources/META-INF/NOTICE
[INFO] Deleting file /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/maven-shared-archive-resources/META-INF/DEPENDENCIES
[INFO] Deleting file /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/maven-shared-archive-resources/META-INF/LICENSE
[INFO] Deleting directory /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/maven-shared-archive-resources/META-INF
[INFO] Deleting directory /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/maven-shared-archive-resources
[INFO] Deleting directory /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/generated-sources/annotations
[INFO] Deleting directory /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/generated-sources
[INFO] Deleting directory /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target
[DEBUG] Skipping non-existing directory /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/classes
[DEBUG] Skipping non-existing directory /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/test-classes
[DEBUG] Skipping non-existing directory /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/classes
[INFO] 
[INFO] --- maven-checkstyle-plugin:3.1.2:check (checkstyle) @ pinot-pulsar ---
[DEBUG] Using mirror maven-default-http-blocker (http://0.0.0.0/) for codehaus.snapshots (http://snapshots.repository.codehaus.org).
[DEBUG] Using mirror maven-default-http-blocker (http://0.0.0.0/) for apache.snapshots (http://people.apache.org/repo/m2-snapshot-repository).
[DEBUG] Using mirror maven-default-http-blocker (http://0.0.0.0/) for apache-snapshots (http://people.apache.org/maven-snapshot-repository).
[DEBUG] Using mirror maven-default-http-blocker (http://0.0.0.0/) for codehaus-snapshots (http://snapshots.repository.codehaus.org).
[DEBUG] Using mirror maven-default-http-blocker (http://0.0.0.0/) for apache.snapshots (http://people.apache.org/maven-snapshot-repository).
[DEBUG] Using mirror maven-default-http-blocker (http://0.0.0.0/) for snapshots (http://snapshots.maven.codehaus.org/maven2).
[DEBUG] Using mirror maven-default-http-blocker (http://0.0.0.0/) for central (http://repo1.maven.org/maven2).
[DEBUG] Dependency collection stats {ConflictMarker.analyzeTime=1015917, ConflictMarker.markTime=178625, ConflictMarker.nodeCount=285, ConflictIdSorter.graphTime=507333, ConflictIdSorter.topsortTime=87375, ConflictIdSorter.conflictIdCount=81, ConflictIdSorter.conflictIdCycleCount=0, ConflictResolver.totalTime=5088125, ConflictResolver.conflictItemCount=186, DefaultDependencyCollector.collectTime=536474375, DefaultDependencyCollector.transformTime=6953166}
[DEBUG] org.apache.maven.plugins:maven-checkstyle-plugin:jar:3.1.2
[DEBUG]    com.puppycrawl.tools:checkstyle:jar:8.45.1:runtime
[DEBUG]       info.picocli:picocli:jar:4.6.1:runtime
[DEBUG]       antlr:antlr:jar:2.7.7:compile
[DEBUG]       org.antlr:antlr4-runtime:jar:4.9.2:runtime
[DEBUG]       commons-beanutils:commons-beanutils:jar:1.9.4:compile
[DEBUG]          commons-logging:commons-logging:jar:1.2:compile
[DEBUG]       com.google.guava:guava:jar:30.1.1-jre:runtime
[DEBUG]          com.google.guava:failureaccess:jar:1.0.1:runtime
[DEBUG]          com.google.guava:listenablefuture:jar:9999.0-empty-to-avoid-conflict-with-guava:runtime
[DEBUG]          com.google.code.findbugs:jsr305:jar:3.0.2:compile
[DEBUG]          org.checkerframework:checker-qual:jar:3.8.0:runtime
[DEBUG]          com.google.errorprone:error_prone_annotations:jar:2.5.1:runtime
[DEBUG]          com.google.j2objc:j2objc-annotations:jar:1.3:runtime
[DEBUG]       org.reflections:reflections:jar:0.9.12:runtime
[DEBUG]          org.javassist:javassist:jar:3.26.0-GA:runtime
[DEBUG]       net.sf.saxon:Saxon-HE:jar:10.5:runtime
[DEBUG]    org.apache.maven:maven-artifact:jar:3.0:compile
[DEBUG]    org.apache.maven:maven-core:jar:3.0:compile
[DEBUG]       org.apache.maven:maven-settings:jar:3.0:compile
[DEBUG]       org.apache.maven:maven-settings-builder:jar:3.0:compile
[DEBUG]       org.apache.maven:maven-repository-metadata:jar:3.0:compile
[DEBUG]       org.apache.maven:maven-model-builder:jar:3.0:compile
[DEBUG]       org.apache.maven:maven-aether-provider:jar:3.0:runtime
[DEBUG]       org.sonatype.aether:aether-impl:jar:1.7:compile
[DEBUG]          org.sonatype.aether:aether-spi:jar:1.7:compile
[DEBUG]       org.sonatype.aether:aether-api:jar:1.7:compile
[DEBUG]       org.sonatype.aether:aether-util:jar:1.7:compile
[DEBUG]       org.sonatype.sisu:sisu-inject-plexus:jar:1.4.2:compile
[DEBUG]          org.sonatype.sisu:sisu-inject-bean:jar:1.4.2:compile
[DEBUG]             org.sonatype.sisu:sisu-guice:jar:noaop:2.1.7:compile
[DEBUG]       org.codehaus.plexus:plexus-classworlds:jar:2.2.3:compile
[DEBUG]       org.sonatype.plexus:plexus-sec-dispatcher:jar:1.3:compile
[DEBUG]          org.sonatype.plexus:plexus-cipher:jar:1.4:compile
[DEBUG]    org.apache.maven:maven-model:jar:3.0:compile
[DEBUG]    org.apache.maven:maven-plugin-api:jar:3.0:compile
[DEBUG]    org.apache.maven.reporting:maven-reporting-api:jar:3.0:compile
[DEBUG]    org.apache.maven.reporting:maven-reporting-impl:jar:2.3:compile
[DEBUG]       org.apache.maven.shared:maven-shared-utils:jar:0.6:compile
[DEBUG]       org.apache.maven.doxia:doxia-core:jar:1.2:compile
[DEBUG]          xerces:xercesImpl:jar:2.9.1:compile
[DEBUG]             xml-apis:xml-apis:jar:1.3.04:compile
[DEBUG]          org.apache.httpcomponents:httpclient:jar:4.0.2:compile
[DEBUG]             org.apache.httpcomponents:httpcore:jar:4.0.1:compile
[DEBUG]             commons-codec:commons-codec:jar:1.3:compile
[DEBUG]       commons-validator:commons-validator:jar:1.3.1:compile
[DEBUG]          commons-digester:commons-digester:jar:1.6:compile
[DEBUG]    org.apache.maven.doxia:doxia-sink-api:jar:1.4:compile
[DEBUG]       org.apache.maven.doxia:doxia-logging-api:jar:1.4:compile
[DEBUG]    org.apache.maven.doxia:doxia-decoration-model:jar:1.4:compile
[DEBUG]    org.apache.maven.doxia:doxia-site-renderer:jar:1.4:compile
[DEBUG]       org.apache.maven.doxia:doxia-module-xhtml:jar:1.4:compile
[DEBUG]       org.apache.maven.doxia:doxia-module-fml:jar:1.4:compile
[DEBUG]       org.codehaus.plexus:plexus-i18n:jar:1.0-beta-7:compile
[DEBUG]       org.apache.velocity:velocity-tools:jar:2.0:compile
[DEBUG]          commons-chain:commons-chain:jar:1.1:compile
[DEBUG]          dom4j:dom4j:jar:1.1:compile
[DEBUG]          oro:oro:jar:2.0.8:compile
[DEBUG]          sslext:sslext:jar:1.2-0:compile
[DEBUG]          org.apache.struts:struts-core:jar:1.3.8:compile
[DEBUG]          org.apache.struts:struts-taglib:jar:1.3.8:compile
[DEBUG]          org.apache.struts:struts-tiles:jar:1.3.8:compile
[DEBUG]       commons-collections:commons-collections:jar:3.2.1:compile
[DEBUG]    org.apache.maven.doxia:doxia-integration-tools:jar:1.6:compile
[DEBUG]       commons-io:commons-io:jar:1.4:compile
[DEBUG]       org.codehaus.plexus:plexus-container-default:jar:1.0-alpha-9:compile
[DEBUG]          junit:junit:jar:3.8.1:compile
[DEBUG]          classworlds:classworlds:jar:1.1-alpha-2:compile
[DEBUG]    org.codehaus.plexus:plexus-component-annotations:jar:2.0.0:compile
[DEBUG]    org.codehaus.plexus:plexus-resources:jar:1.1.0:compile
[DEBUG]    org.codehaus.plexus:plexus-utils:jar:3.3.0:compile
[DEBUG]    org.codehaus.plexus:plexus-interpolation:jar:1.26:compile
[DEBUG]    org.codehaus.plexus:plexus-velocity:jar:1.2:compile
[DEBUG]    org.apache.velocity:velocity:jar:1.7:compile
[DEBUG]       commons-lang:commons-lang:jar:2.4:compile
[DEBUG]    javax.xml.bind:jaxb-api:jar:2.3.1:compile
[DEBUG]       javax.activation:javax.activation-api:jar:1.2.0:compile
[DEBUG] Created new class realm plugin>org.apache.maven.plugins:maven-checkstyle-plugin:3.1.2
[DEBUG] Importing foreign packages into class realm plugin>org.apache.maven.plugins:maven-checkstyle-plugin:3.1.2
[DEBUG]   Imported:  < project>org.apache.pinot:pinot-pulsar:0.11.0-SNAPSHOT
[DEBUG] Populating class realm plugin>org.apache.maven.plugins:maven-checkstyle-plugin:3.1.2
[DEBUG]   Included: org.apache.maven.plugins:maven-checkstyle-plugin:jar:3.1.2
[DEBUG]   Included: com.puppycrawl.tools:checkstyle:jar:8.45.1
[DEBUG]   Included: info.picocli:picocli:jar:4.6.1
[DEBUG]   Included: antlr:antlr:jar:2.7.7
[DEBUG]   Included: org.antlr:antlr4-runtime:jar:4.9.2
[DEBUG]   Included: commons-beanutils:commons-beanutils:jar:1.9.4
[DEBUG]   Included: commons-logging:commons-logging:jar:1.2
[DEBUG]   Included: com.google.guava:guava:jar:30.1.1-jre
[DEBUG]   Included: com.google.guava:failureaccess:jar:1.0.1
[DEBUG]   Included: com.google.guava:listenablefuture:jar:9999.0-empty-to-avoid-conflict-with-guava
[DEBUG]   Included: com.google.code.findbugs:jsr305:jar:3.0.2
[DEBUG]   Included: org.checkerframework:checker-qual:jar:3.8.0
[DEBUG]   Included: com.google.errorprone:error_prone_annotations:jar:2.5.1
[DEBUG]   Included: com.google.j2objc:j2objc-annotations:jar:1.3
[DEBUG]   Included: org.reflections:reflections:jar:0.9.12
[DEBUG]   Included: org.javassist:javassist:jar:3.26.0-GA
[DEBUG]   Included: net.sf.saxon:Saxon-HE:jar:10.5
[DEBUG]   Included: org.sonatype.aether:aether-util:jar:1.7
[DEBUG]   Included: org.sonatype.sisu:sisu-inject-bean:jar:1.4.2
[DEBUG]   Included: org.sonatype.sisu:sisu-guice:jar:noaop:2.1.7
[DEBUG]   Included: org.sonatype.plexus:plexus-sec-dispatcher:jar:1.3
[DEBUG]   Included: org.sonatype.plexus:plexus-cipher:jar:1.4
[DEBUG]   Included: org.apache.maven.reporting:maven-reporting-api:jar:3.0
[DEBUG]   Included: org.apache.maven.reporting:maven-reporting-impl:jar:2.3
[DEBUG]   Included: org.apache.maven.shared:maven-shared-utils:jar:0.6
[DEBUG]   Included: org.apache.maven.doxia:doxia-core:jar:1.2
[DEBUG]   Included: xerces:xercesImpl:jar:2.9.1
[DEBUG]   Included: xml-apis:xml-apis:jar:1.3.04
[DEBUG]   Included: org.apache.httpcomponents:httpclient:jar:4.0.2
[DEBUG]   Included: org.apache.httpcomponents:httpcore:jar:4.0.1
[DEBUG]   Included: commons-codec:commons-codec:jar:1.3
[DEBUG]   Included: commons-validator:commons-validator:jar:1.3.1
[DEBUG]   Included: commons-digester:commons-digester:jar:1.6
[DEBUG]   Included: org.apache.maven.doxia:doxia-sink-api:jar:1.4
[DEBUG]   Included: org.apache.maven.doxia:doxia-logging-api:jar:1.4
[DEBUG]   Included: org.apache.maven.doxia:doxia-decoration-model:jar:1.4
[DEBUG]   Included: org.apache.maven.doxia:doxia-site-renderer:jar:1.4
[DEBUG]   Included: org.apache.maven.doxia:doxia-module-xhtml:jar:1.4
[DEBUG]   Included: org.apache.maven.doxia:doxia-module-fml:jar:1.4
[DEBUG]   Included: org.codehaus.plexus:plexus-i18n:jar:1.0-beta-7
[DEBUG]   Included: org.apache.velocity:velocity-tools:jar:2.0
[DEBUG]   Included: commons-chain:commons-chain:jar:1.1
[DEBUG]   Included: dom4j:dom4j:jar:1.1
[DEBUG]   Included: oro:oro:jar:2.0.8
[DEBUG]   Included: sslext:sslext:jar:1.2-0
[DEBUG]   Included: org.apache.struts:struts-core:jar:1.3.8
[DEBUG]   Included: org.apache.struts:struts-taglib:jar:1.3.8
[DEBUG]   Included: org.apache.struts:struts-tiles:jar:1.3.8
[DEBUG]   Included: commons-collections:commons-collections:jar:3.2.1
[DEBUG]   Included: org.apache.maven.doxia:doxia-integration-tools:jar:1.6
[DEBUG]   Included: commons-io:commons-io:jar:1.4
[DEBUG]   Included: junit:junit:jar:3.8.1
[DEBUG]   Included: org.codehaus.plexus:plexus-component-annotations:jar:2.0.0
[DEBUG]   Included: org.codehaus.plexus:plexus-resources:jar:1.1.0
[DEBUG]   Included: org.codehaus.plexus:plexus-utils:jar:3.3.0
[DEBUG]   Included: org.codehaus.plexus:plexus-interpolation:jar:1.26
[DEBUG]   Included: org.codehaus.plexus:plexus-velocity:jar:1.2
[DEBUG]   Included: org.apache.velocity:velocity:jar:1.7
[DEBUG]   Included: commons-lang:commons-lang:jar:2.4
[DEBUG]   Included: javax.xml.bind:jaxb-api:jar:2.3.1
[DEBUG]   Included: javax.activation:javax.activation-api:jar:1.2.0
[DEBUG] Configuring mojo org.apache.maven.plugins:maven-checkstyle-plugin:3.1.2:check from plugin realm ClassRealm[plugin>org.apache.maven.plugins:maven-checkstyle-plugin:3.1.2, parent: jdk.internal.loader.ClassLoaders$AppClassLoader@2c13da15]
[DEBUG] Configuring mojo 'org.apache.maven.plugins:maven-checkstyle-plugin:3.1.2:check' with basic configurator -->
[DEBUG]   (f) cacheFile = /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/checkstyle-cachefile
[DEBUG]   (f) checkstyleRulesHeader = <?xml version="1.0"?>
<!DOCTYPE module PUBLIC "-//Checkstyle//DTD Checkstyle Configuration 1.3//EN"
        "https://checkstyle.org/dtds/configuration_1_3.dtd">

[DEBUG]   (f) configLocation = /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/../../../config/checkstyle.xml
[DEBUG]   (f) consoleOutput = false
[DEBUG]   (f) encoding = UTF-8
[DEBUG]   (f) failOnViolation = true
[DEBUG]   (f) failsOnError = false
[DEBUG]   (f) headerLocation = LICENSE.txt
[DEBUG]   (f) includeResources = true
[DEBUG]   (f) includeTestResources = true
[DEBUG]   (f) includeTestSourceDirectory = true
[DEBUG]   (f) includes = **\/*.java
[DEBUG]   (f) logViolationCountToConsole = true
[DEBUG]   (f) logViolationsToConsole = true
[DEBUG]   (f) maxAllowedViolations = 0
[DEBUG]   (f) omitIgnoredModules = false
[DEBUG]   (f) outputFile = /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/checkstyle-result.xml
[DEBUG]   (f) outputFileFormat = xml
[DEBUG]   (f) plugin = Component Descriptor: role: 'org.apache.maven.plugin.Mojo', implementation: 'org.apache.maven.plugins.checkstyle.CheckstyleViolationCheckMojo', role hint: 'org.apache.maven.plugins:maven-checkstyle-plugin:3.1.2:check'
role: 'org.apache.maven.plugin.Mojo', implementation: 'org.apache.maven.plugins.checkstyle.CheckstyleReport', role hint: 'org.apache.maven.plugins:maven-checkstyle-plugin:3.1.2:checkstyle'
role: 'org.apache.maven.plugin.Mojo', implementation: 'org.apache.maven.plugins.checkstyle.CheckstyleAggregateReport', role hint: 'org.apache.maven.plugins:maven-checkstyle-plugin:3.1.2:checkstyle-aggregate'
role: 'org.apache.maven.plugin.Mojo', implementation: 'org.apache.maven.plugins.checkstyle.HelpMojo', role hint: 'org.apache.maven.plugins:maven-checkstyle-plugin:3.1.2:help'
---
[DEBUG]   (f) project = MavenProject: org.apache.pinot:pinot-pulsar:0.11.0-SNAPSHOT @ /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/pom.xml
[DEBUG]   (f) propertyExpansion = config_loc=/Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/../../../config
[DEBUG]   (f) resourceIncludes = **/*.properties
[DEBUG]   (f) resources = [Resource {targetPath: null, filtering: false, FileSet {directory: /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/src/main/resources, PatternSet [includes: {}, excludes: {}]}}]
[DEBUG]   (f) rulesFiles = /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/checkstyle-rules.xml
[DEBUG]   (f) skip = false
[DEBUG]   (f) skipExec = false
[DEBUG]   (f) suppressionsFileExpression = checkstyle.suppressions.file
[DEBUG]   (f) suppressionsLocation = /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/../../../config/suppressions.xml
[DEBUG]   (f) testResources = [Resource {targetPath: null, filtering: false, FileSet {directory: /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/src/test/resources, PatternSet [includes: {}, excludes: {}]}}]
[DEBUG]   (f) violationSeverity = warning
[DEBUG] -- end configuration --
[DEBUG] executeCheckstyle start headerLocation : LICENSE.txt
[DEBUG] Added 11 source files found in '/Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/src/main/java'.
[DEBUG] Added 1 test source files found in '/Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/src/test/java'.
[DEBUG] The resources directory '/Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/src/main/resources' does not exist or is not a directory.
[DEBUG] The resources directory '/Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/src/test/resources' does not exist or is not a directory.
[DEBUG] Added 12 files to process.
[DEBUG] The resource '/Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/../../../config/suppressions.xml' was found as /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/../../../config/suppressions.xml.
[DEBUG] request.getConfigLocation() /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/../../../config/checkstyle.xml
[DEBUG] The resource '/Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/../../../config/checkstyle.xml' was found as /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/../../../config/checkstyle.xml.
[DEBUG] headerLocation LICENSE.txt
[DEBUG] The resource 'LICENSE.txt' was not found with resourceLoader org.codehaus.plexus.resource.loader.FileResourceLoader.
[DEBUG] URLResourceLoader: No valid URL 'LICENSE.txt'
[DEBUG] URLResourceLoader: No valid URL 'LICENSE.txt'
[DEBUG] The resource 'LICENSE.txt' was not found with resourceLoader org.codehaus.plexus.resource.loader.URLResourceLoader.
[DEBUG] JarResourceLoader : trying to load "jar:file:/Users/.../.m2/repository/com/puppycrawl/tools/checkstyle/8.45.1/checkstyle-8.45.1.jar"
[DEBUG] The resource 'LICENSE.txt' was not found with resourceLoader org.codehaus.plexus.resource.loader.JarResourceLoader.
[DEBUG] Unable to process header location: LICENSE.txt
[DEBUG] Checkstyle will throw exception if ${checkstyle.header.file} is used
[DEBUG] The resource '/Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/../../../config/suppressions.xml' was found as /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/../../../config/suppressions.xml.
[INFO] You have 0 Checkstyle violations.
[INFO] 
[INFO] --- buildnumber-maven-plugin:1.3:create (default) @ pinot-pulsar ---
[DEBUG] Using mirror maven-default-http-blocker (http://0.0.0.0/) for apache.snapshots (http://cvs.apache.org/maven-snapshot-repository).
[DEBUG] Using mirror maven-default-http-blocker (http://0.0.0.0/) for apache.snapshots (http://repository.apache.org/content/repositories/snapshots/).
[DEBUG] Using mirror maven-default-http-blocker (http://0.0.0.0/) for antlr-snapshot (http://antlr.org/antlr-snapshot).
[DEBUG] Dependency collection stats {ConflictMarker.analyzeTime=1920417, ConflictMarker.markTime=174958, ConflictMarker.nodeCount=133, ConflictIdSorter.graphTime=2484708, ConflictIdSorter.topsortTime=72333, ConflictIdSorter.conflictIdCount=48, ConflictIdSorter.conflictIdCycleCount=0, ConflictResolver.totalTime=6140875, ConflictResolver.conflictItemCount=122, DefaultDependencyCollector.collectTime=326459167, DefaultDependencyCollector.transformTime=10842958}
[DEBUG] org.codehaus.mojo:buildnumber-maven-plugin:jar:1.3
[DEBUG]    org.apache.maven:maven-project:jar:2.0.6:compile
[DEBUG]       org.apache.maven:maven-profile:jar:2.0.6:compile
[DEBUG]       org.apache.maven:maven-model:jar:2.0.6:compile
[DEBUG]       org.apache.maven:maven-artifact-manager:jar:2.0.6:compile
[DEBUG]       org.apache.maven:maven-plugin-registry:jar:2.0.6:compile
[DEBUG]       org.apache.maven:maven-artifact:jar:2.0.6:compile
[DEBUG]    org.apache.maven:maven-settings:jar:2.0.6:compile
[DEBUG]    org.apache.maven:maven-core:jar:2.0.6:compile
[DEBUG]       org.apache.maven:maven-plugin-parameter-documenter:jar:2.0.6:compile
[DEBUG]       org.apache.maven.reporting:maven-reporting-api:jar:2.0.6:compile
[DEBUG]          org.apache.maven.doxia:doxia-sink-api:jar:1.0-alpha-7:compile
[DEBUG]       org.apache.maven:maven-repository-metadata:jar:2.0.6:compile
[DEBUG]       org.apache.maven:maven-error-diagnostics:jar:2.0.6:compile
[DEBUG]       commons-cli:commons-cli:jar:1.0:compile
[DEBUG]       org.apache.maven:maven-plugin-descriptor:jar:2.0.6:compile
[DEBUG]       org.codehaus.plexus:plexus-interactivity-api:jar:1.0-alpha-4:compile
[DEBUG]       org.apache.maven:maven-monitor:jar:2.0.6:compile
[DEBUG]       classworlds:classworlds:jar:1.1:compile
[DEBUG]    org.apache.maven:maven-plugin-api:jar:2.0.6:compile
[DEBUG]    org.codehaus.plexus:plexus-container-default:jar:1.0-alpha-9-stable-1:compile
[DEBUG]       junit:junit:jar:4.11:test (scope managed from default) (version managed from default)
[DEBUG]          org.hamcrest:hamcrest-core:jar:1.3:test
[DEBUG]    org.apache.maven.scm:maven-scm-api:jar:1.9:compile
[DEBUG]    org.apache.maven.scm:maven-scm-manager-plexus:jar:1.9:compile
[DEBUG]    org.apache.maven.scm:maven-scm-provider-bazaar:jar:1.9:compile
[DEBUG]       regexp:regexp:jar:1.3:compile
[DEBUG]    org.apache.maven.scm:maven-scm-provider-svnexe:jar:1.9:compile
[DEBUG]       commons-lang:commons-lang:jar:2.6:compile
[DEBUG]    org.apache.maven.scm:maven-scm-provider-gitexe:jar:1.9:compile
[DEBUG]       commons-io:commons-io:jar:2.2:compile
[DEBUG]       org.apache.maven.scm:maven-scm-provider-git-commons:jar:1.9:compile
[DEBUG]    org.apache.maven.scm:maven-scm-provider-svn-commons:jar:1.9:compile
[DEBUG]    org.apache.maven.scm:maven-scm-provider-cvsexe:jar:1.9:compile
[DEBUG]       org.apache.maven.scm:maven-scm-provider-cvs-commons:jar:1.9:compile
[DEBUG]    org.apache.maven.scm:maven-scm-provider-starteam:jar:1.9:compile
[DEBUG]    org.apache.maven.scm:maven-scm-provider-clearcase:jar:1.9:compile
[DEBUG]    org.apache.maven.scm:maven-scm-provider-perforce:jar:1.9:compile
[DEBUG]    org.apache.maven.scm:maven-scm-provider-hg:jar:1.9:compile
[DEBUG]    com.google.code.maven-scm-provider-svnjava:maven-scm-provider-svnjava:jar:1.13:compile
[DEBUG]    org.codehaus.plexus:plexus-utils:jar:2.0.5:compile
[DEBUG]    org.tmatesoft.svnkit:svnkit:jar:1.3.5:compile
[DEBUG]       org.tmatesoft.svnkit:trilead-ssh2:jar:build213-svnkit-1.3-patch:compile
[DEBUG]       org.tmatesoft.sqljet:sqljet:jar:1.0.4:compile
[DEBUG]          org.antlr:antlr-runtime:jar:3.1.3:compile
[DEBUG]             org.antlr:stringtemplate:jar:3.2:compile
[DEBUG]                antlr:antlr:jar:2.7.7:compile
[DEBUG]    net.java.dev.jna:jna:jar:3.2.2:compile
[DEBUG] Created new class realm plugin>org.codehaus.mojo:buildnumber-maven-plugin:1.3
[DEBUG] Importing foreign packages into class realm plugin>org.codehaus.mojo:buildnumber-maven-plugin:1.3
[DEBUG]   Imported:  < project>org.apache.pinot:pinot-pulsar:0.11.0-SNAPSHOT
[DEBUG] Populating class realm plugin>org.codehaus.mojo:buildnumber-maven-plugin:1.3
[DEBUG]   Included: org.codehaus.mojo:buildnumber-maven-plugin:jar:1.3
[DEBUG]   Included: org.apache.maven.reporting:maven-reporting-api:jar:2.0.6
[DEBUG]   Included: org.apache.maven.doxia:doxia-sink-api:jar:1.0-alpha-7
[DEBUG]   Included: commons-cli:commons-cli:jar:1.0
[DEBUG]   Included: org.codehaus.plexus:plexus-interactivity-api:jar:1.0-alpha-4
[DEBUG]   Included: org.apache.maven.scm:maven-scm-api:jar:1.9
[DEBUG]   Included: org.apache.maven.scm:maven-scm-manager-plexus:jar:1.9
[DEBUG]   Included: org.apache.maven.scm:maven-scm-provider-bazaar:jar:1.9
[DEBUG]   Included: regexp:regexp:jar:1.3
[DEBUG]   Included: org.apache.maven.scm:maven-scm-provider-svnexe:jar:1.9
[DEBUG]   Included: commons-lang:commons-lang:jar:2.6
[DEBUG]   Included: org.apache.maven.scm:maven-scm-provider-gitexe:jar:1.9
[DEBUG]   Included: commons-io:commons-io:jar:2.2
[DEBUG]   Included: org.apache.maven.scm:maven-scm-provider-git-commons:jar:1.9
[DEBUG]   Included: org.apache.maven.scm:maven-scm-provider-svn-commons:jar:1.9
[DEBUG]   Included: org.apache.maven.scm:maven-scm-provider-cvsexe:jar:1.9
[DEBUG]   Included: org.apache.maven.scm:maven-scm-provider-cvs-commons:jar:1.9
[DEBUG]   Included: org.apache.maven.scm:maven-scm-provider-starteam:jar:1.9
[DEBUG]   Included: org.apache.maven.scm:maven-scm-provider-clearcase:jar:1.9
[DEBUG]   Included: org.apache.maven.scm:maven-scm-provider-perforce:jar:1.9
[DEBUG]   Included: org.apache.maven.scm:maven-scm-provider-hg:jar:1.9
[DEBUG]   Included: com.google.code.maven-scm-provider-svnjava:maven-scm-provider-svnjava:jar:1.13
[DEBUG]   Included: org.codehaus.plexus:plexus-utils:jar:2.0.5
[DEBUG]   Included: org.tmatesoft.svnkit:svnkit:jar:1.3.5
[DEBUG]   Included: org.tmatesoft.svnkit:trilead-ssh2:jar:build213-svnkit-1.3-patch
[DEBUG]   Included: org.tmatesoft.sqljet:sqljet:jar:1.0.4
[DEBUG]   Included: org.antlr:antlr-runtime:jar:3.1.3
[DEBUG]   Included: org.antlr:stringtemplate:jar:3.2
[DEBUG]   Included: antlr:antlr:jar:2.7.7
[DEBUG]   Included: net.java.dev.jna:jna:jar:3.2.2
[DEBUG] Configuring mojo org.codehaus.mojo:buildnumber-maven-plugin:1.3:create from plugin realm ClassRealm[plugin>org.codehaus.mojo:buildnumber-maven-plugin:1.3, parent: jdk.internal.loader.ClassLoaders$AppClassLoader@2c13da15]
[DEBUG] Configuring mojo 'org.codehaus.mojo:buildnumber-maven-plugin:1.3:create' with basic configurator -->
[DEBUG]   (s) buildNumberPropertiesFileLocation = /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/buildNumber.properties
[DEBUG]   (f) buildNumberPropertyName = buildNumber
[DEBUG]   (s) doCheck = false
[DEBUG]   (s) doUpdate = false
[DEBUG]   (f) getRevisionOnlyOnce = false
[DEBUG]   (f) project = MavenProject: org.apache.pinot:pinot-pulsar:0.11.0-SNAPSHOT @ /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/pom.xml
[DEBUG]   (f) reactorProjects = [MavenProject: org.apache.pinot:pinot-pulsar:0.11.0-SNAPSHOT @ /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/pom.xml]
[DEBUG]   (f) readUrlScm = scm:git:https://gitbox.apache.org/repos/asf/maven-apache-parent.git/pinot/pinot-plugins/pinot-stream-ingestion/pinot-pulsar
[DEBUG]   (f) scmBranchPropertyName = scmBranch
[DEBUG]   (s) scmDirectory = /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar
[DEBUG]   (f) session = org.apache.maven.execution.MavenSession@53d6e959
[DEBUG]   (f) skip = false
[DEBUG]   (f) timestampPropertyName = timestamp
[DEBUG]   (s) urlScm = scm:git:git@github.com:apache/pinot.git/pinot-plugins/pinot-stream-ingestion/pinot-pulsar
[DEBUG]   (f) useLastCommittedRevision = false
[DEBUG] -- end configuration --
[DEBUG] Checking for local modifications: skipped.
[DEBUG] Updating project files from SCM: skipped.
[INFO] Executing: /bin/sh -c cd /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar && git rev-parse --verify HEAD
[INFO] Working directory: /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar
[DEBUG] consume line 7dce7cb1e0f149429778c955d372aac018725aca
[INFO] Storing buildNumber: 7dce7cb1e0f149429778c955d372aac018725aca at timestamp: 1656386998585
[INFO] Storing buildScmBranch: master
[INFO] 
[INFO] --- maven-enforcer-plugin:3.0.0-M2:enforce (enforce-dependency-convergence) @ pinot-pulsar ---
[DEBUG] Dependency collection stats {ConflictMarker.analyzeTime=844333, ConflictMarker.markTime=90208, ConflictMarker.nodeCount=101, ConflictIdSorter.graphTime=164166, ConflictIdSorter.topsortTime=197542, ConflictIdSorter.conflictIdCount=39, ConflictIdSorter.conflictIdCycleCount=0, ConflictResolver.totalTime=4855709, ConflictResolver.conflictItemCount=95, DefaultDependencyCollector.collectTime=106516167, DefaultDependencyCollector.transformTime=6917875}
[DEBUG] org.apache.maven.plugins:maven-enforcer-plugin:jar:3.0.0-M2
[DEBUG]    org.apache.maven:maven-artifact:jar:3.0:compile
[DEBUG]    org.apache.maven:maven-plugin-api:jar:3.0:compile
[DEBUG]       org.apache.maven:maven-model:jar:3.0:compile
[DEBUG]       org.sonatype.sisu:sisu-inject-plexus:jar:1.4.2:compile
[DEBUG]          org.sonatype.sisu:sisu-inject-bean:jar:1.4.2:compile
[DEBUG]             org.sonatype.sisu:sisu-guice:jar:noaop:2.1.7:compile
[DEBUG]    org.apache.maven:maven-core:jar:3.0:compile
[DEBUG]       org.apache.maven:maven-settings:jar:3.0:compile
[DEBUG]       org.apache.maven:maven-settings-builder:jar:3.0:compile
[DEBUG]       org.apache.maven:maven-repository-metadata:jar:3.0:compile
[DEBUG]       org.apache.maven:maven-model-builder:jar:3.0:compile
[DEBUG]       org.apache.maven:maven-aether-provider:jar:3.0:runtime
[DEBUG]       org.sonatype.aether:aether-impl:jar:1.7:compile
[DEBUG]          org.sonatype.aether:aether-spi:jar:1.7:compile
[DEBUG]       org.sonatype.aether:aether-api:jar:1.7:compile
[DEBUG]       org.sonatype.aether:aether-util:jar:1.7:compile
[DEBUG]       org.codehaus.plexus:plexus-interpolation:jar:1.14:compile
[DEBUG]       org.codehaus.plexus:plexus-classworlds:jar:2.2.3:compile
[DEBUG]       org.codehaus.plexus:plexus-component-annotations:jar:1.7.1:compile (version managed from default)
[DEBUG]       org.sonatype.plexus:plexus-sec-dispatcher:jar:1.3:compile
[DEBUG]          org.sonatype.plexus:plexus-cipher:jar:1.4:compile
[DEBUG]    org.codehaus.plexus:plexus-utils:jar:3.1.0:compile
[DEBUG]    org.apache.maven.enforcer:enforcer-api:jar:3.0.0-M2:compile
[DEBUG]       org.codehaus.plexus:plexus-container-default:jar:1.0-alpha-9:compile
[DEBUG]          junit:junit:jar:4.11:compile (version managed from default)
[DEBUG]             org.hamcrest:hamcrest-core:jar:1.3:compile
[DEBUG]          classworlds:classworlds:jar:1.1-alpha-2:compile
[DEBUG]    org.apache.maven.enforcer:enforcer-rules:jar:3.0.0-M2:compile
[DEBUG]       org.apache.maven.shared:maven-common-artifact-filters:jar:3.0.1:compile (version managed from default)
[DEBUG]          org.apache.maven.shared:maven-shared-utils:jar:3.1.0:compile
[DEBUG]             commons-io:commons-io:jar:2.5:compile
[DEBUG]       org.apache.commons:commons-lang3:jar:3.5:compile (version managed from default)
[DEBUG]       commons-codec:commons-codec:jar:1.6:compile (version managed from default)
[DEBUG]       org.beanshell:bsh:jar:2.0b4:compile
[DEBUG]       org.apache.maven.shared:maven-dependency-tree:jar:2.2:compile (version managed from default)
[DEBUG]          org.eclipse.aether:aether-util:jar:0.9.0.M2:compile
[DEBUG]       org.apache.maven:maven-compat:jar:3.0:compile (version managed from default)
[DEBUG]          org.apache.maven.wagon:wagon-provider-api:jar:1.0-beta-6:compile
[DEBUG] Created new class realm plugin>org.apache.maven.plugins:maven-enforcer-plugin:3.0.0-M2
[DEBUG] Importing foreign packages into class realm plugin>org.apache.maven.plugins:maven-enforcer-plugin:3.0.0-M2
[DEBUG]   Imported:  < project>org.apache.pinot:pinot-pulsar:0.11.0-SNAPSHOT
[DEBUG] Populating class realm plugin>org.apache.maven.plugins:maven-enforcer-plugin:3.0.0-M2
[DEBUG]   Included: org.apache.maven.plugins:maven-enforcer-plugin:jar:3.0.0-M2
[DEBUG]   Included: org.sonatype.sisu:sisu-inject-bean:jar:1.4.2
[DEBUG]   Included: org.sonatype.sisu:sisu-guice:jar:noaop:2.1.7
[DEBUG]   Included: org.sonatype.aether:aether-util:jar:1.7
[DEBUG]   Included: org.codehaus.plexus:plexus-interpolation:jar:1.14
[DEBUG]   Included: org.codehaus.plexus:plexus-component-annotations:jar:1.7.1
[DEBUG]   Included: org.sonatype.plexus:plexus-sec-dispatcher:jar:1.3
[DEBUG]   Included: org.sonatype.plexus:plexus-cipher:jar:1.4
[DEBUG]   Included: org.codehaus.plexus:plexus-utils:jar:3.1.0
[DEBUG]   Included: org.apache.maven.enforcer:enforcer-api:jar:3.0.0-M2
[DEBUG]   Included: junit:junit:jar:4.11
[DEBUG]   Included: org.hamcrest:hamcrest-core:jar:1.3
[DEBUG]   Included: org.apache.maven.enforcer:enforcer-rules:jar:3.0.0-M2
[DEBUG]   Included: org.apache.maven.shared:maven-common-artifact-filters:jar:3.0.1
[DEBUG]   Included: org.apache.maven.shared:maven-shared-utils:jar:3.1.0
[DEBUG]   Included: commons-io:commons-io:jar:2.5
[DEBUG]   Included: org.apache.commons:commons-lang3:jar:3.5
[DEBUG]   Included: commons-codec:commons-codec:jar:1.6
[DEBUG]   Included: org.beanshell:bsh:jar:2.0b4
[DEBUG]   Included: org.apache.maven.shared:maven-dependency-tree:jar:2.2
[DEBUG]   Included: org.eclipse.aether:aether-util:jar:0.9.0.M2
[DEBUG] Configuring mojo org.apache.maven.plugins:maven-enforcer-plugin:3.0.0-M2:enforce from plugin realm ClassRealm[plugin>org.apache.maven.plugins:maven-enforcer-plugin:3.0.0-M2, parent: jdk.internal.loader.ClassLoaders$AppClassLoader@2c13da15]
[DEBUG] Configuring mojo 'org.apache.maven.plugins:maven-enforcer-plugin:3.0.0-M2:enforce' with basic configurator -->
[DEBUG]   (s) fail = true
[DEBUG]   (s) failFast = false
[DEBUG]   (f) ignoreCache = false
[DEBUG]   (f) mojoExecution = org.apache.maven.plugins:maven-enforcer-plugin:3.0.0-M2:enforce {execution: enforce-dependency-convergence}
[DEBUG]   (s) project = MavenProject: org.apache.pinot:pinot-pulsar:0.11.0-SNAPSHOT @ /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/pom.xml
[DEBUG]   (s) rules = [org.apache.maven.plugins.enforcer.DependencyConvergence@787178b1]
[DEBUG]   (s) session = org.apache.maven.execution.MavenSession@53d6e959
[DEBUG]   (s) skip = false
[DEBUG] -- end configuration --
[DEBUG] Executing rule: org.apache.maven.plugins.enforcer.DependencyConvergence
[DEBUG] Dependency tree resolution listener events:
[DEBUG] testArtifact: artifact=org.apache.pinot:pinot-pulsar:jar:0.11.0-SNAPSHOT
[DEBUG] includeArtifact: artifact=org.apache.pinot:pinot-pulsar:jar:0.11.0-SNAPSHOT
[DEBUG] startProcessChildren: artifact=org.apache.pinot:pinot-pulsar:jar:0.11.0-SNAPSHOT
[DEBUG]   testArtifact: artifact=org.eclipse.jetty:jetty-server:jar:9.4.45.v20220203:compile
[DEBUG]   includeArtifact: artifact=org.eclipse.jetty:jetty-server:jar:9.4.45.v20220203:compile
[DEBUG]   startProcessChildren: artifact=org.eclipse.jetty:jetty-server:jar:9.4.45.v20220203:compile
[DEBUG]     testArtifact: artifact=org.eclipse.jetty:jetty-http:jar:9.4.45.v20220203:compile
[DEBUG]     includeArtifact: artifact=org.eclipse.jetty:jetty-http:jar:9.4.45.v20220203:compile
[DEBUG]     startProcessChildren: artifact=org.eclipse.jetty:jetty-http:jar:9.4.45.v20220203:compile
[DEBUG]       testArtifact: artifact=org.eclipse.jetty:jetty-util:jar:9.4.45.v20220203:compile
[DEBUG]       includeArtifact: artifact=org.eclipse.jetty:jetty-util:jar:9.4.45.v20220203:compile
[DEBUG]       startProcessChildren: artifact=org.eclipse.jetty:jetty-util:jar:9.4.45.v20220203:compile
[DEBUG]       endProcessChildren: artifact=org.eclipse.jetty:jetty-util:jar:9.4.45.v20220203:compile
[DEBUG]       testArtifact: artifact=org.eclipse.jetty:jetty-io:jar:9.4.45.v20220203:compile
[DEBUG]       includeArtifact: artifact=org.eclipse.jetty:jetty-io:jar:9.4.45.v20220203:compile
[DEBUG]       startProcessChildren: artifact=org.eclipse.jetty:jetty-io:jar:9.4.45.v20220203:compile
[DEBUG]         testArtifact: artifact=org.eclipse.jetty:jetty-util:jar:9.4.45.v20220203:compile
[DEBUG]         omitForNearer: omitted=org.eclipse.jetty:jetty-util:jar:9.4.45.v20220203:compile kept=org.eclipse.jetty:jetty-util:jar:9.4.45.v20220203:compile
[DEBUG]       endProcessChildren: artifact=org.eclipse.jetty:jetty-io:jar:9.4.45.v20220203:compile
[DEBUG]     endProcessChildren: artifact=org.eclipse.jetty:jetty-http:jar:9.4.45.v20220203:compile
[DEBUG]     testArtifact: artifact=org.eclipse.jetty:jetty-io:jar:9.4.45.v20220203:compile
[DEBUG]     omitForNearer: omitted=org.eclipse.jetty:jetty-io:jar:9.4.45.v20220203:compile kept=org.eclipse.jetty:jetty-io:jar:9.4.45.v20220203:compile
[DEBUG]     includeArtifact: artifact=org.eclipse.jetty:jetty-io:jar:9.4.45.v20220203:compile
[DEBUG]     startProcessChildren: artifact=org.eclipse.jetty:jetty-io:jar:9.4.45.v20220203:compile
[DEBUG]       testArtifact: artifact=org.eclipse.jetty:jetty-util:jar:9.4.45.v20220203:compile
[DEBUG]       omitForNearer: omitted=org.eclipse.jetty:jetty-util:jar:9.4.45.v20220203:compile kept=org.eclipse.jetty:jetty-util:jar:9.4.45.v20220203:compile
[DEBUG]     endProcessChildren: artifact=org.eclipse.jetty:jetty-io:jar:9.4.45.v20220203:compile
[DEBUG]   endProcessChildren: artifact=org.eclipse.jetty:jetty-server:jar:9.4.45.v20220203:compile
[DEBUG]   testArtifact: artifact=org.testcontainers:pulsar:jar:1.17.1:test
[DEBUG]   includeArtifact: artifact=org.testcontainers:pulsar:jar:1.17.1:test
[DEBUG]   startProcessChildren: artifact=org.testcontainers:pulsar:jar:1.17.1:test
[DEBUG]     testArtifact: artifact=org.testcontainers:testcontainers:jar:1.17.1:test
[DEBUG]     includeArtifact: artifact=org.testcontainers:testcontainers:jar:1.17.1:test
[DEBUG]     startProcessChildren: artifact=org.testcontainers:testcontainers:jar:1.17.1:test
[DEBUG]       testArtifact: artifact=junit:junit:jar:4.13.2:test
[DEBUG]       includeArtifact: artifact=junit:junit:jar:4.13.2:test
[DEBUG]       startProcessChildren: artifact=junit:junit:jar:4.13.2:test
[DEBUG]         testArtifact: artifact=org.hamcrest:hamcrest-core:jar:1.3:test
[DEBUG]         includeArtifact: artifact=org.hamcrest:hamcrest-core:jar:1.3:test
[DEBUG]         startProcessChildren: artifact=org.hamcrest:hamcrest-core:jar:1.3:test
[DEBUG]         endProcessChildren: artifact=org.hamcrest:hamcrest-core:jar:1.3:test
[DEBUG]       endProcessChildren: artifact=junit:junit:jar:4.13.2:test
[DEBUG]       manageArtifactVersion: artifact=org.slf4j:slf4j-api:jar:1.7.35:test, replacement=org.slf4j:slf4j-api:jar:1.7.25
[DEBUG]       testArtifact: artifact=org.slf4j:slf4j-api:jar:1.7.25:test
[DEBUG]       manageArtifactVersion: artifact=org.slf4j:slf4j-api:jar:1.7.25:test, replacement=org.slf4j:slf4j-api:jar:1.7.25
[DEBUG]       includeArtifact: artifact=org.slf4j:slf4j-api:jar:1.7.25:test
[DEBUG]       startProcessChildren: artifact=org.slf4j:slf4j-api:jar:1.7.25:test
[DEBUG]       endProcessChildren: artifact=org.slf4j:slf4j-api:jar:1.7.25:test
[DEBUG]       manageArtifactVersion: artifact=org.apache.commons:commons-compress:jar:1.21:test, replacement=org.apache.commons:commons-compress:jar:1.21
[DEBUG]       testArtifact: artifact=org.apache.commons:commons-compress:jar:1.21:test
[DEBUG]       manageArtifactVersion: artifact=org.apache.commons:commons-compress:jar:1.21:test, replacement=org.apache.commons:commons-compress:jar:1.21
[DEBUG]       includeArtifact: artifact=org.apache.commons:commons-compress:jar:1.21:test
[DEBUG]       startProcessChildren: artifact=org.apache.commons:commons-compress:jar:1.21:test
[DEBUG]       endProcessChildren: artifact=org.apache.commons:commons-compress:jar:1.21:test
[DEBUG]       testArtifact: artifact=org.rnorth.duct-tape:duct-tape:jar:1.0.8:test
[DEBUG]       includeArtifact: artifact=org.rnorth.duct-tape:duct-tape:jar:1.0.8:test
[DEBUG]       startProcessChildren: artifact=org.rnorth.duct-tape:duct-tape:jar:1.0.8:test
[DEBUG]         testArtifact: artifact=org.jetbrains:annotations:jar:17.0.0:test
[DEBUG]         includeArtifact: artifact=org.jetbrains:annotations:jar:17.0.0:test
[DEBUG]         startProcessChildren: artifact=org.jetbrains:annotations:jar:17.0.0:test
[DEBUG]         endProcessChildren: artifact=org.jetbrains:annotations:jar:17.0.0:test
[DEBUG]       endProcessChildren: artifact=org.rnorth.duct-tape:duct-tape:jar:1.0.8:test
[DEBUG]       testArtifact: artifact=com.github.docker-java:docker-java-api:jar:3.2.13:test
[DEBUG]       includeArtifact: artifact=com.github.docker-java:docker-java-api:jar:3.2.13:test
[DEBUG]       startProcessChildren: artifact=com.github.docker-java:docker-java-api:jar:3.2.13:test
[DEBUG]         manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.3:test, replacement=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0
[DEBUG]         testArtifact: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:test
[DEBUG]         manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:test, replacement=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0
[DEBUG]         includeArtifact: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:test
[DEBUG]         startProcessChildren: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:test
[DEBUG]         endProcessChildren: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:test
[DEBUG]         manageArtifactVersion: artifact=org.slf4j:slf4j-api:jar:1.7.30:test, replacement=org.slf4j:slf4j-api:jar:1.7.25
[DEBUG]         testArtifact: artifact=org.slf4j:slf4j-api:jar:1.7.25:test
[DEBUG]         manageArtifactVersion: artifact=org.slf4j:slf4j-api:jar:1.7.25:test, replacement=org.slf4j:slf4j-api:jar:1.7.25
[DEBUG]         omitForNearer: omitted=org.slf4j:slf4j-api:jar:1.7.25:test kept=org.slf4j:slf4j-api:jar:1.7.25:test
[DEBUG]       endProcessChildren: artifact=com.github.docker-java:docker-java-api:jar:3.2.13:test
[DEBUG]       testArtifact: artifact=com.github.docker-java:docker-java-transport-zerodep:jar:3.2.13:test
[DEBUG]       includeArtifact: artifact=com.github.docker-java:docker-java-transport-zerodep:jar:3.2.13:test
[DEBUG]       startProcessChildren: artifact=com.github.docker-java:docker-java-transport-zerodep:jar:3.2.13:test
[DEBUG]         testArtifact: artifact=com.github.docker-java:docker-java-transport:jar:3.2.13:test
[DEBUG]         includeArtifact: artifact=com.github.docker-java:docker-java-transport:jar:3.2.13:test
[DEBUG]         startProcessChildren: artifact=com.github.docker-java:docker-java-transport:jar:3.2.13:test
[DEBUG]         endProcessChildren: artifact=com.github.docker-java:docker-java-transport:jar:3.2.13:test
[DEBUG]         manageArtifactVersion: artifact=org.slf4j:slf4j-api:jar:1.7.25:test, replacement=org.slf4j:slf4j-api:jar:1.7.25
[DEBUG]         testArtifact: artifact=org.slf4j:slf4j-api:jar:1.7.25:test
[DEBUG]         manageArtifactVersion: artifact=org.slf4j:slf4j-api:jar:1.7.25:test, replacement=org.slf4j:slf4j-api:jar:1.7.25
[DEBUG]         omitForNearer: omitted=org.slf4j:slf4j-api:jar:1.7.25:test kept=org.slf4j:slf4j-api:jar:1.7.25:test
[DEBUG]         testArtifact: artifact=net.java.dev.jna:jna:jar:5.8.0:test
[DEBUG]         includeArtifact: artifact=net.java.dev.jna:jna:jar:5.8.0:test
[DEBUG]         startProcessChildren: artifact=net.java.dev.jna:jna:jar:5.8.0:test
[DEBUG]         endProcessChildren: artifact=net.java.dev.jna:jna:jar:5.8.0:test
[DEBUG]       endProcessChildren: artifact=com.github.docker-java:docker-java-transport-zerodep:jar:3.2.13:test
[DEBUG]     endProcessChildren: artifact=org.testcontainers:testcontainers:jar:1.17.1:test
[DEBUG]   endProcessChildren: artifact=org.testcontainers:pulsar:jar:1.17.1:test
[DEBUG]   testArtifact: artifact=org.apache.pulsar:pulsar-client-original:jar:2.7.2:compile
[DEBUG]   includeArtifact: artifact=org.apache.pulsar:pulsar-client-original:jar:2.7.2:compile
[DEBUG]   startProcessChildren: artifact=org.apache.pulsar:pulsar-client-original:jar:2.7.2:compile
[DEBUG]     testArtifact: artifact=org.apache.pulsar:pulsar-client-api:jar:2.7.2:compile
[DEBUG]     includeArtifact: artifact=org.apache.pulsar:pulsar-client-api:jar:2.7.2:compile
[DEBUG]     startProcessChildren: artifact=org.apache.pulsar:pulsar-client-api:jar:2.7.2:compile
[DEBUG]     endProcessChildren: artifact=org.apache.pulsar:pulsar-client-api:jar:2.7.2:compile
[DEBUG]     testArtifact: artifact=org.apache.pulsar:pulsar-common:jar:2.7.2:compile
[DEBUG]     includeArtifact: artifact=org.apache.pulsar:pulsar-common:jar:2.7.2:compile
[DEBUG]     startProcessChildren: artifact=org.apache.pulsar:pulsar-common:jar:2.7.2:compile
[DEBUG]       testArtifact: artifact=org.apache.pulsar:pulsar-client-api:jar:2.7.2:compile
[DEBUG]       omitForNearer: omitted=org.apache.pulsar:pulsar-client-api:jar:2.7.2:compile kept=org.apache.pulsar:pulsar-client-api:jar:2.7.2:compile
[DEBUG]       testArtifact: artifact=io.swagger:swagger-annotations:jar:1.5.21:compile
[DEBUG]       includeArtifact: artifact=io.swagger:swagger-annotations:jar:1.5.21:compile
[DEBUG]       startProcessChildren: artifact=io.swagger:swagger-annotations:jar:1.5.21:compile
[DEBUG]       endProcessChildren: artifact=io.swagger:swagger-annotations:jar:1.5.21:compile
[DEBUG]       manageArtifactVersion: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile, replacement=org.slf4j:slf4j-api:jar:1.7.25
[DEBUG]       testArtifact: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile
[DEBUG]       manageArtifactVersion: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile, replacement=org.slf4j:slf4j-api:jar:1.7.25
[DEBUG]       updateScope: artifact=org.slf4j:slf4j-api:jar:1.7.25:test, scope=compile
[DEBUG]       omitForNearer: omitted=org.slf4j:slf4j-api:jar:1.7.25:compile kept=org.slf4j:slf4j-api:jar:1.7.25:compile
[DEBUG]       includeArtifact: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile
[DEBUG]       startProcessChildren: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile
[DEBUG]       endProcessChildren: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-databind:jar:2.11.1:compile, replacement=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0
[DEBUG]       testArtifact: artifact=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0
[DEBUG]       includeArtifact: artifact=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile
[DEBUG]       startProcessChildren: artifact=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile
[DEBUG]         manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0
[DEBUG]         testArtifact: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile
[DEBUG]         manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0
[DEBUG]         updateScope: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:test, scope=compile
[DEBUG]         omitForNearer: omitted=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile kept=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile
[DEBUG]         includeArtifact: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile
[DEBUG]         startProcessChildren: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile
[DEBUG]         endProcessChildren: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile
[DEBUG]         manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-core:jar:2.10.0
[DEBUG]         testArtifact: artifact=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile
[DEBUG]         manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-core:jar:2.10.0
[DEBUG]         includeArtifact: artifact=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile
[DEBUG]         startProcessChildren: artifact=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile
[DEBUG]         endProcessChildren: artifact=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile
[DEBUG]       endProcessChildren: artifact=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile
[DEBUG]       testArtifact: artifact=org.apache.pulsar:protobuf-shaded:jar:2.1.0-incubating:compile
[DEBUG]       includeArtifact: artifact=org.apache.pulsar:protobuf-shaded:jar:2.1.0-incubating:compile
[DEBUG]       startProcessChildren: artifact=org.apache.pulsar:protobuf-shaded:jar:2.1.0-incubating:compile
[DEBUG]       endProcessChildren: artifact=org.apache.pulsar:protobuf-shaded:jar:2.1.0-incubating:compile
[DEBUG]       manageArtifactVersion: artifact=com.google.guava:guava:jar:30.1-jre:compile, replacement=com.google.guava:guava:jar:20.0
[DEBUG]       testArtifact: artifact=com.google.guava:guava:jar:20.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.google.guava:guava:jar:20.0:compile, replacement=com.google.guava:guava:jar:20.0
[DEBUG]       includeArtifact: artifact=com.google.guava:guava:jar:20.0:compile
[DEBUG]       startProcessChildren: artifact=com.google.guava:guava:jar:20.0:compile
[DEBUG]       endProcessChildren: artifact=com.google.guava:guava:jar:20.0:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-handler:jar:4.1.60.Final:compile, replacement=io.netty:netty-handler:jar:4.1.74.Final
[DEBUG]       testArtifact: artifact=io.netty:netty-handler:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-handler:jar:4.1.74.Final:compile, replacement=io.netty:netty-handler:jar:4.1.74.Final
[DEBUG]       includeArtifact: artifact=io.netty:netty-handler:jar:4.1.74.Final:compile
[DEBUG]       startProcessChildren: artifact=io.netty:netty-handler:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]         testArtifact: artifact=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]         includeArtifact: artifact=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]         startProcessChildren: artifact=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]         endProcessChildren: artifact=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile, replacement=io.netty:netty-buffer:jar:4.1.74.Final
[DEBUG]         testArtifact: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile, replacement=io.netty:netty-buffer:jar:4.1.74.Final
[DEBUG]         includeArtifact: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]         startProcessChildren: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]           manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]           testArtifact: artifact=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]           manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]           omitForNearer: omitted=io.netty:netty-common:jar:4.1.74.Final:compile kept=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]         endProcessChildren: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile, replacement=io.netty:netty-transport:jar:4.1.74.Final
[DEBUG]         testArtifact: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile, replacement=io.netty:netty-transport:jar:4.1.74.Final
[DEBUG]         includeArtifact: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG]         startProcessChildren: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG]           manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]           testArtifact: artifact=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]           manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]           omitForNearer: omitted=io.netty:netty-common:jar:4.1.74.Final:compile kept=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]           manageArtifactVersion: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile, replacement=io.netty:netty-buffer:jar:4.1.74.Final
[DEBUG]           testArtifact: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]           manageArtifactVersion: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile, replacement=io.netty:netty-buffer:jar:4.1.74.Final
[DEBUG]           omitForNearer: omitted=io.netty:netty-buffer:jar:4.1.74.Final:compile kept=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]         endProcessChildren: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-codec:jar:4.1.74.Final:compile, replacement=io.netty:netty-codec:jar:4.1.74.Final
[DEBUG]         testArtifact: artifact=io.netty:netty-codec:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-codec:jar:4.1.74.Final:compile, replacement=io.netty:netty-codec:jar:4.1.74.Final
[DEBUG]         includeArtifact: artifact=io.netty:netty-codec:jar:4.1.74.Final:compile
[DEBUG]         startProcessChildren: artifact=io.netty:netty-codec:jar:4.1.74.Final:compile
[DEBUG]           manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]           testArtifact: artifact=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]           manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]           omitForNearer: omitted=io.netty:netty-common:jar:4.1.74.Final:compile kept=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]           manageArtifactVersion: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile, replacement=io.netty:netty-buffer:jar:4.1.74.Final
[DEBUG]           testArtifact: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]           manageArtifactVersion: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile, replacement=io.netty:netty-buffer:jar:4.1.74.Final
[DEBUG]           omitForNearer: omitted=io.netty:netty-buffer:jar:4.1.74.Final:compile kept=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]           manageArtifactVersion: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile, replacement=io.netty:netty-transport:jar:4.1.74.Final
[DEBUG]           testArtifact: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG]           manageArtifactVersion: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile, replacement=io.netty:netty-transport:jar:4.1.74.Final
[DEBUG]           omitForNearer: omitted=io.netty:netty-transport:jar:4.1.74.Final:compile kept=io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG]         endProcessChildren: artifact=io.netty:netty-codec:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-tcnative-classes:jar:2.0.48.Final:compile, replacement=io.netty:netty-tcnative-classes:jar:2.0.48.Final
[DEBUG]         testArtifact: artifact=io.netty:netty-tcnative-classes:jar:2.0.48.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-tcnative-classes:jar:2.0.48.Final:compile, replacement=io.netty:netty-tcnative-classes:jar:2.0.48.Final
[DEBUG]         includeArtifact: artifact=io.netty:netty-tcnative-classes:jar:2.0.48.Final:compile
[DEBUG]         startProcessChildren: artifact=io.netty:netty-tcnative-classes:jar:2.0.48.Final:compile
[DEBUG]         endProcessChildren: artifact=io.netty:netty-tcnative-classes:jar:2.0.48.Final:compile
[DEBUG]       endProcessChildren: artifact=io.netty:netty-handler:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-transport-native-epoll:jar:linux-x86_64:4.1.60.Final:compile, replacement=io.netty:netty-transport-native-epoll:jar:linux-x86_64:4.1.74.Final
[DEBUG]       testArtifact: artifact=io.netty:netty-transport-native-epoll:jar:linux-x86_64:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-transport-native-epoll:jar:linux-x86_64:4.1.74.Final:compile, replacement=io.netty:netty-transport-native-epoll:jar:linux-x86_64:4.1.74.Final
[DEBUG]       includeArtifact: artifact=io.netty:netty-transport-native-epoll:jar:linux-x86_64:4.1.74.Final:compile
[DEBUG]       startProcessChildren: artifact=io.netty:netty-transport-native-epoll:jar:linux-x86_64:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]         testArtifact: artifact=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]         omitForNearer: omitted=io.netty:netty-common:jar:4.1.74.Final:compile kept=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile, replacement=io.netty:netty-buffer:jar:4.1.74.Final
[DEBUG]         testArtifact: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile, replacement=io.netty:netty-buffer:jar:4.1.74.Final
[DEBUG]         omitForNearer: omitted=io.netty:netty-buffer:jar:4.1.74.Final:compile kept=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile, replacement=io.netty:netty-transport:jar:4.1.74.Final
[DEBUG]         testArtifact: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile, replacement=io.netty:netty-transport:jar:4.1.74.Final
[DEBUG]         omitForNearer: omitted=io.netty:netty-transport:jar:4.1.74.Final:compile kept=io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-transport-classes-epoll:jar:4.1.74.Final:compile, replacement=io.netty:netty-transport-classes-epoll:jar:4.1.74.Final
[DEBUG]         testArtifact: artifact=io.netty:netty-transport-classes-epoll:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-transport-classes-epoll:jar:4.1.74.Final:compile, replacement=io.netty:netty-transport-classes-epoll:jar:4.1.74.Final
[DEBUG]         includeArtifact: artifact=io.netty:netty-transport-classes-epoll:jar:4.1.74.Final:compile
[DEBUG]         startProcessChildren: artifact=io.netty:netty-transport-classes-epoll:jar:4.1.74.Final:compile
[DEBUG]           manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]           testArtifact: artifact=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]           manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]           omitForNearer: omitted=io.netty:netty-common:jar:4.1.74.Final:compile kept=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]           manageArtifactVersion: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile, replacement=io.netty:netty-buffer:jar:4.1.74.Final
[DEBUG]           testArtifact: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]           manageArtifactVersion: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile, replacement=io.netty:netty-buffer:jar:4.1.74.Final
[DEBUG]           omitForNearer: omitted=io.netty:netty-buffer:jar:4.1.74.Final:compile kept=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]           manageArtifactVersion: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile, replacement=io.netty:netty-transport:jar:4.1.74.Final
[DEBUG]           testArtifact: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG]           manageArtifactVersion: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile, replacement=io.netty:netty-transport:jar:4.1.74.Final
[DEBUG]           omitForNearer: omitted=io.netty:netty-transport:jar:4.1.74.Final:compile kept=io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG]         endProcessChildren: artifact=io.netty:netty-transport-classes-epoll:jar:4.1.74.Final:compile
[DEBUG]       endProcessChildren: artifact=io.netty:netty-transport-native-epoll:jar:linux-x86_64:4.1.74.Final:compile
[DEBUG]       testArtifact: artifact=org.apache.bookkeeper:bookkeeper-common-allocator:jar:4.12.0:compile
[DEBUG]       includeArtifact: artifact=org.apache.bookkeeper:bookkeeper-common-allocator:jar:4.12.0:compile
[DEBUG]       startProcessChildren: artifact=org.apache.bookkeeper:bookkeeper-common-allocator:jar:4.12.0:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-buffer:jar:4.1.50.Final:compile, replacement=io.netty:netty-buffer:jar:4.1.74.Final
[DEBUG]         testArtifact: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile, replacement=io.netty:netty-buffer:jar:4.1.74.Final
[DEBUG]         omitForNearer: omitted=io.netty:netty-buffer:jar:4.1.74.Final:compile kept=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile, replacement=org.slf4j:slf4j-api:jar:1.7.25
[DEBUG]         testArtifact: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile
[DEBUG]         manageArtifactVersion: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile, replacement=org.slf4j:slf4j-api:jar:1.7.25
[DEBUG]         omitForNearer: omitted=org.slf4j:slf4j-api:jar:1.7.25:compile kept=org.slf4j:slf4j-api:jar:1.7.25:compile
[DEBUG]       endProcessChildren: artifact=org.apache.bookkeeper:bookkeeper-common-allocator:jar:4.12.0:compile
[DEBUG]       testArtifact: artifact=io.airlift:aircompressor:jar:0.16:compile
[DEBUG]       includeArtifact: artifact=io.airlift:aircompressor:jar:0.16:compile
[DEBUG]       startProcessChildren: artifact=io.airlift:aircompressor:jar:0.16:compile
[DEBUG]       endProcessChildren: artifact=io.airlift:aircompressor:jar:0.16:compile
[DEBUG]       testArtifact: artifact=org.apache.bookkeeper:circe-checksum:jar:4.12.0:compile
[DEBUG]       includeArtifact: artifact=org.apache.bookkeeper:circe-checksum:jar:4.12.0:compile
[DEBUG]       startProcessChildren: artifact=org.apache.bookkeeper:circe-checksum:jar:4.12.0:compile
[DEBUG]         manageArtifactVersion: artifact=com.google.guava:guava:jar:30.0-jre:compile, replacement=com.google.guava:guava:jar:20.0
[DEBUG]         testArtifact: artifact=com.google.guava:guava:jar:20.0:compile
[DEBUG]         manageArtifactVersion: artifact=com.google.guava:guava:jar:20.0:compile, replacement=com.google.guava:guava:jar:20.0
[DEBUG]         omitForNearer: omitted=com.google.guava:guava:jar:20.0:compile kept=com.google.guava:guava:jar:20.0:compile
[DEBUG]         manageArtifactVersion: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile, replacement=org.slf4j:slf4j-api:jar:1.7.25
[DEBUG]         testArtifact: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile
[DEBUG]         manageArtifactVersion: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile, replacement=org.slf4j:slf4j-api:jar:1.7.25
[DEBUG]         omitForNearer: omitted=org.slf4j:slf4j-api:jar:1.7.25:compile kept=org.slf4j:slf4j-api:jar:1.7.25:compile
[DEBUG]         manageArtifactVersion: artifact=commons-configuration:commons-configuration:jar:1.10:compile, replacement=commons-configuration:commons-configuration:jar:1.10
[DEBUG]         testArtifact: artifact=commons-configuration:commons-configuration:jar:1.10:compile
[DEBUG]         manageArtifactVersion: artifact=commons-configuration:commons-configuration:jar:1.10:compile, replacement=commons-configuration:commons-configuration:jar:1.10
[DEBUG]         includeArtifact: artifact=commons-configuration:commons-configuration:jar:1.10:compile
[DEBUG]         startProcessChildren: artifact=commons-configuration:commons-configuration:jar:1.10:compile
[DEBUG]           manageArtifactVersion: artifact=commons-lang:commons-lang:jar:2.6:compile, replacement=commons-lang:commons-lang:jar:2.6
[DEBUG]           testArtifact: artifact=commons-lang:commons-lang:jar:2.6:compile
[DEBUG]           manageArtifactVersion: artifact=commons-lang:commons-lang:jar:2.6:compile, replacement=commons-lang:commons-lang:jar:2.6
[DEBUG]           includeArtifact: artifact=commons-lang:commons-lang:jar:2.6:compile
[DEBUG]           startProcessChildren: artifact=commons-lang:commons-lang:jar:2.6:compile
[DEBUG]           endProcessChildren: artifact=commons-lang:commons-lang:jar:2.6:compile
[DEBUG]           manageArtifactVersion: artifact=commons-logging:commons-logging:jar:1.1.1:compile, replacement=commons-logging:commons-logging:jar:1.2
[DEBUG]           testArtifact: artifact=commons-logging:commons-logging:jar:1.2:compile
[DEBUG]           manageArtifactVersion: artifact=commons-logging:commons-logging:jar:1.2:compile, replacement=commons-logging:commons-logging:jar:1.2
[DEBUG]           includeArtifact: artifact=commons-logging:commons-logging:jar:1.2:compile
[DEBUG]           startProcessChildren: artifact=commons-logging:commons-logging:jar:1.2:compile
[DEBUG]           endProcessChildren: artifact=commons-logging:commons-logging:jar:1.2:compile
[DEBUG]         endProcessChildren: artifact=commons-configuration:commons-configuration:jar:1.10:compile
[DEBUG]       endProcessChildren: artifact=org.apache.bookkeeper:circe-checksum:jar:4.12.0:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-tcnative-boringssl-static:jar:2.0.36.Final:compile, replacement=io.netty:netty-tcnative-boringssl-static:jar:2.0.48.Final
[DEBUG]       testArtifact: artifact=io.netty:netty-tcnative-boringssl-static:jar:2.0.48.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-tcnative-boringssl-static:jar:2.0.48.Final:compile, replacement=io.netty:netty-tcnative-boringssl-static:jar:2.0.48.Final
[DEBUG]       includeArtifact: artifact=io.netty:netty-tcnative-boringssl-static:jar:2.0.48.Final:compile
[DEBUG]       startProcessChildren: artifact=io.netty:netty-tcnative-boringssl-static:jar:2.0.48.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-tcnative-classes:jar:2.0.48.Final:compile, replacement=io.netty:netty-tcnative-classes:jar:2.0.48.Final
[DEBUG]         testArtifact: artifact=io.netty:netty-tcnative-classes:jar:2.0.48.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-tcnative-classes:jar:2.0.48.Final:compile, replacement=io.netty:netty-tcnative-classes:jar:2.0.48.Final
[DEBUG]         omitForNearer: omitted=io.netty:netty-tcnative-classes:jar:2.0.48.Final:compile kept=io.netty:netty-tcnative-classes:jar:2.0.48.Final:compile
[DEBUG]       endProcessChildren: artifact=io.netty:netty-tcnative-boringssl-static:jar:2.0.48.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-codec-haproxy:jar:4.1.60.Final:compile, replacement=io.netty:netty-codec-haproxy:jar:4.1.74.Final
[DEBUG]       testArtifact: artifact=io.netty:netty-codec-haproxy:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-codec-haproxy:jar:4.1.74.Final:compile, replacement=io.netty:netty-codec-haproxy:jar:4.1.74.Final
[DEBUG]       includeArtifact: artifact=io.netty:netty-codec-haproxy:jar:4.1.74.Final:compile
[DEBUG]       startProcessChildren: artifact=io.netty:netty-codec-haproxy:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile, replacement=io.netty:netty-buffer:jar:4.1.74.Final
[DEBUG]         testArtifact: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile, replacement=io.netty:netty-buffer:jar:4.1.74.Final
[DEBUG]         omitForNearer: omitted=io.netty:netty-buffer:jar:4.1.74.Final:compile kept=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile, replacement=io.netty:netty-transport:jar:4.1.74.Final
[DEBUG]         testArtifact: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile, replacement=io.netty:netty-transport:jar:4.1.74.Final
[DEBUG]         omitForNearer: omitted=io.netty:netty-transport:jar:4.1.74.Final:compile kept=io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-codec:jar:4.1.74.Final:compile, replacement=io.netty:netty-codec:jar:4.1.74.Final
[DEBUG]         testArtifact: artifact=io.netty:netty-codec:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-codec:jar:4.1.74.Final:compile, replacement=io.netty:netty-codec:jar:4.1.74.Final
[DEBUG]         omitForNearer: omitted=io.netty:netty-codec:jar:4.1.74.Final:compile kept=io.netty:netty-codec:jar:4.1.74.Final:compile
[DEBUG]       endProcessChildren: artifact=io.netty:netty-codec-haproxy:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=org.apache.commons:commons-lang3:jar:3.6:compile, replacement=org.apache.commons:commons-lang3:jar:3.5
[DEBUG]       testArtifact: artifact=org.apache.commons:commons-lang3:jar:3.5:compile
[DEBUG]       manageArtifactVersion: artifact=org.apache.commons:commons-lang3:jar:3.5:compile, replacement=org.apache.commons:commons-lang3:jar:3.5
[DEBUG]       includeArtifact: artifact=org.apache.commons:commons-lang3:jar:3.5:compile
[DEBUG]       startProcessChildren: artifact=org.apache.commons:commons-lang3:jar:3.5:compile
[DEBUG]       endProcessChildren: artifact=org.apache.commons:commons-lang3:jar:3.5:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.dataformat:jackson-dataformat-yaml:jar:2.11.1:compile, replacement=com.fasterxml.jackson.dataformat:jackson-dataformat-yaml:jar:2.10.0
[DEBUG]       testArtifact: artifact=com.fasterxml.jackson.dataformat:jackson-dataformat-yaml:jar:2.10.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.dataformat:jackson-dataformat-yaml:jar:2.10.0:compile, replacement=com.fasterxml.jackson.dataformat:jackson-dataformat-yaml:jar:2.10.0
[DEBUG]       includeArtifact: artifact=com.fasterxml.jackson.dataformat:jackson-dataformat-yaml:jar:2.10.0:compile
[DEBUG]       startProcessChildren: artifact=com.fasterxml.jackson.dataformat:jackson-dataformat-yaml:jar:2.10.0:compile
[DEBUG]         manageArtifactVersion: artifact=org.yaml:snakeyaml:jar:1.24:compile, replacement=org.yaml:snakeyaml:jar:1.30
[DEBUG]         testArtifact: artifact=org.yaml:snakeyaml:jar:1.30:compile
[DEBUG]         manageArtifactVersion: artifact=org.yaml:snakeyaml:jar:1.30:compile, replacement=org.yaml:snakeyaml:jar:1.30
[DEBUG]         includeArtifact: artifact=org.yaml:snakeyaml:jar:1.30:compile
[DEBUG]         startProcessChildren: artifact=org.yaml:snakeyaml:jar:1.30:compile
[DEBUG]         endProcessChildren: artifact=org.yaml:snakeyaml:jar:1.30:compile
[DEBUG]         manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-core:jar:2.10.0
[DEBUG]         testArtifact: artifact=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile
[DEBUG]         manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-core:jar:2.10.0
[DEBUG]         omitForNearer: omitted=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile kept=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile
[DEBUG]       endProcessChildren: artifact=com.fasterxml.jackson.dataformat:jackson-dataformat-yaml:jar:2.10.0:compile
[DEBUG]       manageArtifactVersion: artifact=commons-io:commons-io:jar:2.8.0:compile, replacement=commons-io:commons-io:jar:2.11.0
[DEBUG]       testArtifact: artifact=commons-io:commons-io:jar:2.11.0:compile
[DEBUG]       manageArtifactVersion: artifact=commons-io:commons-io:jar:2.11.0:compile, replacement=commons-io:commons-io:jar:2.11.0
[DEBUG]       includeArtifact: artifact=commons-io:commons-io:jar:2.11.0:compile
[DEBUG]       startProcessChildren: artifact=commons-io:commons-io:jar:2.11.0:compile
[DEBUG]       endProcessChildren: artifact=commons-io:commons-io:jar:2.11.0:compile
[DEBUG]     endProcessChildren: artifact=org.apache.pulsar:pulsar-common:jar:2.7.2:compile
[DEBUG]     testArtifact: artifact=org.apache.pulsar:pulsar-transaction-common:jar:2.7.2:compile
[DEBUG]     includeArtifact: artifact=org.apache.pulsar:pulsar-transaction-common:jar:2.7.2:compile
[DEBUG]     startProcessChildren: artifact=org.apache.pulsar:pulsar-transaction-common:jar:2.7.2:compile
[DEBUG]       manageArtifactVersion: artifact=com.google.protobuf:protobuf-java:jar:3.11.4:compile, replacement=com.google.protobuf:protobuf-java:jar:3.19.2
[DEBUG]       testArtifact: artifact=com.google.protobuf:protobuf-java:jar:3.19.2:compile
[DEBUG]       manageArtifactVersion: artifact=com.google.protobuf:protobuf-java:jar:3.19.2:compile, replacement=com.google.protobuf:protobuf-java:jar:3.19.2
[DEBUG]       includeArtifact: artifact=com.google.protobuf:protobuf-java:jar:3.19.2:compile
[DEBUG]       startProcessChildren: artifact=com.google.protobuf:protobuf-java:jar:3.19.2:compile
[DEBUG]       endProcessChildren: artifact=com.google.protobuf:protobuf-java:jar:3.19.2:compile
[DEBUG]       testArtifact: artifact=com.google.protobuf:protobuf-java-util:jar:3.11.4:compile
[DEBUG]       includeArtifact: artifact=com.google.protobuf:protobuf-java-util:jar:3.11.4:compile
[DEBUG]       startProcessChildren: artifact=com.google.protobuf:protobuf-java-util:jar:3.11.4:compile
[DEBUG]         manageArtifactVersion: artifact=com.google.protobuf:protobuf-java:jar:3.11.4:compile, replacement=com.google.protobuf:protobuf-java:jar:3.19.2
[DEBUG]         testArtifact: artifact=com.google.protobuf:protobuf-java:jar:3.19.2:compile
[DEBUG]         manageArtifactVersion: artifact=com.google.protobuf:protobuf-java:jar:3.19.2:compile, replacement=com.google.protobuf:protobuf-java:jar:3.19.2
[DEBUG]         omitForNearer: omitted=com.google.protobuf:protobuf-java:jar:3.19.2:compile kept=com.google.protobuf:protobuf-java:jar:3.19.2:compile
[DEBUG]         manageArtifactVersion: artifact=com.google.guava:guava:jar:28.1-android:compile, replacement=com.google.guava:guava:jar:20.0
[DEBUG]         testArtifact: artifact=com.google.guava:guava:jar:20.0:compile
[DEBUG]         manageArtifactVersion: artifact=com.google.guava:guava:jar:20.0:compile, replacement=com.google.guava:guava:jar:20.0
[DEBUG]         omitForNearer: omitted=com.google.guava:guava:jar:20.0:compile kept=com.google.guava:guava:jar:20.0:compile
[DEBUG]         testArtifact: artifact=com.google.errorprone:error_prone_annotations:jar:2.3.4:compile
[DEBUG]         includeArtifact: artifact=com.google.errorprone:error_prone_annotations:jar:2.3.4:compile
[DEBUG]         startProcessChildren: artifact=com.google.errorprone:error_prone_annotations:jar:2.3.4:compile
[DEBUG]         endProcessChildren: artifact=com.google.errorprone:error_prone_annotations:jar:2.3.4:compile
[DEBUG]         manageArtifactVersion: artifact=com.google.code.gson:gson:jar:2.8.6:compile, replacement=com.google.code.gson:gson:jar:2.2.4
[DEBUG]         testArtifact: artifact=com.google.code.gson:gson:jar:2.2.4:compile
[DEBUG]         manageArtifactVersion: artifact=com.google.code.gson:gson:jar:2.2.4:compile, replacement=com.google.code.gson:gson:jar:2.2.4
[DEBUG]         includeArtifact: artifact=com.google.code.gson:gson:jar:2.2.4:compile
[DEBUG]         startProcessChildren: artifact=com.google.code.gson:gson:jar:2.2.4:compile
[DEBUG]         endProcessChildren: artifact=com.google.code.gson:gson:jar:2.2.4:compile
[DEBUG]       endProcessChildren: artifact=com.google.protobuf:protobuf-java-util:jar:3.11.4:compile
[DEBUG]     endProcessChildren: artifact=org.apache.pulsar:pulsar-transaction-common:jar:2.7.2:compile
[DEBUG]     testArtifact: artifact=org.apache.pulsar:bouncy-castle-bc:jar:pkg:2.7.2:compile
[DEBUG]     includeArtifact: artifact=org.apache.pulsar:bouncy-castle-bc:jar:pkg:2.7.2:compile
[DEBUG]     startProcessChildren: artifact=org.apache.pulsar:bouncy-castle-bc:jar:pkg:2.7.2:compile
[DEBUG]     endProcessChildren: artifact=org.apache.pulsar:bouncy-castle-bc:jar:pkg:2.7.2:compile
[DEBUG]     manageArtifactVersion: artifact=io.netty:netty-codec-http:jar:4.1.60.Final:compile, replacement=io.netty:netty-codec-http:jar:4.1.74.Final
[DEBUG]     testArtifact: artifact=io.netty:netty-codec-http:jar:4.1.74.Final:compile
[DEBUG]     manageArtifactVersion: artifact=io.netty:netty-codec-http:jar:4.1.74.Final:compile, replacement=io.netty:netty-codec-http:jar:4.1.74.Final
[DEBUG]     includeArtifact: artifact=io.netty:netty-codec-http:jar:4.1.74.Final:compile
[DEBUG]     startProcessChildren: artifact=io.netty:netty-codec-http:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]       testArtifact: artifact=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]       omitForNearer: omitted=io.netty:netty-common:jar:4.1.74.Final:compile kept=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]       includeArtifact: artifact=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]       startProcessChildren: artifact=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]       endProcessChildren: artifact=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile, replacement=io.netty:netty-buffer:jar:4.1.74.Final
[DEBUG]       testArtifact: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile, replacement=io.netty:netty-buffer:jar:4.1.74.Final
[DEBUG]       omitForNearer: omitted=io.netty:netty-buffer:jar:4.1.74.Final:compile kept=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]       includeArtifact: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]       startProcessChildren: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]         testArtifact: artifact=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]         omitForNearer: omitted=io.netty:netty-common:jar:4.1.74.Final:compile kept=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]       endProcessChildren: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile, replacement=io.netty:netty-transport:jar:4.1.74.Final
[DEBUG]       testArtifact: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile, replacement=io.netty:netty-transport:jar:4.1.74.Final
[DEBUG]       omitForNearer: omitted=io.netty:netty-transport:jar:4.1.74.Final:compile kept=io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG]       includeArtifact: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG]       startProcessChildren: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]         testArtifact: artifact=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]         omitForNearer: omitted=io.netty:netty-common:jar:4.1.74.Final:compile kept=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile, replacement=io.netty:netty-buffer:jar:4.1.74.Final
[DEBUG]         testArtifact: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile, replacement=io.netty:netty-buffer:jar:4.1.74.Final
[DEBUG]         omitForNearer: omitted=io.netty:netty-buffer:jar:4.1.74.Final:compile kept=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]       endProcessChildren: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-codec:jar:4.1.74.Final:compile, replacement=io.netty:netty-codec:jar:4.1.74.Final
[DEBUG]       testArtifact: artifact=io.netty:netty-codec:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-codec:jar:4.1.74.Final:compile, replacement=io.netty:netty-codec:jar:4.1.74.Final
[DEBUG]       omitForNearer: omitted=io.netty:netty-codec:jar:4.1.74.Final:compile kept=io.netty:netty-codec:jar:4.1.74.Final:compile
[DEBUG]       includeArtifact: artifact=io.netty:netty-codec:jar:4.1.74.Final:compile
[DEBUG]       startProcessChildren: artifact=io.netty:netty-codec:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]         testArtifact: artifact=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]         omitForNearer: omitted=io.netty:netty-common:jar:4.1.74.Final:compile kept=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile, replacement=io.netty:netty-buffer:jar:4.1.74.Final
[DEBUG]         testArtifact: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile, replacement=io.netty:netty-buffer:jar:4.1.74.Final
[DEBUG]         omitForNearer: omitted=io.netty:netty-buffer:jar:4.1.74.Final:compile kept=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile, replacement=io.netty:netty-transport:jar:4.1.74.Final
[DEBUG]         testArtifact: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile, replacement=io.netty:netty-transport:jar:4.1.74.Final
[DEBUG]         omitForNearer: omitted=io.netty:netty-transport:jar:4.1.74.Final:compile kept=io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG]       endProcessChildren: artifact=io.netty:netty-codec:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-handler:jar:4.1.74.Final:compile, replacement=io.netty:netty-handler:jar:4.1.74.Final
[DEBUG]       testArtifact: artifact=io.netty:netty-handler:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-handler:jar:4.1.74.Final:compile, replacement=io.netty:netty-handler:jar:4.1.74.Final
[DEBUG]       omitForNearer: omitted=io.netty:netty-handler:jar:4.1.74.Final:compile kept=io.netty:netty-handler:jar:4.1.74.Final:compile
[DEBUG]     endProcessChildren: artifact=io.netty:netty-codec-http:jar:4.1.74.Final:compile
[DEBUG]     manageArtifactVersion: artifact=io.netty:netty-resolver-dns:jar:4.1.60.Final:compile, replacement=io.netty:netty-resolver-dns:jar:4.1.74.Final
[DEBUG]     testArtifact: artifact=io.netty:netty-resolver-dns:jar:4.1.74.Final:compile
[DEBUG]     manageArtifactVersion: artifact=io.netty:netty-resolver-dns:jar:4.1.74.Final:compile, replacement=io.netty:netty-resolver-dns:jar:4.1.74.Final
[DEBUG]     includeArtifact: artifact=io.netty:netty-resolver-dns:jar:4.1.74.Final:compile
[DEBUG]     startProcessChildren: artifact=io.netty:netty-resolver-dns:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]       testArtifact: artifact=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]       omitForNearer: omitted=io.netty:netty-common:jar:4.1.74.Final:compile kept=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile, replacement=io.netty:netty-buffer:jar:4.1.74.Final
[DEBUG]       testArtifact: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile, replacement=io.netty:netty-buffer:jar:4.1.74.Final
[DEBUG]       omitForNearer: omitted=io.netty:netty-buffer:jar:4.1.74.Final:compile kept=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile, replacement=io.netty:netty-transport:jar:4.1.74.Final
[DEBUG]       testArtifact: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile, replacement=io.netty:netty-transport:jar:4.1.74.Final
[DEBUG]       omitForNearer: omitted=io.netty:netty-transport:jar:4.1.74.Final:compile kept=io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-codec:jar:4.1.74.Final:compile, replacement=io.netty:netty-codec:jar:4.1.74.Final
[DEBUG]       testArtifact: artifact=io.netty:netty-codec:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-codec:jar:4.1.74.Final:compile, replacement=io.netty:netty-codec:jar:4.1.74.Final
[DEBUG]       omitForNearer: omitted=io.netty:netty-codec:jar:4.1.74.Final:compile kept=io.netty:netty-codec:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-codec-dns:jar:4.1.74.Final:compile, replacement=io.netty:netty-codec-dns:jar:4.1.74.Final
[DEBUG]       testArtifact: artifact=io.netty:netty-codec-dns:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-codec-dns:jar:4.1.74.Final:compile, replacement=io.netty:netty-codec-dns:jar:4.1.74.Final
[DEBUG]       includeArtifact: artifact=io.netty:netty-codec-dns:jar:4.1.74.Final:compile
[DEBUG]       startProcessChildren: artifact=io.netty:netty-codec-dns:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]         testArtifact: artifact=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]         omitForNearer: omitted=io.netty:netty-common:jar:4.1.74.Final:compile kept=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile, replacement=io.netty:netty-buffer:jar:4.1.74.Final
[DEBUG]         testArtifact: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile, replacement=io.netty:netty-buffer:jar:4.1.74.Final
[DEBUG]         omitForNearer: omitted=io.netty:netty-buffer:jar:4.1.74.Final:compile kept=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile, replacement=io.netty:netty-transport:jar:4.1.74.Final
[DEBUG]         testArtifact: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile, replacement=io.netty:netty-transport:jar:4.1.74.Final
[DEBUG]         omitForNearer: omitted=io.netty:netty-transport:jar:4.1.74.Final:compile kept=io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-codec:jar:4.1.74.Final:compile, replacement=io.netty:netty-codec:jar:4.1.74.Final
[DEBUG]         testArtifact: artifact=io.netty:netty-codec:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-codec:jar:4.1.74.Final:compile, replacement=io.netty:netty-codec:jar:4.1.74.Final
[DEBUG]         omitForNearer: omitted=io.netty:netty-codec:jar:4.1.74.Final:compile kept=io.netty:netty-codec:jar:4.1.74.Final:compile
[DEBUG]       endProcessChildren: artifact=io.netty:netty-codec-dns:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-handler:jar:4.1.74.Final:compile, replacement=io.netty:netty-handler:jar:4.1.74.Final
[DEBUG]       testArtifact: artifact=io.netty:netty-handler:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-handler:jar:4.1.74.Final:compile, replacement=io.netty:netty-handler:jar:4.1.74.Final
[DEBUG]       omitForNearer: omitted=io.netty:netty-handler:jar:4.1.74.Final:compile kept=io.netty:netty-handler:jar:4.1.74.Final:compile
[DEBUG]     endProcessChildren: artifact=io.netty:netty-resolver-dns:jar:4.1.74.Final:compile
[DEBUG]     manageArtifactVersion: artifact=org.apache.commons:commons-lang3:jar:3.6:compile, replacement=org.apache.commons:commons-lang3:jar:3.5
[DEBUG]     testArtifact: artifact=org.apache.commons:commons-lang3:jar:3.5:compile
[DEBUG]     manageArtifactVersion: artifact=org.apache.commons:commons-lang3:jar:3.5:compile, replacement=org.apache.commons:commons-lang3:jar:3.5
[DEBUG]     omitForNearer: omitted=org.apache.commons:commons-lang3:jar:3.5:compile kept=org.apache.commons:commons-lang3:jar:3.5:compile
[DEBUG]     includeArtifact: artifact=org.apache.commons:commons-lang3:jar:3.5:compile
[DEBUG]     startProcessChildren: artifact=org.apache.commons:commons-lang3:jar:3.5:compile
[DEBUG]     endProcessChildren: artifact=org.apache.commons:commons-lang3:jar:3.5:compile
[DEBUG]     manageArtifactVersion: artifact=org.asynchttpclient:async-http-client:jar:2.12.1:compile, replacement=org.asynchttpclient:async-http-client:jar:2.12.3
[DEBUG]     testArtifact: artifact=org.asynchttpclient:async-http-client:jar:2.12.3:compile
[DEBUG]     manageArtifactVersion: artifact=org.asynchttpclient:async-http-client:jar:2.12.3:compile, replacement=org.asynchttpclient:async-http-client:jar:2.12.3
[DEBUG]     includeArtifact: artifact=org.asynchttpclient:async-http-client:jar:2.12.3:compile
[DEBUG]     startProcessChildren: artifact=org.asynchttpclient:async-http-client:jar:2.12.3:compile
[DEBUG]       testArtifact: artifact=org.asynchttpclient:async-http-client-netty-utils:jar:2.12.3:compile
[DEBUG]       includeArtifact: artifact=org.asynchttpclient:async-http-client-netty-utils:jar:2.12.3:compile
[DEBUG]       startProcessChildren: artifact=org.asynchttpclient:async-http-client-netty-utils:jar:2.12.3:compile
[DEBUG]         manageArtifactVersion: artifact=org.slf4j:slf4j-api:jar:1.7.30:compile, replacement=org.slf4j:slf4j-api:jar:1.7.25
[DEBUG]         testArtifact: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile
[DEBUG]         manageArtifactVersion: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile, replacement=org.slf4j:slf4j-api:jar:1.7.25
[DEBUG]         omitForNearer: omitted=org.slf4j:slf4j-api:jar:1.7.25:compile kept=org.slf4j:slf4j-api:jar:1.7.25:compile
[DEBUG]         testArtifact: artifact=com.sun.activation:jakarta.activation:jar:1.2.2:compile
[DEBUG]         includeArtifact: artifact=com.sun.activation:jakarta.activation:jar:1.2.2:compile
[DEBUG]         startProcessChildren: artifact=com.sun.activation:jakarta.activation:jar:1.2.2:compile
[DEBUG]         endProcessChildren: artifact=com.sun.activation:jakarta.activation:jar:1.2.2:compile
[DEBUG]       endProcessChildren: artifact=org.asynchttpclient:async-http-client-netty-utils:jar:2.12.3:compile
[DEBUG]       manageArtifactVersion: artifact=org.reactivestreams:reactive-streams:jar:1.0.3:compile, replacement=org.reactivestreams:reactive-streams:jar:1.0.3
[DEBUG]       testArtifact: artifact=org.reactivestreams:reactive-streams:jar:1.0.3:compile
[DEBUG]       manageArtifactVersion: artifact=org.reactivestreams:reactive-streams:jar:1.0.3:compile, replacement=org.reactivestreams:reactive-streams:jar:1.0.3
[DEBUG]       includeArtifact: artifact=org.reactivestreams:reactive-streams:jar:1.0.3:compile
[DEBUG]       startProcessChildren: artifact=org.reactivestreams:reactive-streams:jar:1.0.3:compile
[DEBUG]       endProcessChildren: artifact=org.reactivestreams:reactive-streams:jar:1.0.3:compile
[DEBUG]       testArtifact: artifact=com.typesafe.netty:netty-reactive-streams:jar:2.0.4:compile
[DEBUG]       includeArtifact: artifact=com.typesafe.netty:netty-reactive-streams:jar:2.0.4:compile
[DEBUG]       startProcessChildren: artifact=com.typesafe.netty:netty-reactive-streams:jar:2.0.4:compile
[DEBUG]         manageArtifactVersion: artifact=org.reactivestreams:reactive-streams:jar:1.0.3:compile, replacement=org.reactivestreams:reactive-streams:jar:1.0.3
[DEBUG]         testArtifact: artifact=org.reactivestreams:reactive-streams:jar:1.0.3:compile
[DEBUG]         manageArtifactVersion: artifact=org.reactivestreams:reactive-streams:jar:1.0.3:compile, replacement=org.reactivestreams:reactive-streams:jar:1.0.3
[DEBUG]         omitForNearer: omitted=org.reactivestreams:reactive-streams:jar:1.0.3:compile kept=org.reactivestreams:reactive-streams:jar:1.0.3:compile
[DEBUG]       endProcessChildren: artifact=com.typesafe.netty:netty-reactive-streams:jar:2.0.4:compile
[DEBUG]       manageArtifactVersion: artifact=org.slf4j:slf4j-api:jar:1.7.30:compile, replacement=org.slf4j:slf4j-api:jar:1.7.25
[DEBUG]       testArtifact: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile
[DEBUG]       manageArtifactVersion: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile, replacement=org.slf4j:slf4j-api:jar:1.7.25
[DEBUG]       omitForNearer: omitted=org.slf4j:slf4j-api:jar:1.7.25:compile kept=org.slf4j:slf4j-api:jar:1.7.25:compile
[DEBUG]       testArtifact: artifact=com.sun.activation:jakarta.activation:jar:1.2.2:compile
[DEBUG]       omitForNearer: omitted=com.sun.activation:jakarta.activation:jar:1.2.2:compile kept=com.sun.activation:jakarta.activation:jar:1.2.2:compile
[DEBUG]       includeArtifact: artifact=com.sun.activation:jakarta.activation:jar:1.2.2:compile
[DEBUG]       startProcessChildren: artifact=com.sun.activation:jakarta.activation:jar:1.2.2:compile
[DEBUG]       endProcessChildren: artifact=com.sun.activation:jakarta.activation:jar:1.2.2:compile
[DEBUG]     endProcessChildren: artifact=org.asynchttpclient:async-http-client:jar:2.12.3:compile
[DEBUG]     manageArtifactVersion: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile, replacement=org.slf4j:slf4j-api:jar:1.7.25
[DEBUG]     testArtifact: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile
[DEBUG]     manageArtifactVersion: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile, replacement=org.slf4j:slf4j-api:jar:1.7.25
[DEBUG]     omitForNearer: omitted=org.slf4j:slf4j-api:jar:1.7.25:compile kept=org.slf4j:slf4j-api:jar:1.7.25:compile
[DEBUG]     includeArtifact: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile
[DEBUG]     startProcessChildren: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile
[DEBUG]     endProcessChildren: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile
[DEBUG]     testArtifact: artifact=com.yahoo.datasketches:sketches-core:jar:0.8.3:compile
[DEBUG]     includeArtifact: artifact=com.yahoo.datasketches:sketches-core:jar:0.8.3:compile
[DEBUG]     startProcessChildren: artifact=com.yahoo.datasketches:sketches-core:jar:0.8.3:compile
[DEBUG]       testArtifact: artifact=com.yahoo.datasketches:memory:jar:0.8.3:compile
[DEBUG]       includeArtifact: artifact=com.yahoo.datasketches:memory:jar:0.8.3:compile
[DEBUG]       startProcessChildren: artifact=com.yahoo.datasketches:memory:jar:0.8.3:compile
[DEBUG]       endProcessChildren: artifact=com.yahoo.datasketches:memory:jar:0.8.3:compile
[DEBUG]     endProcessChildren: artifact=com.yahoo.datasketches:sketches-core:jar:0.8.3:compile
[DEBUG]     manageArtifactVersion: artifact=com.google.code.gson:gson:jar:2.8.6:compile, replacement=com.google.code.gson:gson:jar:2.2.4
[DEBUG]     testArtifact: artifact=com.google.code.gson:gson:jar:2.2.4:compile
[DEBUG]     manageArtifactVersion: artifact=com.google.code.gson:gson:jar:2.2.4:compile, replacement=com.google.code.gson:gson:jar:2.2.4
[DEBUG]     omitForNearer: omitted=com.google.code.gson:gson:jar:2.2.4:compile kept=com.google.code.gson:gson:jar:2.2.4:compile
[DEBUG]     includeArtifact: artifact=com.google.code.gson:gson:jar:2.2.4:compile
[DEBUG]     startProcessChildren: artifact=com.google.code.gson:gson:jar:2.2.4:compile
[DEBUG]     endProcessChildren: artifact=com.google.code.gson:gson:jar:2.2.4:compile
[DEBUG]     manageArtifactVersion: artifact=org.apache.avro:avro:jar:1.9.1:compile, replacement=org.apache.avro:avro:jar:1.9.2
[DEBUG]     testArtifact: artifact=org.apache.avro:avro:jar:1.9.2:compile
[DEBUG]     manageArtifactVersion: artifact=org.apache.avro:avro:jar:1.9.2:compile, replacement=org.apache.avro:avro:jar:1.9.2
[DEBUG]     includeArtifact: artifact=org.apache.avro:avro:jar:1.9.2:compile
[DEBUG]     startProcessChildren: artifact=org.apache.avro:avro:jar:1.9.2:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-core:jar:2.10.2:compile, replacement=com.fasterxml.jackson.core:jackson-core:jar:2.10.0
[DEBUG]       testArtifact: artifact=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-core:jar:2.10.0
[DEBUG]       omitForNearer: omitted=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile kept=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile
[DEBUG]       includeArtifact: artifact=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile
[DEBUG]       startProcessChildren: artifact=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile
[DEBUG]       endProcessChildren: artifact=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-databind:jar:2.10.2:compile, replacement=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0
[DEBUG]       testArtifact: artifact=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0
[DEBUG]       omitForNearer: omitted=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile kept=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile
[DEBUG]       manageArtifactVersion: artifact=org.apache.commons:commons-compress:jar:1.19:compile, replacement=org.apache.commons:commons-compress:jar:1.21
[DEBUG]       testArtifact: artifact=org.apache.commons:commons-compress:jar:1.21:compile
[DEBUG]       manageArtifactVersion: artifact=org.apache.commons:commons-compress:jar:1.21:compile, replacement=org.apache.commons:commons-compress:jar:1.21
[DEBUG]       updateScope: artifact=org.apache.commons:commons-compress:jar:1.21:test, scope=compile
[DEBUG]       omitForNearer: omitted=org.apache.commons:commons-compress:jar:1.21:compile kept=org.apache.commons:commons-compress:jar:1.21:compile
[DEBUG]       includeArtifact: artifact=org.apache.commons:commons-compress:jar:1.21:compile
[DEBUG]       startProcessChildren: artifact=org.apache.commons:commons-compress:jar:1.21:compile
[DEBUG]       endProcessChildren: artifact=org.apache.commons:commons-compress:jar:1.21:compile
[DEBUG]       manageArtifactVersion: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile, replacement=org.slf4j:slf4j-api:jar:1.7.25
[DEBUG]       testArtifact: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile
[DEBUG]       manageArtifactVersion: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile, replacement=org.slf4j:slf4j-api:jar:1.7.25
[DEBUG]       omitForNearer: omitted=org.slf4j:slf4j-api:jar:1.7.25:compile kept=org.slf4j:slf4j-api:jar:1.7.25:compile
[DEBUG]     endProcessChildren: artifact=org.apache.avro:avro:jar:1.9.2:compile
[DEBUG]     testArtifact: artifact=org.apache.avro:avro-protobuf:jar:1.9.1:compile
[DEBUG]     includeArtifact: artifact=org.apache.avro:avro-protobuf:jar:1.9.1:compile
[DEBUG]     startProcessChildren: artifact=org.apache.avro:avro-protobuf:jar:1.9.1:compile
[DEBUG]       manageArtifactVersion: artifact=org.apache.avro:avro:jar:1.9.1:compile, replacement=org.apache.avro:avro:jar:1.9.2
[DEBUG]       testArtifact: artifact=org.apache.avro:avro:jar:1.9.2:compile
[DEBUG]       manageArtifactVersion: artifact=org.apache.avro:avro:jar:1.9.2:compile, replacement=org.apache.avro:avro:jar:1.9.2
[DEBUG]       omitForNearer: omitted=org.apache.avro:avro:jar:1.9.2:compile kept=org.apache.avro:avro:jar:1.9.2:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-core:jar:2.9.9:compile, replacement=com.fasterxml.jackson.core:jackson-core:jar:2.10.0
[DEBUG]       testArtifact: artifact=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-core:jar:2.10.0
[DEBUG]       omitForNearer: omitted=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile kept=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-databind:jar:2.9.9.3:compile, replacement=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0
[DEBUG]       testArtifact: artifact=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0
[DEBUG]       omitForNearer: omitted=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile kept=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile
[DEBUG]       manageArtifactVersion: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile, replacement=org.slf4j:slf4j-api:jar:1.7.25
[DEBUG]       testArtifact: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile
[DEBUG]       manageArtifactVersion: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile, replacement=org.slf4j:slf4j-api:jar:1.7.25
[DEBUG]       omitForNearer: omitted=org.slf4j:slf4j-api:jar:1.7.25:compile kept=org.slf4j:slf4j-api:jar:1.7.25:compile
[DEBUG]     endProcessChildren: artifact=org.apache.avro:avro-protobuf:jar:1.9.1:compile
[DEBUG]     testArtifact: artifact=com.fasterxml.jackson.module:jackson-module-jsonSchema:jar:2.11.1:compile
[DEBUG]     includeArtifact: artifact=com.fasterxml.jackson.module:jackson-module-jsonSchema:jar:2.11.1:compile
[DEBUG]     startProcessChildren: artifact=com.fasterxml.jackson.module:jackson-module-jsonSchema:jar:2.11.1:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.11.1:compile, replacement=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0
[DEBUG]       testArtifact: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0
[DEBUG]       omitForNearer: omitted=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile kept=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile
[DEBUG]       includeArtifact: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile
[DEBUG]       startProcessChildren: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile
[DEBUG]       endProcessChildren: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-core:jar:2.11.1:compile, replacement=com.fasterxml.jackson.core:jackson-core:jar:2.10.0
[DEBUG]       testArtifact: artifact=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-core:jar:2.10.0
[DEBUG]       omitForNearer: omitted=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile kept=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-databind:jar:2.11.1:compile, replacement=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0
[DEBUG]       testArtifact: artifact=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0
[DEBUG]       omitForNearer: omitted=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile kept=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile
[DEBUG]       manageArtifactVersion: artifact=javax.validation:validation-api:jar:1.1.0.Final:compile, replacement=javax.validation:validation-api:jar:2.0.1.Final
[DEBUG]       testArtifact: artifact=javax.validation:validation-api:jar:2.0.1.Final:compile
[DEBUG]       manageArtifactVersion: artifact=javax.validation:validation-api:jar:2.0.1.Final:compile, replacement=javax.validation:validation-api:jar:2.0.1.Final
[DEBUG]       includeArtifact: artifact=javax.validation:validation-api:jar:2.0.1.Final:compile
[DEBUG]       startProcessChildren: artifact=javax.validation:validation-api:jar:2.0.1.Final:compile
[DEBUG]       endProcessChildren: artifact=javax.validation:validation-api:jar:2.0.1.Final:compile
[DEBUG]     endProcessChildren: artifact=com.fasterxml.jackson.module:jackson-module-jsonSchema:jar:2.11.1:compile
[DEBUG]     testArtifact: artifact=net.jcip:jcip-annotations:jar:1.0:compile
[DEBUG]     includeArtifact: artifact=net.jcip:jcip-annotations:jar:1.0:compile
[DEBUG]     startProcessChildren: artifact=net.jcip:jcip-annotations:jar:1.0:compile
[DEBUG]     endProcessChildren: artifact=net.jcip:jcip-annotations:jar:1.0:compile
[DEBUG]   endProcessChildren: artifact=org.apache.pulsar:pulsar-client-original:jar:2.7.2:compile
[DEBUG]   testArtifact: artifact=org.apache.pulsar:pulsar-client-admin-original:jar:2.7.2:compile
[DEBUG]   includeArtifact: artifact=org.apache.pulsar:pulsar-client-admin-original:jar:2.7.2:compile
[DEBUG]   startProcessChildren: artifact=org.apache.pulsar:pulsar-client-admin-original:jar:2.7.2:compile
[DEBUG]     testArtifact: artifact=org.apache.pulsar:pulsar-client-original:jar:2.7.2:compile
[DEBUG]     omitForNearer: omitted=org.apache.pulsar:pulsar-client-original:jar:2.7.2:compile kept=org.apache.pulsar:pulsar-client-original:jar:2.7.2:compile
[DEBUG]     manageArtifactVersion: artifact=org.glassfish.jersey.core:jersey-client:jar:2.31:compile, replacement=org.glassfish.jersey.core:jersey-client:jar:2.35
[DEBUG]     testArtifact: artifact=org.glassfish.jersey.core:jersey-client:jar:2.35:compile
[DEBUG]     manageArtifactVersion: artifact=org.glassfish.jersey.core:jersey-client:jar:2.35:compile, replacement=org.glassfish.jersey.core:jersey-client:jar:2.35
[DEBUG]     includeArtifact: artifact=org.glassfish.jersey.core:jersey-client:jar:2.35:compile
[DEBUG]     startProcessChildren: artifact=org.glassfish.jersey.core:jersey-client:jar:2.35:compile
[DEBUG]       testArtifact: artifact=jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile
[DEBUG]       includeArtifact: artifact=jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile
[DEBUG]       startProcessChildren: artifact=jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile
[DEBUG]       endProcessChildren: artifact=jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile
[DEBUG]       manageArtifactVersion: artifact=org.glassfish.jersey.core:jersey-common:jar:2.35:compile, replacement=org.glassfish.jersey.core:jersey-common:jar:2.35
[DEBUG]       testArtifact: artifact=org.glassfish.jersey.core:jersey-common:jar:2.35:compile
[DEBUG]       manageArtifactVersion: artifact=org.glassfish.jersey.core:jersey-common:jar:2.35:compile, replacement=org.glassfish.jersey.core:jersey-common:jar:2.35
[DEBUG]       includeArtifact: artifact=org.glassfish.jersey.core:jersey-common:jar:2.35:compile
[DEBUG]       startProcessChildren: artifact=org.glassfish.jersey.core:jersey-common:jar:2.35:compile
[DEBUG]         testArtifact: artifact=jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile
[DEBUG]         omitForNearer: omitted=jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile kept=jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile
[DEBUG]         testArtifact: artifact=jakarta.annotation:jakarta.annotation-api:jar:1.3.5:compile
[DEBUG]         includeArtifact: artifact=jakarta.annotation:jakarta.annotation-api:jar:1.3.5:compile
[DEBUG]         startProcessChildren: artifact=jakarta.annotation:jakarta.annotation-api:jar:1.3.5:compile
[DEBUG]         endProcessChildren: artifact=jakarta.annotation:jakarta.annotation-api:jar:1.3.5:compile
[DEBUG]         testArtifact: artifact=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]         includeArtifact: artifact=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]         startProcessChildren: artifact=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]         endProcessChildren: artifact=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]         testArtifact: artifact=org.glassfish.hk2:osgi-resource-locator:jar:1.0.3:compile
[DEBUG]         includeArtifact: artifact=org.glassfish.hk2:osgi-resource-locator:jar:1.0.3:compile
[DEBUG]         startProcessChildren: artifact=org.glassfish.hk2:osgi-resource-locator:jar:1.0.3:compile
[DEBUG]         endProcessChildren: artifact=org.glassfish.hk2:osgi-resource-locator:jar:1.0.3:compile
[DEBUG]       endProcessChildren: artifact=org.glassfish.jersey.core:jersey-common:jar:2.35:compile
[DEBUG]       testArtifact: artifact=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]       omitForNearer: omitted=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile kept=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]       includeArtifact: artifact=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]       startProcessChildren: artifact=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]       endProcessChildren: artifact=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]     endProcessChildren: artifact=org.glassfish.jersey.core:jersey-client:jar:2.35:compile
[DEBUG]     manageArtifactVersion: artifact=org.glassfish.jersey.media:jersey-media-json-jackson:jar:2.31:compile, replacement=org.glassfish.jersey.media:jersey-media-json-jackson:jar:2.35
[DEBUG]     testArtifact: artifact=org.glassfish.jersey.media:jersey-media-json-jackson:jar:2.35:compile
[DEBUG]     manageArtifactVersion: artifact=org.glassfish.jersey.media:jersey-media-json-jackson:jar:2.35:compile, replacement=org.glassfish.jersey.media:jersey-media-json-jackson:jar:2.35
[DEBUG]     includeArtifact: artifact=org.glassfish.jersey.media:jersey-media-json-jackson:jar:2.35:compile
[DEBUG]     startProcessChildren: artifact=org.glassfish.jersey.media:jersey-media-json-jackson:jar:2.35:compile
[DEBUG]       manageArtifactVersion: artifact=org.glassfish.jersey.core:jersey-common:jar:2.35:compile, replacement=org.glassfish.jersey.core:jersey-common:jar:2.35
[DEBUG]       testArtifact: artifact=org.glassfish.jersey.core:jersey-common:jar:2.35:compile
[DEBUG]       manageArtifactVersion: artifact=org.glassfish.jersey.core:jersey-common:jar:2.35:compile, replacement=org.glassfish.jersey.core:jersey-common:jar:2.35
[DEBUG]       omitForNearer: omitted=org.glassfish.jersey.core:jersey-common:jar:2.35:compile kept=org.glassfish.jersey.core:jersey-common:jar:2.35:compile
[DEBUG]       testArtifact: artifact=org.glassfish.jersey.ext:jersey-entity-filtering:jar:2.35:compile
[DEBUG]       includeArtifact: artifact=org.glassfish.jersey.ext:jersey-entity-filtering:jar:2.35:compile
[DEBUG]       startProcessChildren: artifact=org.glassfish.jersey.ext:jersey-entity-filtering:jar:2.35:compile
[DEBUG]         testArtifact: artifact=jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile
[DEBUG]         omitForNearer: omitted=jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile kept=jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile
[DEBUG]       endProcessChildren: artifact=org.glassfish.jersey.ext:jersey-entity-filtering:jar:2.35:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.12.2:compile, replacement=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0
[DEBUG]       testArtifact: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0
[DEBUG]       omitForNearer: omitted=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile kept=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-databind:jar:2.12.2:compile, replacement=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0
[DEBUG]       testArtifact: artifact=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0
[DEBUG]       omitForNearer: omitted=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile kept=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.module:jackson-module-jaxb-annotations:jar:2.12.2:compile, replacement=com.fasterxml.jackson.module:jackson-module-jaxb-annotations:jar:2.10.0
[DEBUG]       testArtifact: artifact=com.fasterxml.jackson.module:jackson-module-jaxb-annotations:jar:2.10.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.module:jackson-module-jaxb-annotations:jar:2.10.0:compile, replacement=com.fasterxml.jackson.module:jackson-module-jaxb-annotations:jar:2.10.0
[DEBUG]       includeArtifact: artifact=com.fasterxml.jackson.module:jackson-module-jaxb-annotations:jar:2.10.0:compile
[DEBUG]       startProcessChildren: artifact=com.fasterxml.jackson.module:jackson-module-jaxb-annotations:jar:2.10.0:compile
[DEBUG]         manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0
[DEBUG]         testArtifact: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile
[DEBUG]         manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0
[DEBUG]         omitForNearer: omitted=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile kept=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile
[DEBUG]         manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-core:jar:2.10.0
[DEBUG]         testArtifact: artifact=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile
[DEBUG]         manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-core:jar:2.10.0
[DEBUG]         omitForNearer: omitted=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile kept=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile
[DEBUG]         manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0
[DEBUG]         testArtifact: artifact=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile
[DEBUG]         manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0
[DEBUG]         omitForNearer: omitted=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile kept=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile
[DEBUG]         testArtifact: artifact=jakarta.xml.bind:jakarta.xml.bind-api:jar:2.3.2:compile
[DEBUG]         includeArtifact: artifact=jakarta.xml.bind:jakarta.xml.bind-api:jar:2.3.2:compile
[DEBUG]         startProcessChildren: artifact=jakarta.xml.bind:jakarta.xml.bind-api:jar:2.3.2:compile
[DEBUG]           testArtifact: artifact=jakarta.activation:jakarta.activation-api:jar:1.2.1:compile
[DEBUG]           includeArtifact: artifact=jakarta.activation:jakarta.activation-api:jar:1.2.1:compile
[DEBUG]           startProcessChildren: artifact=jakarta.activation:jakarta.activation-api:jar:1.2.1:compile
[DEBUG]           endProcessChildren: artifact=jakarta.activation:jakarta.activation-api:jar:1.2.1:compile
[DEBUG]         endProcessChildren: artifact=jakarta.xml.bind:jakarta.xml.bind-api:jar:2.3.2:compile
[DEBUG]         testArtifact: artifact=jakarta.activation:jakarta.activation-api:jar:1.2.1:compile
[DEBUG]         omitForNearer: omitted=jakarta.activation:jakarta.activation-api:jar:1.2.1:compile kept=jakarta.activation:jakarta.activation-api:jar:1.2.1:compile
[DEBUG]         includeArtifact: artifact=jakarta.activation:jakarta.activation-api:jar:1.2.1:compile
[DEBUG]         startProcessChildren: artifact=jakarta.activation:jakarta.activation-api:jar:1.2.1:compile
[DEBUG]         endProcessChildren: artifact=jakarta.activation:jakarta.activation-api:jar:1.2.1:compile
[DEBUG]       endProcessChildren: artifact=com.fasterxml.jackson.module:jackson-module-jaxb-annotations:jar:2.10.0:compile
[DEBUG]     endProcessChildren: artifact=org.glassfish.jersey.media:jersey-media-json-jackson:jar:2.35:compile
[DEBUG]     manageArtifactVersion: artifact=org.glassfish.jersey.media:jersey-media-multipart:jar:2.31:compile, replacement=org.glassfish.jersey.media:jersey-media-multipart:jar:2.35
[DEBUG]     testArtifact: artifact=org.glassfish.jersey.media:jersey-media-multipart:jar:2.35:compile
[DEBUG]     manageArtifactVersion: artifact=org.glassfish.jersey.media:jersey-media-multipart:jar:2.35:compile, replacement=org.glassfish.jersey.media:jersey-media-multipart:jar:2.35
[DEBUG]     includeArtifact: artifact=org.glassfish.jersey.media:jersey-media-multipart:jar:2.35:compile
[DEBUG]     startProcessChildren: artifact=org.glassfish.jersey.media:jersey-media-multipart:jar:2.35:compile
[DEBUG]       manageArtifactVersion: artifact=org.glassfish.jersey.core:jersey-common:jar:2.35:compile, replacement=org.glassfish.jersey.core:jersey-common:jar:2.35
[DEBUG]       testArtifact: artifact=org.glassfish.jersey.core:jersey-common:jar:2.35:compile
[DEBUG]       manageArtifactVersion: artifact=org.glassfish.jersey.core:jersey-common:jar:2.35:compile, replacement=org.glassfish.jersey.core:jersey-common:jar:2.35
[DEBUG]       omitForNearer: omitted=org.glassfish.jersey.core:jersey-common:jar:2.35:compile kept=org.glassfish.jersey.core:jersey-common:jar:2.35:compile
[DEBUG]       testArtifact: artifact=org.jvnet.mimepull:mimepull:jar:1.9.13:compile
[DEBUG]       includeArtifact: artifact=org.jvnet.mimepull:mimepull:jar:1.9.13:compile
[DEBUG]       startProcessChildren: artifact=org.jvnet.mimepull:mimepull:jar:1.9.13:compile
[DEBUG]       endProcessChildren: artifact=org.jvnet.mimepull:mimepull:jar:1.9.13:compile
[DEBUG]     endProcessChildren: artifact=org.glassfish.jersey.media:jersey-media-multipart:jar:2.35:compile
[DEBUG]     manageArtifactVersion: artifact=com.fasterxml.jackson.jaxrs:jackson-jaxrs-json-provider:jar:2.11.1:compile, replacement=com.fasterxml.jackson.jaxrs:jackson-jaxrs-json-provider:jar:2.10.0
[DEBUG]     testArtifact: artifact=com.fasterxml.jackson.jaxrs:jackson-jaxrs-json-provider:jar:2.10.0:compile
[DEBUG]     manageArtifactVersion: artifact=com.fasterxml.jackson.jaxrs:jackson-jaxrs-json-provider:jar:2.10.0:compile, replacement=com.fasterxml.jackson.jaxrs:jackson-jaxrs-json-provider:jar:2.10.0
[DEBUG]     includeArtifact: artifact=com.fasterxml.jackson.jaxrs:jackson-jaxrs-json-provider:jar:2.10.0:compile
[DEBUG]     startProcessChildren: artifact=com.fasterxml.jackson.jaxrs:jackson-jaxrs-json-provider:jar:2.10.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.jaxrs:jackson-jaxrs-base:jar:2.10.0:compile, replacement=com.fasterxml.jackson.jaxrs:jackson-jaxrs-base:jar:2.10.0
[DEBUG]       testArtifact: artifact=com.fasterxml.jackson.jaxrs:jackson-jaxrs-base:jar:2.10.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.jaxrs:jackson-jaxrs-base:jar:2.10.0:compile, replacement=com.fasterxml.jackson.jaxrs:jackson-jaxrs-base:jar:2.10.0
[DEBUG]       includeArtifact: artifact=com.fasterxml.jackson.jaxrs:jackson-jaxrs-base:jar:2.10.0:compile
[DEBUG]       startProcessChildren: artifact=com.fasterxml.jackson.jaxrs:jackson-jaxrs-base:jar:2.10.0:compile
[DEBUG]         manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-core:jar:2.10.0
[DEBUG]         testArtifact: artifact=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile
[DEBUG]         manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-core:jar:2.10.0
[DEBUG]         omitForNearer: omitted=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile kept=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile
[DEBUG]         manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0
[DEBUG]         testArtifact: artifact=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile
[DEBUG]         manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0
[DEBUG]         omitForNearer: omitted=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile kept=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile
[DEBUG]       endProcessChildren: artifact=com.fasterxml.jackson.jaxrs:jackson-jaxrs-base:jar:2.10.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.module:jackson-module-jaxb-annotations:jar:2.10.0:compile, replacement=com.fasterxml.jackson.module:jackson-module-jaxb-annotations:jar:2.10.0
[DEBUG]       testArtifact: artifact=com.fasterxml.jackson.module:jackson-module-jaxb-annotations:jar:2.10.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.module:jackson-module-jaxb-annotations:jar:2.10.0:compile, replacement=com.fasterxml.jackson.module:jackson-module-jaxb-annotations:jar:2.10.0
[DEBUG]       omitForNearer: omitted=com.fasterxml.jackson.module:jackson-module-jaxb-annotations:jar:2.10.0:compile kept=com.fasterxml.jackson.module:jackson-module-jaxb-annotations:jar:2.10.0:compile
[DEBUG]     endProcessChildren: artifact=com.fasterxml.jackson.jaxrs:jackson-jaxrs-json-provider:jar:2.10.0:compile
[DEBUG]     manageArtifactVersion: artifact=org.glassfish.jersey.inject:jersey-hk2:jar:2.31:compile, replacement=org.glassfish.jersey.inject:jersey-hk2:jar:2.35
[DEBUG]     testArtifact: artifact=org.glassfish.jersey.inject:jersey-hk2:jar:2.35:compile
[DEBUG]     manageArtifactVersion: artifact=org.glassfish.jersey.inject:jersey-hk2:jar:2.35:compile, replacement=org.glassfish.jersey.inject:jersey-hk2:jar:2.35
[DEBUG]     includeArtifact: artifact=org.glassfish.jersey.inject:jersey-hk2:jar:2.35:compile
[DEBUG]     startProcessChildren: artifact=org.glassfish.jersey.inject:jersey-hk2:jar:2.35:compile
[DEBUG]       manageArtifactVersion: artifact=org.glassfish.jersey.core:jersey-common:jar:2.35:compile, replacement=org.glassfish.jersey.core:jersey-common:jar:2.35
[DEBUG]       testArtifact: artifact=org.glassfish.jersey.core:jersey-common:jar:2.35:compile
[DEBUG]       manageArtifactVersion: artifact=org.glassfish.jersey.core:jersey-common:jar:2.35:compile, replacement=org.glassfish.jersey.core:jersey-common:jar:2.35
[DEBUG]       omitForNearer: omitted=org.glassfish.jersey.core:jersey-common:jar:2.35:compile kept=org.glassfish.jersey.core:jersey-common:jar:2.35:compile
[DEBUG]       manageArtifactVersion: artifact=org.glassfish.hk2:hk2-locator:jar:2.6.1:compile, replacement=org.glassfish.hk2:hk2-locator:jar:2.6.1
[DEBUG]       testArtifact: artifact=org.glassfish.hk2:hk2-locator:jar:2.6.1:compile
[DEBUG]       manageArtifactVersion: artifact=org.glassfish.hk2:hk2-locator:jar:2.6.1:compile, replacement=org.glassfish.hk2:hk2-locator:jar:2.6.1
[DEBUG]       includeArtifact: artifact=org.glassfish.hk2:hk2-locator:jar:2.6.1:compile
[DEBUG]       startProcessChildren: artifact=org.glassfish.hk2:hk2-locator:jar:2.6.1:compile
[DEBUG]         testArtifact: artifact=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]         omitForNearer: omitted=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile kept=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]         testArtifact: artifact=org.glassfish.hk2.external:aopalliance-repackaged:jar:2.6.1:compile
[DEBUG]         includeArtifact: artifact=org.glassfish.hk2.external:aopalliance-repackaged:jar:2.6.1:compile
[DEBUG]         startProcessChildren: artifact=org.glassfish.hk2.external:aopalliance-repackaged:jar:2.6.1:compile
[DEBUG]         endProcessChildren: artifact=org.glassfish.hk2.external:aopalliance-repackaged:jar:2.6.1:compile
[DEBUG]         testArtifact: artifact=org.glassfish.hk2:hk2-api:jar:2.6.1:compile
[DEBUG]         includeArtifact: artifact=org.glassfish.hk2:hk2-api:jar:2.6.1:compile
[DEBUG]         startProcessChildren: artifact=org.glassfish.hk2:hk2-api:jar:2.6.1:compile
[DEBUG]           testArtifact: artifact=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]           omitForNearer: omitted=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile kept=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]           testArtifact: artifact=org.glassfish.hk2:hk2-utils:jar:2.6.1:compile
[DEBUG]           includeArtifact: artifact=org.glassfish.hk2:hk2-utils:jar:2.6.1:compile
[DEBUG]           startProcessChildren: artifact=org.glassfish.hk2:hk2-utils:jar:2.6.1:compile
[DEBUG]             testArtifact: artifact=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]             omitForNearer: omitted=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile kept=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]           endProcessChildren: artifact=org.glassfish.hk2:hk2-utils:jar:2.6.1:compile
[DEBUG]           testArtifact: artifact=org.glassfish.hk2.external:aopalliance-repackaged:jar:2.6.1:compile
[DEBUG]           omitForNearer: omitted=org.glassfish.hk2.external:aopalliance-repackaged:jar:2.6.1:compile kept=org.glassfish.hk2.external:aopalliance-repackaged:jar:2.6.1:compile
[DEBUG]         endProcessChildren: artifact=org.glassfish.hk2:hk2-api:jar:2.6.1:compile
[DEBUG]         testArtifact: artifact=org.glassfish.hk2:hk2-utils:jar:2.6.1:compile
[DEBUG]         omitForNearer: omitted=org.glassfish.hk2:hk2-utils:jar:2.6.1:compile kept=org.glassfish.hk2:hk2-utils:jar:2.6.1:compile
[DEBUG]         includeArtifact: artifact=org.glassfish.hk2:hk2-utils:jar:2.6.1:compile
[DEBUG]         startProcessChildren: artifact=org.glassfish.hk2:hk2-utils:jar:2.6.1:compile
[DEBUG]           testArtifact: artifact=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]           omitForNearer: omitted=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile kept=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]         endProcessChildren: artifact=org.glassfish.hk2:hk2-utils:jar:2.6.1:compile
[DEBUG]       endProcessChildren: artifact=org.glassfish.hk2:hk2-locator:jar:2.6.1:compile
[DEBUG]       manageArtifactVersion: artifact=org.javassist:javassist:jar:3.25.0-GA:compile, replacement=org.javassist:javassist:jar:3.19.0-GA
[DEBUG]       testArtifact: artifact=org.javassist:javassist:jar:3.19.0-GA:compile
[DEBUG]       manageArtifactVersion: artifact=org.javassist:javassist:jar:3.19.0-GA:compile, replacement=org.javassist:javassist:jar:3.19.0-GA
[DEBUG]       includeArtifact: artifact=org.javassist:javassist:jar:3.19.0-GA:compile
[DEBUG]       startProcessChildren: artifact=org.javassist:javassist:jar:3.19.0-GA:compile
[DEBUG]       endProcessChildren: artifact=org.javassist:javassist:jar:3.19.0-GA:compile
[DEBUG]     endProcessChildren: artifact=org.glassfish.jersey.inject:jersey-hk2:jar:2.35:compile
[DEBUG]     manageArtifactVersion: artifact=javax.xml.bind:jaxb-api:jar:2.3.1:compile, replacement=javax.xml.bind:jaxb-api:jar:2.3.0
[DEBUG]     testArtifact: artifact=javax.xml.bind:jaxb-api:jar:2.3.0:compile
[DEBUG]     manageArtifactVersion: artifact=javax.xml.bind:jaxb-api:jar:2.3.0:compile, replacement=javax.xml.bind:jaxb-api:jar:2.3.0
[DEBUG]     includeArtifact: artifact=javax.xml.bind:jaxb-api:jar:2.3.0:compile
[DEBUG]     startProcessChildren: artifact=javax.xml.bind:jaxb-api:jar:2.3.0:compile
[DEBUG]     endProcessChildren: artifact=javax.xml.bind:jaxb-api:jar:2.3.0:compile
[DEBUG]     testArtifact: artifact=com.sun.activation:javax.activation:jar:1.2.0:runtime
[DEBUG]     includeArtifact: artifact=com.sun.activation:javax.activation:jar:1.2.0:runtime
[DEBUG]     startProcessChildren: artifact=com.sun.activation:javax.activation:jar:1.2.0:runtime
[DEBUG]     endProcessChildren: artifact=com.sun.activation:javax.activation:jar:1.2.0:runtime
[DEBUG]     testArtifact: artifact=org.slf4j:jul-to-slf4j:jar:1.7.25:compile
[DEBUG]     includeArtifact: artifact=org.slf4j:jul-to-slf4j:jar:1.7.25:compile
[DEBUG]     startProcessChildren: artifact=org.slf4j:jul-to-slf4j:jar:1.7.25:compile
[DEBUG]       manageArtifactVersion: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile, replacement=org.slf4j:slf4j-api:jar:1.7.25
[DEBUG]       testArtifact: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile
[DEBUG]       manageArtifactVersion: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile, replacement=org.slf4j:slf4j-api:jar:1.7.25
[DEBUG]       omitForNearer: omitted=org.slf4j:slf4j-api:jar:1.7.25:compile kept=org.slf4j:slf4j-api:jar:1.7.25:compile
[DEBUG]     endProcessChildren: artifact=org.slf4j:jul-to-slf4j:jar:1.7.25:compile
[DEBUG]     manageArtifactVersion: artifact=com.google.guava:guava:jar:30.1-jre:compile, replacement=com.google.guava:guava:jar:20.0
[DEBUG]     testArtifact: artifact=com.google.guava:guava:jar:20.0:compile
[DEBUG]     manageArtifactVersion: artifact=com.google.guava:guava:jar:20.0:compile, replacement=com.google.guava:guava:jar:20.0
[DEBUG]     omitForNearer: omitted=com.google.guava:guava:jar:20.0:compile kept=com.google.guava:guava:jar:20.0:compile
[DEBUG]     includeArtifact: artifact=com.google.guava:guava:jar:20.0:compile
[DEBUG]     startProcessChildren: artifact=com.google.guava:guava:jar:20.0:compile
[DEBUG]     endProcessChildren: artifact=com.google.guava:guava:jar:20.0:compile
[DEBUG]     manageArtifactVersion: artifact=com.google.code.gson:gson:jar:2.8.6:compile, replacement=com.google.code.gson:gson:jar:2.2.4
[DEBUG]     testArtifact: artifact=com.google.code.gson:gson:jar:2.2.4:compile
[DEBUG]     manageArtifactVersion: artifact=com.google.code.gson:gson:jar:2.2.4:compile, replacement=com.google.code.gson:gson:jar:2.2.4
[DEBUG]     omitForNearer: omitted=com.google.code.gson:gson:jar:2.2.4:compile kept=com.google.code.gson:gson:jar:2.2.4:compile
[DEBUG]   endProcessChildren: artifact=org.apache.pulsar:pulsar-client-admin-original:jar:2.7.2:compile
[DEBUG]   testArtifact: artifact=javax.servlet:javax.servlet-api:jar:3.1.0:compile
[DEBUG]   includeArtifact: artifact=javax.servlet:javax.servlet-api:jar:3.1.0:compile
[DEBUG]   startProcessChildren: artifact=javax.servlet:javax.servlet-api:jar:3.1.0:compile
[DEBUG]   endProcessChildren: artifact=javax.servlet:javax.servlet-api:jar:3.1.0:compile
[DEBUG]   testArtifact: artifact=javax.ws.rs:javax.ws.rs-api:jar:2.1:compile
[DEBUG]   includeArtifact: artifact=javax.ws.rs:javax.ws.rs-api:jar:2.1:compile
[DEBUG]   startProcessChildren: artifact=javax.ws.rs:javax.ws.rs-api:jar:2.1:compile
[DEBUG]   endProcessChildren: artifact=javax.ws.rs:javax.ws.rs-api:jar:2.1:compile
[DEBUG]   testArtifact: artifact=org.glassfish.jersey.containers:jersey-container-grizzly2-http:jar:2.35:compile
[DEBUG]   includeArtifact: artifact=org.glassfish.jersey.containers:jersey-container-grizzly2-http:jar:2.35:compile
[DEBUG]   startProcessChildren: artifact=org.glassfish.jersey.containers:jersey-container-grizzly2-http:jar:2.35:compile
[DEBUG]     testArtifact: artifact=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]     omitForNearer: omitted=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile kept=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]     includeArtifact: artifact=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]     startProcessChildren: artifact=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]     endProcessChildren: artifact=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]     manageArtifactVersion: artifact=org.glassfish.grizzly:grizzly-http-server:jar:2.4.4:compile, replacement=org.glassfish.grizzly:grizzly-http-server:jar:2.4.4
[DEBUG]     testArtifact: artifact=org.glassfish.grizzly:grizzly-http-server:jar:2.4.4:compile
[DEBUG]     manageArtifactVersion: artifact=org.glassfish.grizzly:grizzly-http-server:jar:2.4.4:compile, replacement=org.glassfish.grizzly:grizzly-http-server:jar:2.4.4
[DEBUG]     includeArtifact: artifact=org.glassfish.grizzly:grizzly-http-server:jar:2.4.4:compile
[DEBUG]     startProcessChildren: artifact=org.glassfish.grizzly:grizzly-http-server:jar:2.4.4:compile
[DEBUG]       testArtifact: artifact=org.glassfish.grizzly:grizzly-http:jar:2.4.4:compile
[DEBUG]       includeArtifact: artifact=org.glassfish.grizzly:grizzly-http:jar:2.4.4:compile
[DEBUG]       startProcessChildren: artifact=org.glassfish.grizzly:grizzly-http:jar:2.4.4:compile
[DEBUG]         testArtifact: artifact=org.glassfish.grizzly:grizzly-framework:jar:2.4.4:compile
[DEBUG]         includeArtifact: artifact=org.glassfish.grizzly:grizzly-framework:jar:2.4.4:compile
[DEBUG]         startProcessChildren: artifact=org.glassfish.grizzly:grizzly-framework:jar:2.4.4:compile
[DEBUG]         endProcessChildren: artifact=org.glassfish.grizzly:grizzly-framework:jar:2.4.4:compile
[DEBUG]       endProcessChildren: artifact=org.glassfish.grizzly:grizzly-http:jar:2.4.4:compile
[DEBUG]     endProcessChildren: artifact=org.glassfish.grizzly:grizzly-http-server:jar:2.4.4:compile
[DEBUG]     manageArtifactVersion: artifact=org.glassfish.jersey.core:jersey-common:jar:2.35:compile, replacement=org.glassfish.jersey.core:jersey-common:jar:2.35
[DEBUG]     testArtifact: artifact=org.glassfish.jersey.core:jersey-common:jar:2.35:compile
[DEBUG]     manageArtifactVersion: artifact=org.glassfish.jersey.core:jersey-common:jar:2.35:compile, replacement=org.glassfish.jersey.core:jersey-common:jar:2.35
[DEBUG]     omitForNearer: omitted=org.glassfish.jersey.core:jersey-common:jar:2.35:compile kept=org.glassfish.jersey.core:jersey-common:jar:2.35:compile
[DEBUG]     includeArtifact: artifact=org.glassfish.jersey.core:jersey-common:jar:2.35:compile
[DEBUG]     startProcessChildren: artifact=org.glassfish.jersey.core:jersey-common:jar:2.35:compile
[DEBUG]       testArtifact: artifact=jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile
[DEBUG]       omitForNearer: omitted=jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile kept=jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile
[DEBUG]       testArtifact: artifact=jakarta.annotation:jakarta.annotation-api:jar:1.3.5:compile
[DEBUG]       includeArtifact: artifact=jakarta.annotation:jakarta.annotation-api:jar:1.3.5:compile
[DEBUG]       startProcessChildren: artifact=jakarta.annotation:jakarta.annotation-api:jar:1.3.5:compile
[DEBUG]       endProcessChildren: artifact=jakarta.annotation:jakarta.annotation-api:jar:1.3.5:compile
[DEBUG]       testArtifact: artifact=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]       omitForNearer: omitted=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile kept=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]       testArtifact: artifact=org.glassfish.hk2:osgi-resource-locator:jar:1.0.3:compile
[DEBUG]       includeArtifact: artifact=org.glassfish.hk2:osgi-resource-locator:jar:1.0.3:compile
[DEBUG]       startProcessChildren: artifact=org.glassfish.hk2:osgi-resource-locator:jar:1.0.3:compile
[DEBUG]       endProcessChildren: artifact=org.glassfish.hk2:osgi-resource-locator:jar:1.0.3:compile
[DEBUG]     endProcessChildren: artifact=org.glassfish.jersey.core:jersey-common:jar:2.35:compile
[DEBUG]     manageArtifactVersion: artifact=org.glassfish.jersey.core:jersey-server:jar:2.35:compile, replacement=org.glassfish.jersey.core:jersey-server:jar:2.35
[DEBUG]     testArtifact: artifact=org.glassfish.jersey.core:jersey-server:jar:2.35:compile
[DEBUG]     manageArtifactVersion: artifact=org.glassfish.jersey.core:jersey-server:jar:2.35:compile, replacement=org.glassfish.jersey.core:jersey-server:jar:2.35
[DEBUG]     includeArtifact: artifact=org.glassfish.jersey.core:jersey-server:jar:2.35:compile
[DEBUG]     startProcessChildren: artifact=org.glassfish.jersey.core:jersey-server:jar:2.35:compile
[DEBUG]       manageArtifactVersion: artifact=org.glassfish.jersey.core:jersey-common:jar:2.35:compile, replacement=org.glassfish.jersey.core:jersey-common:jar:2.35
[DEBUG]       testArtifact: artifact=org.glassfish.jersey.core:jersey-common:jar:2.35:compile
[DEBUG]       manageArtifactVersion: artifact=org.glassfish.jersey.core:jersey-common:jar:2.35:compile, replacement=org.glassfish.jersey.core:jersey-common:jar:2.35
[DEBUG]       omitForNearer: omitted=org.glassfish.jersey.core:jersey-common:jar:2.35:compile kept=org.glassfish.jersey.core:jersey-common:jar:2.35:compile
[DEBUG]       manageArtifactVersion: artifact=org.glassfish.jersey.core:jersey-client:jar:2.35:compile, replacement=org.glassfish.jersey.core:jersey-client:jar:2.35
[DEBUG]       testArtifact: artifact=org.glassfish.jersey.core:jersey-client:jar:2.35:compile
[DEBUG]       manageArtifactVersion: artifact=org.glassfish.jersey.core:jersey-client:jar:2.35:compile, replacement=org.glassfish.jersey.core:jersey-client:jar:2.35
[DEBUG]       omitForNearer: omitted=org.glassfish.jersey.core:jersey-client:jar:2.35:compile kept=org.glassfish.jersey.core:jersey-client:jar:2.35:compile
[DEBUG]       testArtifact: artifact=jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile
[DEBUG]       omitForNearer: omitted=jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile kept=jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile
[DEBUG]       testArtifact: artifact=jakarta.annotation:jakarta.annotation-api:jar:1.3.5:compile
[DEBUG]       omitForNearer: omitted=jakarta.annotation:jakarta.annotation-api:jar:1.3.5:compile kept=jakarta.annotation:jakarta.annotation-api:jar:1.3.5:compile
[DEBUG]       testArtifact: artifact=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]       omitForNearer: omitted=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile kept=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]       testArtifact: artifact=jakarta.validation:jakarta.validation-api:jar:2.0.2:compile
[DEBUG]       includeArtifact: artifact=jakarta.validation:jakarta.validation-api:jar:2.0.2:compile
[DEBUG]       startProcessChildren: artifact=jakarta.validation:jakarta.validation-api:jar:2.0.2:compile
[DEBUG]       endProcessChildren: artifact=jakarta.validation:jakarta.validation-api:jar:2.0.2:compile
[DEBUG]     endProcessChildren: artifact=org.glassfish.jersey.core:jersey-server:jar:2.35:compile
[DEBUG]     testArtifact: artifact=jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile
[DEBUG]     omitForNearer: omitted=jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile kept=jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile
[DEBUG]     includeArtifact: artifact=jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile
[DEBUG]     startProcessChildren: artifact=jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile
[DEBUG]     endProcessChildren: artifact=jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile
[DEBUG]   endProcessChildren: artifact=org.glassfish.jersey.containers:jersey-container-grizzly2-http:jar:2.35:compile
[DEBUG]   testArtifact: artifact=org.glassfish.jersey.core:jersey-server:jar:2.35:compile
[DEBUG]   omitForNearer: omitted=org.glassfish.jersey.core:jersey-server:jar:2.35:compile kept=org.glassfish.jersey.core:jersey-server:jar:2.35:compile
[DEBUG]   includeArtifact: artifact=org.glassfish.jersey.core:jersey-server:jar:2.35:compile
[DEBUG]   startProcessChildren: artifact=org.glassfish.jersey.core:jersey-server:jar:2.35:compile
[DEBUG]     manageArtifactVersion: artifact=org.glassfish.jersey.core:jersey-common:jar:2.35:compile, replacement=org.glassfish.jersey.core:jersey-common:jar:2.35
[DEBUG]     testArtifact: artifact=org.glassfish.jersey.core:jersey-common:jar:2.35:compile
[DEBUG]     manageArtifactVersion: artifact=org.glassfish.jersey.core:jersey-common:jar:2.35:compile, replacement=org.glassfish.jersey.core:jersey-common:jar:2.35
[DEBUG]     omitForNearer: omitted=org.glassfish.jersey.core:jersey-common:jar:2.35:compile kept=org.glassfish.jersey.core:jersey-common:jar:2.35:compile
[DEBUG]     manageArtifactVersion: artifact=org.glassfish.jersey.core:jersey-client:jar:2.35:compile, replacement=org.glassfish.jersey.core:jersey-client:jar:2.35
[DEBUG]     testArtifact: artifact=org.glassfish.jersey.core:jersey-client:jar:2.35:compile
[DEBUG]     manageArtifactVersion: artifact=org.glassfish.jersey.core:jersey-client:jar:2.35:compile, replacement=org.glassfish.jersey.core:jersey-client:jar:2.35
[DEBUG]     omitForNearer: omitted=org.glassfish.jersey.core:jersey-client:jar:2.35:compile kept=org.glassfish.jersey.core:jersey-client:jar:2.35:compile
[DEBUG]     testArtifact: artifact=jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile
[DEBUG]     omitForNearer: omitted=jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile kept=jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile
[DEBUG]     testArtifact: artifact=jakarta.annotation:jakarta.annotation-api:jar:1.3.5:compile
[DEBUG]     omitForNearer: omitted=jakarta.annotation:jakarta.annotation-api:jar:1.3.5:compile kept=jakarta.annotation:jakarta.annotation-api:jar:1.3.5:compile
[DEBUG]     includeArtifact: artifact=jakarta.annotation:jakarta.annotation-api:jar:1.3.5:compile
[DEBUG]     startProcessChildren: artifact=jakarta.annotation:jakarta.annotation-api:jar:1.3.5:compile
[DEBUG]     endProcessChildren: artifact=jakarta.annotation:jakarta.annotation-api:jar:1.3.5:compile
[DEBUG]     testArtifact: artifact=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]     omitForNearer: omitted=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile kept=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]     testArtifact: artifact=jakarta.validation:jakarta.validation-api:jar:2.0.2:compile
[DEBUG]     includeArtifact: artifact=jakarta.validation:jakarta.validation-api:jar:2.0.2:compile
[DEBUG]     startProcessChildren: artifact=jakarta.validation:jakarta.validation-api:jar:2.0.2:compile
[DEBUG]     endProcessChildren: artifact=jakarta.validation:jakarta.validation-api:jar:2.0.2:compile
[DEBUG]   endProcessChildren: artifact=org.glassfish.jersey.core:jersey-server:jar:2.35:compile
[DEBUG]   testArtifact: artifact=org.glassfish.jersey.containers:jersey-container-servlet-core:jar:2.35:compile
[DEBUG]   includeArtifact: artifact=org.glassfish.jersey.containers:jersey-container-servlet-core:jar:2.35:compile
[DEBUG]   startProcessChildren: artifact=org.glassfish.jersey.containers:jersey-container-servlet-core:jar:2.35:compile
[DEBUG]     testArtifact: artifact=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]     omitForNearer: omitted=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile kept=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]     manageArtifactVersion: artifact=org.glassfish.jersey.core:jersey-common:jar:2.35:compile, replacement=org.glassfish.jersey.core:jersey-common:jar:2.35
[DEBUG]     testArtifact: artifact=org.glassfish.jersey.core:jersey-common:jar:2.35:compile
[DEBUG]     manageArtifactVersion: artifact=org.glassfish.jersey.core:jersey-common:jar:2.35:compile, replacement=org.glassfish.jersey.core:jersey-common:jar:2.35
[DEBUG]     omitForNearer: omitted=org.glassfish.jersey.core:jersey-common:jar:2.35:compile kept=org.glassfish.jersey.core:jersey-common:jar:2.35:compile
[DEBUG]     manageArtifactVersion: artifact=org.glassfish.jersey.core:jersey-server:jar:2.35:compile, replacement=org.glassfish.jersey.core:jersey-server:jar:2.35
[DEBUG]     testArtifact: artifact=org.glassfish.jersey.core:jersey-server:jar:2.35:compile
[DEBUG]     manageArtifactVersion: artifact=org.glassfish.jersey.core:jersey-server:jar:2.35:compile, replacement=org.glassfish.jersey.core:jersey-server:jar:2.35
[DEBUG]     omitForNearer: omitted=org.glassfish.jersey.core:jersey-server:jar:2.35:compile kept=org.glassfish.jersey.core:jersey-server:jar:2.35:compile
[DEBUG]     testArtifact: artifact=jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile
[DEBUG]     omitForNearer: omitted=jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile kept=jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile
[DEBUG]   endProcessChildren: artifact=org.glassfish.jersey.containers:jersey-container-servlet-core:jar:2.35:compile
[DEBUG]   testArtifact: artifact=io.netty:netty-resolver:jar:4.1.74.Final:compile
[DEBUG]   includeArtifact: artifact=io.netty:netty-resolver:jar:4.1.74.Final:compile
[DEBUG]   startProcessChildren: artifact=io.netty:netty-resolver:jar:4.1.74.Final:compile
[DEBUG]     manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]     testArtifact: artifact=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]     manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]     omitForNearer: omitted=io.netty:netty-common:jar:4.1.74.Final:compile kept=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]     includeArtifact: artifact=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]     startProcessChildren: artifact=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]     endProcessChildren: artifact=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]   endProcessChildren: artifact=io.netty:netty-resolver:jar:4.1.74.Final:compile
[DEBUG]   testArtifact: artifact=io.prometheus:simpleclient_common:jar:0.8.1:compile
[DEBUG]   includeArtifact: artifact=io.prometheus:simpleclient_common:jar:0.8.1:compile
[DEBUG]   startProcessChildren: artifact=io.prometheus:simpleclient_common:jar:0.8.1:compile
[DEBUG]     testArtifact: artifact=io.prometheus:simpleclient:jar:0.8.1:compile
[DEBUG]     includeArtifact: artifact=io.prometheus:simpleclient:jar:0.8.1:compile
[DEBUG]     startProcessChildren: artifact=io.prometheus:simpleclient:jar:0.8.1:compile
[DEBUG]     endProcessChildren: artifact=io.prometheus:simpleclient:jar:0.8.1:compile
[DEBUG]   endProcessChildren: artifact=io.prometheus:simpleclient_common:jar:0.8.1:compile
[DEBUG]   testArtifact: artifact=com.google.api.grpc:proto-google-common-protos:jar:1.12.0:compile
[DEBUG]   includeArtifact: artifact=com.google.api.grpc:proto-google-common-protos:jar:1.12.0:compile
[DEBUG]   startProcessChildren: artifact=com.google.api.grpc:proto-google-common-protos:jar:1.12.0:compile
[DEBUG]     manageArtifactVersion: artifact=com.google.protobuf:protobuf-java:jar:3.5.1:compile, replacement=com.google.protobuf:protobuf-java:jar:3.19.2
[DEBUG]     testArtifact: artifact=com.google.protobuf:protobuf-java:jar:3.19.2:compile
[DEBUG]     manageArtifactVersion: artifact=com.google.protobuf:protobuf-java:jar:3.19.2:compile, replacement=com.google.protobuf:protobuf-java:jar:3.19.2
[DEBUG]     omitForNearer: omitted=com.google.protobuf:protobuf-java:jar:3.19.2:compile kept=com.google.protobuf:protobuf-java:jar:3.19.2:compile
[DEBUG]     includeArtifact: artifact=com.google.protobuf:protobuf-java:jar:3.19.2:compile
[DEBUG]     startProcessChildren: artifact=com.google.protobuf:protobuf-java:jar:3.19.2:compile
[DEBUG]     endProcessChildren: artifact=com.google.protobuf:protobuf-java:jar:3.19.2:compile
[DEBUG]   endProcessChildren: artifact=com.google.api.grpc:proto-google-common-protos:jar:1.12.0:compile
[DEBUG]   testArtifact: artifact=io.grpc:grpc-context:jar:1.14.0:compile
[DEBUG]   includeArtifact: artifact=io.grpc:grpc-context:jar:1.14.0:compile
[DEBUG]   startProcessChildren: artifact=io.grpc:grpc-context:jar:1.14.0:compile
[DEBUG]   endProcessChildren: artifact=io.grpc:grpc-context:jar:1.14.0:compile
[DEBUG]   testArtifact: artifact=commons-codec:commons-codec:jar:1.11:compile
[DEBUG]   includeArtifact: artifact=commons-codec:commons-codec:jar:1.11:compile
[DEBUG]   startProcessChildren: artifact=commons-codec:commons-codec:jar:1.11:compile
[DEBUG]   endProcessChildren: artifact=commons-codec:commons-codec:jar:1.11:compile
[DEBUG]   testArtifact: artifact=com.google.errorprone:error_prone_annotations:jar:2.3.4:compile
[DEBUG]   omitForNearer: omitted=com.google.errorprone:error_prone_annotations:jar:2.3.4:compile kept=com.google.errorprone:error_prone_annotations:jar:2.3.4:compile
[DEBUG]   includeArtifact: artifact=com.google.errorprone:error_prone_annotations:jar:2.3.4:compile
[DEBUG]   startProcessChildren: artifact=com.google.errorprone:error_prone_annotations:jar:2.3.4:compile
[DEBUG]   endProcessChildren: artifact=com.google.errorprone:error_prone_annotations:jar:2.3.4:compile
[DEBUG]   testArtifact: artifact=io.prometheus:simpleclient:jar:0.8.1:compile
[DEBUG]   omitForNearer: omitted=io.prometheus:simpleclient:jar:0.8.1:compile kept=io.prometheus:simpleclient:jar:0.8.1:compile
[DEBUG]   includeArtifact: artifact=io.prometheus:simpleclient:jar:0.8.1:compile
[DEBUG]   startProcessChildren: artifact=io.prometheus:simpleclient:jar:0.8.1:compile
[DEBUG]   endProcessChildren: artifact=io.prometheus:simpleclient:jar:0.8.1:compile
[DEBUG]   testArtifact: artifact=org.eclipse.jetty:jetty-servlet:jar:9.4.45.v20220203:compile
[DEBUG]   includeArtifact: artifact=org.eclipse.jetty:jetty-servlet:jar:9.4.45.v20220203:compile
[DEBUG]   startProcessChildren: artifact=org.eclipse.jetty:jetty-servlet:jar:9.4.45.v20220203:compile
[DEBUG]     testArtifact: artifact=org.eclipse.jetty:jetty-security:jar:9.4.45.v20220203:compile
[DEBUG]     includeArtifact: artifact=org.eclipse.jetty:jetty-security:jar:9.4.45.v20220203:compile
[DEBUG]     startProcessChildren: artifact=org.eclipse.jetty:jetty-security:jar:9.4.45.v20220203:compile
[DEBUG]       testArtifact: artifact=org.eclipse.jetty:jetty-server:jar:9.4.45.v20220203:compile
[DEBUG]       omitForNearer: omitted=org.eclipse.jetty:jetty-server:jar:9.4.45.v20220203:compile kept=org.eclipse.jetty:jetty-server:jar:9.4.45.v20220203:compile
[DEBUG]     endProcessChildren: artifact=org.eclipse.jetty:jetty-security:jar:9.4.45.v20220203:compile
[DEBUG]     testArtifact: artifact=org.eclipse.jetty:jetty-util-ajax:jar:9.4.45.v20220203:compile
[DEBUG]     includeArtifact: artifact=org.eclipse.jetty:jetty-util-ajax:jar:9.4.45.v20220203:compile
[DEBUG]     startProcessChildren: artifact=org.eclipse.jetty:jetty-util-ajax:jar:9.4.45.v20220203:compile
[DEBUG]       testArtifact: artifact=org.eclipse.jetty:jetty-util:jar:9.4.45.v20220203:compile
[DEBUG]       omitForNearer: omitted=org.eclipse.jetty:jetty-util:jar:9.4.45.v20220203:compile kept=org.eclipse.jetty:jetty-util:jar:9.4.45.v20220203:compile
[DEBUG]     endProcessChildren: artifact=org.eclipse.jetty:jetty-util-ajax:jar:9.4.45.v20220203:compile
[DEBUG]   endProcessChildren: artifact=org.eclipse.jetty:jetty-servlet:jar:9.4.45.v20220203:compile
[DEBUG]   testArtifact: artifact=com.squareup.okio:okio:jar:1.6.0:compile
[DEBUG]   includeArtifact: artifact=com.squareup.okio:okio:jar:1.6.0:compile
[DEBUG]   startProcessChildren: artifact=com.squareup.okio:okio:jar:1.6.0:compile
[DEBUG]   endProcessChildren: artifact=com.squareup.okio:okio:jar:1.6.0:compile
[DEBUG]   testArtifact: artifact=io.prometheus:simpleclient_hotspot:jar:0.8.1:compile
[DEBUG]   includeArtifact: artifact=io.prometheus:simpleclient_hotspot:jar:0.8.1:compile
[DEBUG]   startProcessChildren: artifact=io.prometheus:simpleclient_hotspot:jar:0.8.1:compile
[DEBUG]     testArtifact: artifact=io.prometheus:simpleclient:jar:0.8.1:compile
[DEBUG]     omitForNearer: omitted=io.prometheus:simpleclient:jar:0.8.1:compile kept=io.prometheus:simpleclient:jar:0.8.1:compile
[DEBUG]   endProcessChildren: artifact=io.prometheus:simpleclient_hotspot:jar:0.8.1:compile
[DEBUG]   testArtifact: artifact=io.swagger:swagger-annotations:jar:1.5.21:compile
[DEBUG]   omitForNearer: omitted=io.swagger:swagger-annotations:jar:1.5.21:compile kept=io.swagger:swagger-annotations:jar:1.5.21:compile
[DEBUG]   includeArtifact: artifact=io.swagger:swagger-annotations:jar:1.5.21:compile
[DEBUG]   startProcessChildren: artifact=io.swagger:swagger-annotations:jar:1.5.21:compile
[DEBUG]   endProcessChildren: artifact=io.swagger:swagger-annotations:jar:1.5.21:compile
[DEBUG]   testArtifact: artifact=io.grpc:grpc-protobuf-lite:jar:1.19.0:compile
[DEBUG]   includeArtifact: artifact=io.grpc:grpc-protobuf-lite:jar:1.19.0:compile
[DEBUG]   startProcessChildren: artifact=io.grpc:grpc-protobuf-lite:jar:1.19.0:compile
[DEBUG]     testArtifact: artifact=io.grpc:grpc-core:jar:1.19.0:compile
[DEBUG]     includeArtifact: artifact=io.grpc:grpc-core:jar:1.19.0:compile
[DEBUG]     startProcessChildren: artifact=io.grpc:grpc-core:jar:1.19.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.google.code.gson:gson:jar:2.7:compile, replacement=com.google.code.gson:gson:jar:2.2.4
[DEBUG]       testArtifact: artifact=com.google.code.gson:gson:jar:2.2.4:compile
[DEBUG]       manageArtifactVersion: artifact=com.google.code.gson:gson:jar:2.2.4:compile, replacement=com.google.code.gson:gson:jar:2.2.4
[DEBUG]       omitForNearer: omitted=com.google.code.gson:gson:jar:2.2.4:compile kept=com.google.code.gson:gson:jar:2.2.4:compile
[DEBUG]       manageArtifactVersion: artifact=com.google.code.findbugs:jsr305:jar:3.0.2:compile, replacement=com.google.code.findbugs:jsr305:jar:3.0.0
[DEBUG]       testArtifact: artifact=com.google.code.findbugs:jsr305:jar:3.0.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.google.code.findbugs:jsr305:jar:3.0.0:compile, replacement=com.google.code.findbugs:jsr305:jar:3.0.0
[DEBUG]       includeArtifact: artifact=com.google.code.findbugs:jsr305:jar:3.0.0:compile
[DEBUG]       startProcessChildren: artifact=com.google.code.findbugs:jsr305:jar:3.0.0:compile
[DEBUG]       endProcessChildren: artifact=com.google.code.findbugs:jsr305:jar:3.0.0:compile
[DEBUG]       testArtifact: artifact=org.codehaus.mojo:animal-sniffer-annotations:jar:1.17:compile
[DEBUG]       includeArtifact: artifact=org.codehaus.mojo:animal-sniffer-annotations:jar:1.17:compile
[DEBUG]       startProcessChildren: artifact=org.codehaus.mojo:animal-sniffer-annotations:jar:1.17:compile
[DEBUG]       endProcessChildren: artifact=org.codehaus.mojo:animal-sniffer-annotations:jar:1.17:compile
[DEBUG]       manageArtifactVersion: artifact=com.google.guava:guava:jar:26.0-android:compile, replacement=com.google.guava:guava:jar:20.0
[DEBUG]       testArtifact: artifact=com.google.guava:guava:jar:20.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.google.guava:guava:jar:20.0:compile, replacement=com.google.guava:guava:jar:20.0
[DEBUG]       omitForNearer: omitted=com.google.guava:guava:jar:20.0:compile kept=com.google.guava:guava:jar:20.0:compile
[DEBUG]       testArtifact: artifact=io.opencensus:opencensus-api:jar:0.19.2:compile
[DEBUG]       includeArtifact: artifact=io.opencensus:opencensus-api:jar:0.19.2:compile
[DEBUG]       startProcessChildren: artifact=io.opencensus:opencensus-api:jar:0.19.2:compile
[DEBUG]       endProcessChildren: artifact=io.opencensus:opencensus-api:jar:0.19.2:compile
[DEBUG]       testArtifact: artifact=io.opencensus:opencensus-contrib-grpc-metrics:jar:0.19.2:compile
[DEBUG]       includeArtifact: artifact=io.opencensus:opencensus-contrib-grpc-metrics:jar:0.19.2:compile
[DEBUG]       startProcessChildren: artifact=io.opencensus:opencensus-contrib-grpc-metrics:jar:0.19.2:compile
[DEBUG]         testArtifact: artifact=io.opencensus:opencensus-api:jar:0.19.2:compile
[DEBUG]         omitForNearer: omitted=io.opencensus:opencensus-api:jar:0.19.2:compile kept=io.opencensus:opencensus-api:jar:0.19.2:compile
[DEBUG]       endProcessChildren: artifact=io.opencensus:opencensus-contrib-grpc-metrics:jar:0.19.2:compile
[DEBUG]     endProcessChildren: artifact=io.grpc:grpc-core:jar:1.19.0:compile
[DEBUG]     testArtifact: artifact=com.google.protobuf:protobuf-lite:jar:3.0.1:compile
[DEBUG]     includeArtifact: artifact=com.google.protobuf:protobuf-lite:jar:3.0.1:compile
[DEBUG]     startProcessChildren: artifact=com.google.protobuf:protobuf-lite:jar:3.0.1:compile
[DEBUG]     endProcessChildren: artifact=com.google.protobuf:protobuf-lite:jar:3.0.1:compile
[DEBUG]     manageArtifactVersion: artifact=com.google.guava:guava:jar:26.0-android:compile, replacement=com.google.guava:guava:jar:20.0
[DEBUG]     testArtifact: artifact=com.google.guava:guava:jar:20.0:compile
[DEBUG]     manageArtifactVersion: artifact=com.google.guava:guava:jar:20.0:compile, replacement=com.google.guava:guava:jar:20.0
[DEBUG]     omitForNearer: omitted=com.google.guava:guava:jar:20.0:compile kept=com.google.guava:guava:jar:20.0:compile
[DEBUG]   endProcessChildren: artifact=io.grpc:grpc-protobuf-lite:jar:1.19.0:compile
[DEBUG]   testArtifact: artifact=org.apache.commons:commons-collections4:jar:4.1:compile
[DEBUG]   includeArtifact: artifact=org.apache.commons:commons-collections4:jar:4.1:compile
[DEBUG]   startProcessChildren: artifact=org.apache.commons:commons-collections4:jar:4.1:compile
[DEBUG]   endProcessChildren: artifact=org.apache.commons:commons-collections4:jar:4.1:compile
[DEBUG]   testArtifact: artifact=javax.annotation:javax.annotation-api:jar:1.2:compile
[DEBUG]   includeArtifact: artifact=javax.annotation:javax.annotation-api:jar:1.2:compile
[DEBUG]   startProcessChildren: artifact=javax.annotation:javax.annotation-api:jar:1.2:compile
[DEBUG]   endProcessChildren: artifact=javax.annotation:javax.annotation-api:jar:1.2:compile
[DEBUG]   testArtifact: artifact=org.codehaus.mojo:animal-sniffer-annotations:jar:1.17:compile
[DEBUG]   omitForNearer: omitted=org.codehaus.mojo:animal-sniffer-annotations:jar:1.17:compile kept=org.codehaus.mojo:animal-sniffer-annotations:jar:1.17:compile
[DEBUG]   includeArtifact: artifact=org.codehaus.mojo:animal-sniffer-annotations:jar:1.17:compile
[DEBUG]   startProcessChildren: artifact=org.codehaus.mojo:animal-sniffer-annotations:jar:1.17:compile
[DEBUG]   endProcessChildren: artifact=org.codehaus.mojo:animal-sniffer-annotations:jar:1.17:compile
[DEBUG]   testArtifact: artifact=com.github.ben-manes.caffeine:caffeine:jar:2.6.2:compile
[DEBUG]   includeArtifact: artifact=com.github.ben-manes.caffeine:caffeine:jar:2.6.2:compile
[DEBUG]   startProcessChildren: artifact=com.github.ben-manes.caffeine:caffeine:jar:2.6.2:compile
[DEBUG]   endProcessChildren: artifact=com.github.ben-manes.caffeine:caffeine:jar:2.6.2:compile
[DEBUG]   testArtifact: artifact=io.netty:netty-codec-socks:jar:4.1.74.Final:compile
[DEBUG]   includeArtifact: artifact=io.netty:netty-codec-socks:jar:4.1.74.Final:compile
[DEBUG]   startProcessChildren: artifact=io.netty:netty-codec-socks:jar:4.1.74.Final:compile
[DEBUG]     manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]     testArtifact: artifact=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]     manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]     omitForNearer: omitted=io.netty:netty-common:jar:4.1.74.Final:compile kept=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]     manageArtifactVersion: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile, replacement=io.netty:netty-buffer:jar:4.1.74.Final
[DEBUG]     testArtifact: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]     manageArtifactVersion: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile, replacement=io.netty:netty-buffer:jar:4.1.74.Final
[DEBUG]     omitForNearer: omitted=io.netty:netty-buffer:jar:4.1.74.Final:compile kept=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]     includeArtifact: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]     startProcessChildren: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]       testArtifact: artifact=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]       omitForNearer: omitted=io.netty:netty-common:jar:4.1.74.Final:compile kept=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]     endProcessChildren: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]     manageArtifactVersion: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile, replacement=io.netty:netty-transport:jar:4.1.74.Final
[DEBUG]     testArtifact: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG]     manageArtifactVersion: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile, replacement=io.netty:netty-transport:jar:4.1.74.Final
[DEBUG]     omitForNearer: omitted=io.netty:netty-transport:jar:4.1.74.Final:compile kept=io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG]     includeArtifact: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG]     startProcessChildren: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]       testArtifact: artifact=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]       omitForNearer: omitted=io.netty:netty-common:jar:4.1.74.Final:compile kept=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile, replacement=io.netty:netty-buffer:jar:4.1.74.Final
[DEBUG]       testArtifact: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile, replacement=io.netty:netty-buffer:jar:4.1.74.Final
[DEBUG]       omitForNearer: omitted=io.netty:netty-buffer:jar:4.1.74.Final:compile kept=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-resolver:jar:4.1.74.Final:compile, replacement=io.netty:netty-resolver:jar:4.1.74.Final
[DEBUG]       testArtifact: artifact=io.netty:netty-resolver:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-resolver:jar:4.1.74.Final:compile, replacement=io.netty:netty-resolver:jar:4.1.74.Final
[DEBUG]       omitForNearer: omitted=io.netty:netty-resolver:jar:4.1.74.Final:compile kept=io.netty:netty-resolver:jar:4.1.74.Final:compile
[DEBUG]     endProcessChildren: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG]     manageArtifactVersion: artifact=io.netty:netty-codec:jar:4.1.74.Final:compile, replacement=io.netty:netty-codec:jar:4.1.74.Final
[DEBUG]     testArtifact: artifact=io.netty:netty-codec:jar:4.1.74.Final:compile
[DEBUG]     manageArtifactVersion: artifact=io.netty:netty-codec:jar:4.1.74.Final:compile, replacement=io.netty:netty-codec:jar:4.1.74.Final
[DEBUG]     omitForNearer: omitted=io.netty:netty-codec:jar:4.1.74.Final:compile kept=io.netty:netty-codec:jar:4.1.74.Final:compile
[DEBUG]     includeArtifact: artifact=io.netty:netty-codec:jar:4.1.74.Final:compile
[DEBUG]     startProcessChildren: artifact=io.netty:netty-codec:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]       testArtifact: artifact=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]       omitForNearer: omitted=io.netty:netty-common:jar:4.1.74.Final:compile kept=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile, replacement=io.netty:netty-buffer:jar:4.1.74.Final
[DEBUG]       testArtifact: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile, replacement=io.netty:netty-buffer:jar:4.1.74.Final
[DEBUG]       omitForNearer: omitted=io.netty:netty-buffer:jar:4.1.74.Final:compile kept=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile, replacement=io.netty:netty-transport:jar:4.1.74.Final
[DEBUG]       testArtifact: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile, replacement=io.netty:netty-transport:jar:4.1.74.Final
[DEBUG]       omitForNearer: omitted=io.netty:netty-transport:jar:4.1.74.Final:compile kept=io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG]     endProcessChildren: artifact=io.netty:netty-codec:jar:4.1.74.Final:compile
[DEBUG]   endProcessChildren: artifact=io.netty:netty-codec-socks:jar:4.1.74.Final:compile
[DEBUG]   testArtifact: artifact=org.bouncycastle:bcpkix-jdk15to18:jar:1.68:compile
[DEBUG]   includeArtifact: artifact=org.bouncycastle:bcpkix-jdk15to18:jar:1.68:compile
[DEBUG]   startProcessChildren: artifact=org.bouncycastle:bcpkix-jdk15to18:jar:1.68:compile
[DEBUG]     testArtifact: artifact=org.bouncycastle:bcprov-jdk15to18:jar:1.68:compile
[DEBUG]     includeArtifact: artifact=org.bouncycastle:bcprov-jdk15to18:jar:1.68:compile
[DEBUG]     startProcessChildren: artifact=org.bouncycastle:bcprov-jdk15to18:jar:1.68:compile
[DEBUG]     endProcessChildren: artifact=org.bouncycastle:bcprov-jdk15to18:jar:1.68:compile
[DEBUG]   endProcessChildren: artifact=org.bouncycastle:bcpkix-jdk15to18:jar:1.68:compile
[DEBUG]   testArtifact: artifact=org.bouncycastle:bcprov-ext-jdk15to18:jar:1.68:compile
[DEBUG]   includeArtifact: artifact=org.bouncycastle:bcprov-ext-jdk15to18:jar:1.68:compile
[DEBUG]   startProcessChildren: artifact=org.bouncycastle:bcprov-ext-jdk15to18:jar:1.68:compile
[DEBUG]   endProcessChildren: artifact=org.bouncycastle:bcprov-ext-jdk15to18:jar:1.68:compile
[DEBUG]   testArtifact: artifact=org.bouncycastle:bcprov-jdk15to18:jar:1.68:compile
[DEBUG]   omitForNearer: omitted=org.bouncycastle:bcprov-jdk15to18:jar:1.68:compile kept=org.bouncycastle:bcprov-jdk15to18:jar:1.68:compile
[DEBUG]   includeArtifact: artifact=org.bouncycastle:bcprov-jdk15to18:jar:1.68:compile
[DEBUG]   startProcessChildren: artifact=org.bouncycastle:bcprov-jdk15to18:jar:1.68:compile
[DEBUG]   endProcessChildren: artifact=org.bouncycastle:bcprov-jdk15to18:jar:1.68:compile
[DEBUG]   testArtifact: artifact=org.apache.pinot:pinot-spi:jar:0.11.0-SNAPSHOT:compile
[DEBUG]   includeArtifact: artifact=org.apache.pinot:pinot-spi:jar:0.11.0-SNAPSHOT:compile
[DEBUG]   startProcessChildren: artifact=org.apache.pinot:pinot-spi:jar:0.11.0-SNAPSHOT:compile
[DEBUG]     manageArtifactVersion: artifact=commons-configuration:commons-configuration:jar:1.10:compile, replacement=commons-configuration:commons-configuration:jar:1.10
[DEBUG]     testArtifact: artifact=commons-configuration:commons-configuration:jar:1.10:compile
[DEBUG]     manageArtifactVersion: artifact=commons-configuration:commons-configuration:jar:1.10:compile, replacement=commons-configuration:commons-configuration:jar:1.10
[DEBUG]     omitForNearer: omitted=commons-configuration:commons-configuration:jar:1.10:compile kept=commons-configuration:commons-configuration:jar:1.10:compile
[DEBUG]     includeArtifact: artifact=commons-configuration:commons-configuration:jar:1.10:compile
[DEBUG]     startProcessChildren: artifact=commons-configuration:commons-configuration:jar:1.10:compile
[DEBUG]     endProcessChildren: artifact=commons-configuration:commons-configuration:jar:1.10:compile
[DEBUG]     manageArtifactVersion: artifact=commons-io:commons-io:jar:2.11.0:compile, replacement=commons-io:commons-io:jar:2.11.0
[DEBUG]     testArtifact: artifact=commons-io:commons-io:jar:2.11.0:compile
[DEBUG]     manageArtifactVersion: artifact=commons-io:commons-io:jar:2.11.0:compile, replacement=commons-io:commons-io:jar:2.11.0
[DEBUG]     omitForNearer: omitted=commons-io:commons-io:jar:2.11.0:compile kept=commons-io:commons-io:jar:2.11.0:compile
[DEBUG]     includeArtifact: artifact=commons-io:commons-io:jar:2.11.0:compile
[DEBUG]     startProcessChildren: artifact=commons-io:commons-io:jar:2.11.0:compile
[DEBUG]     endProcessChildren: artifact=commons-io:commons-io:jar:2.11.0:compile
[DEBUG]     manageArtifactVersion: artifact=commons-lang:commons-lang:jar:2.6:compile, replacement=commons-lang:commons-lang:jar:2.6
[DEBUG]     testArtifact: artifact=commons-lang:commons-lang:jar:2.6:compile
[DEBUG]     manageArtifactVersion: artifact=commons-lang:commons-lang:jar:2.6:compile, replacement=commons-lang:commons-lang:jar:2.6
[DEBUG]     includeArtifact: artifact=commons-lang:commons-lang:jar:2.6:compile
[DEBUG]     startProcessChildren: artifact=commons-lang:commons-lang:jar:2.6:compile
[DEBUG]     endProcessChildren: artifact=commons-lang:commons-lang:jar:2.6:compile
[DEBUG]     manageArtifactVersion: artifact=commons-logging:commons-logging:jar:1.2:compile, replacement=commons-logging:commons-logging:jar:1.2
[DEBUG]     testArtifact: artifact=commons-logging:commons-logging:jar:1.2:compile
[DEBUG]     manageArtifactVersion: artifact=commons-logging:commons-logging:jar:1.2:compile, replacement=commons-logging:commons-logging:jar:1.2
[DEBUG]     includeArtifact: artifact=commons-logging:commons-logging:jar:1.2:compile
[DEBUG]     startProcessChildren: artifact=commons-logging:commons-logging:jar:1.2:compile
[DEBUG]     endProcessChildren: artifact=commons-logging:commons-logging:jar:1.2:compile
[DEBUG]     manageArtifactVersion: artifact=org.apache.commons:commons-lang3:jar:3.5:compile, replacement=org.apache.commons:commons-lang3:jar:3.5
[DEBUG]     testArtifact: artifact=org.apache.commons:commons-lang3:jar:3.5:compile
[DEBUG]     manageArtifactVersion: artifact=org.apache.commons:commons-lang3:jar:3.5:compile, replacement=org.apache.commons:commons-lang3:jar:3.5
[DEBUG]     omitForNearer: omitted=org.apache.commons:commons-lang3:jar:3.5:compile kept=org.apache.commons:commons-lang3:jar:3.5:compile
[DEBUG]     manageArtifactVersion: artifact=commons-collections:commons-collections:jar:3.2.2:compile, replacement=commons-collections:commons-collections:jar:3.2.2
[DEBUG]     testArtifact: artifact=commons-collections:commons-collections:jar:3.2.2:compile
[DEBUG]     manageArtifactVersion: artifact=commons-collections:commons-collections:jar:3.2.2:compile, replacement=commons-collections:commons-collections:jar:3.2.2
[DEBUG]     includeArtifact: artifact=commons-collections:commons-collections:jar:3.2.2:compile
[DEBUG]     startProcessChildren: artifact=commons-collections:commons-collections:jar:3.2.2:compile
[DEBUG]     endProcessChildren: artifact=commons-collections:commons-collections:jar:3.2.2:compile
[DEBUG]     manageArtifactVersion: artifact=com.google.guava:guava:jar:20.0:compile, replacement=com.google.guava:guava:jar:20.0
[DEBUG]     testArtifact: artifact=com.google.guava:guava:jar:20.0:compile
[DEBUG]     manageArtifactVersion: artifact=com.google.guava:guava:jar:20.0:compile, replacement=com.google.guava:guava:jar:20.0
[DEBUG]     omitForNearer: omitted=com.google.guava:guava:jar:20.0:compile kept=com.google.guava:guava:jar:20.0:compile
[DEBUG]     manageArtifactVersion: artifact=com.google.code.findbugs:jsr305:jar:3.0.0:compile, replacement=com.google.code.findbugs:jsr305:jar:3.0.0
[DEBUG]     testArtifact: artifact=com.google.code.findbugs:jsr305:jar:3.0.0:compile
[DEBUG]     manageArtifactVersion: artifact=com.google.code.findbugs:jsr305:jar:3.0.0:compile, replacement=com.google.code.findbugs:jsr305:jar:3.0.0
[DEBUG]     omitForNearer: omitted=com.google.code.findbugs:jsr305:jar:3.0.0:compile kept=com.google.code.findbugs:jsr305:jar:3.0.0:compile
[DEBUG]     includeArtifact: artifact=com.google.code.findbugs:jsr305:jar:3.0.0:compile
[DEBUG]     startProcessChildren: artifact=com.google.code.findbugs:jsr305:jar:3.0.0:compile
[DEBUG]     endProcessChildren: artifact=com.google.code.findbugs:jsr305:jar:3.0.0:compile
[DEBUG]     manageArtifactVersion: artifact=org.apache.logging.log4j:log4j-slf4j-impl:jar:2.17.1:compile, replacement=org.apache.logging.log4j:log4j-slf4j-impl:jar:2.17.1
[DEBUG]     testArtifact: artifact=org.apache.logging.log4j:log4j-slf4j-impl:jar:2.17.1:compile
[DEBUG]     manageArtifactVersion: artifact=org.apache.logging.log4j:log4j-slf4j-impl:jar:2.17.1:compile, replacement=org.apache.logging.log4j:log4j-slf4j-impl:jar:2.17.1
[DEBUG]     includeArtifact: artifact=org.apache.logging.log4j:log4j-slf4j-impl:jar:2.17.1:compile
[DEBUG]     startProcessChildren: artifact=org.apache.logging.log4j:log4j-slf4j-impl:jar:2.17.1:compile
[DEBUG]       manageArtifactVersion: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile, replacement=org.slf4j:slf4j-api:jar:1.7.25
[DEBUG]       testArtifact: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile
[DEBUG]       manageArtifactVersion: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile, replacement=org.slf4j:slf4j-api:jar:1.7.25
[DEBUG]       omitForNearer: omitted=org.slf4j:slf4j-api:jar:1.7.25:compile kept=org.slf4j:slf4j-api:jar:1.7.25:compile
[DEBUG]       manageArtifactVersion: artifact=org.apache.logging.log4j:log4j-api:jar:2.17.1:compile, replacement=org.apache.logging.log4j:log4j-api:jar:2.17.1
[DEBUG]       testArtifact: artifact=org.apache.logging.log4j:log4j-api:jar:2.17.1:compile
[DEBUG]       manageArtifactVersion: artifact=org.apache.logging.log4j:log4j-api:jar:2.17.1:compile, replacement=org.apache.logging.log4j:log4j-api:jar:2.17.1
[DEBUG]       includeArtifact: artifact=org.apache.logging.log4j:log4j-api:jar:2.17.1:compile
[DEBUG]       startProcessChildren: artifact=org.apache.logging.log4j:log4j-api:jar:2.17.1:compile
[DEBUG]       endProcessChildren: artifact=org.apache.logging.log4j:log4j-api:jar:2.17.1:compile
[DEBUG]       manageArtifactVersion: artifact=org.apache.logging.log4j:log4j-core:jar:2.17.1:runtime, replacement=org.apache.logging.log4j:log4j-core:jar:2.17.1
[DEBUG]       testArtifact: artifact=org.apache.logging.log4j:log4j-core:jar:2.17.1:runtime
[DEBUG]       manageArtifactVersion: artifact=org.apache.logging.log4j:log4j-core:jar:2.17.1:runtime, replacement=org.apache.logging.log4j:log4j-core:jar:2.17.1
[DEBUG]       includeArtifact: artifact=org.apache.logging.log4j:log4j-core:jar:2.17.1:runtime
[DEBUG]       startProcessChildren: artifact=org.apache.logging.log4j:log4j-core:jar:2.17.1:runtime
[DEBUG]         manageArtifactVersion: artifact=org.apache.logging.log4j:log4j-api:jar:2.17.1:runtime, replacement=org.apache.logging.log4j:log4j-api:jar:2.17.1
[DEBUG]         testArtifact: artifact=org.apache.logging.log4j:log4j-api:jar:2.17.1:runtime
[DEBUG]         manageArtifactVersion: artifact=org.apache.logging.log4j:log4j-api:jar:2.17.1:runtime, replacement=org.apache.logging.log4j:log4j-api:jar:2.17.1
[DEBUG]         omitForNearer: omitted=org.apache.logging.log4j:log4j-api:jar:2.17.1:runtime kept=org.apache.logging.log4j:log4j-api:jar:2.17.1:compile
[DEBUG]       endProcessChildren: artifact=org.apache.logging.log4j:log4j-core:jar:2.17.1:runtime
[DEBUG]     endProcessChildren: artifact=org.apache.logging.log4j:log4j-slf4j-impl:jar:2.17.1:compile
[DEBUG]     manageArtifactVersion: artifact=com.lmax:disruptor:jar:3.3.4:compile, replacement=com.lmax:disruptor:jar:3.3.4
[DEBUG]     testArtifact: artifact=com.lmax:disruptor:jar:3.3.4:compile
[DEBUG]     manageArtifactVersion: artifact=com.lmax:disruptor:jar:3.3.4:compile, replacement=com.lmax:disruptor:jar:3.3.4
[DEBUG]     includeArtifact: artifact=com.lmax:disruptor:jar:3.3.4:compile
[DEBUG]     startProcessChildren: artifact=com.lmax:disruptor:jar:3.3.4:compile
[DEBUG]     endProcessChildren: artifact=com.lmax:disruptor:jar:3.3.4:compile
[DEBUG]     manageArtifactVersion: artifact=org.apache.logging.log4j:log4j-1.2-api:jar:2.17.1:compile, replacement=org.apache.logging.log4j:log4j-1.2-api:jar:2.17.1
[DEBUG]     testArtifact: artifact=org.apache.logging.log4j:log4j-1.2-api:jar:2.17.1:compile
[DEBUG]     manageArtifactVersion: artifact=org.apache.logging.log4j:log4j-1.2-api:jar:2.17.1:compile, replacement=org.apache.logging.log4j:log4j-1.2-api:jar:2.17.1
[DEBUG]     includeArtifact: artifact=org.apache.logging.log4j:log4j-1.2-api:jar:2.17.1:compile
[DEBUG]     startProcessChildren: artifact=org.apache.logging.log4j:log4j-1.2-api:jar:2.17.1:compile
[DEBUG]       manageArtifactVersion: artifact=org.apache.logging.log4j:log4j-api:jar:2.17.1:compile, replacement=org.apache.logging.log4j:log4j-api:jar:2.17.1
[DEBUG]       testArtifact: artifact=org.apache.logging.log4j:log4j-api:jar:2.17.1:compile
[DEBUG]       manageArtifactVersion: artifact=org.apache.logging.log4j:log4j-api:jar:2.17.1:compile, replacement=org.apache.logging.log4j:log4j-api:jar:2.17.1
[DEBUG]       omitForNearer: omitted=org.apache.logging.log4j:log4j-api:jar:2.17.1:compile kept=org.apache.logging.log4j:log4j-api:jar:2.17.1:compile
[DEBUG]     endProcessChildren: artifact=org.apache.logging.log4j:log4j-1.2-api:jar:2.17.1:compile
[DEBUG]     manageArtifactVersion: artifact=joda-time:joda-time:jar:2.10.5:compile, replacement=joda-time:joda-time:jar:2.10.5
[DEBUG]     testArtifact: artifact=joda-time:joda-time:jar:2.10.5:compile
[DEBUG]     manageArtifactVersion: artifact=joda-time:joda-time:jar:2.10.5:compile, replacement=joda-time:joda-time:jar:2.10.5
[DEBUG]     includeArtifact: artifact=joda-time:joda-time:jar:2.10.5:compile
[DEBUG]     startProcessChildren: artifact=joda-time:joda-time:jar:2.10.5:compile
[DEBUG]     endProcessChildren: artifact=joda-time:joda-time:jar:2.10.5:compile
[DEBUG]     manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0
[DEBUG]     testArtifact: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile
[DEBUG]     manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0
[DEBUG]     omitForNearer: omitted=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile kept=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile
[DEBUG]     includeArtifact: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile
[DEBUG]     startProcessChildren: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile
[DEBUG]     endProcessChildren: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile
[DEBUG]     manageArtifactVersion: artifact=org.yaml:snakeyaml:jar:1.30:compile, replacement=org.yaml:snakeyaml:jar:1.30
[DEBUG]     testArtifact: artifact=org.yaml:snakeyaml:jar:1.30:compile
[DEBUG]     manageArtifactVersion: artifact=org.yaml:snakeyaml:jar:1.30:compile, replacement=org.yaml:snakeyaml:jar:1.30
[DEBUG]     omitForNearer: omitted=org.yaml:snakeyaml:jar:1.30:compile kept=org.yaml:snakeyaml:jar:1.30:compile
[DEBUG]     includeArtifact: artifact=org.yaml:snakeyaml:jar:1.30:compile
[DEBUG]     startProcessChildren: artifact=org.yaml:snakeyaml:jar:1.30:compile
[DEBUG]     endProcessChildren: artifact=org.yaml:snakeyaml:jar:1.30:compile
[DEBUG]     manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0
[DEBUG]     testArtifact: artifact=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile
[DEBUG]     manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0
[DEBUG]     omitForNearer: omitted=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile kept=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile
[DEBUG]     includeArtifact: artifact=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile
[DEBUG]     startProcessChildren: artifact=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0
[DEBUG]       testArtifact: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0
[DEBUG]       omitForNearer: omitted=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile kept=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-core:jar:2.10.0
[DEBUG]       testArtifact: artifact=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-core:jar:2.10.0
[DEBUG]       omitForNearer: omitted=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile kept=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile
[DEBUG]     endProcessChildren: artifact=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile
[DEBUG]     manageArtifactVersion: artifact=org.apache.avro:avro:jar:1.9.2:compile, replacement=org.apache.avro:avro:jar:1.9.2
[DEBUG]     testArtifact: artifact=org.apache.avro:avro:jar:1.9.2:compile
[DEBUG]     manageArtifactVersion: artifact=org.apache.avro:avro:jar:1.9.2:compile, replacement=org.apache.avro:avro:jar:1.9.2
[DEBUG]     omitForNearer: omitted=org.apache.avro:avro:jar:1.9.2:compile kept=org.apache.avro:avro:jar:1.9.2:compile
[DEBUG]     manageArtifactVersion: artifact=org.codehaus.groovy:groovy-all:jar:2.4.21:compile, replacement=org.codehaus.groovy:groovy-all:jar:2.4.21
[DEBUG]     testArtifact: artifact=org.codehaus.groovy:groovy-all:jar:2.4.21:compile
[DEBUG]     manageArtifactVersion: artifact=org.codehaus.groovy:groovy-all:jar:2.4.21:compile, replacement=org.codehaus.groovy:groovy-all:jar:2.4.21
[DEBUG]     includeArtifact: artifact=org.codehaus.groovy:groovy-all:jar:2.4.21:compile
[DEBUG]     startProcessChildren: artifact=org.codehaus.groovy:groovy-all:jar:2.4.21:compile
[DEBUG]     endProcessChildren: artifact=org.codehaus.groovy:groovy-all:jar:2.4.21:compile
[DEBUG]     manageArtifactVersion: artifact=org.reflections:reflections:jar:0.9.9:compile, replacement=org.reflections:reflections:jar:0.9.9
[DEBUG]     testArtifact: artifact=org.reflections:reflections:jar:0.9.9:compile
[DEBUG]     manageArtifactVersion: artifact=org.reflections:reflections:jar:0.9.9:compile, replacement=org.reflections:reflections:jar:0.9.9
[DEBUG]     includeArtifact: artifact=org.reflections:reflections:jar:0.9.9:compile
[DEBUG]     startProcessChildren: artifact=org.reflections:reflections:jar:0.9.9:compile
[DEBUG]       manageArtifactVersion: artifact=com.google.guava:guava:jar:15.0:compile, replacement=com.google.guava:guava:jar:20.0
[DEBUG]       testArtifact: artifact=com.google.guava:guava:jar:20.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.google.guava:guava:jar:20.0:compile, replacement=com.google.guava:guava:jar:20.0
[DEBUG]       omitForNearer: omitted=com.google.guava:guava:jar:20.0:compile kept=com.google.guava:guava:jar:20.0:compile
[DEBUG]       manageArtifactVersion: artifact=org.javassist:javassist:jar:3.18.2-GA:compile, replacement=org.javassist:javassist:jar:3.19.0-GA
[DEBUG]       testArtifact: artifact=org.javassist:javassist:jar:3.19.0-GA:compile
[DEBUG]       manageArtifactVersion: artifact=org.javassist:javassist:jar:3.19.0-GA:compile, replacement=org.javassist:javassist:jar:3.19.0-GA
[DEBUG]       omitForNearer: omitted=org.javassist:javassist:jar:3.19.0-GA:compile kept=org.javassist:javassist:jar:3.19.0-GA:compile
[DEBUG]       testArtifact: artifact=com.google.code.findbugs:annotations:jar:2.0.1:compile
[DEBUG]       includeArtifact: artifact=com.google.code.findbugs:annotations:jar:2.0.1:compile
[DEBUG]       startProcessChildren: artifact=com.google.code.findbugs:annotations:jar:2.0.1:compile
[DEBUG]       endProcessChildren: artifact=com.google.code.findbugs:annotations:jar:2.0.1:compile
[DEBUG]     endProcessChildren: artifact=org.reflections:reflections:jar:0.9.9:compile
[DEBUG]   endProcessChildren: artifact=org.apache.pinot:pinot-spi:jar:0.11.0-SNAPSHOT:compile
[DEBUG]   testArtifact: artifact=org.testng:testng:jar:6.11:test
[DEBUG]   includeArtifact: artifact=org.testng:testng:jar:6.11:test
[DEBUG]   startProcessChildren: artifact=org.testng:testng:jar:6.11:test
[DEBUG]     testArtifact: artifact=com.beust:jcommander:jar:1.64:test
[DEBUG]     includeArtifact: artifact=com.beust:jcommander:jar:1.64:test
[DEBUG]     startProcessChildren: artifact=com.beust:jcommander:jar:1.64:test
[DEBUG]     endProcessChildren: artifact=com.beust:jcommander:jar:1.64:test
[DEBUG]     manageArtifactVersion: artifact=org.yaml:snakeyaml:jar:1.17:test, replacement=org.yaml:snakeyaml:jar:1.30
[DEBUG]     testArtifact: artifact=org.yaml:snakeyaml:jar:1.30:test
[DEBUG]     manageArtifactVersion: artifact=org.yaml:snakeyaml:jar:1.30:test, replacement=org.yaml:snakeyaml:jar:1.30
[DEBUG]     omitForNearer: omitted=org.yaml:snakeyaml:jar:1.30:test kept=org.yaml:snakeyaml:jar:1.30:compile
[DEBUG]   endProcessChildren: artifact=org.testng:testng:jar:6.11:test
[DEBUG] endProcessChildren: artifact=org.apache.pinot:pinot-pulsar:jar:0.11.0-SNAPSHOT
[INFO] 
[INFO] --- maven-enforcer-plugin:3.0.0-M2:enforce (enforce-maven-version) @ pinot-pulsar ---
[DEBUG] Configuring mojo org.apache.maven.plugins:maven-enforcer-plugin:3.0.0-M2:enforce from plugin realm ClassRealm[plugin>org.apache.maven.plugins:maven-enforcer-plugin:3.0.0-M2, parent: jdk.internal.loader.ClassLoaders$AppClassLoader@2c13da15]
[DEBUG] Configuring mojo 'org.apache.maven.plugins:maven-enforcer-plugin:3.0.0-M2:enforce' with basic configurator -->
[DEBUG]   (s) fail = true
[DEBUG]   (s) failFast = false
[DEBUG]   (f) ignoreCache = false
[DEBUG]   (f) mojoExecution = org.apache.maven.plugins:maven-enforcer-plugin:3.0.0-M2:enforce {execution: enforce-maven-version}
[DEBUG]   (s) project = MavenProject: org.apache.pinot:pinot-pulsar:0.11.0-SNAPSHOT @ /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/pom.xml
[DEBUG]   (s) version = 3.0.5
[DEBUG]   (s) rules = [org.apache.maven.plugins.enforcer.RequireMavenVersion@78288f83, org.apache.maven.plugins.enforcer.DependencyConvergence@29c1249a]
[DEBUG]   (s) session = org.apache.maven.execution.MavenSession@53d6e959
[DEBUG]   (s) skip = false
[DEBUG] -- end configuration --
[DEBUG] Executing rule: org.apache.maven.plugins.enforcer.RequireMavenVersion
[DEBUG] Rule org.apache.maven.plugins.enforcer.RequireMavenVersion is cacheable.
[DEBUG] Detected Maven Version: 3.8.1
[DEBUG] Detected Maven Version: 3.8.1 is allowed in the range 3.0.5.
[DEBUG] Executing rule: org.apache.maven.plugins.enforcer.DependencyConvergence
[DEBUG] Dependency tree resolution listener events:
[DEBUG] testArtifact: artifact=org.apache.pinot:pinot-pulsar:jar:0.11.0-SNAPSHOT
[DEBUG] includeArtifact: artifact=org.apache.pinot:pinot-pulsar:jar:0.11.0-SNAPSHOT
[DEBUG] startProcessChildren: artifact=org.apache.pinot:pinot-pulsar:jar:0.11.0-SNAPSHOT
[DEBUG]   testArtifact: artifact=org.eclipse.jetty:jetty-server:jar:9.4.45.v20220203:compile
[DEBUG]   includeArtifact: artifact=org.eclipse.jetty:jetty-server:jar:9.4.45.v20220203:compile
[DEBUG]   startProcessChildren: artifact=org.eclipse.jetty:jetty-server:jar:9.4.45.v20220203:compile
[DEBUG]     testArtifact: artifact=org.eclipse.jetty:jetty-http:jar:9.4.45.v20220203:compile
[DEBUG]     includeArtifact: artifact=org.eclipse.jetty:jetty-http:jar:9.4.45.v20220203:compile
[DEBUG]     startProcessChildren: artifact=org.eclipse.jetty:jetty-http:jar:9.4.45.v20220203:compile
[DEBUG]       testArtifact: artifact=org.eclipse.jetty:jetty-util:jar:9.4.45.v20220203:compile
[DEBUG]       includeArtifact: artifact=org.eclipse.jetty:jetty-util:jar:9.4.45.v20220203:compile
[DEBUG]       startProcessChildren: artifact=org.eclipse.jetty:jetty-util:jar:9.4.45.v20220203:compile
[DEBUG]       endProcessChildren: artifact=org.eclipse.jetty:jetty-util:jar:9.4.45.v20220203:compile
[DEBUG]       testArtifact: artifact=org.eclipse.jetty:jetty-io:jar:9.4.45.v20220203:compile
[DEBUG]       includeArtifact: artifact=org.eclipse.jetty:jetty-io:jar:9.4.45.v20220203:compile
[DEBUG]       startProcessChildren: artifact=org.eclipse.jetty:jetty-io:jar:9.4.45.v20220203:compile
[DEBUG]         testArtifact: artifact=org.eclipse.jetty:jetty-util:jar:9.4.45.v20220203:compile
[DEBUG]         omitForNearer: omitted=org.eclipse.jetty:jetty-util:jar:9.4.45.v20220203:compile kept=org.eclipse.jetty:jetty-util:jar:9.4.45.v20220203:compile
[DEBUG]       endProcessChildren: artifact=org.eclipse.jetty:jetty-io:jar:9.4.45.v20220203:compile
[DEBUG]     endProcessChildren: artifact=org.eclipse.jetty:jetty-http:jar:9.4.45.v20220203:compile
[DEBUG]     testArtifact: artifact=org.eclipse.jetty:jetty-io:jar:9.4.45.v20220203:compile
[DEBUG]     omitForNearer: omitted=org.eclipse.jetty:jetty-io:jar:9.4.45.v20220203:compile kept=org.eclipse.jetty:jetty-io:jar:9.4.45.v20220203:compile
[DEBUG]     includeArtifact: artifact=org.eclipse.jetty:jetty-io:jar:9.4.45.v20220203:compile
[DEBUG]     startProcessChildren: artifact=org.eclipse.jetty:jetty-io:jar:9.4.45.v20220203:compile
[DEBUG]       testArtifact: artifact=org.eclipse.jetty:jetty-util:jar:9.4.45.v20220203:compile
[DEBUG]       omitForNearer: omitted=org.eclipse.jetty:jetty-util:jar:9.4.45.v20220203:compile kept=org.eclipse.jetty:jetty-util:jar:9.4.45.v20220203:compile
[DEBUG]     endProcessChildren: artifact=org.eclipse.jetty:jetty-io:jar:9.4.45.v20220203:compile
[DEBUG]   endProcessChildren: artifact=org.eclipse.jetty:jetty-server:jar:9.4.45.v20220203:compile
[DEBUG]   testArtifact: artifact=org.testcontainers:pulsar:jar:1.17.1:test
[DEBUG]   includeArtifact: artifact=org.testcontainers:pulsar:jar:1.17.1:test
[DEBUG]   startProcessChildren: artifact=org.testcontainers:pulsar:jar:1.17.1:test
[DEBUG]     testArtifact: artifact=org.testcontainers:testcontainers:jar:1.17.1:test
[DEBUG]     includeArtifact: artifact=org.testcontainers:testcontainers:jar:1.17.1:test
[DEBUG]     startProcessChildren: artifact=org.testcontainers:testcontainers:jar:1.17.1:test
[DEBUG]       testArtifact: artifact=junit:junit:jar:4.13.2:test
[DEBUG]       includeArtifact: artifact=junit:junit:jar:4.13.2:test
[DEBUG]       startProcessChildren: artifact=junit:junit:jar:4.13.2:test
[DEBUG]         testArtifact: artifact=org.hamcrest:hamcrest-core:jar:1.3:test
[DEBUG]         includeArtifact: artifact=org.hamcrest:hamcrest-core:jar:1.3:test
[DEBUG]         startProcessChildren: artifact=org.hamcrest:hamcrest-core:jar:1.3:test
[DEBUG]         endProcessChildren: artifact=org.hamcrest:hamcrest-core:jar:1.3:test
[DEBUG]       endProcessChildren: artifact=junit:junit:jar:4.13.2:test
[DEBUG]       manageArtifactVersion: artifact=org.slf4j:slf4j-api:jar:1.7.35:test, replacement=org.slf4j:slf4j-api:jar:1.7.25
[DEBUG]       testArtifact: artifact=org.slf4j:slf4j-api:jar:1.7.25:test
[DEBUG]       manageArtifactVersion: artifact=org.slf4j:slf4j-api:jar:1.7.25:test, replacement=org.slf4j:slf4j-api:jar:1.7.25
[DEBUG]       includeArtifact: artifact=org.slf4j:slf4j-api:jar:1.7.25:test
[DEBUG]       startProcessChildren: artifact=org.slf4j:slf4j-api:jar:1.7.25:test
[DEBUG]       endProcessChildren: artifact=org.slf4j:slf4j-api:jar:1.7.25:test
[DEBUG]       manageArtifactVersion: artifact=org.apache.commons:commons-compress:jar:1.21:test, replacement=org.apache.commons:commons-compress:jar:1.21
[DEBUG]       testArtifact: artifact=org.apache.commons:commons-compress:jar:1.21:test
[DEBUG]       manageArtifactVersion: artifact=org.apache.commons:commons-compress:jar:1.21:test, replacement=org.apache.commons:commons-compress:jar:1.21
[DEBUG]       includeArtifact: artifact=org.apache.commons:commons-compress:jar:1.21:test
[DEBUG]       startProcessChildren: artifact=org.apache.commons:commons-compress:jar:1.21:test
[DEBUG]       endProcessChildren: artifact=org.apache.commons:commons-compress:jar:1.21:test
[DEBUG]       testArtifact: artifact=org.rnorth.duct-tape:duct-tape:jar:1.0.8:test
[DEBUG]       includeArtifact: artifact=org.rnorth.duct-tape:duct-tape:jar:1.0.8:test
[DEBUG]       startProcessChildren: artifact=org.rnorth.duct-tape:duct-tape:jar:1.0.8:test
[DEBUG]         testArtifact: artifact=org.jetbrains:annotations:jar:17.0.0:test
[DEBUG]         includeArtifact: artifact=org.jetbrains:annotations:jar:17.0.0:test
[DEBUG]         startProcessChildren: artifact=org.jetbrains:annotations:jar:17.0.0:test
[DEBUG]         endProcessChildren: artifact=org.jetbrains:annotations:jar:17.0.0:test
[DEBUG]       endProcessChildren: artifact=org.rnorth.duct-tape:duct-tape:jar:1.0.8:test
[DEBUG]       testArtifact: artifact=com.github.docker-java:docker-java-api:jar:3.2.13:test
[DEBUG]       includeArtifact: artifact=com.github.docker-java:docker-java-api:jar:3.2.13:test
[DEBUG]       startProcessChildren: artifact=com.github.docker-java:docker-java-api:jar:3.2.13:test
[DEBUG]         manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.3:test, replacement=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0
[DEBUG]         testArtifact: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:test
[DEBUG]         manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:test, replacement=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0
[DEBUG]         includeArtifact: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:test
[DEBUG]         startProcessChildren: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:test
[DEBUG]         endProcessChildren: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:test
[DEBUG]         manageArtifactVersion: artifact=org.slf4j:slf4j-api:jar:1.7.30:test, replacement=org.slf4j:slf4j-api:jar:1.7.25
[DEBUG]         testArtifact: artifact=org.slf4j:slf4j-api:jar:1.7.25:test
[DEBUG]         manageArtifactVersion: artifact=org.slf4j:slf4j-api:jar:1.7.25:test, replacement=org.slf4j:slf4j-api:jar:1.7.25
[DEBUG]         omitForNearer: omitted=org.slf4j:slf4j-api:jar:1.7.25:test kept=org.slf4j:slf4j-api:jar:1.7.25:test
[DEBUG]       endProcessChildren: artifact=com.github.docker-java:docker-java-api:jar:3.2.13:test
[DEBUG]       testArtifact: artifact=com.github.docker-java:docker-java-transport-zerodep:jar:3.2.13:test
[DEBUG]       includeArtifact: artifact=com.github.docker-java:docker-java-transport-zerodep:jar:3.2.13:test
[DEBUG]       startProcessChildren: artifact=com.github.docker-java:docker-java-transport-zerodep:jar:3.2.13:test
[DEBUG]         testArtifact: artifact=com.github.docker-java:docker-java-transport:jar:3.2.13:test
[DEBUG]         includeArtifact: artifact=com.github.docker-java:docker-java-transport:jar:3.2.13:test
[DEBUG]         startProcessChildren: artifact=com.github.docker-java:docker-java-transport:jar:3.2.13:test
[DEBUG]         endProcessChildren: artifact=com.github.docker-java:docker-java-transport:jar:3.2.13:test
[DEBUG]         manageArtifactVersion: artifact=org.slf4j:slf4j-api:jar:1.7.25:test, replacement=org.slf4j:slf4j-api:jar:1.7.25
[DEBUG]         testArtifact: artifact=org.slf4j:slf4j-api:jar:1.7.25:test
[DEBUG]         manageArtifactVersion: artifact=org.slf4j:slf4j-api:jar:1.7.25:test, replacement=org.slf4j:slf4j-api:jar:1.7.25
[DEBUG]         omitForNearer: omitted=org.slf4j:slf4j-api:jar:1.7.25:test kept=org.slf4j:slf4j-api:jar:1.7.25:test
[DEBUG]         testArtifact: artifact=net.java.dev.jna:jna:jar:5.8.0:test
[DEBUG]         includeArtifact: artifact=net.java.dev.jna:jna:jar:5.8.0:test
[DEBUG]         startProcessChildren: artifact=net.java.dev.jna:jna:jar:5.8.0:test
[DEBUG]         endProcessChildren: artifact=net.java.dev.jna:jna:jar:5.8.0:test
[DEBUG]       endProcessChildren: artifact=com.github.docker-java:docker-java-transport-zerodep:jar:3.2.13:test
[DEBUG]     endProcessChildren: artifact=org.testcontainers:testcontainers:jar:1.17.1:test
[DEBUG]   endProcessChildren: artifact=org.testcontainers:pulsar:jar:1.17.1:test
[DEBUG]   testArtifact: artifact=org.apache.pulsar:pulsar-client-original:jar:2.7.2:compile
[DEBUG]   includeArtifact: artifact=org.apache.pulsar:pulsar-client-original:jar:2.7.2:compile
[DEBUG]   startProcessChildren: artifact=org.apache.pulsar:pulsar-client-original:jar:2.7.2:compile
[DEBUG]     testArtifact: artifact=org.apache.pulsar:pulsar-client-api:jar:2.7.2:compile
[DEBUG]     includeArtifact: artifact=org.apache.pulsar:pulsar-client-api:jar:2.7.2:compile
[DEBUG]     startProcessChildren: artifact=org.apache.pulsar:pulsar-client-api:jar:2.7.2:compile
[DEBUG]     endProcessChildren: artifact=org.apache.pulsar:pulsar-client-api:jar:2.7.2:compile
[DEBUG]     testArtifact: artifact=org.apache.pulsar:pulsar-common:jar:2.7.2:compile
[DEBUG]     includeArtifact: artifact=org.apache.pulsar:pulsar-common:jar:2.7.2:compile
[DEBUG]     startProcessChildren: artifact=org.apache.pulsar:pulsar-common:jar:2.7.2:compile
[DEBUG]       testArtifact: artifact=org.apache.pulsar:pulsar-client-api:jar:2.7.2:compile
[DEBUG]       omitForNearer: omitted=org.apache.pulsar:pulsar-client-api:jar:2.7.2:compile kept=org.apache.pulsar:pulsar-client-api:jar:2.7.2:compile
[DEBUG]       testArtifact: artifact=io.swagger:swagger-annotations:jar:1.5.21:compile
[DEBUG]       includeArtifact: artifact=io.swagger:swagger-annotations:jar:1.5.21:compile
[DEBUG]       startProcessChildren: artifact=io.swagger:swagger-annotations:jar:1.5.21:compile
[DEBUG]       endProcessChildren: artifact=io.swagger:swagger-annotations:jar:1.5.21:compile
[DEBUG]       manageArtifactVersion: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile, replacement=org.slf4j:slf4j-api:jar:1.7.25
[DEBUG]       testArtifact: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile
[DEBUG]       manageArtifactVersion: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile, replacement=org.slf4j:slf4j-api:jar:1.7.25
[DEBUG]       updateScope: artifact=org.slf4j:slf4j-api:jar:1.7.25:test, scope=compile
[DEBUG]       omitForNearer: omitted=org.slf4j:slf4j-api:jar:1.7.25:compile kept=org.slf4j:slf4j-api:jar:1.7.25:compile
[DEBUG]       includeArtifact: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile
[DEBUG]       startProcessChildren: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile
[DEBUG]       endProcessChildren: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-databind:jar:2.11.1:compile, replacement=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0
[DEBUG]       testArtifact: artifact=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0
[DEBUG]       includeArtifact: artifact=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile
[DEBUG]       startProcessChildren: artifact=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile
[DEBUG]         manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0
[DEBUG]         testArtifact: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile
[DEBUG]         manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0
[DEBUG]         updateScope: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:test, scope=compile
[DEBUG]         omitForNearer: omitted=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile kept=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile
[DEBUG]         includeArtifact: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile
[DEBUG]         startProcessChildren: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile
[DEBUG]         endProcessChildren: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile
[DEBUG]         manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-core:jar:2.10.0
[DEBUG]         testArtifact: artifact=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile
[DEBUG]         manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-core:jar:2.10.0
[DEBUG]         includeArtifact: artifact=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile
[DEBUG]         startProcessChildren: artifact=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile
[DEBUG]         endProcessChildren: artifact=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile
[DEBUG]       endProcessChildren: artifact=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile
[DEBUG]       testArtifact: artifact=org.apache.pulsar:protobuf-shaded:jar:2.1.0-incubating:compile
[DEBUG]       includeArtifact: artifact=org.apache.pulsar:protobuf-shaded:jar:2.1.0-incubating:compile
[DEBUG]       startProcessChildren: artifact=org.apache.pulsar:protobuf-shaded:jar:2.1.0-incubating:compile
[DEBUG]       endProcessChildren: artifact=org.apache.pulsar:protobuf-shaded:jar:2.1.0-incubating:compile
[DEBUG]       manageArtifactVersion: artifact=com.google.guava:guava:jar:30.1-jre:compile, replacement=com.google.guava:guava:jar:20.0
[DEBUG]       testArtifact: artifact=com.google.guava:guava:jar:20.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.google.guava:guava:jar:20.0:compile, replacement=com.google.guava:guava:jar:20.0
[DEBUG]       includeArtifact: artifact=com.google.guava:guava:jar:20.0:compile
[DEBUG]       startProcessChildren: artifact=com.google.guava:guava:jar:20.0:compile
[DEBUG]       endProcessChildren: artifact=com.google.guava:guava:jar:20.0:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-handler:jar:4.1.60.Final:compile, replacement=io.netty:netty-handler:jar:4.1.74.Final
[DEBUG]       testArtifact: artifact=io.netty:netty-handler:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-handler:jar:4.1.74.Final:compile, replacement=io.netty:netty-handler:jar:4.1.74.Final
[DEBUG]       includeArtifact: artifact=io.netty:netty-handler:jar:4.1.74.Final:compile
[DEBUG]       startProcessChildren: artifact=io.netty:netty-handler:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]         testArtifact: artifact=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]         includeArtifact: artifact=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]         startProcessChildren: artifact=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]         endProcessChildren: artifact=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile, replacement=io.netty:netty-buffer:jar:4.1.74.Final
[DEBUG]         testArtifact: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile, replacement=io.netty:netty-buffer:jar:4.1.74.Final
[DEBUG]         includeArtifact: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]         startProcessChildren: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]           manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]           testArtifact: artifact=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]           manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]           omitForNearer: omitted=io.netty:netty-common:jar:4.1.74.Final:compile kept=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]         endProcessChildren: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile, replacement=io.netty:netty-transport:jar:4.1.74.Final
[DEBUG]         testArtifact: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile, replacement=io.netty:netty-transport:jar:4.1.74.Final
[DEBUG]         includeArtifact: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG]         startProcessChildren: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG]           manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]           testArtifact: artifact=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]           manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]           omitForNearer: omitted=io.netty:netty-common:jar:4.1.74.Final:compile kept=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]           manageArtifactVersion: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile, replacement=io.netty:netty-buffer:jar:4.1.74.Final
[DEBUG]           testArtifact: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]           manageArtifactVersion: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile, replacement=io.netty:netty-buffer:jar:4.1.74.Final
[DEBUG]           omitForNearer: omitted=io.netty:netty-buffer:jar:4.1.74.Final:compile kept=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]         endProcessChildren: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-codec:jar:4.1.74.Final:compile, replacement=io.netty:netty-codec:jar:4.1.74.Final
[DEBUG]         testArtifact: artifact=io.netty:netty-codec:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-codec:jar:4.1.74.Final:compile, replacement=io.netty:netty-codec:jar:4.1.74.Final
[DEBUG]         includeArtifact: artifact=io.netty:netty-codec:jar:4.1.74.Final:compile
[DEBUG]         startProcessChildren: artifact=io.netty:netty-codec:jar:4.1.74.Final:compile
[DEBUG]           manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]           testArtifact: artifact=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]           manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]           omitForNearer: omitted=io.netty:netty-common:jar:4.1.74.Final:compile kept=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]           manageArtifactVersion: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile, replacement=io.netty:netty-buffer:jar:4.1.74.Final
[DEBUG]           testArtifact: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]           manageArtifactVersion: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile, replacement=io.netty:netty-buffer:jar:4.1.74.Final
[DEBUG]           omitForNearer: omitted=io.netty:netty-buffer:jar:4.1.74.Final:compile kept=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]           manageArtifactVersion: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile, replacement=io.netty:netty-transport:jar:4.1.74.Final
[DEBUG]           testArtifact: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG]           manageArtifactVersion: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile, replacement=io.netty:netty-transport:jar:4.1.74.Final
[DEBUG]           omitForNearer: omitted=io.netty:netty-transport:jar:4.1.74.Final:compile kept=io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG]         endProcessChildren: artifact=io.netty:netty-codec:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-tcnative-classes:jar:2.0.48.Final:compile, replacement=io.netty:netty-tcnative-classes:jar:2.0.48.Final
[DEBUG]         testArtifact: artifact=io.netty:netty-tcnative-classes:jar:2.0.48.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-tcnative-classes:jar:2.0.48.Final:compile, replacement=io.netty:netty-tcnative-classes:jar:2.0.48.Final
[DEBUG]         includeArtifact: artifact=io.netty:netty-tcnative-classes:jar:2.0.48.Final:compile
[DEBUG]         startProcessChildren: artifact=io.netty:netty-tcnative-classes:jar:2.0.48.Final:compile
[DEBUG]         endProcessChildren: artifact=io.netty:netty-tcnative-classes:jar:2.0.48.Final:compile
[DEBUG]       endProcessChildren: artifact=io.netty:netty-handler:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-transport-native-epoll:jar:linux-x86_64:4.1.60.Final:compile, replacement=io.netty:netty-transport-native-epoll:jar:linux-x86_64:4.1.74.Final
[DEBUG]       testArtifact: artifact=io.netty:netty-transport-native-epoll:jar:linux-x86_64:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-transport-native-epoll:jar:linux-x86_64:4.1.74.Final:compile, replacement=io.netty:netty-transport-native-epoll:jar:linux-x86_64:4.1.74.Final
[DEBUG]       includeArtifact: artifact=io.netty:netty-transport-native-epoll:jar:linux-x86_64:4.1.74.Final:compile
[DEBUG]       startProcessChildren: artifact=io.netty:netty-transport-native-epoll:jar:linux-x86_64:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]         testArtifact: artifact=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]         omitForNearer: omitted=io.netty:netty-common:jar:4.1.74.Final:compile kept=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile, replacement=io.netty:netty-buffer:jar:4.1.74.Final
[DEBUG]         testArtifact: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile, replacement=io.netty:netty-buffer:jar:4.1.74.Final
[DEBUG]         omitForNearer: omitted=io.netty:netty-buffer:jar:4.1.74.Final:compile kept=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile, replacement=io.netty:netty-transport:jar:4.1.74.Final
[DEBUG]         testArtifact: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile, replacement=io.netty:netty-transport:jar:4.1.74.Final
[DEBUG]         omitForNearer: omitted=io.netty:netty-transport:jar:4.1.74.Final:compile kept=io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-transport-classes-epoll:jar:4.1.74.Final:compile, replacement=io.netty:netty-transport-classes-epoll:jar:4.1.74.Final
[DEBUG]         testArtifact: artifact=io.netty:netty-transport-classes-epoll:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-transport-classes-epoll:jar:4.1.74.Final:compile, replacement=io.netty:netty-transport-classes-epoll:jar:4.1.74.Final
[DEBUG]         includeArtifact: artifact=io.netty:netty-transport-classes-epoll:jar:4.1.74.Final:compile
[DEBUG]         startProcessChildren: artifact=io.netty:netty-transport-classes-epoll:jar:4.1.74.Final:compile
[DEBUG]           manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]           testArtifact: artifact=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]           manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]           omitForNearer: omitted=io.netty:netty-common:jar:4.1.74.Final:compile kept=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]           manageArtifactVersion: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile, replacement=io.netty:netty-buffer:jar:4.1.74.Final
[DEBUG]           testArtifact: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]           manageArtifactVersion: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile, replacement=io.netty:netty-buffer:jar:4.1.74.Final
[DEBUG]           omitForNearer: omitted=io.netty:netty-buffer:jar:4.1.74.Final:compile kept=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]           manageArtifactVersion: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile, replacement=io.netty:netty-transport:jar:4.1.74.Final
[DEBUG]           testArtifact: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG]           manageArtifactVersion: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile, replacement=io.netty:netty-transport:jar:4.1.74.Final
[DEBUG]           omitForNearer: omitted=io.netty:netty-transport:jar:4.1.74.Final:compile kept=io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG]         endProcessChildren: artifact=io.netty:netty-transport-classes-epoll:jar:4.1.74.Final:compile
[DEBUG]       endProcessChildren: artifact=io.netty:netty-transport-native-epoll:jar:linux-x86_64:4.1.74.Final:compile
[DEBUG]       testArtifact: artifact=org.apache.bookkeeper:bookkeeper-common-allocator:jar:4.12.0:compile
[DEBUG]       includeArtifact: artifact=org.apache.bookkeeper:bookkeeper-common-allocator:jar:4.12.0:compile
[DEBUG]       startProcessChildren: artifact=org.apache.bookkeeper:bookkeeper-common-allocator:jar:4.12.0:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-buffer:jar:4.1.50.Final:compile, replacement=io.netty:netty-buffer:jar:4.1.74.Final
[DEBUG]         testArtifact: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile, replacement=io.netty:netty-buffer:jar:4.1.74.Final
[DEBUG]         omitForNearer: omitted=io.netty:netty-buffer:jar:4.1.74.Final:compile kept=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile, replacement=org.slf4j:slf4j-api:jar:1.7.25
[DEBUG]         testArtifact: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile
[DEBUG]         manageArtifactVersion: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile, replacement=org.slf4j:slf4j-api:jar:1.7.25
[DEBUG]         omitForNearer: omitted=org.slf4j:slf4j-api:jar:1.7.25:compile kept=org.slf4j:slf4j-api:jar:1.7.25:compile
[DEBUG]       endProcessChildren: artifact=org.apache.bookkeeper:bookkeeper-common-allocator:jar:4.12.0:compile
[DEBUG]       testArtifact: artifact=io.airlift:aircompressor:jar:0.16:compile
[DEBUG]       includeArtifact: artifact=io.airlift:aircompressor:jar:0.16:compile
[DEBUG]       startProcessChildren: artifact=io.airlift:aircompressor:jar:0.16:compile
[DEBUG]       endProcessChildren: artifact=io.airlift:aircompressor:jar:0.16:compile
[DEBUG]       testArtifact: artifact=org.apache.bookkeeper:circe-checksum:jar:4.12.0:compile
[DEBUG]       includeArtifact: artifact=org.apache.bookkeeper:circe-checksum:jar:4.12.0:compile
[DEBUG]       startProcessChildren: artifact=org.apache.bookkeeper:circe-checksum:jar:4.12.0:compile
[DEBUG]         manageArtifactVersion: artifact=com.google.guava:guava:jar:30.0-jre:compile, replacement=com.google.guava:guava:jar:20.0
[DEBUG]         testArtifact: artifact=com.google.guava:guava:jar:20.0:compile
[DEBUG]         manageArtifactVersion: artifact=com.google.guava:guava:jar:20.0:compile, replacement=com.google.guava:guava:jar:20.0
[DEBUG]         omitForNearer: omitted=com.google.guava:guava:jar:20.0:compile kept=com.google.guava:guava:jar:20.0:compile
[DEBUG]         manageArtifactVersion: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile, replacement=org.slf4j:slf4j-api:jar:1.7.25
[DEBUG]         testArtifact: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile
[DEBUG]         manageArtifactVersion: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile, replacement=org.slf4j:slf4j-api:jar:1.7.25
[DEBUG]         omitForNearer: omitted=org.slf4j:slf4j-api:jar:1.7.25:compile kept=org.slf4j:slf4j-api:jar:1.7.25:compile
[DEBUG]         manageArtifactVersion: artifact=commons-configuration:commons-configuration:jar:1.10:compile, replacement=commons-configuration:commons-configuration:jar:1.10
[DEBUG]         testArtifact: artifact=commons-configuration:commons-configuration:jar:1.10:compile
[DEBUG]         manageArtifactVersion: artifact=commons-configuration:commons-configuration:jar:1.10:compile, replacement=commons-configuration:commons-configuration:jar:1.10
[DEBUG]         includeArtifact: artifact=commons-configuration:commons-configuration:jar:1.10:compile
[DEBUG]         startProcessChildren: artifact=commons-configuration:commons-configuration:jar:1.10:compile
[DEBUG]           manageArtifactVersion: artifact=commons-lang:commons-lang:jar:2.6:compile, replacement=commons-lang:commons-lang:jar:2.6
[DEBUG]           testArtifact: artifact=commons-lang:commons-lang:jar:2.6:compile
[DEBUG]           manageArtifactVersion: artifact=commons-lang:commons-lang:jar:2.6:compile, replacement=commons-lang:commons-lang:jar:2.6
[DEBUG]           includeArtifact: artifact=commons-lang:commons-lang:jar:2.6:compile
[DEBUG]           startProcessChildren: artifact=commons-lang:commons-lang:jar:2.6:compile
[DEBUG]           endProcessChildren: artifact=commons-lang:commons-lang:jar:2.6:compile
[DEBUG]           manageArtifactVersion: artifact=commons-logging:commons-logging:jar:1.1.1:compile, replacement=commons-logging:commons-logging:jar:1.2
[DEBUG]           testArtifact: artifact=commons-logging:commons-logging:jar:1.2:compile
[DEBUG]           manageArtifactVersion: artifact=commons-logging:commons-logging:jar:1.2:compile, replacement=commons-logging:commons-logging:jar:1.2
[DEBUG]           includeArtifact: artifact=commons-logging:commons-logging:jar:1.2:compile
[DEBUG]           startProcessChildren: artifact=commons-logging:commons-logging:jar:1.2:compile
[DEBUG]           endProcessChildren: artifact=commons-logging:commons-logging:jar:1.2:compile
[DEBUG]         endProcessChildren: artifact=commons-configuration:commons-configuration:jar:1.10:compile
[DEBUG]       endProcessChildren: artifact=org.apache.bookkeeper:circe-checksum:jar:4.12.0:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-tcnative-boringssl-static:jar:2.0.36.Final:compile, replacement=io.netty:netty-tcnative-boringssl-static:jar:2.0.48.Final
[DEBUG]       testArtifact: artifact=io.netty:netty-tcnative-boringssl-static:jar:2.0.48.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-tcnative-boringssl-static:jar:2.0.48.Final:compile, replacement=io.netty:netty-tcnative-boringssl-static:jar:2.0.48.Final
[DEBUG]       includeArtifact: artifact=io.netty:netty-tcnative-boringssl-static:jar:2.0.48.Final:compile
[DEBUG]       startProcessChildren: artifact=io.netty:netty-tcnative-boringssl-static:jar:2.0.48.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-tcnative-classes:jar:2.0.48.Final:compile, replacement=io.netty:netty-tcnative-classes:jar:2.0.48.Final
[DEBUG]         testArtifact: artifact=io.netty:netty-tcnative-classes:jar:2.0.48.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-tcnative-classes:jar:2.0.48.Final:compile, replacement=io.netty:netty-tcnative-classes:jar:2.0.48.Final
[DEBUG]         omitForNearer: omitted=io.netty:netty-tcnative-classes:jar:2.0.48.Final:compile kept=io.netty:netty-tcnative-classes:jar:2.0.48.Final:compile
[DEBUG]       endProcessChildren: artifact=io.netty:netty-tcnative-boringssl-static:jar:2.0.48.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-codec-haproxy:jar:4.1.60.Final:compile, replacement=io.netty:netty-codec-haproxy:jar:4.1.74.Final
[DEBUG]       testArtifact: artifact=io.netty:netty-codec-haproxy:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-codec-haproxy:jar:4.1.74.Final:compile, replacement=io.netty:netty-codec-haproxy:jar:4.1.74.Final
[DEBUG]       includeArtifact: artifact=io.netty:netty-codec-haproxy:jar:4.1.74.Final:compile
[DEBUG]       startProcessChildren: artifact=io.netty:netty-codec-haproxy:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile, replacement=io.netty:netty-buffer:jar:4.1.74.Final
[DEBUG]         testArtifact: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile, replacement=io.netty:netty-buffer:jar:4.1.74.Final
[DEBUG]         omitForNearer: omitted=io.netty:netty-buffer:jar:4.1.74.Final:compile kept=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile, replacement=io.netty:netty-transport:jar:4.1.74.Final
[DEBUG]         testArtifact: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile, replacement=io.netty:netty-transport:jar:4.1.74.Final
[DEBUG]         omitForNearer: omitted=io.netty:netty-transport:jar:4.1.74.Final:compile kept=io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-codec:jar:4.1.74.Final:compile, replacement=io.netty:netty-codec:jar:4.1.74.Final
[DEBUG]         testArtifact: artifact=io.netty:netty-codec:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-codec:jar:4.1.74.Final:compile, replacement=io.netty:netty-codec:jar:4.1.74.Final
[DEBUG]         omitForNearer: omitted=io.netty:netty-codec:jar:4.1.74.Final:compile kept=io.netty:netty-codec:jar:4.1.74.Final:compile
[DEBUG]       endProcessChildren: artifact=io.netty:netty-codec-haproxy:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=org.apache.commons:commons-lang3:jar:3.6:compile, replacement=org.apache.commons:commons-lang3:jar:3.5
[DEBUG]       testArtifact: artifact=org.apache.commons:commons-lang3:jar:3.5:compile
[DEBUG]       manageArtifactVersion: artifact=org.apache.commons:commons-lang3:jar:3.5:compile, replacement=org.apache.commons:commons-lang3:jar:3.5
[DEBUG]       includeArtifact: artifact=org.apache.commons:commons-lang3:jar:3.5:compile
[DEBUG]       startProcessChildren: artifact=org.apache.commons:commons-lang3:jar:3.5:compile
[DEBUG]       endProcessChildren: artifact=org.apache.commons:commons-lang3:jar:3.5:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.dataformat:jackson-dataformat-yaml:jar:2.11.1:compile, replacement=com.fasterxml.jackson.dataformat:jackson-dataformat-yaml:jar:2.10.0
[DEBUG]       testArtifact: artifact=com.fasterxml.jackson.dataformat:jackson-dataformat-yaml:jar:2.10.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.dataformat:jackson-dataformat-yaml:jar:2.10.0:compile, replacement=com.fasterxml.jackson.dataformat:jackson-dataformat-yaml:jar:2.10.0
[DEBUG]       includeArtifact: artifact=com.fasterxml.jackson.dataformat:jackson-dataformat-yaml:jar:2.10.0:compile
[DEBUG]       startProcessChildren: artifact=com.fasterxml.jackson.dataformat:jackson-dataformat-yaml:jar:2.10.0:compile
[DEBUG]         manageArtifactVersion: artifact=org.yaml:snakeyaml:jar:1.24:compile, replacement=org.yaml:snakeyaml:jar:1.30
[DEBUG]         testArtifact: artifact=org.yaml:snakeyaml:jar:1.30:compile
[DEBUG]         manageArtifactVersion: artifact=org.yaml:snakeyaml:jar:1.30:compile, replacement=org.yaml:snakeyaml:jar:1.30
[DEBUG]         includeArtifact: artifact=org.yaml:snakeyaml:jar:1.30:compile
[DEBUG]         startProcessChildren: artifact=org.yaml:snakeyaml:jar:1.30:compile
[DEBUG]         endProcessChildren: artifact=org.yaml:snakeyaml:jar:1.30:compile
[DEBUG]         manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-core:jar:2.10.0
[DEBUG]         testArtifact: artifact=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile
[DEBUG]         manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-core:jar:2.10.0
[DEBUG]         omitForNearer: omitted=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile kept=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile
[DEBUG]       endProcessChildren: artifact=com.fasterxml.jackson.dataformat:jackson-dataformat-yaml:jar:2.10.0:compile
[DEBUG]       manageArtifactVersion: artifact=commons-io:commons-io:jar:2.8.0:compile, replacement=commons-io:commons-io:jar:2.11.0
[DEBUG]       testArtifact: artifact=commons-io:commons-io:jar:2.11.0:compile
[DEBUG]       manageArtifactVersion: artifact=commons-io:commons-io:jar:2.11.0:compile, replacement=commons-io:commons-io:jar:2.11.0
[DEBUG]       includeArtifact: artifact=commons-io:commons-io:jar:2.11.0:compile
[DEBUG]       startProcessChildren: artifact=commons-io:commons-io:jar:2.11.0:compile
[DEBUG]       endProcessChildren: artifact=commons-io:commons-io:jar:2.11.0:compile
[DEBUG]     endProcessChildren: artifact=org.apache.pulsar:pulsar-common:jar:2.7.2:compile
[DEBUG]     testArtifact: artifact=org.apache.pulsar:pulsar-transaction-common:jar:2.7.2:compile
[DEBUG]     includeArtifact: artifact=org.apache.pulsar:pulsar-transaction-common:jar:2.7.2:compile
[DEBUG]     startProcessChildren: artifact=org.apache.pulsar:pulsar-transaction-common:jar:2.7.2:compile
[DEBUG]       manageArtifactVersion: artifact=com.google.protobuf:protobuf-java:jar:3.11.4:compile, replacement=com.google.protobuf:protobuf-java:jar:3.19.2
[DEBUG]       testArtifact: artifact=com.google.protobuf:protobuf-java:jar:3.19.2:compile
[DEBUG]       manageArtifactVersion: artifact=com.google.protobuf:protobuf-java:jar:3.19.2:compile, replacement=com.google.protobuf:protobuf-java:jar:3.19.2
[DEBUG]       includeArtifact: artifact=com.google.protobuf:protobuf-java:jar:3.19.2:compile
[DEBUG]       startProcessChildren: artifact=com.google.protobuf:protobuf-java:jar:3.19.2:compile
[DEBUG]       endProcessChildren: artifact=com.google.protobuf:protobuf-java:jar:3.19.2:compile
[DEBUG]       testArtifact: artifact=com.google.protobuf:protobuf-java-util:jar:3.11.4:compile
[DEBUG]       includeArtifact: artifact=com.google.protobuf:protobuf-java-util:jar:3.11.4:compile
[DEBUG]       startProcessChildren: artifact=com.google.protobuf:protobuf-java-util:jar:3.11.4:compile
[DEBUG]         manageArtifactVersion: artifact=com.google.protobuf:protobuf-java:jar:3.11.4:compile, replacement=com.google.protobuf:protobuf-java:jar:3.19.2
[DEBUG]         testArtifact: artifact=com.google.protobuf:protobuf-java:jar:3.19.2:compile
[DEBUG]         manageArtifactVersion: artifact=com.google.protobuf:protobuf-java:jar:3.19.2:compile, replacement=com.google.protobuf:protobuf-java:jar:3.19.2
[DEBUG]         omitForNearer: omitted=com.google.protobuf:protobuf-java:jar:3.19.2:compile kept=com.google.protobuf:protobuf-java:jar:3.19.2:compile
[DEBUG]         manageArtifactVersion: artifact=com.google.guava:guava:jar:28.1-android:compile, replacement=com.google.guava:guava:jar:20.0
[DEBUG]         testArtifact: artifact=com.google.guava:guava:jar:20.0:compile
[DEBUG]         manageArtifactVersion: artifact=com.google.guava:guava:jar:20.0:compile, replacement=com.google.guava:guava:jar:20.0
[DEBUG]         omitForNearer: omitted=com.google.guava:guava:jar:20.0:compile kept=com.google.guava:guava:jar:20.0:compile
[DEBUG]         testArtifact: artifact=com.google.errorprone:error_prone_annotations:jar:2.3.4:compile
[DEBUG]         includeArtifact: artifact=com.google.errorprone:error_prone_annotations:jar:2.3.4:compile
[DEBUG]         startProcessChildren: artifact=com.google.errorprone:error_prone_annotations:jar:2.3.4:compile
[DEBUG]         endProcessChildren: artifact=com.google.errorprone:error_prone_annotations:jar:2.3.4:compile
[DEBUG]         manageArtifactVersion: artifact=com.google.code.gson:gson:jar:2.8.6:compile, replacement=com.google.code.gson:gson:jar:2.2.4
[DEBUG]         testArtifact: artifact=com.google.code.gson:gson:jar:2.2.4:compile
[DEBUG]         manageArtifactVersion: artifact=com.google.code.gson:gson:jar:2.2.4:compile, replacement=com.google.code.gson:gson:jar:2.2.4
[DEBUG]         includeArtifact: artifact=com.google.code.gson:gson:jar:2.2.4:compile
[DEBUG]         startProcessChildren: artifact=com.google.code.gson:gson:jar:2.2.4:compile
[DEBUG]         endProcessChildren: artifact=com.google.code.gson:gson:jar:2.2.4:compile
[DEBUG]       endProcessChildren: artifact=com.google.protobuf:protobuf-java-util:jar:3.11.4:compile
[DEBUG]     endProcessChildren: artifact=org.apache.pulsar:pulsar-transaction-common:jar:2.7.2:compile
[DEBUG]     testArtifact: artifact=org.apache.pulsar:bouncy-castle-bc:jar:pkg:2.7.2:compile
[DEBUG]     includeArtifact: artifact=org.apache.pulsar:bouncy-castle-bc:jar:pkg:2.7.2:compile
[DEBUG]     startProcessChildren: artifact=org.apache.pulsar:bouncy-castle-bc:jar:pkg:2.7.2:compile
[DEBUG]     endProcessChildren: artifact=org.apache.pulsar:bouncy-castle-bc:jar:pkg:2.7.2:compile
[DEBUG]     manageArtifactVersion: artifact=io.netty:netty-codec-http:jar:4.1.60.Final:compile, replacement=io.netty:netty-codec-http:jar:4.1.74.Final
[DEBUG]     testArtifact: artifact=io.netty:netty-codec-http:jar:4.1.74.Final:compile
[DEBUG]     manageArtifactVersion: artifact=io.netty:netty-codec-http:jar:4.1.74.Final:compile, replacement=io.netty:netty-codec-http:jar:4.1.74.Final
[DEBUG]     includeArtifact: artifact=io.netty:netty-codec-http:jar:4.1.74.Final:compile
[DEBUG]     startProcessChildren: artifact=io.netty:netty-codec-http:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]       testArtifact: artifact=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]       omitForNearer: omitted=io.netty:netty-common:jar:4.1.74.Final:compile kept=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]       includeArtifact: artifact=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]       startProcessChildren: artifact=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]       endProcessChildren: artifact=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile, replacement=io.netty:netty-buffer:jar:4.1.74.Final
[DEBUG]       testArtifact: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile, replacement=io.netty:netty-buffer:jar:4.1.74.Final
[DEBUG]       omitForNearer: omitted=io.netty:netty-buffer:jar:4.1.74.Final:compile kept=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]       includeArtifact: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]       startProcessChildren: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]         testArtifact: artifact=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]         omitForNearer: omitted=io.netty:netty-common:jar:4.1.74.Final:compile kept=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]       endProcessChildren: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile, replacement=io.netty:netty-transport:jar:4.1.74.Final
[DEBUG]       testArtifact: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile, replacement=io.netty:netty-transport:jar:4.1.74.Final
[DEBUG]       omitForNearer: omitted=io.netty:netty-transport:jar:4.1.74.Final:compile kept=io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG]       includeArtifact: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG]       startProcessChildren: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]         testArtifact: artifact=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]         omitForNearer: omitted=io.netty:netty-common:jar:4.1.74.Final:compile kept=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile, replacement=io.netty:netty-buffer:jar:4.1.74.Final
[DEBUG]         testArtifact: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile, replacement=io.netty:netty-buffer:jar:4.1.74.Final
[DEBUG]         omitForNearer: omitted=io.netty:netty-buffer:jar:4.1.74.Final:compile kept=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]       endProcessChildren: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-codec:jar:4.1.74.Final:compile, replacement=io.netty:netty-codec:jar:4.1.74.Final
[DEBUG]       testArtifact: artifact=io.netty:netty-codec:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-codec:jar:4.1.74.Final:compile, replacement=io.netty:netty-codec:jar:4.1.74.Final
[DEBUG]       omitForNearer: omitted=io.netty:netty-codec:jar:4.1.74.Final:compile kept=io.netty:netty-codec:jar:4.1.74.Final:compile
[DEBUG]       includeArtifact: artifact=io.netty:netty-codec:jar:4.1.74.Final:compile
[DEBUG]       startProcessChildren: artifact=io.netty:netty-codec:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]         testArtifact: artifact=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]         omitForNearer: omitted=io.netty:netty-common:jar:4.1.74.Final:compile kept=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile, replacement=io.netty:netty-buffer:jar:4.1.74.Final
[DEBUG]         testArtifact: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile, replacement=io.netty:netty-buffer:jar:4.1.74.Final
[DEBUG]         omitForNearer: omitted=io.netty:netty-buffer:jar:4.1.74.Final:compile kept=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile, replacement=io.netty:netty-transport:jar:4.1.74.Final
[DEBUG]         testArtifact: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile, replacement=io.netty:netty-transport:jar:4.1.74.Final
[DEBUG]         omitForNearer: omitted=io.netty:netty-transport:jar:4.1.74.Final:compile kept=io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG]       endProcessChildren: artifact=io.netty:netty-codec:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-handler:jar:4.1.74.Final:compile, replacement=io.netty:netty-handler:jar:4.1.74.Final
[DEBUG]       testArtifact: artifact=io.netty:netty-handler:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-handler:jar:4.1.74.Final:compile, replacement=io.netty:netty-handler:jar:4.1.74.Final
[DEBUG]       omitForNearer: omitted=io.netty:netty-handler:jar:4.1.74.Final:compile kept=io.netty:netty-handler:jar:4.1.74.Final:compile
[DEBUG]     endProcessChildren: artifact=io.netty:netty-codec-http:jar:4.1.74.Final:compile
[DEBUG]     manageArtifactVersion: artifact=io.netty:netty-resolver-dns:jar:4.1.60.Final:compile, replacement=io.netty:netty-resolver-dns:jar:4.1.74.Final
[DEBUG]     testArtifact: artifact=io.netty:netty-resolver-dns:jar:4.1.74.Final:compile
[DEBUG]     manageArtifactVersion: artifact=io.netty:netty-resolver-dns:jar:4.1.74.Final:compile, replacement=io.netty:netty-resolver-dns:jar:4.1.74.Final
[DEBUG]     includeArtifact: artifact=io.netty:netty-resolver-dns:jar:4.1.74.Final:compile
[DEBUG]     startProcessChildren: artifact=io.netty:netty-resolver-dns:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]       testArtifact: artifact=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]       omitForNearer: omitted=io.netty:netty-common:jar:4.1.74.Final:compile kept=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile, replacement=io.netty:netty-buffer:jar:4.1.74.Final
[DEBUG]       testArtifact: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile, replacement=io.netty:netty-buffer:jar:4.1.74.Final
[DEBUG]       omitForNearer: omitted=io.netty:netty-buffer:jar:4.1.74.Final:compile kept=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile, replacement=io.netty:netty-transport:jar:4.1.74.Final
[DEBUG]       testArtifact: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile, replacement=io.netty:netty-transport:jar:4.1.74.Final
[DEBUG]       omitForNearer: omitted=io.netty:netty-transport:jar:4.1.74.Final:compile kept=io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-codec:jar:4.1.74.Final:compile, replacement=io.netty:netty-codec:jar:4.1.74.Final
[DEBUG]       testArtifact: artifact=io.netty:netty-codec:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-codec:jar:4.1.74.Final:compile, replacement=io.netty:netty-codec:jar:4.1.74.Final
[DEBUG]       omitForNearer: omitted=io.netty:netty-codec:jar:4.1.74.Final:compile kept=io.netty:netty-codec:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-codec-dns:jar:4.1.74.Final:compile, replacement=io.netty:netty-codec-dns:jar:4.1.74.Final
[DEBUG]       testArtifact: artifact=io.netty:netty-codec-dns:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-codec-dns:jar:4.1.74.Final:compile, replacement=io.netty:netty-codec-dns:jar:4.1.74.Final
[DEBUG]       includeArtifact: artifact=io.netty:netty-codec-dns:jar:4.1.74.Final:compile
[DEBUG]       startProcessChildren: artifact=io.netty:netty-codec-dns:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]         testArtifact: artifact=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]         omitForNearer: omitted=io.netty:netty-common:jar:4.1.74.Final:compile kept=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile, replacement=io.netty:netty-buffer:jar:4.1.74.Final
[DEBUG]         testArtifact: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile, replacement=io.netty:netty-buffer:jar:4.1.74.Final
[DEBUG]         omitForNearer: omitted=io.netty:netty-buffer:jar:4.1.74.Final:compile kept=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile, replacement=io.netty:netty-transport:jar:4.1.74.Final
[DEBUG]         testArtifact: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile, replacement=io.netty:netty-transport:jar:4.1.74.Final
[DEBUG]         omitForNearer: omitted=io.netty:netty-transport:jar:4.1.74.Final:compile kept=io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-codec:jar:4.1.74.Final:compile, replacement=io.netty:netty-codec:jar:4.1.74.Final
[DEBUG]         testArtifact: artifact=io.netty:netty-codec:jar:4.1.74.Final:compile
[DEBUG]         manageArtifactVersion: artifact=io.netty:netty-codec:jar:4.1.74.Final:compile, replacement=io.netty:netty-codec:jar:4.1.74.Final
[DEBUG]         omitForNearer: omitted=io.netty:netty-codec:jar:4.1.74.Final:compile kept=io.netty:netty-codec:jar:4.1.74.Final:compile
[DEBUG]       endProcessChildren: artifact=io.netty:netty-codec-dns:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-handler:jar:4.1.74.Final:compile, replacement=io.netty:netty-handler:jar:4.1.74.Final
[DEBUG]       testArtifact: artifact=io.netty:netty-handler:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-handler:jar:4.1.74.Final:compile, replacement=io.netty:netty-handler:jar:4.1.74.Final
[DEBUG]       omitForNearer: omitted=io.netty:netty-handler:jar:4.1.74.Final:compile kept=io.netty:netty-handler:jar:4.1.74.Final:compile
[DEBUG]     endProcessChildren: artifact=io.netty:netty-resolver-dns:jar:4.1.74.Final:compile
[DEBUG]     manageArtifactVersion: artifact=org.apache.commons:commons-lang3:jar:3.6:compile, replacement=org.apache.commons:commons-lang3:jar:3.5
[DEBUG]     testArtifact: artifact=org.apache.commons:commons-lang3:jar:3.5:compile
[DEBUG]     manageArtifactVersion: artifact=org.apache.commons:commons-lang3:jar:3.5:compile, replacement=org.apache.commons:commons-lang3:jar:3.5
[DEBUG]     omitForNearer: omitted=org.apache.commons:commons-lang3:jar:3.5:compile kept=org.apache.commons:commons-lang3:jar:3.5:compile
[DEBUG]     includeArtifact: artifact=org.apache.commons:commons-lang3:jar:3.5:compile
[DEBUG]     startProcessChildren: artifact=org.apache.commons:commons-lang3:jar:3.5:compile
[DEBUG]     endProcessChildren: artifact=org.apache.commons:commons-lang3:jar:3.5:compile
[DEBUG]     manageArtifactVersion: artifact=org.asynchttpclient:async-http-client:jar:2.12.1:compile, replacement=org.asynchttpclient:async-http-client:jar:2.12.3
[DEBUG]     testArtifact: artifact=org.asynchttpclient:async-http-client:jar:2.12.3:compile
[DEBUG]     manageArtifactVersion: artifact=org.asynchttpclient:async-http-client:jar:2.12.3:compile, replacement=org.asynchttpclient:async-http-client:jar:2.12.3
[DEBUG]     includeArtifact: artifact=org.asynchttpclient:async-http-client:jar:2.12.3:compile
[DEBUG]     startProcessChildren: artifact=org.asynchttpclient:async-http-client:jar:2.12.3:compile
[DEBUG]       testArtifact: artifact=org.asynchttpclient:async-http-client-netty-utils:jar:2.12.3:compile
[DEBUG]       includeArtifact: artifact=org.asynchttpclient:async-http-client-netty-utils:jar:2.12.3:compile
[DEBUG]       startProcessChildren: artifact=org.asynchttpclient:async-http-client-netty-utils:jar:2.12.3:compile
[DEBUG]         manageArtifactVersion: artifact=org.slf4j:slf4j-api:jar:1.7.30:compile, replacement=org.slf4j:slf4j-api:jar:1.7.25
[DEBUG]         testArtifact: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile
[DEBUG]         manageArtifactVersion: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile, replacement=org.slf4j:slf4j-api:jar:1.7.25
[DEBUG]         omitForNearer: omitted=org.slf4j:slf4j-api:jar:1.7.25:compile kept=org.slf4j:slf4j-api:jar:1.7.25:compile
[DEBUG]         testArtifact: artifact=com.sun.activation:jakarta.activation:jar:1.2.2:compile
[DEBUG]         includeArtifact: artifact=com.sun.activation:jakarta.activation:jar:1.2.2:compile
[DEBUG]         startProcessChildren: artifact=com.sun.activation:jakarta.activation:jar:1.2.2:compile
[DEBUG]         endProcessChildren: artifact=com.sun.activation:jakarta.activation:jar:1.2.2:compile
[DEBUG]       endProcessChildren: artifact=org.asynchttpclient:async-http-client-netty-utils:jar:2.12.3:compile
[DEBUG]       manageArtifactVersion: artifact=org.reactivestreams:reactive-streams:jar:1.0.3:compile, replacement=org.reactivestreams:reactive-streams:jar:1.0.3
[DEBUG]       testArtifact: artifact=org.reactivestreams:reactive-streams:jar:1.0.3:compile
[DEBUG]       manageArtifactVersion: artifact=org.reactivestreams:reactive-streams:jar:1.0.3:compile, replacement=org.reactivestreams:reactive-streams:jar:1.0.3
[DEBUG]       includeArtifact: artifact=org.reactivestreams:reactive-streams:jar:1.0.3:compile
[DEBUG]       startProcessChildren: artifact=org.reactivestreams:reactive-streams:jar:1.0.3:compile
[DEBUG]       endProcessChildren: artifact=org.reactivestreams:reactive-streams:jar:1.0.3:compile
[DEBUG]       testArtifact: artifact=com.typesafe.netty:netty-reactive-streams:jar:2.0.4:compile
[DEBUG]       includeArtifact: artifact=com.typesafe.netty:netty-reactive-streams:jar:2.0.4:compile
[DEBUG]       startProcessChildren: artifact=com.typesafe.netty:netty-reactive-streams:jar:2.0.4:compile
[DEBUG]         manageArtifactVersion: artifact=org.reactivestreams:reactive-streams:jar:1.0.3:compile, replacement=org.reactivestreams:reactive-streams:jar:1.0.3
[DEBUG]         testArtifact: artifact=org.reactivestreams:reactive-streams:jar:1.0.3:compile
[DEBUG]         manageArtifactVersion: artifact=org.reactivestreams:reactive-streams:jar:1.0.3:compile, replacement=org.reactivestreams:reactive-streams:jar:1.0.3
[DEBUG]         omitForNearer: omitted=org.reactivestreams:reactive-streams:jar:1.0.3:compile kept=org.reactivestreams:reactive-streams:jar:1.0.3:compile
[DEBUG]       endProcessChildren: artifact=com.typesafe.netty:netty-reactive-streams:jar:2.0.4:compile
[DEBUG]       manageArtifactVersion: artifact=org.slf4j:slf4j-api:jar:1.7.30:compile, replacement=org.slf4j:slf4j-api:jar:1.7.25
[DEBUG]       testArtifact: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile
[DEBUG]       manageArtifactVersion: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile, replacement=org.slf4j:slf4j-api:jar:1.7.25
[DEBUG]       omitForNearer: omitted=org.slf4j:slf4j-api:jar:1.7.25:compile kept=org.slf4j:slf4j-api:jar:1.7.25:compile
[DEBUG]       testArtifact: artifact=com.sun.activation:jakarta.activation:jar:1.2.2:compile
[DEBUG]       omitForNearer: omitted=com.sun.activation:jakarta.activation:jar:1.2.2:compile kept=com.sun.activation:jakarta.activation:jar:1.2.2:compile
[DEBUG]       includeArtifact: artifact=com.sun.activation:jakarta.activation:jar:1.2.2:compile
[DEBUG]       startProcessChildren: artifact=com.sun.activation:jakarta.activation:jar:1.2.2:compile
[DEBUG]       endProcessChildren: artifact=com.sun.activation:jakarta.activation:jar:1.2.2:compile
[DEBUG]     endProcessChildren: artifact=org.asynchttpclient:async-http-client:jar:2.12.3:compile
[DEBUG]     manageArtifactVersion: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile, replacement=org.slf4j:slf4j-api:jar:1.7.25
[DEBUG]     testArtifact: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile
[DEBUG]     manageArtifactVersion: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile, replacement=org.slf4j:slf4j-api:jar:1.7.25
[DEBUG]     omitForNearer: omitted=org.slf4j:slf4j-api:jar:1.7.25:compile kept=org.slf4j:slf4j-api:jar:1.7.25:compile
[DEBUG]     includeArtifact: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile
[DEBUG]     startProcessChildren: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile
[DEBUG]     endProcessChildren: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile
[DEBUG]     testArtifact: artifact=com.yahoo.datasketches:sketches-core:jar:0.8.3:compile
[DEBUG]     includeArtifact: artifact=com.yahoo.datasketches:sketches-core:jar:0.8.3:compile
[DEBUG]     startProcessChildren: artifact=com.yahoo.datasketches:sketches-core:jar:0.8.3:compile
[DEBUG]       testArtifact: artifact=com.yahoo.datasketches:memory:jar:0.8.3:compile
[DEBUG]       includeArtifact: artifact=com.yahoo.datasketches:memory:jar:0.8.3:compile
[DEBUG]       startProcessChildren: artifact=com.yahoo.datasketches:memory:jar:0.8.3:compile
[DEBUG]       endProcessChildren: artifact=com.yahoo.datasketches:memory:jar:0.8.3:compile
[DEBUG]     endProcessChildren: artifact=com.yahoo.datasketches:sketches-core:jar:0.8.3:compile
[DEBUG]     manageArtifactVersion: artifact=com.google.code.gson:gson:jar:2.8.6:compile, replacement=com.google.code.gson:gson:jar:2.2.4
[DEBUG]     testArtifact: artifact=com.google.code.gson:gson:jar:2.2.4:compile
[DEBUG]     manageArtifactVersion: artifact=com.google.code.gson:gson:jar:2.2.4:compile, replacement=com.google.code.gson:gson:jar:2.2.4
[DEBUG]     omitForNearer: omitted=com.google.code.gson:gson:jar:2.2.4:compile kept=com.google.code.gson:gson:jar:2.2.4:compile
[DEBUG]     includeArtifact: artifact=com.google.code.gson:gson:jar:2.2.4:compile
[DEBUG]     startProcessChildren: artifact=com.google.code.gson:gson:jar:2.2.4:compile
[DEBUG]     endProcessChildren: artifact=com.google.code.gson:gson:jar:2.2.4:compile
[DEBUG]     manageArtifactVersion: artifact=org.apache.avro:avro:jar:1.9.1:compile, replacement=org.apache.avro:avro:jar:1.9.2
[DEBUG]     testArtifact: artifact=org.apache.avro:avro:jar:1.9.2:compile
[DEBUG]     manageArtifactVersion: artifact=org.apache.avro:avro:jar:1.9.2:compile, replacement=org.apache.avro:avro:jar:1.9.2
[DEBUG]     includeArtifact: artifact=org.apache.avro:avro:jar:1.9.2:compile
[DEBUG]     startProcessChildren: artifact=org.apache.avro:avro:jar:1.9.2:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-core:jar:2.10.2:compile, replacement=com.fasterxml.jackson.core:jackson-core:jar:2.10.0
[DEBUG]       testArtifact: artifact=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-core:jar:2.10.0
[DEBUG]       omitForNearer: omitted=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile kept=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile
[DEBUG]       includeArtifact: artifact=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile
[DEBUG]       startProcessChildren: artifact=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile
[DEBUG]       endProcessChildren: artifact=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-databind:jar:2.10.2:compile, replacement=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0
[DEBUG]       testArtifact: artifact=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0
[DEBUG]       omitForNearer: omitted=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile kept=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile
[DEBUG]       manageArtifactVersion: artifact=org.apache.commons:commons-compress:jar:1.19:compile, replacement=org.apache.commons:commons-compress:jar:1.21
[DEBUG]       testArtifact: artifact=org.apache.commons:commons-compress:jar:1.21:compile
[DEBUG]       manageArtifactVersion: artifact=org.apache.commons:commons-compress:jar:1.21:compile, replacement=org.apache.commons:commons-compress:jar:1.21
[DEBUG]       updateScope: artifact=org.apache.commons:commons-compress:jar:1.21:test, scope=compile
[DEBUG]       omitForNearer: omitted=org.apache.commons:commons-compress:jar:1.21:compile kept=org.apache.commons:commons-compress:jar:1.21:compile
[DEBUG]       includeArtifact: artifact=org.apache.commons:commons-compress:jar:1.21:compile
[DEBUG]       startProcessChildren: artifact=org.apache.commons:commons-compress:jar:1.21:compile
[DEBUG]       endProcessChildren: artifact=org.apache.commons:commons-compress:jar:1.21:compile
[DEBUG]       manageArtifactVersion: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile, replacement=org.slf4j:slf4j-api:jar:1.7.25
[DEBUG]       testArtifact: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile
[DEBUG]       manageArtifactVersion: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile, replacement=org.slf4j:slf4j-api:jar:1.7.25
[DEBUG]       omitForNearer: omitted=org.slf4j:slf4j-api:jar:1.7.25:compile kept=org.slf4j:slf4j-api:jar:1.7.25:compile
[DEBUG]     endProcessChildren: artifact=org.apache.avro:avro:jar:1.9.2:compile
[DEBUG]     testArtifact: artifact=org.apache.avro:avro-protobuf:jar:1.9.1:compile
[DEBUG]     includeArtifact: artifact=org.apache.avro:avro-protobuf:jar:1.9.1:compile
[DEBUG]     startProcessChildren: artifact=org.apache.avro:avro-protobuf:jar:1.9.1:compile
[DEBUG]       manageArtifactVersion: artifact=org.apache.avro:avro:jar:1.9.1:compile, replacement=org.apache.avro:avro:jar:1.9.2
[DEBUG]       testArtifact: artifact=org.apache.avro:avro:jar:1.9.2:compile
[DEBUG]       manageArtifactVersion: artifact=org.apache.avro:avro:jar:1.9.2:compile, replacement=org.apache.avro:avro:jar:1.9.2
[DEBUG]       omitForNearer: omitted=org.apache.avro:avro:jar:1.9.2:compile kept=org.apache.avro:avro:jar:1.9.2:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-core:jar:2.9.9:compile, replacement=com.fasterxml.jackson.core:jackson-core:jar:2.10.0
[DEBUG]       testArtifact: artifact=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-core:jar:2.10.0
[DEBUG]       omitForNearer: omitted=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile kept=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-databind:jar:2.9.9.3:compile, replacement=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0
[DEBUG]       testArtifact: artifact=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0
[DEBUG]       omitForNearer: omitted=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile kept=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile
[DEBUG]       manageArtifactVersion: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile, replacement=org.slf4j:slf4j-api:jar:1.7.25
[DEBUG]       testArtifact: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile
[DEBUG]       manageArtifactVersion: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile, replacement=org.slf4j:slf4j-api:jar:1.7.25
[DEBUG]       omitForNearer: omitted=org.slf4j:slf4j-api:jar:1.7.25:compile kept=org.slf4j:slf4j-api:jar:1.7.25:compile
[DEBUG]     endProcessChildren: artifact=org.apache.avro:avro-protobuf:jar:1.9.1:compile
[DEBUG]     testArtifact: artifact=com.fasterxml.jackson.module:jackson-module-jsonSchema:jar:2.11.1:compile
[DEBUG]     includeArtifact: artifact=com.fasterxml.jackson.module:jackson-module-jsonSchema:jar:2.11.1:compile
[DEBUG]     startProcessChildren: artifact=com.fasterxml.jackson.module:jackson-module-jsonSchema:jar:2.11.1:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.11.1:compile, replacement=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0
[DEBUG]       testArtifact: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0
[DEBUG]       omitForNearer: omitted=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile kept=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile
[DEBUG]       includeArtifact: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile
[DEBUG]       startProcessChildren: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile
[DEBUG]       endProcessChildren: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-core:jar:2.11.1:compile, replacement=com.fasterxml.jackson.core:jackson-core:jar:2.10.0
[DEBUG]       testArtifact: artifact=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-core:jar:2.10.0
[DEBUG]       omitForNearer: omitted=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile kept=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-databind:jar:2.11.1:compile, replacement=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0
[DEBUG]       testArtifact: artifact=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0
[DEBUG]       omitForNearer: omitted=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile kept=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile
[DEBUG]       manageArtifactVersion: artifact=javax.validation:validation-api:jar:1.1.0.Final:compile, replacement=javax.validation:validation-api:jar:2.0.1.Final
[DEBUG]       testArtifact: artifact=javax.validation:validation-api:jar:2.0.1.Final:compile
[DEBUG]       manageArtifactVersion: artifact=javax.validation:validation-api:jar:2.0.1.Final:compile, replacement=javax.validation:validation-api:jar:2.0.1.Final
[DEBUG]       includeArtifact: artifact=javax.validation:validation-api:jar:2.0.1.Final:compile
[DEBUG]       startProcessChildren: artifact=javax.validation:validation-api:jar:2.0.1.Final:compile
[DEBUG]       endProcessChildren: artifact=javax.validation:validation-api:jar:2.0.1.Final:compile
[DEBUG]     endProcessChildren: artifact=com.fasterxml.jackson.module:jackson-module-jsonSchema:jar:2.11.1:compile
[DEBUG]     testArtifact: artifact=net.jcip:jcip-annotations:jar:1.0:compile
[DEBUG]     includeArtifact: artifact=net.jcip:jcip-annotations:jar:1.0:compile
[DEBUG]     startProcessChildren: artifact=net.jcip:jcip-annotations:jar:1.0:compile
[DEBUG]     endProcessChildren: artifact=net.jcip:jcip-annotations:jar:1.0:compile
[DEBUG]   endProcessChildren: artifact=org.apache.pulsar:pulsar-client-original:jar:2.7.2:compile
[DEBUG]   testArtifact: artifact=org.apache.pulsar:pulsar-client-admin-original:jar:2.7.2:compile
[DEBUG]   includeArtifact: artifact=org.apache.pulsar:pulsar-client-admin-original:jar:2.7.2:compile
[DEBUG]   startProcessChildren: artifact=org.apache.pulsar:pulsar-client-admin-original:jar:2.7.2:compile
[DEBUG]     testArtifact: artifact=org.apache.pulsar:pulsar-client-original:jar:2.7.2:compile
[DEBUG]     omitForNearer: omitted=org.apache.pulsar:pulsar-client-original:jar:2.7.2:compile kept=org.apache.pulsar:pulsar-client-original:jar:2.7.2:compile
[DEBUG]     manageArtifactVersion: artifact=org.glassfish.jersey.core:jersey-client:jar:2.31:compile, replacement=org.glassfish.jersey.core:jersey-client:jar:2.35
[DEBUG]     testArtifact: artifact=org.glassfish.jersey.core:jersey-client:jar:2.35:compile
[DEBUG]     manageArtifactVersion: artifact=org.glassfish.jersey.core:jersey-client:jar:2.35:compile, replacement=org.glassfish.jersey.core:jersey-client:jar:2.35
[DEBUG]     includeArtifact: artifact=org.glassfish.jersey.core:jersey-client:jar:2.35:compile
[DEBUG]     startProcessChildren: artifact=org.glassfish.jersey.core:jersey-client:jar:2.35:compile
[DEBUG]       testArtifact: artifact=jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile
[DEBUG]       includeArtifact: artifact=jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile
[DEBUG]       startProcessChildren: artifact=jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile
[DEBUG]       endProcessChildren: artifact=jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile
[DEBUG]       manageArtifactVersion: artifact=org.glassfish.jersey.core:jersey-common:jar:2.35:compile, replacement=org.glassfish.jersey.core:jersey-common:jar:2.35
[DEBUG]       testArtifact: artifact=org.glassfish.jersey.core:jersey-common:jar:2.35:compile
[DEBUG]       manageArtifactVersion: artifact=org.glassfish.jersey.core:jersey-common:jar:2.35:compile, replacement=org.glassfish.jersey.core:jersey-common:jar:2.35
[DEBUG]       includeArtifact: artifact=org.glassfish.jersey.core:jersey-common:jar:2.35:compile
[DEBUG]       startProcessChildren: artifact=org.glassfish.jersey.core:jersey-common:jar:2.35:compile
[DEBUG]         testArtifact: artifact=jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile
[DEBUG]         omitForNearer: omitted=jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile kept=jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile
[DEBUG]         testArtifact: artifact=jakarta.annotation:jakarta.annotation-api:jar:1.3.5:compile
[DEBUG]         includeArtifact: artifact=jakarta.annotation:jakarta.annotation-api:jar:1.3.5:compile
[DEBUG]         startProcessChildren: artifact=jakarta.annotation:jakarta.annotation-api:jar:1.3.5:compile
[DEBUG]         endProcessChildren: artifact=jakarta.annotation:jakarta.annotation-api:jar:1.3.5:compile
[DEBUG]         testArtifact: artifact=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]         includeArtifact: artifact=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]         startProcessChildren: artifact=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]         endProcessChildren: artifact=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]         testArtifact: artifact=org.glassfish.hk2:osgi-resource-locator:jar:1.0.3:compile
[DEBUG]         includeArtifact: artifact=org.glassfish.hk2:osgi-resource-locator:jar:1.0.3:compile
[DEBUG]         startProcessChildren: artifact=org.glassfish.hk2:osgi-resource-locator:jar:1.0.3:compile
[DEBUG]         endProcessChildren: artifact=org.glassfish.hk2:osgi-resource-locator:jar:1.0.3:compile
[DEBUG]       endProcessChildren: artifact=org.glassfish.jersey.core:jersey-common:jar:2.35:compile
[DEBUG]       testArtifact: artifact=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]       omitForNearer: omitted=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile kept=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]       includeArtifact: artifact=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]       startProcessChildren: artifact=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]       endProcessChildren: artifact=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]     endProcessChildren: artifact=org.glassfish.jersey.core:jersey-client:jar:2.35:compile
[DEBUG]     manageArtifactVersion: artifact=org.glassfish.jersey.media:jersey-media-json-jackson:jar:2.31:compile, replacement=org.glassfish.jersey.media:jersey-media-json-jackson:jar:2.35
[DEBUG]     testArtifact: artifact=org.glassfish.jersey.media:jersey-media-json-jackson:jar:2.35:compile
[DEBUG]     manageArtifactVersion: artifact=org.glassfish.jersey.media:jersey-media-json-jackson:jar:2.35:compile, replacement=org.glassfish.jersey.media:jersey-media-json-jackson:jar:2.35
[DEBUG]     includeArtifact: artifact=org.glassfish.jersey.media:jersey-media-json-jackson:jar:2.35:compile
[DEBUG]     startProcessChildren: artifact=org.glassfish.jersey.media:jersey-media-json-jackson:jar:2.35:compile
[DEBUG]       manageArtifactVersion: artifact=org.glassfish.jersey.core:jersey-common:jar:2.35:compile, replacement=org.glassfish.jersey.core:jersey-common:jar:2.35
[DEBUG]       testArtifact: artifact=org.glassfish.jersey.core:jersey-common:jar:2.35:compile
[DEBUG]       manageArtifactVersion: artifact=org.glassfish.jersey.core:jersey-common:jar:2.35:compile, replacement=org.glassfish.jersey.core:jersey-common:jar:2.35
[DEBUG]       omitForNearer: omitted=org.glassfish.jersey.core:jersey-common:jar:2.35:compile kept=org.glassfish.jersey.core:jersey-common:jar:2.35:compile
[DEBUG]       testArtifact: artifact=org.glassfish.jersey.ext:jersey-entity-filtering:jar:2.35:compile
[DEBUG]       includeArtifact: artifact=org.glassfish.jersey.ext:jersey-entity-filtering:jar:2.35:compile
[DEBUG]       startProcessChildren: artifact=org.glassfish.jersey.ext:jersey-entity-filtering:jar:2.35:compile
[DEBUG]         testArtifact: artifact=jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile
[DEBUG]         omitForNearer: omitted=jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile kept=jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile
[DEBUG]       endProcessChildren: artifact=org.glassfish.jersey.ext:jersey-entity-filtering:jar:2.35:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.12.2:compile, replacement=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0
[DEBUG]       testArtifact: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0
[DEBUG]       omitForNearer: omitted=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile kept=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-databind:jar:2.12.2:compile, replacement=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0
[DEBUG]       testArtifact: artifact=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0
[DEBUG]       omitForNearer: omitted=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile kept=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.module:jackson-module-jaxb-annotations:jar:2.12.2:compile, replacement=com.fasterxml.jackson.module:jackson-module-jaxb-annotations:jar:2.10.0
[DEBUG]       testArtifact: artifact=com.fasterxml.jackson.module:jackson-module-jaxb-annotations:jar:2.10.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.module:jackson-module-jaxb-annotations:jar:2.10.0:compile, replacement=com.fasterxml.jackson.module:jackson-module-jaxb-annotations:jar:2.10.0
[DEBUG]       includeArtifact: artifact=com.fasterxml.jackson.module:jackson-module-jaxb-annotations:jar:2.10.0:compile
[DEBUG]       startProcessChildren: artifact=com.fasterxml.jackson.module:jackson-module-jaxb-annotations:jar:2.10.0:compile
[DEBUG]         manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0
[DEBUG]         testArtifact: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile
[DEBUG]         manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0
[DEBUG]         omitForNearer: omitted=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile kept=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile
[DEBUG]         manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-core:jar:2.10.0
[DEBUG]         testArtifact: artifact=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile
[DEBUG]         manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-core:jar:2.10.0
[DEBUG]         omitForNearer: omitted=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile kept=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile
[DEBUG]         manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0
[DEBUG]         testArtifact: artifact=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile
[DEBUG]         manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0
[DEBUG]         omitForNearer: omitted=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile kept=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile
[DEBUG]         testArtifact: artifact=jakarta.xml.bind:jakarta.xml.bind-api:jar:2.3.2:compile
[DEBUG]         includeArtifact: artifact=jakarta.xml.bind:jakarta.xml.bind-api:jar:2.3.2:compile
[DEBUG]         startProcessChildren: artifact=jakarta.xml.bind:jakarta.xml.bind-api:jar:2.3.2:compile
[DEBUG]           testArtifact: artifact=jakarta.activation:jakarta.activation-api:jar:1.2.1:compile
[DEBUG]           includeArtifact: artifact=jakarta.activation:jakarta.activation-api:jar:1.2.1:compile
[DEBUG]           startProcessChildren: artifact=jakarta.activation:jakarta.activation-api:jar:1.2.1:compile
[DEBUG]           endProcessChildren: artifact=jakarta.activation:jakarta.activation-api:jar:1.2.1:compile
[DEBUG]         endProcessChildren: artifact=jakarta.xml.bind:jakarta.xml.bind-api:jar:2.3.2:compile
[DEBUG]         testArtifact: artifact=jakarta.activation:jakarta.activation-api:jar:1.2.1:compile
[DEBUG]         omitForNearer: omitted=jakarta.activation:jakarta.activation-api:jar:1.2.1:compile kept=jakarta.activation:jakarta.activation-api:jar:1.2.1:compile
[DEBUG]         includeArtifact: artifact=jakarta.activation:jakarta.activation-api:jar:1.2.1:compile
[DEBUG]         startProcessChildren: artifact=jakarta.activation:jakarta.activation-api:jar:1.2.1:compile
[DEBUG]         endProcessChildren: artifact=jakarta.activation:jakarta.activation-api:jar:1.2.1:compile
[DEBUG]       endProcessChildren: artifact=com.fasterxml.jackson.module:jackson-module-jaxb-annotations:jar:2.10.0:compile
[DEBUG]     endProcessChildren: artifact=org.glassfish.jersey.media:jersey-media-json-jackson:jar:2.35:compile
[DEBUG]     manageArtifactVersion: artifact=org.glassfish.jersey.media:jersey-media-multipart:jar:2.31:compile, replacement=org.glassfish.jersey.media:jersey-media-multipart:jar:2.35
[DEBUG]     testArtifact: artifact=org.glassfish.jersey.media:jersey-media-multipart:jar:2.35:compile
[DEBUG]     manageArtifactVersion: artifact=org.glassfish.jersey.media:jersey-media-multipart:jar:2.35:compile, replacement=org.glassfish.jersey.media:jersey-media-multipart:jar:2.35
[DEBUG]     includeArtifact: artifact=org.glassfish.jersey.media:jersey-media-multipart:jar:2.35:compile
[DEBUG]     startProcessChildren: artifact=org.glassfish.jersey.media:jersey-media-multipart:jar:2.35:compile
[DEBUG]       manageArtifactVersion: artifact=org.glassfish.jersey.core:jersey-common:jar:2.35:compile, replacement=org.glassfish.jersey.core:jersey-common:jar:2.35
[DEBUG]       testArtifact: artifact=org.glassfish.jersey.core:jersey-common:jar:2.35:compile
[DEBUG]       manageArtifactVersion: artifact=org.glassfish.jersey.core:jersey-common:jar:2.35:compile, replacement=org.glassfish.jersey.core:jersey-common:jar:2.35
[DEBUG]       omitForNearer: omitted=org.glassfish.jersey.core:jersey-common:jar:2.35:compile kept=org.glassfish.jersey.core:jersey-common:jar:2.35:compile
[DEBUG]       testArtifact: artifact=org.jvnet.mimepull:mimepull:jar:1.9.13:compile
[DEBUG]       includeArtifact: artifact=org.jvnet.mimepull:mimepull:jar:1.9.13:compile
[DEBUG]       startProcessChildren: artifact=org.jvnet.mimepull:mimepull:jar:1.9.13:compile
[DEBUG]       endProcessChildren: artifact=org.jvnet.mimepull:mimepull:jar:1.9.13:compile
[DEBUG]     endProcessChildren: artifact=org.glassfish.jersey.media:jersey-media-multipart:jar:2.35:compile
[DEBUG]     manageArtifactVersion: artifact=com.fasterxml.jackson.jaxrs:jackson-jaxrs-json-provider:jar:2.11.1:compile, replacement=com.fasterxml.jackson.jaxrs:jackson-jaxrs-json-provider:jar:2.10.0
[DEBUG]     testArtifact: artifact=com.fasterxml.jackson.jaxrs:jackson-jaxrs-json-provider:jar:2.10.0:compile
[DEBUG]     manageArtifactVersion: artifact=com.fasterxml.jackson.jaxrs:jackson-jaxrs-json-provider:jar:2.10.0:compile, replacement=com.fasterxml.jackson.jaxrs:jackson-jaxrs-json-provider:jar:2.10.0
[DEBUG]     includeArtifact: artifact=com.fasterxml.jackson.jaxrs:jackson-jaxrs-json-provider:jar:2.10.0:compile
[DEBUG]     startProcessChildren: artifact=com.fasterxml.jackson.jaxrs:jackson-jaxrs-json-provider:jar:2.10.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.jaxrs:jackson-jaxrs-base:jar:2.10.0:compile, replacement=com.fasterxml.jackson.jaxrs:jackson-jaxrs-base:jar:2.10.0
[DEBUG]       testArtifact: artifact=com.fasterxml.jackson.jaxrs:jackson-jaxrs-base:jar:2.10.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.jaxrs:jackson-jaxrs-base:jar:2.10.0:compile, replacement=com.fasterxml.jackson.jaxrs:jackson-jaxrs-base:jar:2.10.0
[DEBUG]       includeArtifact: artifact=com.fasterxml.jackson.jaxrs:jackson-jaxrs-base:jar:2.10.0:compile
[DEBUG]       startProcessChildren: artifact=com.fasterxml.jackson.jaxrs:jackson-jaxrs-base:jar:2.10.0:compile
[DEBUG]         manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-core:jar:2.10.0
[DEBUG]         testArtifact: artifact=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile
[DEBUG]         manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-core:jar:2.10.0
[DEBUG]         omitForNearer: omitted=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile kept=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile
[DEBUG]         manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0
[DEBUG]         testArtifact: artifact=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile
[DEBUG]         manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0
[DEBUG]         omitForNearer: omitted=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile kept=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile
[DEBUG]       endProcessChildren: artifact=com.fasterxml.jackson.jaxrs:jackson-jaxrs-base:jar:2.10.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.module:jackson-module-jaxb-annotations:jar:2.10.0:compile, replacement=com.fasterxml.jackson.module:jackson-module-jaxb-annotations:jar:2.10.0
[DEBUG]       testArtifact: artifact=com.fasterxml.jackson.module:jackson-module-jaxb-annotations:jar:2.10.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.module:jackson-module-jaxb-annotations:jar:2.10.0:compile, replacement=com.fasterxml.jackson.module:jackson-module-jaxb-annotations:jar:2.10.0
[DEBUG]       omitForNearer: omitted=com.fasterxml.jackson.module:jackson-module-jaxb-annotations:jar:2.10.0:compile kept=com.fasterxml.jackson.module:jackson-module-jaxb-annotations:jar:2.10.0:compile
[DEBUG]     endProcessChildren: artifact=com.fasterxml.jackson.jaxrs:jackson-jaxrs-json-provider:jar:2.10.0:compile
[DEBUG]     manageArtifactVersion: artifact=org.glassfish.jersey.inject:jersey-hk2:jar:2.31:compile, replacement=org.glassfish.jersey.inject:jersey-hk2:jar:2.35
[DEBUG]     testArtifact: artifact=org.glassfish.jersey.inject:jersey-hk2:jar:2.35:compile
[DEBUG]     manageArtifactVersion: artifact=org.glassfish.jersey.inject:jersey-hk2:jar:2.35:compile, replacement=org.glassfish.jersey.inject:jersey-hk2:jar:2.35
[DEBUG]     includeArtifact: artifact=org.glassfish.jersey.inject:jersey-hk2:jar:2.35:compile
[DEBUG]     startProcessChildren: artifact=org.glassfish.jersey.inject:jersey-hk2:jar:2.35:compile
[DEBUG]       manageArtifactVersion: artifact=org.glassfish.jersey.core:jersey-common:jar:2.35:compile, replacement=org.glassfish.jersey.core:jersey-common:jar:2.35
[DEBUG]       testArtifact: artifact=org.glassfish.jersey.core:jersey-common:jar:2.35:compile
[DEBUG]       manageArtifactVersion: artifact=org.glassfish.jersey.core:jersey-common:jar:2.35:compile, replacement=org.glassfish.jersey.core:jersey-common:jar:2.35
[DEBUG]       omitForNearer: omitted=org.glassfish.jersey.core:jersey-common:jar:2.35:compile kept=org.glassfish.jersey.core:jersey-common:jar:2.35:compile
[DEBUG]       manageArtifactVersion: artifact=org.glassfish.hk2:hk2-locator:jar:2.6.1:compile, replacement=org.glassfish.hk2:hk2-locator:jar:2.6.1
[DEBUG]       testArtifact: artifact=org.glassfish.hk2:hk2-locator:jar:2.6.1:compile
[DEBUG]       manageArtifactVersion: artifact=org.glassfish.hk2:hk2-locator:jar:2.6.1:compile, replacement=org.glassfish.hk2:hk2-locator:jar:2.6.1
[DEBUG]       includeArtifact: artifact=org.glassfish.hk2:hk2-locator:jar:2.6.1:compile
[DEBUG]       startProcessChildren: artifact=org.glassfish.hk2:hk2-locator:jar:2.6.1:compile
[DEBUG]         testArtifact: artifact=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]         omitForNearer: omitted=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile kept=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]         testArtifact: artifact=org.glassfish.hk2.external:aopalliance-repackaged:jar:2.6.1:compile
[DEBUG]         includeArtifact: artifact=org.glassfish.hk2.external:aopalliance-repackaged:jar:2.6.1:compile
[DEBUG]         startProcessChildren: artifact=org.glassfish.hk2.external:aopalliance-repackaged:jar:2.6.1:compile
[DEBUG]         endProcessChildren: artifact=org.glassfish.hk2.external:aopalliance-repackaged:jar:2.6.1:compile
[DEBUG]         testArtifact: artifact=org.glassfish.hk2:hk2-api:jar:2.6.1:compile
[DEBUG]         includeArtifact: artifact=org.glassfish.hk2:hk2-api:jar:2.6.1:compile
[DEBUG]         startProcessChildren: artifact=org.glassfish.hk2:hk2-api:jar:2.6.1:compile
[DEBUG]           testArtifact: artifact=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]           omitForNearer: omitted=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile kept=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]           testArtifact: artifact=org.glassfish.hk2:hk2-utils:jar:2.6.1:compile
[DEBUG]           includeArtifact: artifact=org.glassfish.hk2:hk2-utils:jar:2.6.1:compile
[DEBUG]           startProcessChildren: artifact=org.glassfish.hk2:hk2-utils:jar:2.6.1:compile
[DEBUG]             testArtifact: artifact=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]             omitForNearer: omitted=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile kept=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]           endProcessChildren: artifact=org.glassfish.hk2:hk2-utils:jar:2.6.1:compile
[DEBUG]           testArtifact: artifact=org.glassfish.hk2.external:aopalliance-repackaged:jar:2.6.1:compile
[DEBUG]           omitForNearer: omitted=org.glassfish.hk2.external:aopalliance-repackaged:jar:2.6.1:compile kept=org.glassfish.hk2.external:aopalliance-repackaged:jar:2.6.1:compile
[DEBUG]         endProcessChildren: artifact=org.glassfish.hk2:hk2-api:jar:2.6.1:compile
[DEBUG]         testArtifact: artifact=org.glassfish.hk2:hk2-utils:jar:2.6.1:compile
[DEBUG]         omitForNearer: omitted=org.glassfish.hk2:hk2-utils:jar:2.6.1:compile kept=org.glassfish.hk2:hk2-utils:jar:2.6.1:compile
[DEBUG]         includeArtifact: artifact=org.glassfish.hk2:hk2-utils:jar:2.6.1:compile
[DEBUG]         startProcessChildren: artifact=org.glassfish.hk2:hk2-utils:jar:2.6.1:compile
[DEBUG]           testArtifact: artifact=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]           omitForNearer: omitted=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile kept=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]         endProcessChildren: artifact=org.glassfish.hk2:hk2-utils:jar:2.6.1:compile
[DEBUG]       endProcessChildren: artifact=org.glassfish.hk2:hk2-locator:jar:2.6.1:compile
[DEBUG]       manageArtifactVersion: artifact=org.javassist:javassist:jar:3.25.0-GA:compile, replacement=org.javassist:javassist:jar:3.19.0-GA
[DEBUG]       testArtifact: artifact=org.javassist:javassist:jar:3.19.0-GA:compile
[DEBUG]       manageArtifactVersion: artifact=org.javassist:javassist:jar:3.19.0-GA:compile, replacement=org.javassist:javassist:jar:3.19.0-GA
[DEBUG]       includeArtifact: artifact=org.javassist:javassist:jar:3.19.0-GA:compile
[DEBUG]       startProcessChildren: artifact=org.javassist:javassist:jar:3.19.0-GA:compile
[DEBUG]       endProcessChildren: artifact=org.javassist:javassist:jar:3.19.0-GA:compile
[DEBUG]     endProcessChildren: artifact=org.glassfish.jersey.inject:jersey-hk2:jar:2.35:compile
[DEBUG]     manageArtifactVersion: artifact=javax.xml.bind:jaxb-api:jar:2.3.1:compile, replacement=javax.xml.bind:jaxb-api:jar:2.3.0
[DEBUG]     testArtifact: artifact=javax.xml.bind:jaxb-api:jar:2.3.0:compile
[DEBUG]     manageArtifactVersion: artifact=javax.xml.bind:jaxb-api:jar:2.3.0:compile, replacement=javax.xml.bind:jaxb-api:jar:2.3.0
[DEBUG]     includeArtifact: artifact=javax.xml.bind:jaxb-api:jar:2.3.0:compile
[DEBUG]     startProcessChildren: artifact=javax.xml.bind:jaxb-api:jar:2.3.0:compile
[DEBUG]     endProcessChildren: artifact=javax.xml.bind:jaxb-api:jar:2.3.0:compile
[DEBUG]     testArtifact: artifact=com.sun.activation:javax.activation:jar:1.2.0:runtime
[DEBUG]     includeArtifact: artifact=com.sun.activation:javax.activation:jar:1.2.0:runtime
[DEBUG]     startProcessChildren: artifact=com.sun.activation:javax.activation:jar:1.2.0:runtime
[DEBUG]     endProcessChildren: artifact=com.sun.activation:javax.activation:jar:1.2.0:runtime
[DEBUG]     testArtifact: artifact=org.slf4j:jul-to-slf4j:jar:1.7.25:compile
[DEBUG]     includeArtifact: artifact=org.slf4j:jul-to-slf4j:jar:1.7.25:compile
[DEBUG]     startProcessChildren: artifact=org.slf4j:jul-to-slf4j:jar:1.7.25:compile
[DEBUG]       manageArtifactVersion: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile, replacement=org.slf4j:slf4j-api:jar:1.7.25
[DEBUG]       testArtifact: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile
[DEBUG]       manageArtifactVersion: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile, replacement=org.slf4j:slf4j-api:jar:1.7.25
[DEBUG]       omitForNearer: omitted=org.slf4j:slf4j-api:jar:1.7.25:compile kept=org.slf4j:slf4j-api:jar:1.7.25:compile
[DEBUG]     endProcessChildren: artifact=org.slf4j:jul-to-slf4j:jar:1.7.25:compile
[DEBUG]     manageArtifactVersion: artifact=com.google.guava:guava:jar:30.1-jre:compile, replacement=com.google.guava:guava:jar:20.0
[DEBUG]     testArtifact: artifact=com.google.guava:guava:jar:20.0:compile
[DEBUG]     manageArtifactVersion: artifact=com.google.guava:guava:jar:20.0:compile, replacement=com.google.guava:guava:jar:20.0
[DEBUG]     omitForNearer: omitted=com.google.guava:guava:jar:20.0:compile kept=com.google.guava:guava:jar:20.0:compile
[DEBUG]     includeArtifact: artifact=com.google.guava:guava:jar:20.0:compile
[DEBUG]     startProcessChildren: artifact=com.google.guava:guava:jar:20.0:compile
[DEBUG]     endProcessChildren: artifact=com.google.guava:guava:jar:20.0:compile
[DEBUG]     manageArtifactVersion: artifact=com.google.code.gson:gson:jar:2.8.6:compile, replacement=com.google.code.gson:gson:jar:2.2.4
[DEBUG]     testArtifact: artifact=com.google.code.gson:gson:jar:2.2.4:compile
[DEBUG]     manageArtifactVersion: artifact=com.google.code.gson:gson:jar:2.2.4:compile, replacement=com.google.code.gson:gson:jar:2.2.4
[DEBUG]     omitForNearer: omitted=com.google.code.gson:gson:jar:2.2.4:compile kept=com.google.code.gson:gson:jar:2.2.4:compile
[DEBUG]   endProcessChildren: artifact=org.apache.pulsar:pulsar-client-admin-original:jar:2.7.2:compile
[DEBUG]   testArtifact: artifact=javax.servlet:javax.servlet-api:jar:3.1.0:compile
[DEBUG]   includeArtifact: artifact=javax.servlet:javax.servlet-api:jar:3.1.0:compile
[DEBUG]   startProcessChildren: artifact=javax.servlet:javax.servlet-api:jar:3.1.0:compile
[DEBUG]   endProcessChildren: artifact=javax.servlet:javax.servlet-api:jar:3.1.0:compile
[DEBUG]   testArtifact: artifact=javax.ws.rs:javax.ws.rs-api:jar:2.1:compile
[DEBUG]   includeArtifact: artifact=javax.ws.rs:javax.ws.rs-api:jar:2.1:compile
[DEBUG]   startProcessChildren: artifact=javax.ws.rs:javax.ws.rs-api:jar:2.1:compile
[DEBUG]   endProcessChildren: artifact=javax.ws.rs:javax.ws.rs-api:jar:2.1:compile
[DEBUG]   testArtifact: artifact=org.glassfish.jersey.containers:jersey-container-grizzly2-http:jar:2.35:compile
[DEBUG]   includeArtifact: artifact=org.glassfish.jersey.containers:jersey-container-grizzly2-http:jar:2.35:compile
[DEBUG]   startProcessChildren: artifact=org.glassfish.jersey.containers:jersey-container-grizzly2-http:jar:2.35:compile
[DEBUG]     testArtifact: artifact=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]     omitForNearer: omitted=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile kept=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]     includeArtifact: artifact=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]     startProcessChildren: artifact=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]     endProcessChildren: artifact=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]     manageArtifactVersion: artifact=org.glassfish.grizzly:grizzly-http-server:jar:2.4.4:compile, replacement=org.glassfish.grizzly:grizzly-http-server:jar:2.4.4
[DEBUG]     testArtifact: artifact=org.glassfish.grizzly:grizzly-http-server:jar:2.4.4:compile
[DEBUG]     manageArtifactVersion: artifact=org.glassfish.grizzly:grizzly-http-server:jar:2.4.4:compile, replacement=org.glassfish.grizzly:grizzly-http-server:jar:2.4.4
[DEBUG]     includeArtifact: artifact=org.glassfish.grizzly:grizzly-http-server:jar:2.4.4:compile
[DEBUG]     startProcessChildren: artifact=org.glassfish.grizzly:grizzly-http-server:jar:2.4.4:compile
[DEBUG]       testArtifact: artifact=org.glassfish.grizzly:grizzly-http:jar:2.4.4:compile
[DEBUG]       includeArtifact: artifact=org.glassfish.grizzly:grizzly-http:jar:2.4.4:compile
[DEBUG]       startProcessChildren: artifact=org.glassfish.grizzly:grizzly-http:jar:2.4.4:compile
[DEBUG]         testArtifact: artifact=org.glassfish.grizzly:grizzly-framework:jar:2.4.4:compile
[DEBUG]         includeArtifact: artifact=org.glassfish.grizzly:grizzly-framework:jar:2.4.4:compile
[DEBUG]         startProcessChildren: artifact=org.glassfish.grizzly:grizzly-framework:jar:2.4.4:compile
[DEBUG]         endProcessChildren: artifact=org.glassfish.grizzly:grizzly-framework:jar:2.4.4:compile
[DEBUG]       endProcessChildren: artifact=org.glassfish.grizzly:grizzly-http:jar:2.4.4:compile
[DEBUG]     endProcessChildren: artifact=org.glassfish.grizzly:grizzly-http-server:jar:2.4.4:compile
[DEBUG]     manageArtifactVersion: artifact=org.glassfish.jersey.core:jersey-common:jar:2.35:compile, replacement=org.glassfish.jersey.core:jersey-common:jar:2.35
[DEBUG]     testArtifact: artifact=org.glassfish.jersey.core:jersey-common:jar:2.35:compile
[DEBUG]     manageArtifactVersion: artifact=org.glassfish.jersey.core:jersey-common:jar:2.35:compile, replacement=org.glassfish.jersey.core:jersey-common:jar:2.35
[DEBUG]     omitForNearer: omitted=org.glassfish.jersey.core:jersey-common:jar:2.35:compile kept=org.glassfish.jersey.core:jersey-common:jar:2.35:compile
[DEBUG]     includeArtifact: artifact=org.glassfish.jersey.core:jersey-common:jar:2.35:compile
[DEBUG]     startProcessChildren: artifact=org.glassfish.jersey.core:jersey-common:jar:2.35:compile
[DEBUG]       testArtifact: artifact=jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile
[DEBUG]       omitForNearer: omitted=jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile kept=jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile
[DEBUG]       testArtifact: artifact=jakarta.annotation:jakarta.annotation-api:jar:1.3.5:compile
[DEBUG]       includeArtifact: artifact=jakarta.annotation:jakarta.annotation-api:jar:1.3.5:compile
[DEBUG]       startProcessChildren: artifact=jakarta.annotation:jakarta.annotation-api:jar:1.3.5:compile
[DEBUG]       endProcessChildren: artifact=jakarta.annotation:jakarta.annotation-api:jar:1.3.5:compile
[DEBUG]       testArtifact: artifact=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]       omitForNearer: omitted=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile kept=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]       testArtifact: artifact=org.glassfish.hk2:osgi-resource-locator:jar:1.0.3:compile
[DEBUG]       includeArtifact: artifact=org.glassfish.hk2:osgi-resource-locator:jar:1.0.3:compile
[DEBUG]       startProcessChildren: artifact=org.glassfish.hk2:osgi-resource-locator:jar:1.0.3:compile
[DEBUG]       endProcessChildren: artifact=org.glassfish.hk2:osgi-resource-locator:jar:1.0.3:compile
[DEBUG]     endProcessChildren: artifact=org.glassfish.jersey.core:jersey-common:jar:2.35:compile
[DEBUG]     manageArtifactVersion: artifact=org.glassfish.jersey.core:jersey-server:jar:2.35:compile, replacement=org.glassfish.jersey.core:jersey-server:jar:2.35
[DEBUG]     testArtifact: artifact=org.glassfish.jersey.core:jersey-server:jar:2.35:compile
[DEBUG]     manageArtifactVersion: artifact=org.glassfish.jersey.core:jersey-server:jar:2.35:compile, replacement=org.glassfish.jersey.core:jersey-server:jar:2.35
[DEBUG]     includeArtifact: artifact=org.glassfish.jersey.core:jersey-server:jar:2.35:compile
[DEBUG]     startProcessChildren: artifact=org.glassfish.jersey.core:jersey-server:jar:2.35:compile
[DEBUG]       manageArtifactVersion: artifact=org.glassfish.jersey.core:jersey-common:jar:2.35:compile, replacement=org.glassfish.jersey.core:jersey-common:jar:2.35
[DEBUG]       testArtifact: artifact=org.glassfish.jersey.core:jersey-common:jar:2.35:compile
[DEBUG]       manageArtifactVersion: artifact=org.glassfish.jersey.core:jersey-common:jar:2.35:compile, replacement=org.glassfish.jersey.core:jersey-common:jar:2.35
[DEBUG]       omitForNearer: omitted=org.glassfish.jersey.core:jersey-common:jar:2.35:compile kept=org.glassfish.jersey.core:jersey-common:jar:2.35:compile
[DEBUG]       manageArtifactVersion: artifact=org.glassfish.jersey.core:jersey-client:jar:2.35:compile, replacement=org.glassfish.jersey.core:jersey-client:jar:2.35
[DEBUG]       testArtifact: artifact=org.glassfish.jersey.core:jersey-client:jar:2.35:compile
[DEBUG]       manageArtifactVersion: artifact=org.glassfish.jersey.core:jersey-client:jar:2.35:compile, replacement=org.glassfish.jersey.core:jersey-client:jar:2.35
[DEBUG]       omitForNearer: omitted=org.glassfish.jersey.core:jersey-client:jar:2.35:compile kept=org.glassfish.jersey.core:jersey-client:jar:2.35:compile
[DEBUG]       testArtifact: artifact=jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile
[DEBUG]       omitForNearer: omitted=jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile kept=jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile
[DEBUG]       testArtifact: artifact=jakarta.annotation:jakarta.annotation-api:jar:1.3.5:compile
[DEBUG]       omitForNearer: omitted=jakarta.annotation:jakarta.annotation-api:jar:1.3.5:compile kept=jakarta.annotation:jakarta.annotation-api:jar:1.3.5:compile
[DEBUG]       testArtifact: artifact=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]       omitForNearer: omitted=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile kept=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]       testArtifact: artifact=jakarta.validation:jakarta.validation-api:jar:2.0.2:compile
[DEBUG]       includeArtifact: artifact=jakarta.validation:jakarta.validation-api:jar:2.0.2:compile
[DEBUG]       startProcessChildren: artifact=jakarta.validation:jakarta.validation-api:jar:2.0.2:compile
[DEBUG]       endProcessChildren: artifact=jakarta.validation:jakarta.validation-api:jar:2.0.2:compile
[DEBUG]     endProcessChildren: artifact=org.glassfish.jersey.core:jersey-server:jar:2.35:compile
[DEBUG]     testArtifact: artifact=jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile
[DEBUG]     omitForNearer: omitted=jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile kept=jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile
[DEBUG]     includeArtifact: artifact=jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile
[DEBUG]     startProcessChildren: artifact=jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile
[DEBUG]     endProcessChildren: artifact=jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile
[DEBUG]   endProcessChildren: artifact=org.glassfish.jersey.containers:jersey-container-grizzly2-http:jar:2.35:compile
[DEBUG]   testArtifact: artifact=org.glassfish.jersey.core:jersey-server:jar:2.35:compile
[DEBUG]   omitForNearer: omitted=org.glassfish.jersey.core:jersey-server:jar:2.35:compile kept=org.glassfish.jersey.core:jersey-server:jar:2.35:compile
[DEBUG]   includeArtifact: artifact=org.glassfish.jersey.core:jersey-server:jar:2.35:compile
[DEBUG]   startProcessChildren: artifact=org.glassfish.jersey.core:jersey-server:jar:2.35:compile
[DEBUG]     manageArtifactVersion: artifact=org.glassfish.jersey.core:jersey-common:jar:2.35:compile, replacement=org.glassfish.jersey.core:jersey-common:jar:2.35
[DEBUG]     testArtifact: artifact=org.glassfish.jersey.core:jersey-common:jar:2.35:compile
[DEBUG]     manageArtifactVersion: artifact=org.glassfish.jersey.core:jersey-common:jar:2.35:compile, replacement=org.glassfish.jersey.core:jersey-common:jar:2.35
[DEBUG]     omitForNearer: omitted=org.glassfish.jersey.core:jersey-common:jar:2.35:compile kept=org.glassfish.jersey.core:jersey-common:jar:2.35:compile
[DEBUG]     manageArtifactVersion: artifact=org.glassfish.jersey.core:jersey-client:jar:2.35:compile, replacement=org.glassfish.jersey.core:jersey-client:jar:2.35
[DEBUG]     testArtifact: artifact=org.glassfish.jersey.core:jersey-client:jar:2.35:compile
[DEBUG]     manageArtifactVersion: artifact=org.glassfish.jersey.core:jersey-client:jar:2.35:compile, replacement=org.glassfish.jersey.core:jersey-client:jar:2.35
[DEBUG]     omitForNearer: omitted=org.glassfish.jersey.core:jersey-client:jar:2.35:compile kept=org.glassfish.jersey.core:jersey-client:jar:2.35:compile
[DEBUG]     testArtifact: artifact=jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile
[DEBUG]     omitForNearer: omitted=jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile kept=jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile
[DEBUG]     testArtifact: artifact=jakarta.annotation:jakarta.annotation-api:jar:1.3.5:compile
[DEBUG]     omitForNearer: omitted=jakarta.annotation:jakarta.annotation-api:jar:1.3.5:compile kept=jakarta.annotation:jakarta.annotation-api:jar:1.3.5:compile
[DEBUG]     includeArtifact: artifact=jakarta.annotation:jakarta.annotation-api:jar:1.3.5:compile
[DEBUG]     startProcessChildren: artifact=jakarta.annotation:jakarta.annotation-api:jar:1.3.5:compile
[DEBUG]     endProcessChildren: artifact=jakarta.annotation:jakarta.annotation-api:jar:1.3.5:compile
[DEBUG]     testArtifact: artifact=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]     omitForNearer: omitted=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile kept=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]     testArtifact: artifact=jakarta.validation:jakarta.validation-api:jar:2.0.2:compile
[DEBUG]     includeArtifact: artifact=jakarta.validation:jakarta.validation-api:jar:2.0.2:compile
[DEBUG]     startProcessChildren: artifact=jakarta.validation:jakarta.validation-api:jar:2.0.2:compile
[DEBUG]     endProcessChildren: artifact=jakarta.validation:jakarta.validation-api:jar:2.0.2:compile
[DEBUG]   endProcessChildren: artifact=org.glassfish.jersey.core:jersey-server:jar:2.35:compile
[DEBUG]   testArtifact: artifact=org.glassfish.jersey.containers:jersey-container-servlet-core:jar:2.35:compile
[DEBUG]   includeArtifact: artifact=org.glassfish.jersey.containers:jersey-container-servlet-core:jar:2.35:compile
[DEBUG]   startProcessChildren: artifact=org.glassfish.jersey.containers:jersey-container-servlet-core:jar:2.35:compile
[DEBUG]     testArtifact: artifact=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]     omitForNearer: omitted=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile kept=org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG]     manageArtifactVersion: artifact=org.glassfish.jersey.core:jersey-common:jar:2.35:compile, replacement=org.glassfish.jersey.core:jersey-common:jar:2.35
[DEBUG]     testArtifact: artifact=org.glassfish.jersey.core:jersey-common:jar:2.35:compile
[DEBUG]     manageArtifactVersion: artifact=org.glassfish.jersey.core:jersey-common:jar:2.35:compile, replacement=org.glassfish.jersey.core:jersey-common:jar:2.35
[DEBUG]     omitForNearer: omitted=org.glassfish.jersey.core:jersey-common:jar:2.35:compile kept=org.glassfish.jersey.core:jersey-common:jar:2.35:compile
[DEBUG]     manageArtifactVersion: artifact=org.glassfish.jersey.core:jersey-server:jar:2.35:compile, replacement=org.glassfish.jersey.core:jersey-server:jar:2.35
[DEBUG]     testArtifact: artifact=org.glassfish.jersey.core:jersey-server:jar:2.35:compile
[DEBUG]     manageArtifactVersion: artifact=org.glassfish.jersey.core:jersey-server:jar:2.35:compile, replacement=org.glassfish.jersey.core:jersey-server:jar:2.35
[DEBUG]     omitForNearer: omitted=org.glassfish.jersey.core:jersey-server:jar:2.35:compile kept=org.glassfish.jersey.core:jersey-server:jar:2.35:compile
[DEBUG]     testArtifact: artifact=jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile
[DEBUG]     omitForNearer: omitted=jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile kept=jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile
[DEBUG]   endProcessChildren: artifact=org.glassfish.jersey.containers:jersey-container-servlet-core:jar:2.35:compile
[DEBUG]   testArtifact: artifact=io.netty:netty-resolver:jar:4.1.74.Final:compile
[DEBUG]   includeArtifact: artifact=io.netty:netty-resolver:jar:4.1.74.Final:compile
[DEBUG]   startProcessChildren: artifact=io.netty:netty-resolver:jar:4.1.74.Final:compile
[DEBUG]     manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]     testArtifact: artifact=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]     manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]     omitForNearer: omitted=io.netty:netty-common:jar:4.1.74.Final:compile kept=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]     includeArtifact: artifact=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]     startProcessChildren: artifact=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]     endProcessChildren: artifact=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]   endProcessChildren: artifact=io.netty:netty-resolver:jar:4.1.74.Final:compile
[DEBUG]   testArtifact: artifact=io.prometheus:simpleclient_common:jar:0.8.1:compile
[DEBUG]   includeArtifact: artifact=io.prometheus:simpleclient_common:jar:0.8.1:compile
[DEBUG]   startProcessChildren: artifact=io.prometheus:simpleclient_common:jar:0.8.1:compile
[DEBUG]     testArtifact: artifact=io.prometheus:simpleclient:jar:0.8.1:compile
[DEBUG]     includeArtifact: artifact=io.prometheus:simpleclient:jar:0.8.1:compile
[DEBUG]     startProcessChildren: artifact=io.prometheus:simpleclient:jar:0.8.1:compile
[DEBUG]     endProcessChildren: artifact=io.prometheus:simpleclient:jar:0.8.1:compile
[DEBUG]   endProcessChildren: artifact=io.prometheus:simpleclient_common:jar:0.8.1:compile
[DEBUG]   testArtifact: artifact=com.google.api.grpc:proto-google-common-protos:jar:1.12.0:compile
[DEBUG]   includeArtifact: artifact=com.google.api.grpc:proto-google-common-protos:jar:1.12.0:compile
[DEBUG]   startProcessChildren: artifact=com.google.api.grpc:proto-google-common-protos:jar:1.12.0:compile
[DEBUG]     manageArtifactVersion: artifact=com.google.protobuf:protobuf-java:jar:3.5.1:compile, replacement=com.google.protobuf:protobuf-java:jar:3.19.2
[DEBUG]     testArtifact: artifact=com.google.protobuf:protobuf-java:jar:3.19.2:compile
[DEBUG]     manageArtifactVersion: artifact=com.google.protobuf:protobuf-java:jar:3.19.2:compile, replacement=com.google.protobuf:protobuf-java:jar:3.19.2
[DEBUG]     omitForNearer: omitted=com.google.protobuf:protobuf-java:jar:3.19.2:compile kept=com.google.protobuf:protobuf-java:jar:3.19.2:compile
[DEBUG]     includeArtifact: artifact=com.google.protobuf:protobuf-java:jar:3.19.2:compile
[DEBUG]     startProcessChildren: artifact=com.google.protobuf:protobuf-java:jar:3.19.2:compile
[DEBUG]     endProcessChildren: artifact=com.google.protobuf:protobuf-java:jar:3.19.2:compile
[DEBUG]   endProcessChildren: artifact=com.google.api.grpc:proto-google-common-protos:jar:1.12.0:compile
[DEBUG]   testArtifact: artifact=io.grpc:grpc-context:jar:1.14.0:compile
[DEBUG]   includeArtifact: artifact=io.grpc:grpc-context:jar:1.14.0:compile
[DEBUG]   startProcessChildren: artifact=io.grpc:grpc-context:jar:1.14.0:compile
[DEBUG]   endProcessChildren: artifact=io.grpc:grpc-context:jar:1.14.0:compile
[DEBUG]   testArtifact: artifact=commons-codec:commons-codec:jar:1.11:compile
[DEBUG]   includeArtifact: artifact=commons-codec:commons-codec:jar:1.11:compile
[DEBUG]   startProcessChildren: artifact=commons-codec:commons-codec:jar:1.11:compile
[DEBUG]   endProcessChildren: artifact=commons-codec:commons-codec:jar:1.11:compile
[DEBUG]   testArtifact: artifact=com.google.errorprone:error_prone_annotations:jar:2.3.4:compile
[DEBUG]   omitForNearer: omitted=com.google.errorprone:error_prone_annotations:jar:2.3.4:compile kept=com.google.errorprone:error_prone_annotations:jar:2.3.4:compile
[DEBUG]   includeArtifact: artifact=com.google.errorprone:error_prone_annotations:jar:2.3.4:compile
[DEBUG]   startProcessChildren: artifact=com.google.errorprone:error_prone_annotations:jar:2.3.4:compile
[DEBUG]   endProcessChildren: artifact=com.google.errorprone:error_prone_annotations:jar:2.3.4:compile
[DEBUG]   testArtifact: artifact=io.prometheus:simpleclient:jar:0.8.1:compile
[DEBUG]   omitForNearer: omitted=io.prometheus:simpleclient:jar:0.8.1:compile kept=io.prometheus:simpleclient:jar:0.8.1:compile
[DEBUG]   includeArtifact: artifact=io.prometheus:simpleclient:jar:0.8.1:compile
[DEBUG]   startProcessChildren: artifact=io.prometheus:simpleclient:jar:0.8.1:compile
[DEBUG]   endProcessChildren: artifact=io.prometheus:simpleclient:jar:0.8.1:compile
[DEBUG]   testArtifact: artifact=org.eclipse.jetty:jetty-servlet:jar:9.4.45.v20220203:compile
[DEBUG]   includeArtifact: artifact=org.eclipse.jetty:jetty-servlet:jar:9.4.45.v20220203:compile
[DEBUG]   startProcessChildren: artifact=org.eclipse.jetty:jetty-servlet:jar:9.4.45.v20220203:compile
[DEBUG]     testArtifact: artifact=org.eclipse.jetty:jetty-security:jar:9.4.45.v20220203:compile
[DEBUG]     includeArtifact: artifact=org.eclipse.jetty:jetty-security:jar:9.4.45.v20220203:compile
[DEBUG]     startProcessChildren: artifact=org.eclipse.jetty:jetty-security:jar:9.4.45.v20220203:compile
[DEBUG]       testArtifact: artifact=org.eclipse.jetty:jetty-server:jar:9.4.45.v20220203:compile
[DEBUG]       omitForNearer: omitted=org.eclipse.jetty:jetty-server:jar:9.4.45.v20220203:compile kept=org.eclipse.jetty:jetty-server:jar:9.4.45.v20220203:compile
[DEBUG]     endProcessChildren: artifact=org.eclipse.jetty:jetty-security:jar:9.4.45.v20220203:compile
[DEBUG]     testArtifact: artifact=org.eclipse.jetty:jetty-util-ajax:jar:9.4.45.v20220203:compile
[DEBUG]     includeArtifact: artifact=org.eclipse.jetty:jetty-util-ajax:jar:9.4.45.v20220203:compile
[DEBUG]     startProcessChildren: artifact=org.eclipse.jetty:jetty-util-ajax:jar:9.4.45.v20220203:compile
[DEBUG]       testArtifact: artifact=org.eclipse.jetty:jetty-util:jar:9.4.45.v20220203:compile
[DEBUG]       omitForNearer: omitted=org.eclipse.jetty:jetty-util:jar:9.4.45.v20220203:compile kept=org.eclipse.jetty:jetty-util:jar:9.4.45.v20220203:compile
[DEBUG]     endProcessChildren: artifact=org.eclipse.jetty:jetty-util-ajax:jar:9.4.45.v20220203:compile
[DEBUG]   endProcessChildren: artifact=org.eclipse.jetty:jetty-servlet:jar:9.4.45.v20220203:compile
[DEBUG]   testArtifact: artifact=com.squareup.okio:okio:jar:1.6.0:compile
[DEBUG]   includeArtifact: artifact=com.squareup.okio:okio:jar:1.6.0:compile
[DEBUG]   startProcessChildren: artifact=com.squareup.okio:okio:jar:1.6.0:compile
[DEBUG]   endProcessChildren: artifact=com.squareup.okio:okio:jar:1.6.0:compile
[DEBUG]   testArtifact: artifact=io.prometheus:simpleclient_hotspot:jar:0.8.1:compile
[DEBUG]   includeArtifact: artifact=io.prometheus:simpleclient_hotspot:jar:0.8.1:compile
[DEBUG]   startProcessChildren: artifact=io.prometheus:simpleclient_hotspot:jar:0.8.1:compile
[DEBUG]     testArtifact: artifact=io.prometheus:simpleclient:jar:0.8.1:compile
[DEBUG]     omitForNearer: omitted=io.prometheus:simpleclient:jar:0.8.1:compile kept=io.prometheus:simpleclient:jar:0.8.1:compile
[DEBUG]   endProcessChildren: artifact=io.prometheus:simpleclient_hotspot:jar:0.8.1:compile
[DEBUG]   testArtifact: artifact=io.swagger:swagger-annotations:jar:1.5.21:compile
[DEBUG]   omitForNearer: omitted=io.swagger:swagger-annotations:jar:1.5.21:compile kept=io.swagger:swagger-annotations:jar:1.5.21:compile
[DEBUG]   includeArtifact: artifact=io.swagger:swagger-annotations:jar:1.5.21:compile
[DEBUG]   startProcessChildren: artifact=io.swagger:swagger-annotations:jar:1.5.21:compile
[DEBUG]   endProcessChildren: artifact=io.swagger:swagger-annotations:jar:1.5.21:compile
[DEBUG]   testArtifact: artifact=io.grpc:grpc-protobuf-lite:jar:1.19.0:compile
[DEBUG]   includeArtifact: artifact=io.grpc:grpc-protobuf-lite:jar:1.19.0:compile
[DEBUG]   startProcessChildren: artifact=io.grpc:grpc-protobuf-lite:jar:1.19.0:compile
[DEBUG]     testArtifact: artifact=io.grpc:grpc-core:jar:1.19.0:compile
[DEBUG]     includeArtifact: artifact=io.grpc:grpc-core:jar:1.19.0:compile
[DEBUG]     startProcessChildren: artifact=io.grpc:grpc-core:jar:1.19.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.google.code.gson:gson:jar:2.7:compile, replacement=com.google.code.gson:gson:jar:2.2.4
[DEBUG]       testArtifact: artifact=com.google.code.gson:gson:jar:2.2.4:compile
[DEBUG]       manageArtifactVersion: artifact=com.google.code.gson:gson:jar:2.2.4:compile, replacement=com.google.code.gson:gson:jar:2.2.4
[DEBUG]       omitForNearer: omitted=com.google.code.gson:gson:jar:2.2.4:compile kept=com.google.code.gson:gson:jar:2.2.4:compile
[DEBUG]       manageArtifactVersion: artifact=com.google.code.findbugs:jsr305:jar:3.0.2:compile, replacement=com.google.code.findbugs:jsr305:jar:3.0.0
[DEBUG]       testArtifact: artifact=com.google.code.findbugs:jsr305:jar:3.0.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.google.code.findbugs:jsr305:jar:3.0.0:compile, replacement=com.google.code.findbugs:jsr305:jar:3.0.0
[DEBUG]       includeArtifact: artifact=com.google.code.findbugs:jsr305:jar:3.0.0:compile
[DEBUG]       startProcessChildren: artifact=com.google.code.findbugs:jsr305:jar:3.0.0:compile
[DEBUG]       endProcessChildren: artifact=com.google.code.findbugs:jsr305:jar:3.0.0:compile
[DEBUG]       testArtifact: artifact=org.codehaus.mojo:animal-sniffer-annotations:jar:1.17:compile
[DEBUG]       includeArtifact: artifact=org.codehaus.mojo:animal-sniffer-annotations:jar:1.17:compile
[DEBUG]       startProcessChildren: artifact=org.codehaus.mojo:animal-sniffer-annotations:jar:1.17:compile
[DEBUG]       endProcessChildren: artifact=org.codehaus.mojo:animal-sniffer-annotations:jar:1.17:compile
[DEBUG]       manageArtifactVersion: artifact=com.google.guava:guava:jar:26.0-android:compile, replacement=com.google.guava:guava:jar:20.0
[DEBUG]       testArtifact: artifact=com.google.guava:guava:jar:20.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.google.guava:guava:jar:20.0:compile, replacement=com.google.guava:guava:jar:20.0
[DEBUG]       omitForNearer: omitted=com.google.guava:guava:jar:20.0:compile kept=com.google.guava:guava:jar:20.0:compile
[DEBUG]       testArtifact: artifact=io.opencensus:opencensus-api:jar:0.19.2:compile
[DEBUG]       includeArtifact: artifact=io.opencensus:opencensus-api:jar:0.19.2:compile
[DEBUG]       startProcessChildren: artifact=io.opencensus:opencensus-api:jar:0.19.2:compile
[DEBUG]       endProcessChildren: artifact=io.opencensus:opencensus-api:jar:0.19.2:compile
[DEBUG]       testArtifact: artifact=io.opencensus:opencensus-contrib-grpc-metrics:jar:0.19.2:compile
[DEBUG]       includeArtifact: artifact=io.opencensus:opencensus-contrib-grpc-metrics:jar:0.19.2:compile
[DEBUG]       startProcessChildren: artifact=io.opencensus:opencensus-contrib-grpc-metrics:jar:0.19.2:compile
[DEBUG]         testArtifact: artifact=io.opencensus:opencensus-api:jar:0.19.2:compile
[DEBUG]         omitForNearer: omitted=io.opencensus:opencensus-api:jar:0.19.2:compile kept=io.opencensus:opencensus-api:jar:0.19.2:compile
[DEBUG]       endProcessChildren: artifact=io.opencensus:opencensus-contrib-grpc-metrics:jar:0.19.2:compile
[DEBUG]     endProcessChildren: artifact=io.grpc:grpc-core:jar:1.19.0:compile
[DEBUG]     testArtifact: artifact=com.google.protobuf:protobuf-lite:jar:3.0.1:compile
[DEBUG]     includeArtifact: artifact=com.google.protobuf:protobuf-lite:jar:3.0.1:compile
[DEBUG]     startProcessChildren: artifact=com.google.protobuf:protobuf-lite:jar:3.0.1:compile
[DEBUG]     endProcessChildren: artifact=com.google.protobuf:protobuf-lite:jar:3.0.1:compile
[DEBUG]     manageArtifactVersion: artifact=com.google.guava:guava:jar:26.0-android:compile, replacement=com.google.guava:guava:jar:20.0
[DEBUG]     testArtifact: artifact=com.google.guava:guava:jar:20.0:compile
[DEBUG]     manageArtifactVersion: artifact=com.google.guava:guava:jar:20.0:compile, replacement=com.google.guava:guava:jar:20.0
[DEBUG]     omitForNearer: omitted=com.google.guava:guava:jar:20.0:compile kept=com.google.guava:guava:jar:20.0:compile
[DEBUG]   endProcessChildren: artifact=io.grpc:grpc-protobuf-lite:jar:1.19.0:compile
[DEBUG]   testArtifact: artifact=org.apache.commons:commons-collections4:jar:4.1:compile
[DEBUG]   includeArtifact: artifact=org.apache.commons:commons-collections4:jar:4.1:compile
[DEBUG]   startProcessChildren: artifact=org.apache.commons:commons-collections4:jar:4.1:compile
[DEBUG]   endProcessChildren: artifact=org.apache.commons:commons-collections4:jar:4.1:compile
[DEBUG]   testArtifact: artifact=javax.annotation:javax.annotation-api:jar:1.2:compile
[DEBUG]   includeArtifact: artifact=javax.annotation:javax.annotation-api:jar:1.2:compile
[DEBUG]   startProcessChildren: artifact=javax.annotation:javax.annotation-api:jar:1.2:compile
[DEBUG]   endProcessChildren: artifact=javax.annotation:javax.annotation-api:jar:1.2:compile
[DEBUG]   testArtifact: artifact=org.codehaus.mojo:animal-sniffer-annotations:jar:1.17:compile
[DEBUG]   omitForNearer: omitted=org.codehaus.mojo:animal-sniffer-annotations:jar:1.17:compile kept=org.codehaus.mojo:animal-sniffer-annotations:jar:1.17:compile
[DEBUG]   includeArtifact: artifact=org.codehaus.mojo:animal-sniffer-annotations:jar:1.17:compile
[DEBUG]   startProcessChildren: artifact=org.codehaus.mojo:animal-sniffer-annotations:jar:1.17:compile
[DEBUG]   endProcessChildren: artifact=org.codehaus.mojo:animal-sniffer-annotations:jar:1.17:compile
[DEBUG]   testArtifact: artifact=com.github.ben-manes.caffeine:caffeine:jar:2.6.2:compile
[DEBUG]   includeArtifact: artifact=com.github.ben-manes.caffeine:caffeine:jar:2.6.2:compile
[DEBUG]   startProcessChildren: artifact=com.github.ben-manes.caffeine:caffeine:jar:2.6.2:compile
[DEBUG]   endProcessChildren: artifact=com.github.ben-manes.caffeine:caffeine:jar:2.6.2:compile
[DEBUG]   testArtifact: artifact=io.netty:netty-codec-socks:jar:4.1.74.Final:compile
[DEBUG]   includeArtifact: artifact=io.netty:netty-codec-socks:jar:4.1.74.Final:compile
[DEBUG]   startProcessChildren: artifact=io.netty:netty-codec-socks:jar:4.1.74.Final:compile
[DEBUG]     manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]     testArtifact: artifact=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]     manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]     omitForNearer: omitted=io.netty:netty-common:jar:4.1.74.Final:compile kept=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]     manageArtifactVersion: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile, replacement=io.netty:netty-buffer:jar:4.1.74.Final
[DEBUG]     testArtifact: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]     manageArtifactVersion: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile, replacement=io.netty:netty-buffer:jar:4.1.74.Final
[DEBUG]     omitForNearer: omitted=io.netty:netty-buffer:jar:4.1.74.Final:compile kept=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]     includeArtifact: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]     startProcessChildren: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]       testArtifact: artifact=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]       omitForNearer: omitted=io.netty:netty-common:jar:4.1.74.Final:compile kept=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]     endProcessChildren: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]     manageArtifactVersion: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile, replacement=io.netty:netty-transport:jar:4.1.74.Final
[DEBUG]     testArtifact: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG]     manageArtifactVersion: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile, replacement=io.netty:netty-transport:jar:4.1.74.Final
[DEBUG]     omitForNearer: omitted=io.netty:netty-transport:jar:4.1.74.Final:compile kept=io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG]     includeArtifact: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG]     startProcessChildren: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]       testArtifact: artifact=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]       omitForNearer: omitted=io.netty:netty-common:jar:4.1.74.Final:compile kept=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile, replacement=io.netty:netty-buffer:jar:4.1.74.Final
[DEBUG]       testArtifact: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile, replacement=io.netty:netty-buffer:jar:4.1.74.Final
[DEBUG]       omitForNearer: omitted=io.netty:netty-buffer:jar:4.1.74.Final:compile kept=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-resolver:jar:4.1.74.Final:compile, replacement=io.netty:netty-resolver:jar:4.1.74.Final
[DEBUG]       testArtifact: artifact=io.netty:netty-resolver:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-resolver:jar:4.1.74.Final:compile, replacement=io.netty:netty-resolver:jar:4.1.74.Final
[DEBUG]       omitForNearer: omitted=io.netty:netty-resolver:jar:4.1.74.Final:compile kept=io.netty:netty-resolver:jar:4.1.74.Final:compile
[DEBUG]     endProcessChildren: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG]     manageArtifactVersion: artifact=io.netty:netty-codec:jar:4.1.74.Final:compile, replacement=io.netty:netty-codec:jar:4.1.74.Final
[DEBUG]     testArtifact: artifact=io.netty:netty-codec:jar:4.1.74.Final:compile
[DEBUG]     manageArtifactVersion: artifact=io.netty:netty-codec:jar:4.1.74.Final:compile, replacement=io.netty:netty-codec:jar:4.1.74.Final
[DEBUG]     omitForNearer: omitted=io.netty:netty-codec:jar:4.1.74.Final:compile kept=io.netty:netty-codec:jar:4.1.74.Final:compile
[DEBUG]     includeArtifact: artifact=io.netty:netty-codec:jar:4.1.74.Final:compile
[DEBUG]     startProcessChildren: artifact=io.netty:netty-codec:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]       testArtifact: artifact=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-common:jar:4.1.74.Final:compile, replacement=io.netty:netty-common:jar:4.1.74.Final
[DEBUG]       omitForNearer: omitted=io.netty:netty-common:jar:4.1.74.Final:compile kept=io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile, replacement=io.netty:netty-buffer:jar:4.1.74.Final
[DEBUG]       testArtifact: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-buffer:jar:4.1.74.Final:compile, replacement=io.netty:netty-buffer:jar:4.1.74.Final
[DEBUG]       omitForNearer: omitted=io.netty:netty-buffer:jar:4.1.74.Final:compile kept=io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile, replacement=io.netty:netty-transport:jar:4.1.74.Final
[DEBUG]       testArtifact: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG]       manageArtifactVersion: artifact=io.netty:netty-transport:jar:4.1.74.Final:compile, replacement=io.netty:netty-transport:jar:4.1.74.Final
[DEBUG]       omitForNearer: omitted=io.netty:netty-transport:jar:4.1.74.Final:compile kept=io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG]     endProcessChildren: artifact=io.netty:netty-codec:jar:4.1.74.Final:compile
[DEBUG]   endProcessChildren: artifact=io.netty:netty-codec-socks:jar:4.1.74.Final:compile
[DEBUG]   testArtifact: artifact=org.bouncycastle:bcpkix-jdk15to18:jar:1.68:compile
[DEBUG]   includeArtifact: artifact=org.bouncycastle:bcpkix-jdk15to18:jar:1.68:compile
[DEBUG]   startProcessChildren: artifact=org.bouncycastle:bcpkix-jdk15to18:jar:1.68:compile
[DEBUG]     testArtifact: artifact=org.bouncycastle:bcprov-jdk15to18:jar:1.68:compile
[DEBUG]     includeArtifact: artifact=org.bouncycastle:bcprov-jdk15to18:jar:1.68:compile
[DEBUG]     startProcessChildren: artifact=org.bouncycastle:bcprov-jdk15to18:jar:1.68:compile
[DEBUG]     endProcessChildren: artifact=org.bouncycastle:bcprov-jdk15to18:jar:1.68:compile
[DEBUG]   endProcessChildren: artifact=org.bouncycastle:bcpkix-jdk15to18:jar:1.68:compile
[DEBUG]   testArtifact: artifact=org.bouncycastle:bcprov-ext-jdk15to18:jar:1.68:compile
[DEBUG]   includeArtifact: artifact=org.bouncycastle:bcprov-ext-jdk15to18:jar:1.68:compile
[DEBUG]   startProcessChildren: artifact=org.bouncycastle:bcprov-ext-jdk15to18:jar:1.68:compile
[DEBUG]   endProcessChildren: artifact=org.bouncycastle:bcprov-ext-jdk15to18:jar:1.68:compile
[DEBUG]   testArtifact: artifact=org.bouncycastle:bcprov-jdk15to18:jar:1.68:compile
[DEBUG]   omitForNearer: omitted=org.bouncycastle:bcprov-jdk15to18:jar:1.68:compile kept=org.bouncycastle:bcprov-jdk15to18:jar:1.68:compile
[DEBUG]   includeArtifact: artifact=org.bouncycastle:bcprov-jdk15to18:jar:1.68:compile
[DEBUG]   startProcessChildren: artifact=org.bouncycastle:bcprov-jdk15to18:jar:1.68:compile
[DEBUG]   endProcessChildren: artifact=org.bouncycastle:bcprov-jdk15to18:jar:1.68:compile
[DEBUG]   testArtifact: artifact=org.apache.pinot:pinot-spi:jar:0.11.0-SNAPSHOT:compile
[DEBUG]   includeArtifact: artifact=org.apache.pinot:pinot-spi:jar:0.11.0-SNAPSHOT:compile
[DEBUG]   startProcessChildren: artifact=org.apache.pinot:pinot-spi:jar:0.11.0-SNAPSHOT:compile
[DEBUG]     manageArtifactVersion: artifact=commons-configuration:commons-configuration:jar:1.10:compile, replacement=commons-configuration:commons-configuration:jar:1.10
[DEBUG]     testArtifact: artifact=commons-configuration:commons-configuration:jar:1.10:compile
[DEBUG]     manageArtifactVersion: artifact=commons-configuration:commons-configuration:jar:1.10:compile, replacement=commons-configuration:commons-configuration:jar:1.10
[DEBUG]     omitForNearer: omitted=commons-configuration:commons-configuration:jar:1.10:compile kept=commons-configuration:commons-configuration:jar:1.10:compile
[DEBUG]     includeArtifact: artifact=commons-configuration:commons-configuration:jar:1.10:compile
[DEBUG]     startProcessChildren: artifact=commons-configuration:commons-configuration:jar:1.10:compile
[DEBUG]     endProcessChildren: artifact=commons-configuration:commons-configuration:jar:1.10:compile
[DEBUG]     manageArtifactVersion: artifact=commons-io:commons-io:jar:2.11.0:compile, replacement=commons-io:commons-io:jar:2.11.0
[DEBUG]     testArtifact: artifact=commons-io:commons-io:jar:2.11.0:compile
[DEBUG]     manageArtifactVersion: artifact=commons-io:commons-io:jar:2.11.0:compile, replacement=commons-io:commons-io:jar:2.11.0
[DEBUG]     omitForNearer: omitted=commons-io:commons-io:jar:2.11.0:compile kept=commons-io:commons-io:jar:2.11.0:compile
[DEBUG]     includeArtifact: artifact=commons-io:commons-io:jar:2.11.0:compile
[DEBUG]     startProcessChildren: artifact=commons-io:commons-io:jar:2.11.0:compile
[DEBUG]     endProcessChildren: artifact=commons-io:commons-io:jar:2.11.0:compile
[DEBUG]     manageArtifactVersion: artifact=commons-lang:commons-lang:jar:2.6:compile, replacement=commons-lang:commons-lang:jar:2.6
[DEBUG]     testArtifact: artifact=commons-lang:commons-lang:jar:2.6:compile
[DEBUG]     manageArtifactVersion: artifact=commons-lang:commons-lang:jar:2.6:compile, replacement=commons-lang:commons-lang:jar:2.6
[DEBUG]     includeArtifact: artifact=commons-lang:commons-lang:jar:2.6:compile
[DEBUG]     startProcessChildren: artifact=commons-lang:commons-lang:jar:2.6:compile
[DEBUG]     endProcessChildren: artifact=commons-lang:commons-lang:jar:2.6:compile
[DEBUG]     manageArtifactVersion: artifact=commons-logging:commons-logging:jar:1.2:compile, replacement=commons-logging:commons-logging:jar:1.2
[DEBUG]     testArtifact: artifact=commons-logging:commons-logging:jar:1.2:compile
[DEBUG]     manageArtifactVersion: artifact=commons-logging:commons-logging:jar:1.2:compile, replacement=commons-logging:commons-logging:jar:1.2
[DEBUG]     includeArtifact: artifact=commons-logging:commons-logging:jar:1.2:compile
[DEBUG]     startProcessChildren: artifact=commons-logging:commons-logging:jar:1.2:compile
[DEBUG]     endProcessChildren: artifact=commons-logging:commons-logging:jar:1.2:compile
[DEBUG]     manageArtifactVersion: artifact=org.apache.commons:commons-lang3:jar:3.5:compile, replacement=org.apache.commons:commons-lang3:jar:3.5
[DEBUG]     testArtifact: artifact=org.apache.commons:commons-lang3:jar:3.5:compile
[DEBUG]     manageArtifactVersion: artifact=org.apache.commons:commons-lang3:jar:3.5:compile, replacement=org.apache.commons:commons-lang3:jar:3.5
[DEBUG]     omitForNearer: omitted=org.apache.commons:commons-lang3:jar:3.5:compile kept=org.apache.commons:commons-lang3:jar:3.5:compile
[DEBUG]     manageArtifactVersion: artifact=commons-collections:commons-collections:jar:3.2.2:compile, replacement=commons-collections:commons-collections:jar:3.2.2
[DEBUG]     testArtifact: artifact=commons-collections:commons-collections:jar:3.2.2:compile
[DEBUG]     manageArtifactVersion: artifact=commons-collections:commons-collections:jar:3.2.2:compile, replacement=commons-collections:commons-collections:jar:3.2.2
[DEBUG]     includeArtifact: artifact=commons-collections:commons-collections:jar:3.2.2:compile
[DEBUG]     startProcessChildren: artifact=commons-collections:commons-collections:jar:3.2.2:compile
[DEBUG]     endProcessChildren: artifact=commons-collections:commons-collections:jar:3.2.2:compile
[DEBUG]     manageArtifactVersion: artifact=com.google.guava:guava:jar:20.0:compile, replacement=com.google.guava:guava:jar:20.0
[DEBUG]     testArtifact: artifact=com.google.guava:guava:jar:20.0:compile
[DEBUG]     manageArtifactVersion: artifact=com.google.guava:guava:jar:20.0:compile, replacement=com.google.guava:guava:jar:20.0
[DEBUG]     omitForNearer: omitted=com.google.guava:guava:jar:20.0:compile kept=com.google.guava:guava:jar:20.0:compile
[DEBUG]     manageArtifactVersion: artifact=com.google.code.findbugs:jsr305:jar:3.0.0:compile, replacement=com.google.code.findbugs:jsr305:jar:3.0.0
[DEBUG]     testArtifact: artifact=com.google.code.findbugs:jsr305:jar:3.0.0:compile
[DEBUG]     manageArtifactVersion: artifact=com.google.code.findbugs:jsr305:jar:3.0.0:compile, replacement=com.google.code.findbugs:jsr305:jar:3.0.0
[DEBUG]     omitForNearer: omitted=com.google.code.findbugs:jsr305:jar:3.0.0:compile kept=com.google.code.findbugs:jsr305:jar:3.0.0:compile
[DEBUG]     includeArtifact: artifact=com.google.code.findbugs:jsr305:jar:3.0.0:compile
[DEBUG]     startProcessChildren: artifact=com.google.code.findbugs:jsr305:jar:3.0.0:compile
[DEBUG]     endProcessChildren: artifact=com.google.code.findbugs:jsr305:jar:3.0.0:compile
[DEBUG]     manageArtifactVersion: artifact=org.apache.logging.log4j:log4j-slf4j-impl:jar:2.17.1:compile, replacement=org.apache.logging.log4j:log4j-slf4j-impl:jar:2.17.1
[DEBUG]     testArtifact: artifact=org.apache.logging.log4j:log4j-slf4j-impl:jar:2.17.1:compile
[DEBUG]     manageArtifactVersion: artifact=org.apache.logging.log4j:log4j-slf4j-impl:jar:2.17.1:compile, replacement=org.apache.logging.log4j:log4j-slf4j-impl:jar:2.17.1
[DEBUG]     includeArtifact: artifact=org.apache.logging.log4j:log4j-slf4j-impl:jar:2.17.1:compile
[DEBUG]     startProcessChildren: artifact=org.apache.logging.log4j:log4j-slf4j-impl:jar:2.17.1:compile
[DEBUG]       manageArtifactVersion: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile, replacement=org.slf4j:slf4j-api:jar:1.7.25
[DEBUG]       testArtifact: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile
[DEBUG]       manageArtifactVersion: artifact=org.slf4j:slf4j-api:jar:1.7.25:compile, replacement=org.slf4j:slf4j-api:jar:1.7.25
[DEBUG]       omitForNearer: omitted=org.slf4j:slf4j-api:jar:1.7.25:compile kept=org.slf4j:slf4j-api:jar:1.7.25:compile
[DEBUG]       manageArtifactVersion: artifact=org.apache.logging.log4j:log4j-api:jar:2.17.1:compile, replacement=org.apache.logging.log4j:log4j-api:jar:2.17.1
[DEBUG]       testArtifact: artifact=org.apache.logging.log4j:log4j-api:jar:2.17.1:compile
[DEBUG]       manageArtifactVersion: artifact=org.apache.logging.log4j:log4j-api:jar:2.17.1:compile, replacement=org.apache.logging.log4j:log4j-api:jar:2.17.1
[DEBUG]       includeArtifact: artifact=org.apache.logging.log4j:log4j-api:jar:2.17.1:compile
[DEBUG]       startProcessChildren: artifact=org.apache.logging.log4j:log4j-api:jar:2.17.1:compile
[DEBUG]       endProcessChildren: artifact=org.apache.logging.log4j:log4j-api:jar:2.17.1:compile
[DEBUG]       manageArtifactVersion: artifact=org.apache.logging.log4j:log4j-core:jar:2.17.1:runtime, replacement=org.apache.logging.log4j:log4j-core:jar:2.17.1
[DEBUG]       testArtifact: artifact=org.apache.logging.log4j:log4j-core:jar:2.17.1:runtime
[DEBUG]       manageArtifactVersion: artifact=org.apache.logging.log4j:log4j-core:jar:2.17.1:runtime, replacement=org.apache.logging.log4j:log4j-core:jar:2.17.1
[DEBUG]       includeArtifact: artifact=org.apache.logging.log4j:log4j-core:jar:2.17.1:runtime
[DEBUG]       startProcessChildren: artifact=org.apache.logging.log4j:log4j-core:jar:2.17.1:runtime
[DEBUG]         manageArtifactVersion: artifact=org.apache.logging.log4j:log4j-api:jar:2.17.1:runtime, replacement=org.apache.logging.log4j:log4j-api:jar:2.17.1
[DEBUG]         testArtifact: artifact=org.apache.logging.log4j:log4j-api:jar:2.17.1:runtime
[DEBUG]         manageArtifactVersion: artifact=org.apache.logging.log4j:log4j-api:jar:2.17.1:runtime, replacement=org.apache.logging.log4j:log4j-api:jar:2.17.1
[DEBUG]         omitForNearer: omitted=org.apache.logging.log4j:log4j-api:jar:2.17.1:runtime kept=org.apache.logging.log4j:log4j-api:jar:2.17.1:compile
[DEBUG]       endProcessChildren: artifact=org.apache.logging.log4j:log4j-core:jar:2.17.1:runtime
[DEBUG]     endProcessChildren: artifact=org.apache.logging.log4j:log4j-slf4j-impl:jar:2.17.1:compile
[DEBUG]     manageArtifactVersion: artifact=com.lmax:disruptor:jar:3.3.4:compile, replacement=com.lmax:disruptor:jar:3.3.4
[DEBUG]     testArtifact: artifact=com.lmax:disruptor:jar:3.3.4:compile
[DEBUG]     manageArtifactVersion: artifact=com.lmax:disruptor:jar:3.3.4:compile, replacement=com.lmax:disruptor:jar:3.3.4
[DEBUG]     includeArtifact: artifact=com.lmax:disruptor:jar:3.3.4:compile
[DEBUG]     startProcessChildren: artifact=com.lmax:disruptor:jar:3.3.4:compile
[DEBUG]     endProcessChildren: artifact=com.lmax:disruptor:jar:3.3.4:compile
[DEBUG]     manageArtifactVersion: artifact=org.apache.logging.log4j:log4j-1.2-api:jar:2.17.1:compile, replacement=org.apache.logging.log4j:log4j-1.2-api:jar:2.17.1
[DEBUG]     testArtifact: artifact=org.apache.logging.log4j:log4j-1.2-api:jar:2.17.1:compile
[DEBUG]     manageArtifactVersion: artifact=org.apache.logging.log4j:log4j-1.2-api:jar:2.17.1:compile, replacement=org.apache.logging.log4j:log4j-1.2-api:jar:2.17.1
[DEBUG]     includeArtifact: artifact=org.apache.logging.log4j:log4j-1.2-api:jar:2.17.1:compile
[DEBUG]     startProcessChildren: artifact=org.apache.logging.log4j:log4j-1.2-api:jar:2.17.1:compile
[DEBUG]       manageArtifactVersion: artifact=org.apache.logging.log4j:log4j-api:jar:2.17.1:compile, replacement=org.apache.logging.log4j:log4j-api:jar:2.17.1
[DEBUG]       testArtifact: artifact=org.apache.logging.log4j:log4j-api:jar:2.17.1:compile
[DEBUG]       manageArtifactVersion: artifact=org.apache.logging.log4j:log4j-api:jar:2.17.1:compile, replacement=org.apache.logging.log4j:log4j-api:jar:2.17.1
[DEBUG]       omitForNearer: omitted=org.apache.logging.log4j:log4j-api:jar:2.17.1:compile kept=org.apache.logging.log4j:log4j-api:jar:2.17.1:compile
[DEBUG]     endProcessChildren: artifact=org.apache.logging.log4j:log4j-1.2-api:jar:2.17.1:compile
[DEBUG]     manageArtifactVersion: artifact=joda-time:joda-time:jar:2.10.5:compile, replacement=joda-time:joda-time:jar:2.10.5
[DEBUG]     testArtifact: artifact=joda-time:joda-time:jar:2.10.5:compile
[DEBUG]     manageArtifactVersion: artifact=joda-time:joda-time:jar:2.10.5:compile, replacement=joda-time:joda-time:jar:2.10.5
[DEBUG]     includeArtifact: artifact=joda-time:joda-time:jar:2.10.5:compile
[DEBUG]     startProcessChildren: artifact=joda-time:joda-time:jar:2.10.5:compile
[DEBUG]     endProcessChildren: artifact=joda-time:joda-time:jar:2.10.5:compile
[DEBUG]     manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0
[DEBUG]     testArtifact: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile
[DEBUG]     manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0
[DEBUG]     omitForNearer: omitted=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile kept=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile
[DEBUG]     includeArtifact: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile
[DEBUG]     startProcessChildren: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile
[DEBUG]     endProcessChildren: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile
[DEBUG]     manageArtifactVersion: artifact=org.yaml:snakeyaml:jar:1.30:compile, replacement=org.yaml:snakeyaml:jar:1.30
[DEBUG]     testArtifact: artifact=org.yaml:snakeyaml:jar:1.30:compile
[DEBUG]     manageArtifactVersion: artifact=org.yaml:snakeyaml:jar:1.30:compile, replacement=org.yaml:snakeyaml:jar:1.30
[DEBUG]     omitForNearer: omitted=org.yaml:snakeyaml:jar:1.30:compile kept=org.yaml:snakeyaml:jar:1.30:compile
[DEBUG]     includeArtifact: artifact=org.yaml:snakeyaml:jar:1.30:compile
[DEBUG]     startProcessChildren: artifact=org.yaml:snakeyaml:jar:1.30:compile
[DEBUG]     endProcessChildren: artifact=org.yaml:snakeyaml:jar:1.30:compile
[DEBUG]     manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0
[DEBUG]     testArtifact: artifact=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile
[DEBUG]     manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0
[DEBUG]     omitForNearer: omitted=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile kept=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile
[DEBUG]     includeArtifact: artifact=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile
[DEBUG]     startProcessChildren: artifact=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0
[DEBUG]       testArtifact: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0
[DEBUG]       omitForNearer: omitted=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile kept=com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-core:jar:2.10.0
[DEBUG]       testArtifact: artifact=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile, replacement=com.fasterxml.jackson.core:jackson-core:jar:2.10.0
[DEBUG]       omitForNearer: omitted=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile kept=com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile
[DEBUG]     endProcessChildren: artifact=com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile
[DEBUG]     manageArtifactVersion: artifact=org.apache.avro:avro:jar:1.9.2:compile, replacement=org.apache.avro:avro:jar:1.9.2
[DEBUG]     testArtifact: artifact=org.apache.avro:avro:jar:1.9.2:compile
[DEBUG]     manageArtifactVersion: artifact=org.apache.avro:avro:jar:1.9.2:compile, replacement=org.apache.avro:avro:jar:1.9.2
[DEBUG]     omitForNearer: omitted=org.apache.avro:avro:jar:1.9.2:compile kept=org.apache.avro:avro:jar:1.9.2:compile
[DEBUG]     manageArtifactVersion: artifact=org.codehaus.groovy:groovy-all:jar:2.4.21:compile, replacement=org.codehaus.groovy:groovy-all:jar:2.4.21
[DEBUG]     testArtifact: artifact=org.codehaus.groovy:groovy-all:jar:2.4.21:compile
[DEBUG]     manageArtifactVersion: artifact=org.codehaus.groovy:groovy-all:jar:2.4.21:compile, replacement=org.codehaus.groovy:groovy-all:jar:2.4.21
[DEBUG]     includeArtifact: artifact=org.codehaus.groovy:groovy-all:jar:2.4.21:compile
[DEBUG]     startProcessChildren: artifact=org.codehaus.groovy:groovy-all:jar:2.4.21:compile
[DEBUG]     endProcessChildren: artifact=org.codehaus.groovy:groovy-all:jar:2.4.21:compile
[DEBUG]     manageArtifactVersion: artifact=org.reflections:reflections:jar:0.9.9:compile, replacement=org.reflections:reflections:jar:0.9.9
[DEBUG]     testArtifact: artifact=org.reflections:reflections:jar:0.9.9:compile
[DEBUG]     manageArtifactVersion: artifact=org.reflections:reflections:jar:0.9.9:compile, replacement=org.reflections:reflections:jar:0.9.9
[DEBUG]     includeArtifact: artifact=org.reflections:reflections:jar:0.9.9:compile
[DEBUG]     startProcessChildren: artifact=org.reflections:reflections:jar:0.9.9:compile
[DEBUG]       manageArtifactVersion: artifact=com.google.guava:guava:jar:15.0:compile, replacement=com.google.guava:guava:jar:20.0
[DEBUG]       testArtifact: artifact=com.google.guava:guava:jar:20.0:compile
[DEBUG]       manageArtifactVersion: artifact=com.google.guava:guava:jar:20.0:compile, replacement=com.google.guava:guava:jar:20.0
[DEBUG]       omitForNearer: omitted=com.google.guava:guava:jar:20.0:compile kept=com.google.guava:guava:jar:20.0:compile
[DEBUG]       manageArtifactVersion: artifact=org.javassist:javassist:jar:3.18.2-GA:compile, replacement=org.javassist:javassist:jar:3.19.0-GA
[DEBUG]       testArtifact: artifact=org.javassist:javassist:jar:3.19.0-GA:compile
[DEBUG]       manageArtifactVersion: artifact=org.javassist:javassist:jar:3.19.0-GA:compile, replacement=org.javassist:javassist:jar:3.19.0-GA
[DEBUG]       omitForNearer: omitted=org.javassist:javassist:jar:3.19.0-GA:compile kept=org.javassist:javassist:jar:3.19.0-GA:compile
[DEBUG]       testArtifact: artifact=com.google.code.findbugs:annotations:jar:2.0.1:compile
[DEBUG]       includeArtifact: artifact=com.google.code.findbugs:annotations:jar:2.0.1:compile
[DEBUG]       startProcessChildren: artifact=com.google.code.findbugs:annotations:jar:2.0.1:compile
[DEBUG]       endProcessChildren: artifact=com.google.code.findbugs:annotations:jar:2.0.1:compile
[DEBUG]     endProcessChildren: artifact=org.reflections:reflections:jar:0.9.9:compile
[DEBUG]   endProcessChildren: artifact=org.apache.pinot:pinot-spi:jar:0.11.0-SNAPSHOT:compile
[DEBUG]   testArtifact: artifact=org.testng:testng:jar:6.11:test
[DEBUG]   includeArtifact: artifact=org.testng:testng:jar:6.11:test
[DEBUG]   startProcessChildren: artifact=org.testng:testng:jar:6.11:test
[DEBUG]     testArtifact: artifact=com.beust:jcommander:jar:1.64:test
[DEBUG]     includeArtifact: artifact=com.beust:jcommander:jar:1.64:test
[DEBUG]     startProcessChildren: artifact=com.beust:jcommander:jar:1.64:test
[DEBUG]     endProcessChildren: artifact=com.beust:jcommander:jar:1.64:test
[DEBUG]     manageArtifactVersion: artifact=org.yaml:snakeyaml:jar:1.17:test, replacement=org.yaml:snakeyaml:jar:1.30
[DEBUG]     testArtifact: artifact=org.yaml:snakeyaml:jar:1.30:test
[DEBUG]     manageArtifactVersion: artifact=org.yaml:snakeyaml:jar:1.30:test, replacement=org.yaml:snakeyaml:jar:1.30
[DEBUG]     omitForNearer: omitted=org.yaml:snakeyaml:jar:1.30:test kept=org.yaml:snakeyaml:jar:1.30:compile
[DEBUG]   endProcessChildren: artifact=org.testng:testng:jar:6.11:test
[DEBUG] endProcessChildren: artifact=org.apache.pinot:pinot-pulsar:jar:0.11.0-SNAPSHOT
[INFO] 
[INFO] --- jacoco-maven-plugin:0.8.6:prepare-agent (default) @ pinot-pulsar ---
[DEBUG] Using mirror maven-default-http-blocker (http://0.0.0.0/) for apache.snapshots (http://svn.apache.org/maven-snapshot-repository).
[DEBUG] Using mirror maven-default-http-blocker (http://0.0.0.0/) for ow2-snapshot (http://repository.ow2.org/nexus/content/repositories/snapshots).
[DEBUG] Dependency collection stats {ConflictMarker.analyzeTime=3836250, ConflictMarker.markTime=85083, ConflictMarker.nodeCount=191, ConflictIdSorter.graphTime=127084, ConflictIdSorter.topsortTime=174708, ConflictIdSorter.conflictIdCount=64, ConflictIdSorter.conflictIdCycleCount=0, ConflictResolver.totalTime=2847042, ConflictResolver.conflictItemCount=155, DefaultDependencyCollector.collectTime=221785500, DefaultDependencyCollector.transformTime=7132666}
[DEBUG] org.jacoco:jacoco-maven-plugin:jar:0.8.6
[DEBUG]    org.apache.maven:maven-plugin-api:jar:3.0:compile
[DEBUG]       org.apache.maven:maven-model:jar:3.0:compile
[DEBUG]       org.apache.maven:maven-artifact:jar:3.0:compile
[DEBUG]       org.sonatype.sisu:sisu-inject-plexus:jar:1.4.2:compile
[DEBUG]          org.sonatype.sisu:sisu-inject-bean:jar:1.4.2:compile
[DEBUG]             org.sonatype.sisu:sisu-guice:jar:noaop:2.1.7:compile
[DEBUG]    org.apache.maven:maven-core:jar:3.0:compile
[DEBUG]       org.apache.maven:maven-settings:jar:3.0:compile
[DEBUG]       org.apache.maven:maven-settings-builder:jar:3.0:compile
[DEBUG]       org.apache.maven:maven-repository-metadata:jar:3.0:compile
[DEBUG]       org.apache.maven:maven-model-builder:jar:3.0:compile
[DEBUG]       org.apache.maven:maven-aether-provider:jar:3.0:runtime
[DEBUG]       org.sonatype.aether:aether-impl:jar:1.7:compile
[DEBUG]          org.sonatype.aether:aether-spi:jar:1.7:compile
[DEBUG]       org.sonatype.aether:aether-api:jar:1.7:compile
[DEBUG]       org.sonatype.aether:aether-util:jar:1.7:compile
[DEBUG]       org.codehaus.plexus:plexus-interpolation:jar:1.14:compile
[DEBUG]       org.codehaus.plexus:plexus-classworlds:jar:2.2.3:compile
[DEBUG]       org.codehaus.plexus:plexus-component-annotations:jar:1.5.5:compile
[DEBUG]       org.sonatype.plexus:plexus-sec-dispatcher:jar:1.3:compile
[DEBUG]          org.sonatype.plexus:plexus-cipher:jar:1.4:compile
[DEBUG]    org.codehaus.plexus:plexus-utils:jar:3.0.22:compile
[DEBUG]    org.apache.maven.shared:file-management:jar:1.2.1:compile
[DEBUG]       org.apache.maven.shared:maven-shared-io:jar:1.1:compile
[DEBUG]          org.apache.maven:maven-artifact-manager:jar:2.0.2:compile
[DEBUG]          org.apache.maven.wagon:wagon-provider-api:jar:1.0-alpha-6:compile
[DEBUG]       org.codehaus.plexus:plexus-container-default:jar:1.0-alpha-9:compile
[DEBUG]          junit:junit:jar:4.13:compile (version managed from default)
[DEBUG]             org.hamcrest:hamcrest-core:jar:1.3:compile
[DEBUG]          classworlds:classworlds:jar:1.1-alpha-2:compile
[DEBUG]    org.apache.maven.reporting:maven-reporting-api:jar:3.0:compile
[DEBUG]       org.apache.maven.doxia:doxia-sink-api:jar:1.0:compile
[DEBUG]    org.apache.maven.reporting:maven-reporting-impl:jar:2.1:compile
[DEBUG]       org.apache.maven:maven-project:jar:2.0.10:compile
[DEBUG]          org.apache.maven:maven-profile:jar:2.0.10:compile
[DEBUG]          org.apache.maven:maven-plugin-registry:jar:2.0.10:compile
[DEBUG]       org.apache.maven.doxia:doxia-core:jar:1.1.2:compile
[DEBUG]          org.apache.maven.doxia:doxia-logging-api:jar:1.1.2:compile
[DEBUG]          xerces:xercesImpl:jar:2.8.1:compile
[DEBUG]          commons-lang:commons-lang:jar:2.4:compile
[DEBUG]          commons-httpclient:commons-httpclient:jar:3.1:compile
[DEBUG]             commons-codec:commons-codec:jar:1.2:compile
[DEBUG]       org.apache.maven.doxia:doxia-site-renderer:jar:1.1.2:compile
[DEBUG]          org.apache.maven.doxia:doxia-decoration-model:jar:1.1.2:compile
[DEBUG]          org.apache.maven.doxia:doxia-module-xhtml:jar:1.1.2:compile
[DEBUG]          org.apache.maven.doxia:doxia-module-fml:jar:1.1.2:compile
[DEBUG]          org.codehaus.plexus:plexus-i18n:jar:1.0-beta-7:compile
[DEBUG]          org.codehaus.plexus:plexus-velocity:jar:1.1.7:compile
[DEBUG]          org.apache.velocity:velocity:jar:1.5:compile
[DEBUG]          commons-collections:commons-collections:jar:3.2.2:compile (version managed from default)
[DEBUG]       commons-validator:commons-validator:jar:1.2.0:compile
[DEBUG]          commons-beanutils:commons-beanutils:jar:1.7.0:compile
[DEBUG]          commons-digester:commons-digester:jar:1.6:compile
[DEBUG]          commons-logging:commons-logging:jar:1.0.4:compile
[DEBUG]          oro:oro:jar:2.0.8:compile
[DEBUG]          xml-apis:xml-apis:jar:1.0.b2:compile
[DEBUG]    org.jacoco:org.jacoco.agent:jar:runtime:0.8.6:compile
[DEBUG]    org.jacoco:org.jacoco.core:jar:0.8.6:compile
[DEBUG]       org.ow2.asm:asm:jar:8.0.1:compile (version managed from default)
[DEBUG]       org.ow2.asm:asm-commons:jar:8.0.1:compile (version managed from default)
[DEBUG]          org.ow2.asm:asm-analysis:jar:8.0.1:compile (version managed from default)
[DEBUG]       org.ow2.asm:asm-tree:jar:8.0.1:compile (version managed from default)
[DEBUG]    org.jacoco:org.jacoco.report:jar:0.8.6:compile
[DEBUG] Created new class realm plugin>org.jacoco:jacoco-maven-plugin:0.8.6
[DEBUG] Importing foreign packages into class realm plugin>org.jacoco:jacoco-maven-plugin:0.8.6
[DEBUG]   Imported:  < project>org.apache.pinot:pinot-pulsar:0.11.0-SNAPSHOT
[DEBUG] Populating class realm plugin>org.jacoco:jacoco-maven-plugin:0.8.6
[DEBUG]   Included: org.jacoco:jacoco-maven-plugin:jar:0.8.6
[DEBUG]   Included: org.sonatype.sisu:sisu-inject-bean:jar:1.4.2
[DEBUG]   Included: org.sonatype.sisu:sisu-guice:jar:noaop:2.1.7
[DEBUG]   Included: org.sonatype.aether:aether-util:jar:1.7
[DEBUG]   Included: org.codehaus.plexus:plexus-interpolation:jar:1.14
[DEBUG]   Included: org.codehaus.plexus:plexus-component-annotations:jar:1.5.5
[DEBUG]   Included: org.sonatype.plexus:plexus-sec-dispatcher:jar:1.3
[DEBUG]   Included: org.sonatype.plexus:plexus-cipher:jar:1.4
[DEBUG]   Included: org.codehaus.plexus:plexus-utils:jar:3.0.22
[DEBUG]   Included: org.apache.maven.shared:file-management:jar:1.2.1
[DEBUG]   Included: org.apache.maven.shared:maven-shared-io:jar:1.1
[DEBUG]   Included: junit:junit:jar:4.13
[DEBUG]   Included: org.hamcrest:hamcrest-core:jar:1.3
[DEBUG]   Included: org.apache.maven.reporting:maven-reporting-api:jar:3.0
[DEBUG]   Included: org.apache.maven.doxia:doxia-sink-api:jar:1.0
[DEBUG]   Included: org.apache.maven.reporting:maven-reporting-impl:jar:2.1
[DEBUG]   Included: org.apache.maven.doxia:doxia-core:jar:1.1.2
[DEBUG]   Included: org.apache.maven.doxia:doxia-logging-api:jar:1.1.2
[DEBUG]   Included: xerces:xercesImpl:jar:2.8.1
[DEBUG]   Included: commons-lang:commons-lang:jar:2.4
[DEBUG]   Included: commons-httpclient:commons-httpclient:jar:3.1
[DEBUG]   Included: commons-codec:commons-codec:jar:1.2
[DEBUG]   Included: org.apache.maven.doxia:doxia-site-renderer:jar:1.1.2
[DEBUG]   Included: org.apache.maven.doxia:doxia-decoration-model:jar:1.1.2
[DEBUG]   Included: org.apache.maven.doxia:doxia-module-xhtml:jar:1.1.2
[DEBUG]   Included: org.apache.maven.doxia:doxia-module-fml:jar:1.1.2
[DEBUG]   Included: org.codehaus.plexus:plexus-i18n:jar:1.0-beta-7
[DEBUG]   Included: org.codehaus.plexus:plexus-velocity:jar:1.1.7
[DEBUG]   Included: org.apache.velocity:velocity:jar:1.5
[DEBUG]   Included: commons-collections:commons-collections:jar:3.2.2
[DEBUG]   Included: commons-validator:commons-validator:jar:1.2.0
[DEBUG]   Included: commons-beanutils:commons-beanutils:jar:1.7.0
[DEBUG]   Included: commons-digester:commons-digester:jar:1.6
[DEBUG]   Included: commons-logging:commons-logging:jar:1.0.4
[DEBUG]   Included: oro:oro:jar:2.0.8
[DEBUG]   Included: xml-apis:xml-apis:jar:1.0.b2
[DEBUG]   Included: org.jacoco:org.jacoco.agent:jar:runtime:0.8.6
[DEBUG]   Included: org.jacoco:org.jacoco.core:jar:0.8.6
[DEBUG]   Included: org.ow2.asm:asm:jar:8.0.1
[DEBUG]   Included: org.ow2.asm:asm-commons:jar:8.0.1
[DEBUG]   Included: org.ow2.asm:asm-analysis:jar:8.0.1
[DEBUG]   Included: org.ow2.asm:asm-tree:jar:8.0.1
[DEBUG]   Included: org.jacoco:org.jacoco.report:jar:0.8.6
[DEBUG] Configuring mojo org.jacoco:jacoco-maven-plugin:0.8.6:prepare-agent from plugin realm ClassRealm[plugin>org.jacoco:jacoco-maven-plugin:0.8.6, parent: jdk.internal.loader.ClassLoaders$AppClassLoader@2c13da15]
[DEBUG] Configuring mojo 'org.jacoco:jacoco-maven-plugin:0.8.6:prepare-agent' with basic configurator -->
[DEBUG]   (f) destFile = /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/jacoco.exec
[DEBUG]   (f) includes = [org/apache/pinot/**/*]
[DEBUG]   (f) pluginArtifactMap = {org.jacoco:jacoco-maven-plugin=org.jacoco:jacoco-maven-plugin:maven-plugin:0.8.6:, org.apache.maven:maven-plugin-api=org.apache.maven:maven-plugin-api:jar:3.0:compile, org.apache.maven:maven-model=org.apache.maven:maven-model:jar:3.0:compile, org.apache.maven:maven-artifact=org.apache.maven:maven-artifact:jar:3.0:compile, org.sonatype.sisu:sisu-inject-plexus=org.sonatype.sisu:sisu-inject-plexus:jar:1.4.2:compile, org.sonatype.sisu:sisu-inject-bean=org.sonatype.sisu:sisu-inject-bean:jar:1.4.2:compile, org.sonatype.sisu:sisu-guice=org.sonatype.sisu:sisu-guice:jar:noaop:2.1.7:compile, org.apache.maven:maven-core=org.apache.maven:maven-core:jar:3.0:compile, org.apache.maven:maven-settings=org.apache.maven:maven-settings:jar:3.0:compile, org.apache.maven:maven-settings-builder=org.apache.maven:maven-settings-builder:jar:3.0:compile, org.apache.maven:maven-repository-metadata=org.apache.maven:maven-repository-metadata:jar:3.0:compile, org.apache.maven:maven-model-builder=org.apache.maven:maven-model-builder:jar:3.0:compile, org.apache.maven:maven-aether-provider=org.apache.maven:maven-aether-provider:jar:3.0:runtime, org.sonatype.aether:aether-impl=org.sonatype.aether:aether-impl:jar:1.7:compile, org.sonatype.aether:aether-spi=org.sonatype.aether:aether-spi:jar:1.7:compile, org.sonatype.aether:aether-api=org.sonatype.aether:aether-api:jar:1.7:compile, org.sonatype.aether:aether-util=org.sonatype.aether:aether-util:jar:1.7:compile, org.codehaus.plexus:plexus-interpolation=org.codehaus.plexus:plexus-interpolation:jar:1.14:compile, org.codehaus.plexus:plexus-classworlds=org.codehaus.plexus:plexus-classworlds:jar:2.2.3:compile, org.codehaus.plexus:plexus-component-annotations=org.codehaus.plexus:plexus-component-annotations:jar:1.5.5:compile, org.sonatype.plexus:plexus-sec-dispatcher=org.sonatype.plexus:plexus-sec-dispatcher:jar:1.3:compile, org.sonatype.plexus:plexus-cipher=org.sonatype.plexus:plexus-cipher:jar:1.4:compile, org.codehaus.plexus:plexus-utils=org.codehaus.plexus:plexus-utils:jar:3.0.22:compile, org.apache.maven.shared:file-management=org.apache.maven.shared:file-management:jar:1.2.1:compile, org.apache.maven.shared:maven-shared-io=org.apache.maven.shared:maven-shared-io:jar:1.1:compile, org.apache.maven:maven-artifact-manager=org.apache.maven:maven-artifact-manager:jar:2.0.2:compile, org.apache.maven.wagon:wagon-provider-api=org.apache.maven.wagon:wagon-provider-api:jar:1.0-alpha-6:compile, org.codehaus.plexus:plexus-container-default=org.codehaus.plexus:plexus-container-default:jar:1.0-alpha-9:compile, junit:junit=junit:junit:jar:4.13:compile, org.hamcrest:hamcrest-core=org.hamcrest:hamcrest-core:jar:1.3:compile, classworlds:classworlds=classworlds:classworlds:jar:1.1-alpha-2:compile, org.apache.maven.reporting:maven-reporting-api=org.apache.maven.reporting:maven-reporting-api:jar:3.0:compile, org.apache.maven.doxia:doxia-sink-api=org.apache.maven.doxia:doxia-sink-api:jar:1.0:compile, org.apache.maven.reporting:maven-reporting-impl=org.apache.maven.reporting:maven-reporting-impl:jar:2.1:compile, org.apache.maven:maven-project=org.apache.maven:maven-project:jar:2.0.10:compile, org.apache.maven:maven-profile=org.apache.maven:maven-profile:jar:2.0.10:compile, org.apache.maven:maven-plugin-registry=org.apache.maven:maven-plugin-registry:jar:2.0.10:compile, org.apache.maven.doxia:doxia-core=org.apache.maven.doxia:doxia-core:jar:1.1.2:compile, org.apache.maven.doxia:doxia-logging-api=org.apache.maven.doxia:doxia-logging-api:jar:1.1.2:compile, xerces:xercesImpl=xerces:xercesImpl:jar:2.8.1:compile, commons-lang:commons-lang=commons-lang:commons-lang:jar:2.4:compile, commons-httpclient:commons-httpclient=commons-httpclient:commons-httpclient:jar:3.1:compile, commons-codec:commons-codec=commons-codec:commons-codec:jar:1.2:compile, org.apache.maven.doxia:doxia-site-renderer=org.apache.maven.doxia:doxia-site-renderer:jar:1.1.2:compile, org.apache.maven.doxia:doxia-decoration-model=org.apache.maven.doxia:doxia-decoration-model:jar:1.1.2:compile, org.apache.maven.doxia:doxia-module-xhtml=org.apache.maven.doxia:doxia-module-xhtml:jar:1.1.2:compile, org.apache.maven.doxia:doxia-module-fml=org.apache.maven.doxia:doxia-module-fml:jar:1.1.2:compile, org.codehaus.plexus:plexus-i18n=org.codehaus.plexus:plexus-i18n:jar:1.0-beta-7:compile, org.codehaus.plexus:plexus-velocity=org.codehaus.plexus:plexus-velocity:jar:1.1.7:compile, org.apache.velocity:velocity=org.apache.velocity:velocity:jar:1.5:compile, commons-collections:commons-collections=commons-collections:commons-collections:jar:3.2.2:compile, commons-validator:commons-validator=commons-validator:commons-validator:jar:1.2.0:compile, commons-beanutils:commons-beanutils=commons-beanutils:commons-beanutils:jar:1.7.0:compile, commons-digester:commons-digester=commons-digester:commons-digester:jar:1.6:compile, commons-logging:commons-logging=commons-logging:commons-logging:jar:1.0.4:compile, oro:oro=oro:oro:jar:2.0.8:compile, xml-apis:xml-apis=xml-apis:xml-apis:jar:1.0.b2:compile, org.jacoco:org.jacoco.agent=org.jacoco:org.jacoco.agent:jar:runtime:0.8.6:compile, org.jacoco:org.jacoco.core=org.jacoco:org.jacoco.core:jar:0.8.6:compile, org.ow2.asm:asm=org.ow2.asm:asm:jar:8.0.1:compile, org.ow2.asm:asm-commons=org.ow2.asm:asm-commons:jar:8.0.1:compile, org.ow2.asm:asm-analysis=org.ow2.asm:asm-analysis:jar:8.0.1:compile, org.ow2.asm:asm-tree=org.ow2.asm:asm-tree:jar:8.0.1:compile, org.jacoco:org.jacoco.report=org.jacoco:org.jacoco.report:jar:0.8.6:compile}
[DEBUG]   (f) project = MavenProject: org.apache.pinot:pinot-pulsar:0.11.0-SNAPSHOT @ /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/pom.xml
[DEBUG]   (f) skip = false
[DEBUG] -- end configuration --
[INFO] argLine set to -javaagent:/Users/.../.m2/repository/org/jacoco/org.jacoco.agent/0.8.6/org.jacoco.agent-0.8.6-runtime.jar=destfile=/Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/jacoco.exec,includes=org/apache/pinot/**/* -Xms4g -Xmx4g
[INFO] 
[INFO] --- maven-remote-resources-plugin:1.6.0:process (process-resource-bundles) @ pinot-pulsar ---
[DEBUG] Using mirror maven-default-http-blocker (http://0.0.0.0/) for apache-snapshots (http://people.apache.org/repo/m2-snapshot-repository).
[DEBUG] Dependency collection stats {ConflictMarker.analyzeTime=763458, ConflictMarker.markTime=88209, ConflictMarker.nodeCount=187, ConflictIdSorter.graphTime=78292, ConflictIdSorter.topsortTime=33542, ConflictIdSorter.conflictIdCount=58, ConflictIdSorter.conflictIdCycleCount=0, ConflictResolver.totalTime=4699584, ConflictResolver.conflictItemCount=98, DefaultDependencyCollector.collectTime=208574375, DefaultDependencyCollector.transformTime=5707750}
[DEBUG] org.apache.maven.plugins:maven-remote-resources-plugin:jar:1.6.0
[DEBUG]    org.apache.maven:maven-artifact:jar:2.2.1:compile
[DEBUG]    org.apache.maven:maven-core:jar:2.2.1:compile
[DEBUG]       org.apache.maven:maven-plugin-parameter-documenter:jar:2.2.1:compile
[DEBUG]       org.slf4j:slf4j-jdk14:jar:1.5.6:runtime
[DEBUG]          org.slf4j:slf4j-api:jar:1.5.6:runtime
[DEBUG]       org.slf4j:jcl-over-slf4j:jar:1.5.6:runtime
[DEBUG]       org.apache.maven.reporting:maven-reporting-api:jar:2.2.1:compile
[DEBUG]          org.apache.maven.doxia:doxia-sink-api:jar:1.1:compile
[DEBUG]          org.apache.maven.doxia:doxia-logging-api:jar:1.1:compile
[DEBUG]       org.apache.maven:maven-profile:jar:2.2.1:compile
[DEBUG]       org.codehaus.plexus:plexus-container-default:jar:1.0-alpha-9-stable-1:compile
[DEBUG]          junit:junit:jar:3.8.1:compile
[DEBUG]       org.apache.maven:maven-repository-metadata:jar:2.2.1:compile
[DEBUG]       org.apache.maven:maven-error-diagnostics:jar:2.2.1:compile
[DEBUG]       commons-cli:commons-cli:jar:1.2:compile
[DEBUG]       org.apache.maven:maven-plugin-descriptor:jar:2.2.1:compile
[DEBUG]       org.codehaus.plexus:plexus-interactivity-api:jar:1.0-alpha-4:compile
[DEBUG]       org.apache.maven:maven-artifact-manager:jar:2.2.1:compile
[DEBUG]          backport-util-concurrent:backport-util-concurrent:jar:3.1:compile
[DEBUG]       org.apache.maven:maven-monitor:jar:2.2.1:compile
[DEBUG]       classworlds:classworlds:jar:1.1:compile
[DEBUG]       org.sonatype.plexus:plexus-sec-dispatcher:jar:1.3:compile
[DEBUG]          org.sonatype.plexus:plexus-cipher:jar:1.4:compile
[DEBUG]    org.apache.maven:maven-model:jar:2.2.1:compile
[DEBUG]    org.apache.maven:maven-plugin-api:jar:2.2.1:compile
[DEBUG]    org.apache.maven:maven-project:jar:2.2.1:compile
[DEBUG]       org.apache.maven:maven-plugin-registry:jar:2.2.1:compile
[DEBUG]    org.apache.maven:maven-settings:jar:2.2.1:compile
[DEBUG]    org.apache.maven.shared:maven-artifact-resolver:jar:1.0:compile
[DEBUG]    org.apache.maven.shared:maven-common-artifact-filters:jar:1.4:compile
[DEBUG]    org.apache.maven.shared:maven-filtering:jar:3.1.1:compile
[DEBUG]       org.apache.maven.shared:maven-shared-utils:jar:3.0.0:compile
[DEBUG]          com.google.code.findbugs:jsr305:jar:2.0.1:compile
[DEBUG]       org.sonatype.plexus:plexus-build-api:jar:0.0.7:compile
[DEBUG]    org.codehaus.plexus:plexus-resources:jar:1.0.1:compile
[DEBUG]    org.codehaus.plexus:plexus-interpolation:jar:1.25:compile
[DEBUG]    org.codehaus.plexus:plexus-utils:jar:3.1.0:compile
[DEBUG]    commons-io:commons-io:jar:2.5:compile
[DEBUG]    org.apache.velocity:velocity:jar:1.7:compile
[DEBUG]       commons-collections:commons-collections:jar:3.2.1:compile
[DEBUG]       commons-lang:commons-lang:jar:2.4:compile
[DEBUG] Created new class realm plugin>org.apache.maven.plugins:maven-remote-resources-plugin:1.6.0
[DEBUG] Importing foreign packages into class realm plugin>org.apache.maven.plugins:maven-remote-resources-plugin:1.6.0
[DEBUG]   Imported:  < project>org.apache.pinot:pinot-pulsar:0.11.0-SNAPSHOT
[DEBUG] Populating class realm plugin>org.apache.maven.plugins:maven-remote-resources-plugin:1.6.0
[DEBUG]   Included: org.apache.maven.plugins:maven-remote-resources-plugin:jar:1.6.0
[DEBUG]   Included: org.slf4j:slf4j-jdk14:jar:1.5.6
[DEBUG]   Included: org.slf4j:jcl-over-slf4j:jar:1.5.6
[DEBUG]   Included: org.apache.maven.reporting:maven-reporting-api:jar:2.2.1
[DEBUG]   Included: org.apache.maven.doxia:doxia-sink-api:jar:1.1
[DEBUG]   Included: org.apache.maven.doxia:doxia-logging-api:jar:1.1
[DEBUG]   Included: junit:junit:jar:3.8.1
[DEBUG]   Included: commons-cli:commons-cli:jar:1.2
[DEBUG]   Included: org.codehaus.plexus:plexus-interactivity-api:jar:1.0-alpha-4
[DEBUG]   Included: backport-util-concurrent:backport-util-concurrent:jar:3.1
[DEBUG]   Included: org.sonatype.plexus:plexus-sec-dispatcher:jar:1.3
[DEBUG]   Included: org.sonatype.plexus:plexus-cipher:jar:1.4
[DEBUG]   Included: org.apache.maven.shared:maven-artifact-resolver:jar:1.0
[DEBUG]   Included: org.apache.maven.shared:maven-common-artifact-filters:jar:1.4
[DEBUG]   Included: org.apache.maven.shared:maven-filtering:jar:3.1.1
[DEBUG]   Included: org.apache.maven.shared:maven-shared-utils:jar:3.0.0
[DEBUG]   Included: com.google.code.findbugs:jsr305:jar:2.0.1
[DEBUG]   Included: org.sonatype.plexus:plexus-build-api:jar:0.0.7
[DEBUG]   Included: org.codehaus.plexus:plexus-resources:jar:1.0.1
[DEBUG]   Included: org.codehaus.plexus:plexus-interpolation:jar:1.25
[DEBUG]   Included: org.codehaus.plexus:plexus-utils:jar:3.1.0
[DEBUG]   Included: commons-io:commons-io:jar:2.5
[DEBUG]   Included: org.apache.velocity:velocity:jar:1.7
[DEBUG]   Included: commons-collections:commons-collections:jar:3.2.1
[DEBUG]   Included: commons-lang:commons-lang:jar:2.4
[DEBUG] Configuring mojo org.apache.maven.plugins:maven-remote-resources-plugin:1.6.0:process from plugin realm ClassRealm[plugin>org.apache.maven.plugins:maven-remote-resources-plugin:1.6.0, parent: jdk.internal.loader.ClassLoaders$AppClassLoader@2c13da15]
[DEBUG] Configuring mojo 'org.apache.maven.plugins:maven-remote-resources-plugin:1.6.0:process' with basic configurator -->
[DEBUG]   (f) appendedResourcesDirectory = /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/src/main/appended-resources
[DEBUG]   (f) attachToMain = true
[DEBUG]   (f) attachToTest = true
[DEBUG]   (f) basedir = /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar
[DEBUG]   (f) encoding = UTF-8
[DEBUG]   (f) excludeTransitive = false
[DEBUG]   (f) includeProjectProperties = false
[DEBUG]   (f) includeScope = runtime
[DEBUG]   (f) localRepository =       id: local
      url: file:///Users/.../.m2/repository/
   layout: default
snapshots: [enabled => true, update => always]
 releases: [enabled => true, update => always]
   blocked: false

[DEBUG]   (f) mavenSession = org.apache.maven.execution.MavenSession@53d6e959
[DEBUG]   (f) outputDirectory = /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/maven-shared-archive-resources
[DEBUG]   (f) project = MavenProject: org.apache.pinot:pinot-pulsar:0.11.0-SNAPSHOT @ /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/pom.xml
[DEBUG]   (f) remoteArtifactRepositories = [      id: apache.snapshots
      url: https://repository.apache.org/snapshots
   layout: default
snapshots: [enabled => true, update => daily]
 releases: [enabled => false, update => daily]
   blocked: false
,       id: central
      url: https://repo.maven.apache.org/maven2
   layout: default
snapshots: [enabled => false, update => daily]
 releases: [enabled => true, update => daily]
   blocked: false
]
[DEBUG]   (f) resourceBundles = [org.apache:apache-jar-resource-bundle:1.4]
[DEBUG]   (f) resources = [Resource {targetPath: null, filtering: false, FileSet {directory: /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/src/main/resources, PatternSet [includes: {}, excludes: {}]}}]
[DEBUG]   (f) runOnlyAtExecutionRoot = false
[DEBUG]   (f) skip = false
[DEBUG]   (f) useDefaultFilterDelimiters = true
[DEBUG]   (f) velocityFilterInMemoryThreshold = 5242880
[DEBUG] -- end configuration --
[INFO] Preparing remote bundle org.apache:apache-jar-resource-bundle:1.4
[DEBUG] Supplemental data models won't be loaded.  No models specified.
[DEBUG] Initializing Velocity, Calling init()...
[DEBUG] *******************************************************************
[DEBUG] Starting Apache Velocity v1.7 (compiled: 2010-11-19 12:14:37)
[DEBUG] RuntimeInstance initializing.
[DEBUG] Default Properties File: org/apache/velocity/runtime/defaults/velocity.properties
[DEBUG] Default ResourceManager initializing. (class org.apache.velocity.runtime.resource.ResourceManagerImpl)
[DEBUG] ResourceLoader instantiated: org.apache.velocity.runtime.resource.loader.ClasspathResourceLoader
[DEBUG] ResourceCache: initialized (class org.apache.velocity.runtime.resource.ResourceCacheImpl) with class java.util.Collections$SynchronizedMap cache map.
[DEBUG] Default ResourceManager initialization complete.
[DEBUG] Loaded System Directive: org.apache.velocity.runtime.directive.Stop
[DEBUG] Loaded System Directive: org.apache.velocity.runtime.directive.Define
[DEBUG] Loaded System Directive: org.apache.velocity.runtime.directive.Break
[DEBUG] Loaded System Directive: org.apache.velocity.runtime.directive.Evaluate
[DEBUG] Loaded System Directive: org.apache.velocity.runtime.directive.Literal
[DEBUG] Loaded System Directive: org.apache.velocity.runtime.directive.Macro
[DEBUG] Loaded System Directive: org.apache.velocity.runtime.directive.Parse
[DEBUG] Loaded System Directive: org.apache.velocity.runtime.directive.Include
[DEBUG] Loaded System Directive: org.apache.velocity.runtime.directive.Foreach
[DEBUG] Velocimacro : initialization starting.
[DEBUG] Velocimacro : "velocimacro.library" is not set.  Trying default library: VM_global_library.vm
[DEBUG] Velocimacro : Default library not found.
[DEBUG] Velocimacro : allowInline = true : VMs can be defined inline in templates
[DEBUG] Velocimacro : allowInlineToOverride = false : VMs defined inline may NOT replace previous VM definitions
[DEBUG] Velocimacro : allowInlineLocal = false : VMs defined inline will be global in scope if allowed.
[DEBUG] Velocimacro : autoload off : VM system will not automatically reload global library macros
[DEBUG] Velocimacro : Velocimacro : initialization complete.
[DEBUG] RuntimeInstance successfully initialized.
[DEBUG] processResourceBundle on bundle#1 jar:file:/Users/.../.m2/repository/org/apache/apache-jar-resource-bundle/1.4/apache-jar-resource-bundle-1.4.jar!/META-INF/maven/remote-resources.xml
[DEBUG] bundle#1 resource#1 META-INF/NOTICE.vm
[DEBUG] bundle#1 resource#2 META-INF/LICENSE.vm
[DEBUG] bundle#1 resource#3 META-INF/DEPENDENCIES.vm
[INFO] Copying 3 resources from 1 bundle.
[DEBUG] Writing /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/maven-shared-archive-resources/META-INF/NOTICE
[DEBUG] Writing /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/maven-shared-archive-resources/META-INF/LICENSE
[DEBUG] org.apache.pinot:pinot-pulsar:jar:0.11.0-SNAPSHOT (selected for null)
[DEBUG]   org.eclipse.jetty:jetty-server:jar:9.4.45.v20220203:compile (selected for compile)
[DEBUG]     org.eclipse.jetty:jetty-http:jar:9.4.45.v20220203:compile (selected for compile)
[DEBUG]       org.eclipse.jetty:jetty-util:jar:9.4.45.v20220203:compile (selected for compile)
[DEBUG]       org.eclipse.jetty:jetty-io:jar:9.4.45.v20220203:compile (selected for compile)
[DEBUG]     org.eclipse.jetty:jetty-io:jar:9.4.45.v20220203:compile (selected for compile)
[DEBUG]   org.testcontainers:pulsar:jar:1.17.1:test (selected for test)
[DEBUG]     org.testcontainers:testcontainers:jar:1.17.1:test (selected for test)
[DEBUG]       junit:junit:jar:4.13.2:test (selected for test)
[DEBUG]         org.hamcrest:hamcrest-core:jar:1.3:test (selected for test)
[DEBUG]       org.slf4j:slf4j-api:jar:1.7.35:test (applying version: 1.7.25)
[DEBUG]       org.slf4j:slf4j-api:jar:1.7.25:test (selected for test)
[DEBUG]       org.apache.commons:commons-compress:jar:1.21:test (selected for test)
[DEBUG]       org.rnorth.duct-tape:duct-tape:jar:1.0.8:test (selected for test)
[DEBUG]         org.jetbrains:annotations:jar:17.0.0:test (selected for test)
[DEBUG]       com.github.docker-java:docker-java-api:jar:3.2.13:test (selected for test)
[DEBUG]         com.fasterxml.jackson.core:jackson-annotations:jar:2.10.3:test (applying version: 2.10.0)
[DEBUG]         com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:test (selected for test)
[DEBUG]         org.slf4j:slf4j-api:jar:1.7.30:test (applying version: 1.7.25)
[DEBUG]       com.github.docker-java:docker-java-transport-zerodep:jar:3.2.13:test (selected for test)
[DEBUG]         com.github.docker-java:docker-java-transport:jar:3.2.13:test (selected for test)
[DEBUG]         net.java.dev.jna:jna:jar:5.8.0:test (selected for test)
[DEBUG]   org.apache.pulsar:pulsar-client-original:jar:2.7.2:compile (selected for compile)
[DEBUG]     org.apache.pulsar:pulsar-client-api:jar:2.7.2:compile (selected for compile)
[DEBUG]     org.apache.pulsar:pulsar-common:jar:2.7.2:compile (selected for compile)
[DEBUG]       io.swagger:swagger-annotations:jar:1.5.21:compile (selected for compile)
[DEBUG]       org.slf4j:slf4j-api:jar:1.7.25:test (setting artifactScope to: compile)
[DEBUG]       org.slf4j:slf4j-api:jar:1.7.25:compile (selected for compile)
[DEBUG]       com.fasterxml.jackson.core:jackson-databind:jar:2.11.1:compile (applying version: 2.10.0)
[DEBUG]       com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile (selected for compile)
[DEBUG]         com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:test (setting artifactScope to: compile)
[DEBUG]         com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile (selected for compile)
[DEBUG]         com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile (selected for compile)
[DEBUG]       org.apache.pulsar:protobuf-shaded:jar:2.1.0-incubating:compile (selected for compile)
[DEBUG]       com.google.guava:guava:jar:30.1-jre:compile (applying version: 20.0)
[DEBUG]       com.google.guava:guava:jar:20.0:compile (selected for compile)
[DEBUG]       io.netty:netty-handler:jar:4.1.60.Final:compile (applying version: 4.1.74.Final)
[DEBUG]       io.netty:netty-handler:jar:4.1.74.Final:compile (selected for compile)
[DEBUG]         io.netty:netty-common:jar:4.1.74.Final:compile (selected for compile)
[DEBUG]         io.netty:netty-buffer:jar:4.1.74.Final:compile (selected for compile)
[DEBUG]         io.netty:netty-transport:jar:4.1.74.Final:compile (selected for compile)
[DEBUG]         io.netty:netty-codec:jar:4.1.74.Final:compile (selected for compile)
[DEBUG]         io.netty:netty-tcnative-classes:jar:2.0.48.Final:compile (selected for compile)
[DEBUG]       io.netty:netty-transport-native-epoll:jar:linux-x86_64:4.1.60.Final:compile (applying version: 4.1.74.Final)
[DEBUG]       io.netty:netty-transport-native-epoll:jar:linux-x86_64:4.1.74.Final:compile (selected for compile)
[DEBUG]         io.netty:netty-transport-classes-epoll:jar:4.1.74.Final:compile (selected for compile)
[DEBUG]       org.apache.bookkeeper:bookkeeper-common-allocator:jar:4.12.0:compile (selected for compile)
[DEBUG]         io.netty:netty-buffer:jar:4.1.50.Final:compile (applying version: 4.1.74.Final)
[DEBUG]       io.airlift:aircompressor:jar:0.16:compile (selected for compile)
[DEBUG]       org.apache.bookkeeper:circe-checksum:jar:4.12.0:compile (selected for compile)
[DEBUG]         com.google.guava:guava:jar:30.0-jre:compile (applying version: 20.0)
[DEBUG]         commons-configuration:commons-configuration:jar:1.10:compile (selected for compile)
[DEBUG]           commons-lang:commons-lang:jar:2.6:compile (selected for compile)
[DEBUG]           commons-logging:commons-logging:jar:1.1.1:compile (applying version: 1.2)
[DEBUG]           commons-logging:commons-logging:jar:1.2:compile (selected for compile)
[DEBUG]       io.netty:netty-tcnative-boringssl-static:jar:2.0.36.Final:compile (applying version: 2.0.48.Final)
[DEBUG]       io.netty:netty-tcnative-boringssl-static:jar:2.0.48.Final:compile (selected for compile)
[DEBUG]       io.netty:netty-codec-haproxy:jar:4.1.60.Final:compile (applying version: 4.1.74.Final)
[DEBUG]       io.netty:netty-codec-haproxy:jar:4.1.74.Final:compile (selected for compile)
[DEBUG]       org.apache.commons:commons-lang3:jar:3.6:compile (applying version: 3.5)
[DEBUG]       org.apache.commons:commons-lang3:jar:3.5:compile (selected for compile)
[DEBUG]       com.fasterxml.jackson.dataformat:jackson-dataformat-yaml:jar:2.11.1:compile (applying version: 2.10.0)
[DEBUG]       com.fasterxml.jackson.dataformat:jackson-dataformat-yaml:jar:2.10.0:compile (selected for compile)
[DEBUG]         org.yaml:snakeyaml:jar:1.24:compile (applying version: 1.30)
[DEBUG]         org.yaml:snakeyaml:jar:1.30:compile (selected for compile)
[DEBUG]       commons-io:commons-io:jar:2.8.0:compile (applying version: 2.11.0)
[DEBUG]       commons-io:commons-io:jar:2.11.0:compile (selected for compile)
[DEBUG]     org.apache.pulsar:pulsar-transaction-common:jar:2.7.2:compile (selected for compile)
[DEBUG]       com.google.protobuf:protobuf-java:jar:3.11.4:compile (applying version: 3.19.2)
[DEBUG]       com.google.protobuf:protobuf-java:jar:3.19.2:compile (selected for compile)
[DEBUG]       com.google.protobuf:protobuf-java-util:jar:3.11.4:compile (selected for compile)
[DEBUG]         com.google.protobuf:protobuf-java:jar:3.11.4:compile (applying version: 3.19.2)
[DEBUG]         com.google.guava:guava:jar:28.1-android:compile (applying version: 20.0)
[DEBUG]         com.google.errorprone:error_prone_annotations:jar:2.3.4:compile (selected for compile)
[DEBUG]         com.google.code.gson:gson:jar:2.8.6:compile (applying version: 2.2.4)
[DEBUG]         com.google.code.gson:gson:jar:2.2.4:compile (selected for compile)
[DEBUG]     org.apache.pulsar:bouncy-castle-bc:jar:pkg:2.7.2:compile (selected for compile)
[DEBUG]     io.netty:netty-codec-http:jar:4.1.60.Final:compile (applying version: 4.1.74.Final)
[DEBUG]     io.netty:netty-codec-http:jar:4.1.74.Final:compile (selected for compile)
[DEBUG]       io.netty:netty-common:jar:4.1.74.Final:compile (selected for compile)
[DEBUG]       io.netty:netty-buffer:jar:4.1.74.Final:compile (selected for compile)
[DEBUG]       io.netty:netty-transport:jar:4.1.74.Final:compile (selected for compile)
[DEBUG]       io.netty:netty-codec:jar:4.1.74.Final:compile (selected for compile)
[DEBUG]     io.netty:netty-resolver-dns:jar:4.1.60.Final:compile (applying version: 4.1.74.Final)
[DEBUG]     io.netty:netty-resolver-dns:jar:4.1.74.Final:compile (selected for compile)
[DEBUG]       io.netty:netty-codec-dns:jar:4.1.74.Final:compile (selected for compile)
[DEBUG]     org.apache.commons:commons-lang3:jar:3.6:compile (applying version: 3.5)
[DEBUG]     org.apache.commons:commons-lang3:jar:3.5:compile (selected for compile)
[DEBUG]     org.asynchttpclient:async-http-client:jar:2.12.1:compile (applying version: 2.12.3)
[DEBUG]     org.asynchttpclient:async-http-client:jar:2.12.3:compile (selected for compile)
[DEBUG]       org.asynchttpclient:async-http-client-netty-utils:jar:2.12.3:compile (selected for compile)
[DEBUG]         org.slf4j:slf4j-api:jar:1.7.30:compile (applying version: 1.7.25)
[DEBUG]         com.sun.activation:jakarta.activation:jar:1.2.2:compile (selected for compile)
[DEBUG]       org.reactivestreams:reactive-streams:jar:1.0.3:compile (selected for compile)
[DEBUG]       com.typesafe.netty:netty-reactive-streams:jar:2.0.4:compile (selected for compile)
[DEBUG]       org.slf4j:slf4j-api:jar:1.7.30:compile (applying version: 1.7.25)
[DEBUG]       com.sun.activation:jakarta.activation:jar:1.2.2:compile (selected for compile)
[DEBUG]     org.slf4j:slf4j-api:jar:1.7.25:compile (selected for compile)
[DEBUG]     com.yahoo.datasketches:sketches-core:jar:0.8.3:compile (selected for compile)
[DEBUG]       com.yahoo.datasketches:memory:jar:0.8.3:compile (selected for compile)
[DEBUG]     com.google.code.gson:gson:jar:2.8.6:compile (applying version: 2.2.4)
[DEBUG]     com.google.code.gson:gson:jar:2.2.4:compile (selected for compile)
[DEBUG]     org.apache.avro:avro:jar:1.9.1:compile (applying version: 1.9.2)
[DEBUG]     org.apache.avro:avro:jar:1.9.2:compile (selected for compile)
[DEBUG]       com.fasterxml.jackson.core:jackson-core:jar:2.10.2:compile (applying version: 2.10.0)
[DEBUG]       com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile (selected for compile)
[DEBUG]       com.fasterxml.jackson.core:jackson-databind:jar:2.10.2:compile (applying version: 2.10.0)
[DEBUG]       org.apache.commons:commons-compress:jar:1.19:compile (applying version: 1.21)
[DEBUG]       org.apache.commons:commons-compress:jar:1.21:test (setting artifactScope to: compile)
[DEBUG]       org.apache.commons:commons-compress:jar:1.21:compile (selected for compile)
[DEBUG]     org.apache.avro:avro-protobuf:jar:1.9.1:compile (selected for compile)
[DEBUG]       org.apache.avro:avro:jar:1.9.1:compile (applying version: 1.9.2)
[DEBUG]       com.fasterxml.jackson.core:jackson-core:jar:2.9.9:compile (applying version: 2.10.0)
[DEBUG]       com.fasterxml.jackson.core:jackson-databind:jar:2.9.9.3:compile (applying version: 2.10.0)
[DEBUG]     com.fasterxml.jackson.module:jackson-module-jsonSchema:jar:2.11.1:compile (selected for compile)
[DEBUG]       com.fasterxml.jackson.core:jackson-annotations:jar:2.11.1:compile (applying version: 2.10.0)
[DEBUG]       com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile (selected for compile)
[DEBUG]       com.fasterxml.jackson.core:jackson-core:jar:2.11.1:compile (applying version: 2.10.0)
[DEBUG]       com.fasterxml.jackson.core:jackson-databind:jar:2.11.1:compile (applying version: 2.10.0)
[DEBUG]       javax.validation:validation-api:jar:1.1.0.Final:compile (applying version: 2.0.1.Final)
[DEBUG]       javax.validation:validation-api:jar:2.0.1.Final:compile (selected for compile)
[DEBUG]     net.jcip:jcip-annotations:jar:1.0:compile (selected for compile)
[DEBUG]   org.apache.pulsar:pulsar-client-admin-original:jar:2.7.2:compile (selected for compile)
[DEBUG]     org.glassfish.jersey.core:jersey-client:jar:2.31:compile (applying version: 2.35)
[DEBUG]     org.glassfish.jersey.core:jersey-client:jar:2.35:compile (selected for compile)
[DEBUG]       jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile (selected for compile)
[DEBUG]       org.glassfish.jersey.core:jersey-common:jar:2.35:compile (selected for compile)
[DEBUG]         jakarta.annotation:jakarta.annotation-api:jar:1.3.5:compile (selected for compile)
[DEBUG]         org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile (selected for compile)
[DEBUG]         org.glassfish.hk2:osgi-resource-locator:jar:1.0.3:compile (selected for compile)
[DEBUG]       org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile (selected for compile)
[DEBUG]     org.glassfish.jersey.media:jersey-media-json-jackson:jar:2.31:compile (applying version: 2.35)
[DEBUG]     org.glassfish.jersey.media:jersey-media-json-jackson:jar:2.35:compile (selected for compile)
[DEBUG]       org.glassfish.jersey.ext:jersey-entity-filtering:jar:2.35:compile (selected for compile)
[DEBUG]       com.fasterxml.jackson.core:jackson-annotations:jar:2.12.2:compile (applying version: 2.10.0)
[DEBUG]       com.fasterxml.jackson.core:jackson-databind:jar:2.12.2:compile (applying version: 2.10.0)
[DEBUG]       com.fasterxml.jackson.module:jackson-module-jaxb-annotations:jar:2.12.2:compile (applying version: 2.10.0)
[DEBUG]       com.fasterxml.jackson.module:jackson-module-jaxb-annotations:jar:2.10.0:compile (selected for compile)
[DEBUG]         jakarta.xml.bind:jakarta.xml.bind-api:jar:2.3.2:compile (selected for compile)
[DEBUG]           jakarta.activation:jakarta.activation-api:jar:1.2.1:compile (selected for compile)
[DEBUG]         jakarta.activation:jakarta.activation-api:jar:1.2.1:compile (selected for compile)
[DEBUG]     org.glassfish.jersey.media:jersey-media-multipart:jar:2.31:compile (applying version: 2.35)
[DEBUG]     org.glassfish.jersey.media:jersey-media-multipart:jar:2.35:compile (selected for compile)
[DEBUG]       org.jvnet.mimepull:mimepull:jar:1.9.13:compile (selected for compile)
[DEBUG]     com.fasterxml.jackson.jaxrs:jackson-jaxrs-json-provider:jar:2.11.1:compile (applying version: 2.10.0)
[DEBUG]     com.fasterxml.jackson.jaxrs:jackson-jaxrs-json-provider:jar:2.10.0:compile (selected for compile)
[DEBUG]       com.fasterxml.jackson.jaxrs:jackson-jaxrs-base:jar:2.10.0:compile (selected for compile)
[DEBUG]     org.glassfish.jersey.inject:jersey-hk2:jar:2.31:compile (applying version: 2.35)
[DEBUG]     org.glassfish.jersey.inject:jersey-hk2:jar:2.35:compile (selected for compile)
[DEBUG]       org.glassfish.hk2:hk2-locator:jar:2.6.1:compile (selected for compile)
[DEBUG]         org.glassfish.hk2.external:aopalliance-repackaged:jar:2.6.1:compile (selected for compile)
[DEBUG]         org.glassfish.hk2:hk2-api:jar:2.6.1:compile (selected for compile)
[DEBUG]           org.glassfish.hk2:hk2-utils:jar:2.6.1:compile (selected for compile)
[DEBUG]         org.glassfish.hk2:hk2-utils:jar:2.6.1:compile (selected for compile)
[DEBUG]       org.javassist:javassist:jar:3.25.0-GA:compile (applying version: 3.19.0-GA)
[DEBUG]       org.javassist:javassist:jar:3.19.0-GA:compile (selected for compile)
[DEBUG]     javax.xml.bind:jaxb-api:jar:2.3.1:compile (applying version: 2.3.0)
[DEBUG]     javax.xml.bind:jaxb-api:jar:2.3.0:compile (selected for compile)
[DEBUG]     com.sun.activation:javax.activation:jar:1.2.0:runtime (selected for runtime)
[DEBUG]     org.slf4j:jul-to-slf4j:jar:1.7.25:compile (selected for compile)
[DEBUG]     com.google.guava:guava:jar:30.1-jre:compile (applying version: 20.0)
[DEBUG]     com.google.guava:guava:jar:20.0:compile (selected for compile)
[DEBUG]     com.google.code.gson:gson:jar:2.8.6:compile (applying version: 2.2.4)
[DEBUG]   javax.servlet:javax.servlet-api:jar:3.1.0:compile (selected for compile)
[DEBUG]   javax.ws.rs:javax.ws.rs-api:jar:2.1:compile (selected for compile)
[DEBUG]   org.glassfish.jersey.containers:jersey-container-grizzly2-http:jar:2.35:compile (selected for compile)
[DEBUG]     org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile (selected for compile)
[DEBUG]     org.glassfish.grizzly:grizzly-http-server:jar:2.4.4:compile (selected for compile)
[DEBUG]       org.glassfish.grizzly:grizzly-http:jar:2.4.4:compile (selected for compile)
[DEBUG]         org.glassfish.grizzly:grizzly-framework:jar:2.4.4:compile (selected for compile)
[DEBUG]     org.glassfish.jersey.core:jersey-common:jar:2.35:compile (selected for compile)
[DEBUG]       jakarta.annotation:jakarta.annotation-api:jar:1.3.5:compile (selected for compile)
[DEBUG]       org.glassfish.hk2:osgi-resource-locator:jar:1.0.3:compile (selected for compile)
[DEBUG]     org.glassfish.jersey.core:jersey-server:jar:2.35:compile (selected for compile)
[DEBUG]       jakarta.validation:jakarta.validation-api:jar:2.0.2:compile (selected for compile)
[DEBUG]     jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile (selected for compile)
[DEBUG]   org.glassfish.jersey.core:jersey-server:jar:2.35:compile (selected for compile)
[DEBUG]     jakarta.annotation:jakarta.annotation-api:jar:1.3.5:compile (selected for compile)
[DEBUG]     jakarta.validation:jakarta.validation-api:jar:2.0.2:compile (selected for compile)
[DEBUG]   org.glassfish.jersey.containers:jersey-container-servlet-core:jar:2.35:compile (selected for compile)
[DEBUG]   io.netty:netty-resolver:jar:4.1.74.Final:compile (selected for compile)
[DEBUG]     io.netty:netty-common:jar:4.1.74.Final:compile (selected for compile)
[DEBUG]   io.prometheus:simpleclient_common:jar:0.8.1:compile (selected for compile)
[DEBUG]     io.prometheus:simpleclient:jar:0.8.1:compile (selected for compile)
[DEBUG]   com.google.api.grpc:proto-google-common-protos:jar:1.12.0:compile (selected for compile)
[DEBUG]     com.google.protobuf:protobuf-java:jar:3.5.1:compile (applying version: 3.19.2)
[DEBUG]     com.google.protobuf:protobuf-java:jar:3.19.2:compile (selected for compile)
[DEBUG]   io.grpc:grpc-context:jar:1.14.0:compile (selected for compile)
[DEBUG]   commons-codec:commons-codec:jar:1.11:compile (selected for compile)
[DEBUG]   com.google.errorprone:error_prone_annotations:jar:2.3.4:compile (selected for compile)
[DEBUG]   io.prometheus:simpleclient:jar:0.8.1:compile (selected for compile)
[DEBUG]   org.eclipse.jetty:jetty-servlet:jar:9.4.45.v20220203:compile (selected for compile)
[DEBUG]     org.eclipse.jetty:jetty-security:jar:9.4.45.v20220203:compile (selected for compile)
[DEBUG]     org.eclipse.jetty:jetty-util-ajax:jar:9.4.45.v20220203:compile (selected for compile)
[DEBUG]   com.squareup.okio:okio:jar:1.6.0:compile (selected for compile)
[DEBUG]   io.prometheus:simpleclient_hotspot:jar:0.8.1:compile (selected for compile)
[DEBUG]   io.swagger:swagger-annotations:jar:1.5.21:compile (selected for compile)
[DEBUG]   io.grpc:grpc-protobuf-lite:jar:1.19.0:compile (selected for compile)
[DEBUG]     io.grpc:grpc-core:jar:1.19.0:compile (selected for compile)
[DEBUG]       com.google.code.gson:gson:jar:2.7:compile (applying version: 2.2.4)
[DEBUG]       com.google.code.findbugs:jsr305:jar:3.0.2:compile (applying version: 3.0.0)
[DEBUG]       com.google.code.findbugs:jsr305:jar:3.0.0:compile (selected for compile)
[DEBUG]       org.codehaus.mojo:animal-sniffer-annotations:jar:1.17:compile (selected for compile)
[DEBUG]       com.google.guava:guava:jar:26.0-android:compile (applying version: 20.0)
[DEBUG]       io.opencensus:opencensus-api:jar:0.19.2:compile (selected for compile)
[DEBUG]       io.opencensus:opencensus-contrib-grpc-metrics:jar:0.19.2:compile (selected for compile)
[DEBUG]     com.google.protobuf:protobuf-lite:jar:3.0.1:compile (selected for compile)
[DEBUG]     com.google.guava:guava:jar:26.0-android:compile (applying version: 20.0)
[DEBUG]   org.apache.commons:commons-collections4:jar:4.1:compile (selected for compile)
[DEBUG]   javax.annotation:javax.annotation-api:jar:1.2:compile (selected for compile)
[DEBUG]   org.codehaus.mojo:animal-sniffer-annotations:jar:1.17:compile (selected for compile)
[DEBUG]   com.github.ben-manes.caffeine:caffeine:jar:2.6.2:compile (selected for compile)
[DEBUG]   io.netty:netty-codec-socks:jar:4.1.74.Final:compile (selected for compile)
[DEBUG]     io.netty:netty-buffer:jar:4.1.74.Final:compile (selected for compile)
[DEBUG]     io.netty:netty-transport:jar:4.1.74.Final:compile (selected for compile)
[DEBUG]     io.netty:netty-codec:jar:4.1.74.Final:compile (selected for compile)
[DEBUG]   org.bouncycastle:bcpkix-jdk15to18:jar:1.68:compile (selected for compile)
[DEBUG]     org.bouncycastle:bcprov-jdk15to18:jar:1.68:compile (selected for compile)
[DEBUG]   org.bouncycastle:bcprov-ext-jdk15to18:jar:1.68:compile (selected for compile)
[DEBUG]   org.bouncycastle:bcprov-jdk15to18:jar:1.68:compile (selected for compile)
[DEBUG]   org.apache.pinot:pinot-spi:jar:0.11.0-SNAPSHOT:compile (selected for compile)
[DEBUG]     commons-configuration:commons-configuration:jar:1.10:compile (selected for compile)
[DEBUG]     commons-io:commons-io:jar:2.11.0:compile (selected for compile)
[DEBUG]     commons-lang:commons-lang:jar:2.6:compile (selected for compile)
[DEBUG]     commons-logging:commons-logging:jar:1.2:compile (selected for compile)
[DEBUG]     commons-collections:commons-collections:jar:3.2.2:compile (selected for compile)
[DEBUG]     com.google.code.findbugs:jsr305:jar:3.0.0:compile (selected for compile)
[DEBUG]     org.apache.logging.log4j:log4j-slf4j-impl:jar:2.17.1:compile (selected for compile)
[DEBUG]       org.apache.logging.log4j:log4j-api:jar:2.17.1:compile (selected for compile)
[DEBUG]       org.apache.logging.log4j:log4j-core:jar:2.17.1:runtime (selected for runtime)
[DEBUG]     com.lmax:disruptor:jar:3.3.4:compile (selected for compile)
[DEBUG]     org.apache.logging.log4j:log4j-1.2-api:jar:2.17.1:compile (selected for compile)
[DEBUG]     joda-time:joda-time:jar:2.10.5:compile (selected for compile)
[DEBUG]     com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile (selected for compile)
[DEBUG]     org.yaml:snakeyaml:jar:1.30:compile (selected for compile)
[DEBUG]     com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile (selected for compile)
[DEBUG]     org.codehaus.groovy:groovy-all:jar:2.4.21:compile (selected for compile)
[DEBUG]     org.reflections:reflections:jar:0.9.9:compile (selected for compile)
[DEBUG]       com.google.guava:guava:jar:15.0:compile (applying version: 20.0)
[DEBUG]       org.javassist:javassist:jar:3.18.2-GA:compile (applying version: 3.19.0-GA)
[DEBUG]       com.google.code.findbugs:annotations:jar:2.0.1:compile (selected for compile)
[DEBUG]   org.testng:testng:jar:6.11:test (selected for test)
[DEBUG]     com.beust:jcommander:jar:1.64:test (selected for test)
[DEBUG]     org.yaml:snakeyaml:jar:1.17:test (applying version: 1.30)
[DEBUG] Building project for net.jcip:jcip-annotations:jar:1.0:compile
[DEBUG] Adding project with groupId [net.jcip]
[DEBUG] Building project for org.jvnet.mimepull:mimepull:jar:1.9.13:compile
[DEBUG] Adding project with groupId [org.jvnet.mimepull]
[DEBUG] Building project for org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG] Adding project with groupId [org.glassfish.hk2.external]
[DEBUG] Building project for org.glassfish.hk2:hk2-locator:jar:2.6.1:compile
[DEBUG] Adding project with groupId [org.glassfish.hk2]
[DEBUG] Building project for io.netty:netty-codec:jar:4.1.74.Final:compile
[DEBUG] Adding project with groupId [io.netty]
[DEBUG] Building project for org.glassfish.hk2:hk2-utils:jar:2.6.1:compile
[DEBUG] Adding project with groupId [org.glassfish.hk2]
[DEBUG] Building project for org.glassfish.grizzly:grizzly-http:jar:2.4.4:compile
[DEBUG] Adding project with groupId [org.glassfish.grizzly]
[DEBUG] Building project for org.glassfish.jersey.media:jersey-media-json-jackson:jar:2.35:compile
[DEBUG] Adding project with groupId [org.glassfish.jersey.media]
[DEBUG] Building project for com.squareup.okio:okio:jar:1.6.0:compile
[DEBUG] Adding project with groupId [com.squareup.okio]
[DEBUG] Building project for com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile
[DEBUG] Adding project with groupId [com.fasterxml.jackson.core]
[DEBUG] Building project for io.grpc:grpc-context:jar:1.14.0:compile
[DEBUG] Adding project with groupId [io.grpc]
[DEBUG] Building project for org.bouncycastle:bcpkix-jdk15to18:jar:1.68:compile
[DEBUG] Adding project with groupId [org.bouncycastle]
[DEBUG] Building project for io.netty:netty-resolver:jar:4.1.74.Final:compile
[DEBUG] Adding project with groupId [io.netty]
[DEBUG] Building project for com.google.code.findbugs:jsr305:jar:3.0.0:compile
[DEBUG] Adding project with groupId [com.google.code.findbugs]
[DEBUG] Building project for org.codehaus.mojo:animal-sniffer-annotations:jar:1.17:compile
[DEBUG] Adding project with groupId [org.codehaus.mojo]
[DEBUG] Building project for com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile
[DEBUG] Adding project with groupId [com.fasterxml.jackson.core]
[DEBUG] Building project for io.netty:netty-codec-haproxy:jar:4.1.74.Final:compile
[DEBUG] Adding project with groupId [io.netty]
[DEBUG] Building project for jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile
[DEBUG] Adding project with groupId [jakarta.ws.rs]
[DEBUG] Building project for org.apache.pulsar:bouncy-castle-bc:jar:pkg:2.7.2:compile
[DEBUG] Adding project with groupId [org.apache.pulsar]
[DEBUG] Building project for org.glassfish.hk2.external:aopalliance-repackaged:jar:2.6.1:compile
[DEBUG] Adding project with groupId [org.glassfish.hk2.external]
[DEBUG] Building project for javax.xml.bind:jaxb-api:jar:2.3.0:compile
[DEBUG] Adding project with groupId [javax.xml.bind]
[DEBUG] Building project for io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG] Adding project with groupId [io.netty]
[DEBUG] Building project for org.glassfish.jersey.core:jersey-server:jar:2.35:compile
[DEBUG] Adding project with groupId [org.glassfish.jersey.core]
[DEBUG] Building project for com.fasterxml.jackson.module:jackson-module-jaxb-annotations:jar:2.10.0:compile
[DEBUG] Adding project with groupId [com.fasterxml.jackson.module]
[DEBUG] Building project for org.apache.commons:commons-lang3:jar:3.5:compile
[DEBUG] Adding project with groupId [org.apache.commons]
[DEBUG] Building project for com.google.guava:guava:jar:20.0:compile
[DEBUG] Adding project with groupId [com.google.guava]
[DEBUG] Building project for org.glassfish.jersey.containers:jersey-container-grizzly2-http:jar:2.35:compile
[DEBUG] Adding project with groupId [org.glassfish.jersey.containers]
[DEBUG] Building project for org.apache.logging.log4j:log4j-core:jar:2.17.1:runtime
[DEBUG] Adding project with groupId [org.apache.logging.log4j]
[DEBUG] Building project for commons-logging:commons-logging:jar:1.2:compile
[DEBUG] Adding project with groupId [commons-logging]
[DEBUG] Building project for io.netty:netty-codec-http:jar:4.1.74.Final:compile
[DEBUG] Adding project with groupId [io.netty]
[DEBUG] Building project for org.glassfish.jersey.inject:jersey-hk2:jar:2.35:compile
[DEBUG] Adding project with groupId [org.glassfish.jersey.inject]
[DEBUG] Building project for org.bouncycastle:bcprov-jdk15to18:jar:1.68:compile
[DEBUG] Adding project with groupId [org.bouncycastle]
[DEBUG] Building project for org.glassfish.grizzly:grizzly-http-server:jar:2.4.4:compile
[DEBUG] Adding project with groupId [org.glassfish.grizzly]
[DEBUG] Building project for io.netty:netty-tcnative-classes:jar:2.0.48.Final:compile
[DEBUG] Adding project with groupId [io.netty]
[DEBUG] Building project for io.netty:netty-codec-dns:jar:4.1.74.Final:compile
[DEBUG] Adding project with groupId [io.netty]
[DEBUG] Building project for commons-lang:commons-lang:jar:2.6:compile
[DEBUG] Adding project with groupId [commons-lang]
[DEBUG] Building project for commons-io:commons-io:jar:2.11.0:compile
[DEBUG] Adding project with groupId [commons-io]
[DEBUG] Building project for joda-time:joda-time:jar:2.10.5:compile
[DEBUG] Adding project with groupId [joda-time]
[DEBUG] Building project for com.yahoo.datasketches:sketches-core:jar:0.8.3:compile
[DEBUG] Adding project with groupId [com.yahoo.datasketches]
[DEBUG] Building project for io.netty:netty-codec-socks:jar:4.1.74.Final:compile
[DEBUG] Adding project with groupId [io.netty]
[DEBUG] Building project for org.apache.commons:commons-collections4:jar:4.1:compile
[DEBUG] Adding project with groupId [org.apache.commons]
[DEBUG] Building project for io.grpc:grpc-protobuf-lite:jar:1.19.0:compile
[DEBUG] Adding project with groupId [io.grpc]
[DEBUG] Building project for com.google.protobuf:protobuf-java:jar:3.19.2:compile
[DEBUG] Adding project with groupId [com.google.protobuf]
[DEBUG] Building project for com.google.protobuf:protobuf-java-util:jar:3.11.4:compile
[DEBUG] Adding project with groupId [com.google.protobuf]
[DEBUG] Building project for org.eclipse.jetty:jetty-servlet:jar:9.4.45.v20220203:compile
[DEBUG] Adding project with groupId [org.eclipse.jetty]
[DEBUG] Building project for javax.servlet:javax.servlet-api:jar:3.1.0:compile
[DEBUG] Adding project with groupId [javax.servlet]
[DEBUG] Building project for jakarta.validation:jakarta.validation-api:jar:2.0.2:compile
[DEBUG] Adding project with groupId [jakarta.validation]
[DEBUG] Building project for io.netty:netty-tcnative-boringssl-static:jar:2.0.48.Final:compile
[DEBUG] Adding project with groupId [io.netty]
[DEBUG] Building project for org.apache.avro:avro:jar:1.9.2:compile
[DEBUG] Adding project with groupId [org.apache.avro]
[DEBUG] Building project for org.eclipse.jetty:jetty-security:jar:9.4.45.v20220203:compile
[DEBUG] Adding project with groupId [org.eclipse.jetty]
[DEBUG] Building project for org.glassfish.grizzly:grizzly-framework:jar:2.4.4:compile
[DEBUG] Adding project with groupId [org.glassfish.grizzly]
[DEBUG] Building project for io.prometheus:simpleclient_hotspot:jar:0.8.1:compile
[DEBUG] Adding project with groupId [io.prometheus]
[DEBUG] Building project for org.slf4j:jul-to-slf4j:jar:1.7.25:compile
[DEBUG] Adding project with groupId [org.slf4j]
[DEBUG] Building project for org.glassfish.jersey.containers:jersey-container-servlet-core:jar:2.35:compile
[DEBUG] Adding project with groupId [org.glassfish.jersey.containers]
[DEBUG] Building project for io.prometheus:simpleclient_common:jar:0.8.1:compile
[DEBUG] Adding project with groupId [io.prometheus]
[DEBUG] Building project for org.javassist:javassist:jar:3.19.0-GA:compile
[DEBUG] Adding project with groupId [org.javassist]
[DEBUG] Building project for io.prometheus:simpleclient:jar:0.8.1:compile
[DEBUG] Adding project with groupId [io.prometheus]
[DEBUG] Building project for org.apache.logging.log4j:log4j-slf4j-impl:jar:2.17.1:compile
[DEBUG] Adding project with groupId [org.apache.logging.log4j]
[DEBUG] Building project for com.google.code.findbugs:annotations:jar:2.0.1:compile
[DEBUG] Adding project with groupId [com.google.code.findbugs]
[DEBUG] Building project for org.apache.pulsar:pulsar-common:jar:2.7.2:compile
[DEBUG] Adding project with groupId [org.apache.pulsar]
[DEBUG] Building project for com.fasterxml.jackson.module:jackson-module-jsonSchema:jar:2.11.1:compile
[DEBUG] Adding project with groupId [com.fasterxml.jackson.module]
[DEBUG] Building project for com.google.api.grpc:proto-google-common-protos:jar:1.12.0:compile
[DEBUG] Adding project with groupId [com.google.api.grpc]
[DEBUG] Building project for org.eclipse.jetty:jetty-util-ajax:jar:9.4.45.v20220203:compile
[DEBUG] Adding project with groupId [org.eclipse.jetty]
[DEBUG] Building project for io.netty:netty-transport-classes-epoll:jar:4.1.74.Final:compile
[DEBUG] Adding project with groupId [io.netty]
[DEBUG] Building project for io.netty:netty-handler:jar:4.1.74.Final:compile
[DEBUG] Adding project with groupId [io.netty]
[DEBUG] Building project for javax.ws.rs:javax.ws.rs-api:jar:2.1:compile
[DEBUG] Adding project with groupId [javax.ws.rs]
[DEBUG] Building project for org.apache.logging.log4j:log4j-1.2-api:jar:2.17.1:compile
[DEBUG] Adding project with groupId [org.apache.logging.log4j]
[DEBUG] Building project for org.reactivestreams:reactive-streams:jar:1.0.3:compile
[DEBUG] Adding project with groupId [org.reactivestreams]
[DEBUG] Building project for org.eclipse.jetty:jetty-util:jar:9.4.45.v20220203:compile
[DEBUG] Adding project with groupId [org.eclipse.jetty]
[DEBUG] Building project for org.eclipse.jetty:jetty-io:jar:9.4.45.v20220203:compile
[DEBUG] Adding project with groupId [org.eclipse.jetty]
[DEBUG] Building project for javax.validation:validation-api:jar:2.0.1.Final:compile
[DEBUG] Adding project with groupId [javax.validation]
[DEBUG] Building project for org.apache.pulsar:protobuf-shaded:jar:2.1.0-incubating:compile
[DEBUG] Adding project with groupId [org.apache.pulsar]
[DEBUG] Building project for org.glassfish.hk2:hk2-api:jar:2.6.1:compile
[DEBUG] Adding project with groupId [org.glassfish.hk2]
[DEBUG] Building project for io.grpc:grpc-core:jar:1.19.0:compile
[DEBUG] Adding project with groupId [io.grpc]
[DEBUG] Building project for org.eclipse.jetty:jetty-http:jar:9.4.45.v20220203:compile
[DEBUG] Adding project with groupId [org.eclipse.jetty]
[DEBUG] Building project for jakarta.annotation:jakarta.annotation-api:jar:1.3.5:compile
[DEBUG] Adding project with groupId [jakarta.annotation]
[DEBUG] Building project for com.typesafe.netty:netty-reactive-streams:jar:2.0.4:compile
[DEBUG] Adding project with groupId [com.typesafe.netty]
[DEBUG] Building project for org.glassfish.hk2:osgi-resource-locator:jar:1.0.3:compile
[DEBUG] Adding project with groupId [org.glassfish.hk2]
[DEBUG] Building project for org.glassfish.jersey.core:jersey-common:jar:2.35:compile
[DEBUG] Adding project with groupId [org.glassfish.jersey.core]
[DEBUG] Building project for org.apache.bookkeeper:bookkeeper-common-allocator:jar:4.12.0:compile
[DEBUG] Adding project with groupId [org.apache.bookkeeper]
[DEBUG] Building project for com.github.ben-manes.caffeine:caffeine:jar:2.6.2:compile
[DEBUG] Adding project with groupId [com.github.ben-manes.caffeine]
[DEBUG] Building project for org.eclipse.jetty:jetty-server:jar:9.4.45.v20220203:compile
[DEBUG] Adding project with groupId [org.eclipse.jetty]
[DEBUG] Building project for io.swagger:swagger-annotations:jar:1.5.21:compile
[DEBUG] Adding project with groupId [io.swagger]
[DEBUG] Building project for com.sun.activation:javax.activation:jar:1.2.0:runtime
[DEBUG] Adding project with groupId [com.sun.activation]
[DEBUG] Building project for com.fasterxml.jackson.jaxrs:jackson-jaxrs-base:jar:2.10.0:compile
[DEBUG] Adding project with groupId [com.fasterxml.jackson.jaxrs]
[DEBUG] Building project for org.apache.pulsar:pulsar-client-admin-original:jar:2.7.2:compile
[DEBUG] Adding project with groupId [org.apache.pulsar]
[DEBUG] Building project for org.glassfish.jersey.media:jersey-media-multipart:jar:2.35:compile
[DEBUG] Adding project with groupId [org.glassfish.jersey.media]
[DEBUG] Building project for jakarta.activation:jakarta.activation-api:jar:1.2.1:compile
[DEBUG] Adding project with groupId [jakarta.activation]
[DEBUG] Building project for org.glassfish.jersey.core:jersey-client:jar:2.35:compile
[DEBUG] Adding project with groupId [org.glassfish.jersey.core]
[DEBUG] Building project for com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile
[DEBUG] Adding project with groupId [com.fasterxml.jackson.core]
[DEBUG] Building project for io.netty:netty-resolver-dns:jar:4.1.74.Final:compile
[DEBUG] Adding project with groupId [io.netty]
[DEBUG] Building project for com.yahoo.datasketches:memory:jar:0.8.3:compile
[DEBUG] Adding project with groupId [com.yahoo.datasketches]
[DEBUG] Building project for commons-codec:commons-codec:jar:1.11:compile
[DEBUG] Adding project with groupId [commons-codec]
[DEBUG] Building project for io.opencensus:opencensus-api:jar:0.19.2:compile
[DEBUG] Adding project with groupId [io.opencensus]
[DEBUG] Building project for org.apache.pinot:pinot-spi:jar:0.11.0-SNAPSHOT:compile
[DEBUG] Adding project with groupId [org.apache.pinot]
[DEBUG] Building project for com.google.code.gson:gson:jar:2.2.4:compile
[DEBUG] Adding project with groupId [com.google.code.gson]
[DEBUG] Building project for com.sun.activation:jakarta.activation:jar:1.2.2:compile
[DEBUG] Adding project with groupId [com.sun.activation]
[DEBUG] Building project for org.asynchttpclient:async-http-client:jar:2.12.3:compile
[DEBUG] Adding project with groupId [org.asynchttpclient]
[DEBUG] Building project for org.apache.commons:commons-compress:jar:1.21:compile
[DEBUG] Adding project with groupId [org.apache.commons]
[DEBUG] Building project for commons-configuration:commons-configuration:jar:1.10:compile
[DEBUG] Adding project with groupId [commons-configuration]
[DEBUG] Building project for io.netty:netty-transport-native-epoll:jar:linux-x86_64:4.1.74.Final:compile
[DEBUG] Adding project with groupId [io.netty]
[DEBUG] Building project for org.codehaus.groovy:groovy-all:jar:2.4.21:compile
[DEBUG] Adding project with groupId [org.codehaus.groovy]
[DEBUG] Building project for org.apache.pulsar:pulsar-client-original:jar:2.7.2:compile
[DEBUG] Adding project with groupId [org.apache.pulsar]
[DEBUG] Building project for com.google.errorprone:error_prone_annotations:jar:2.3.4:compile
[DEBUG] Adding project with groupId [com.google.errorprone]
[DEBUG] Building project for org.asynchttpclient:async-http-client-netty-utils:jar:2.12.3:compile
[DEBUG] Adding project with groupId [org.asynchttpclient]
[DEBUG] Building project for org.apache.avro:avro-protobuf:jar:1.9.1:compile
[DEBUG] Adding project with groupId [org.apache.avro]
[DEBUG] Building project for jakarta.xml.bind:jakarta.xml.bind-api:jar:2.3.2:compile
[DEBUG] Adding project with groupId [jakarta.xml.bind]
[DEBUG] Building project for org.apache.logging.log4j:log4j-api:jar:2.17.1:compile
[DEBUG] Adding project with groupId [org.apache.logging.log4j]
[DEBUG] Building project for javax.annotation:javax.annotation-api:jar:1.2:compile
[DEBUG] Adding project with groupId [javax.annotation]
[DEBUG] Building project for com.lmax:disruptor:jar:3.3.4:compile
[DEBUG] Adding project with groupId [com.lmax]
[DEBUG] Building project for org.apache.pulsar:pulsar-client-api:jar:2.7.2:compile
[DEBUG] Adding project with groupId [org.apache.pulsar]
[DEBUG] Building project for com.fasterxml.jackson.jaxrs:jackson-jaxrs-json-provider:jar:2.10.0:compile
[DEBUG] Adding project with groupId [com.fasterxml.jackson.jaxrs]
[DEBUG] Building project for io.airlift:aircompressor:jar:0.16:compile
[DEBUG] Adding project with groupId [io.airlift]
[DEBUG] Building project for org.yaml:snakeyaml:jar:1.30:compile
[DEBUG] Adding project with groupId [org.yaml]
[DEBUG] Building project for commons-collections:commons-collections:jar:3.2.2:compile
[DEBUG] Adding project with groupId [commons-collections]
[DEBUG] Building project for org.apache.pulsar:pulsar-transaction-common:jar:2.7.2:compile
[DEBUG] Adding project with groupId [org.apache.pulsar]
[DEBUG] Building project for org.slf4j:slf4j-api:jar:1.7.25:compile
[DEBUG] Adding project with groupId [org.slf4j]
[DEBUG] Building project for com.google.protobuf:protobuf-lite:jar:3.0.1:compile
[DEBUG] Adding project with groupId [com.google.protobuf]
[DEBUG] Building project for com.fasterxml.jackson.dataformat:jackson-dataformat-yaml:jar:2.10.0:compile
[DEBUG] Adding project with groupId [com.fasterxml.jackson.dataformat]
[DEBUG] Building project for org.reflections:reflections:jar:0.9.9:compile
[DEBUG] Adding project with groupId [org.reflections]
[DEBUG] Building project for org.bouncycastle:bcprov-ext-jdk15to18:jar:1.68:compile
[DEBUG] Adding project with groupId [org.bouncycastle]
[DEBUG] Building project for io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG] Adding project with groupId [io.netty]
[DEBUG] Building project for io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG] Adding project with groupId [io.netty]
[DEBUG] Building project for org.glassfish.jersey.ext:jersey-entity-filtering:jar:2.35:compile
[DEBUG] Adding project with groupId [org.glassfish.jersey.ext]
[DEBUG] Building project for org.apache.bookkeeper:circe-checksum:jar:4.12.0:compile
[DEBUG] Adding project with groupId [org.apache.bookkeeper]
[DEBUG] Building project for io.opencensus:opencensus-contrib-grpc-metrics:jar:0.19.2:compile
[DEBUG] Adding project with groupId [io.opencensus]
[DEBUG] Writing /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/maven-shared-archive-resources/META-INF/DEPENDENCIES
[INFO] 
[INFO] --- maven-remote-resources-plugin:1.6.0:process (default) @ pinot-pulsar ---
[DEBUG] Configuring mojo org.apache.maven.plugins:maven-remote-resources-plugin:1.6.0:process from plugin realm ClassRealm[plugin>org.apache.maven.plugins:maven-remote-resources-plugin:1.6.0, parent: jdk.internal.loader.ClassLoaders$AppClassLoader@2c13da15]
[DEBUG] Configuring mojo 'org.apache.maven.plugins:maven-remote-resources-plugin:1.6.0:process' with basic configurator -->
[DEBUG]   (f) appendedResourcesDirectory = /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/src/main/appended-resources
[DEBUG]   (f) attachToMain = true
[DEBUG]   (f) attachToTest = true
[DEBUG]   (f) basedir = /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar
[DEBUG]   (f) encoding = UTF-8
[DEBUG]   (f) excludeTransitive = false
[DEBUG]   (f) includeProjectProperties = false
[DEBUG]   (f) includeScope = runtime
[DEBUG]   (f) localRepository =       id: local
      url: file:///Users/.../.m2/repository/
   layout: default
snapshots: [enabled => true, update => always]
 releases: [enabled => true, update => always]
   blocked: false

[DEBUG]   (f) mavenSession = org.apache.maven.execution.MavenSession@53d6e959
[DEBUG]   (f) outputDirectory = /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/maven-shared-archive-resources
[DEBUG]   (f) project = MavenProject: org.apache.pinot:pinot-pulsar:0.11.0-SNAPSHOT @ /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/pom.xml
[DEBUG]   (f) properties = {projectName=Apache Pinot}
[DEBUG]   (f) remoteArtifactRepositories = [      id: apache.snapshots
      url: https://repository.apache.org/snapshots
   layout: default
snapshots: [enabled => true, update => daily]
 releases: [enabled => false, update => daily]
   blocked: false
,       id: central
      url: https://repo.maven.apache.org/maven2
   layout: default
snapshots: [enabled => false, update => daily]
 releases: [enabled => true, update => daily]
   blocked: false
]
[DEBUG]   (f) resourceBundles = [org.apache:apache-jar-resource-bundle:1.4]
[DEBUG]   (f) resources = [Resource {targetPath: null, filtering: false, FileSet {directory: /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/src/main/resources, PatternSet [includes: {}, excludes: {}]}}, Resource {targetPath: null, filtering: false, FileSet {directory: /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/maven-shared-archive-resources, PatternSet [includes: {}, excludes: {}]}}]
[DEBUG]   (f) runOnlyAtExecutionRoot = false
[DEBUG]   (f) skip = false
[DEBUG]   (f) useDefaultFilterDelimiters = true
[DEBUG]   (f) velocityFilterInMemoryThreshold = 5242880
[DEBUG] -- end configuration --
[INFO] Preparing remote bundle org.apache:apache-jar-resource-bundle:1.4
[DEBUG] Supplemental data models won't be loaded.  No models specified.
[DEBUG] Initializing Velocity, Calling init()...
[DEBUG] *******************************************************************
[DEBUG] Starting Apache Velocity v1.7 (compiled: 2010-11-19 12:14:37)
[DEBUG] RuntimeInstance initializing.
[DEBUG] Default Properties File: org/apache/velocity/runtime/defaults/velocity.properties
[DEBUG] Default ResourceManager initializing. (class org.apache.velocity.runtime.resource.ResourceManagerImpl)
[DEBUG] ResourceLoader instantiated: org.apache.velocity.runtime.resource.loader.ClasspathResourceLoader
[DEBUG] ResourceCache: initialized (class org.apache.velocity.runtime.resource.ResourceCacheImpl) with class java.util.Collections$SynchronizedMap cache map.
[DEBUG] Default ResourceManager initialization complete.
[DEBUG] Loaded System Directive: org.apache.velocity.runtime.directive.Stop
[DEBUG] Loaded System Directive: org.apache.velocity.runtime.directive.Define
[DEBUG] Loaded System Directive: org.apache.velocity.runtime.directive.Break
[DEBUG] Loaded System Directive: org.apache.velocity.runtime.directive.Evaluate
[DEBUG] Loaded System Directive: org.apache.velocity.runtime.directive.Literal
[DEBUG] Loaded System Directive: org.apache.velocity.runtime.directive.Macro
[DEBUG] Loaded System Directive: org.apache.velocity.runtime.directive.Parse
[DEBUG] Loaded System Directive: org.apache.velocity.runtime.directive.Include
[DEBUG] Loaded System Directive: org.apache.velocity.runtime.directive.Foreach
[DEBUG] Velocimacro : initialization starting.
[DEBUG] Velocimacro : "velocimacro.library" is not set.  Trying default library: VM_global_library.vm
[DEBUG] Velocimacro : Default library not found.
[DEBUG] Velocimacro : allowInline = true : VMs can be defined inline in templates
[DEBUG] Velocimacro : allowInlineToOverride = false : VMs defined inline may NOT replace previous VM definitions
[DEBUG] Velocimacro : allowInlineLocal = false : VMs defined inline will be global in scope if allowed.
[DEBUG] Velocimacro : autoload off : VM system will not automatically reload global library macros
[DEBUG] Velocimacro : Velocimacro : initialization complete.
[DEBUG] RuntimeInstance successfully initialized.
[DEBUG] processResourceBundle on bundle#1 jar:file:/Users/.../.m2/repository/org/apache/apache-jar-resource-bundle/1.4/apache-jar-resource-bundle-1.4.jar!/META-INF/maven/remote-resources.xml
[DEBUG] bundle#1 resource#1 META-INF/NOTICE.vm
[DEBUG] bundle#1 resource#2 META-INF/LICENSE.vm
[DEBUG] bundle#1 resource#3 META-INF/DEPENDENCIES.vm
[INFO] Copying 3 resources from 1 bundle.
[DEBUG] File /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/maven-shared-archive-resources/META-INF/NOTICE contents differs
[DEBUG] Writing /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/maven-shared-archive-resources/META-INF/NOTICE
[DEBUG] File /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/maven-shared-archive-resources/META-INF/LICENSE contents does not differ
[DEBUG] File /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/maven-shared-archive-resources/META-INF/LICENSE is up to date
[DEBUG] org.apache.pinot:pinot-pulsar:jar:0.11.0-SNAPSHOT (selected for null)
[DEBUG]   org.eclipse.jetty:jetty-server:jar:9.4.45.v20220203:compile (selected for compile)
[DEBUG]     org.eclipse.jetty:jetty-http:jar:9.4.45.v20220203:compile (selected for compile)
[DEBUG]       org.eclipse.jetty:jetty-util:jar:9.4.45.v20220203:compile (selected for compile)
[DEBUG]       org.eclipse.jetty:jetty-io:jar:9.4.45.v20220203:compile (selected for compile)
[DEBUG]     org.eclipse.jetty:jetty-io:jar:9.4.45.v20220203:compile (selected for compile)
[DEBUG]   org.testcontainers:pulsar:jar:1.17.1:test (selected for test)
[DEBUG]     org.testcontainers:testcontainers:jar:1.17.1:test (selected for test)
[DEBUG]       junit:junit:jar:4.13.2:test (selected for test)
[DEBUG]         org.hamcrest:hamcrest-core:jar:1.3:test (selected for test)
[DEBUG]       org.slf4j:slf4j-api:jar:1.7.35:test (applying version: 1.7.25)
[DEBUG]       org.slf4j:slf4j-api:jar:1.7.25:test (selected for test)
[DEBUG]       org.apache.commons:commons-compress:jar:1.21:test (selected for test)
[DEBUG]       org.rnorth.duct-tape:duct-tape:jar:1.0.8:test (selected for test)
[DEBUG]         org.jetbrains:annotations:jar:17.0.0:test (selected for test)
[DEBUG]       com.github.docker-java:docker-java-api:jar:3.2.13:test (selected for test)
[DEBUG]         com.fasterxml.jackson.core:jackson-annotations:jar:2.10.3:test (applying version: 2.10.0)
[DEBUG]         com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:test (selected for test)
[DEBUG]         org.slf4j:slf4j-api:jar:1.7.30:test (applying version: 1.7.25)
[DEBUG]       com.github.docker-java:docker-java-transport-zerodep:jar:3.2.13:test (selected for test)
[DEBUG]         com.github.docker-java:docker-java-transport:jar:3.2.13:test (selected for test)
[DEBUG]         net.java.dev.jna:jna:jar:5.8.0:test (selected for test)
[DEBUG]   org.apache.pulsar:pulsar-client-original:jar:2.7.2:compile (selected for compile)
[DEBUG]     org.apache.pulsar:pulsar-client-api:jar:2.7.2:compile (selected for compile)
[DEBUG]     org.apache.pulsar:pulsar-common:jar:2.7.2:compile (selected for compile)
[DEBUG]       io.swagger:swagger-annotations:jar:1.5.21:compile (selected for compile)
[DEBUG]       org.slf4j:slf4j-api:jar:1.7.25:test (setting artifactScope to: compile)
[DEBUG]       org.slf4j:slf4j-api:jar:1.7.25:compile (selected for compile)
[DEBUG]       com.fasterxml.jackson.core:jackson-databind:jar:2.11.1:compile (applying version: 2.10.0)
[DEBUG]       com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile (selected for compile)
[DEBUG]         com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:test (setting artifactScope to: compile)
[DEBUG]         com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile (selected for compile)
[DEBUG]         com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile (selected for compile)
[DEBUG]       org.apache.pulsar:protobuf-shaded:jar:2.1.0-incubating:compile (selected for compile)
[DEBUG]       com.google.guava:guava:jar:30.1-jre:compile (applying version: 20.0)
[DEBUG]       com.google.guava:guava:jar:20.0:compile (selected for compile)
[DEBUG]       io.netty:netty-handler:jar:4.1.60.Final:compile (applying version: 4.1.74.Final)
[DEBUG]       io.netty:netty-handler:jar:4.1.74.Final:compile (selected for compile)
[DEBUG]         io.netty:netty-common:jar:4.1.74.Final:compile (selected for compile)
[DEBUG]         io.netty:netty-buffer:jar:4.1.74.Final:compile (selected for compile)
[DEBUG]         io.netty:netty-transport:jar:4.1.74.Final:compile (selected for compile)
[DEBUG]         io.netty:netty-codec:jar:4.1.74.Final:compile (selected for compile)
[DEBUG]         io.netty:netty-tcnative-classes:jar:2.0.48.Final:compile (selected for compile)
[DEBUG]       io.netty:netty-transport-native-epoll:jar:linux-x86_64:4.1.60.Final:compile (applying version: 4.1.74.Final)
[DEBUG]       io.netty:netty-transport-native-epoll:jar:linux-x86_64:4.1.74.Final:compile (selected for compile)
[DEBUG]         io.netty:netty-transport-classes-epoll:jar:4.1.74.Final:compile (selected for compile)
[DEBUG]       org.apache.bookkeeper:bookkeeper-common-allocator:jar:4.12.0:compile (selected for compile)
[DEBUG]         io.netty:netty-buffer:jar:4.1.50.Final:compile (applying version: 4.1.74.Final)
[DEBUG]       io.airlift:aircompressor:jar:0.16:compile (selected for compile)
[DEBUG]       org.apache.bookkeeper:circe-checksum:jar:4.12.0:compile (selected for compile)
[DEBUG]         com.google.guava:guava:jar:30.0-jre:compile (applying version: 20.0)
[DEBUG]         commons-configuration:commons-configuration:jar:1.10:compile (selected for compile)
[DEBUG]           commons-lang:commons-lang:jar:2.6:compile (selected for compile)
[DEBUG]           commons-logging:commons-logging:jar:1.1.1:compile (applying version: 1.2)
[DEBUG]           commons-logging:commons-logging:jar:1.2:compile (selected for compile)
[DEBUG]       io.netty:netty-tcnative-boringssl-static:jar:2.0.36.Final:compile (applying version: 2.0.48.Final)
[DEBUG]       io.netty:netty-tcnative-boringssl-static:jar:2.0.48.Final:compile (selected for compile)
[DEBUG]       io.netty:netty-codec-haproxy:jar:4.1.60.Final:compile (applying version: 4.1.74.Final)
[DEBUG]       io.netty:netty-codec-haproxy:jar:4.1.74.Final:compile (selected for compile)
[DEBUG]       org.apache.commons:commons-lang3:jar:3.6:compile (applying version: 3.5)
[DEBUG]       org.apache.commons:commons-lang3:jar:3.5:compile (selected for compile)
[DEBUG]       com.fasterxml.jackson.dataformat:jackson-dataformat-yaml:jar:2.11.1:compile (applying version: 2.10.0)
[DEBUG]       com.fasterxml.jackson.dataformat:jackson-dataformat-yaml:jar:2.10.0:compile (selected for compile)
[DEBUG]         org.yaml:snakeyaml:jar:1.24:compile (applying version: 1.30)
[DEBUG]         org.yaml:snakeyaml:jar:1.30:compile (selected for compile)
[DEBUG]       commons-io:commons-io:jar:2.8.0:compile (applying version: 2.11.0)
[DEBUG]       commons-io:commons-io:jar:2.11.0:compile (selected for compile)
[DEBUG]     org.apache.pulsar:pulsar-transaction-common:jar:2.7.2:compile (selected for compile)
[DEBUG]       com.google.protobuf:protobuf-java:jar:3.11.4:compile (applying version: 3.19.2)
[DEBUG]       com.google.protobuf:protobuf-java:jar:3.19.2:compile (selected for compile)
[DEBUG]       com.google.protobuf:protobuf-java-util:jar:3.11.4:compile (selected for compile)
[DEBUG]         com.google.protobuf:protobuf-java:jar:3.11.4:compile (applying version: 3.19.2)
[DEBUG]         com.google.guava:guava:jar:28.1-android:compile (applying version: 20.0)
[DEBUG]         com.google.errorprone:error_prone_annotations:jar:2.3.4:compile (selected for compile)
[DEBUG]         com.google.code.gson:gson:jar:2.8.6:compile (applying version: 2.2.4)
[DEBUG]         com.google.code.gson:gson:jar:2.2.4:compile (selected for compile)
[DEBUG]     org.apache.pulsar:bouncy-castle-bc:jar:pkg:2.7.2:compile (selected for compile)
[DEBUG]     io.netty:netty-codec-http:jar:4.1.60.Final:compile (applying version: 4.1.74.Final)
[DEBUG]     io.netty:netty-codec-http:jar:4.1.74.Final:compile (selected for compile)
[DEBUG]       io.netty:netty-common:jar:4.1.74.Final:compile (selected for compile)
[DEBUG]       io.netty:netty-buffer:jar:4.1.74.Final:compile (selected for compile)
[DEBUG]       io.netty:netty-transport:jar:4.1.74.Final:compile (selected for compile)
[DEBUG]       io.netty:netty-codec:jar:4.1.74.Final:compile (selected for compile)
[DEBUG]     io.netty:netty-resolver-dns:jar:4.1.60.Final:compile (applying version: 4.1.74.Final)
[DEBUG]     io.netty:netty-resolver-dns:jar:4.1.74.Final:compile (selected for compile)
[DEBUG]       io.netty:netty-codec-dns:jar:4.1.74.Final:compile (selected for compile)
[DEBUG]     org.apache.commons:commons-lang3:jar:3.6:compile (applying version: 3.5)
[DEBUG]     org.apache.commons:commons-lang3:jar:3.5:compile (selected for compile)
[DEBUG]     org.asynchttpclient:async-http-client:jar:2.12.1:compile (applying version: 2.12.3)
[DEBUG]     org.asynchttpclient:async-http-client:jar:2.12.3:compile (selected for compile)
[DEBUG]       org.asynchttpclient:async-http-client-netty-utils:jar:2.12.3:compile (selected for compile)
[DEBUG]         org.slf4j:slf4j-api:jar:1.7.30:compile (applying version: 1.7.25)
[DEBUG]         com.sun.activation:jakarta.activation:jar:1.2.2:compile (selected for compile)
[DEBUG]       org.reactivestreams:reactive-streams:jar:1.0.3:compile (selected for compile)
[DEBUG]       com.typesafe.netty:netty-reactive-streams:jar:2.0.4:compile (selected for compile)
[DEBUG]       org.slf4j:slf4j-api:jar:1.7.30:compile (applying version: 1.7.25)
[DEBUG]       com.sun.activation:jakarta.activation:jar:1.2.2:compile (selected for compile)
[DEBUG]     org.slf4j:slf4j-api:jar:1.7.25:compile (selected for compile)
[DEBUG]     com.yahoo.datasketches:sketches-core:jar:0.8.3:compile (selected for compile)
[DEBUG]       com.yahoo.datasketches:memory:jar:0.8.3:compile (selected for compile)
[DEBUG]     com.google.code.gson:gson:jar:2.8.6:compile (applying version: 2.2.4)
[DEBUG]     com.google.code.gson:gson:jar:2.2.4:compile (selected for compile)
[DEBUG]     org.apache.avro:avro:jar:1.9.1:compile (applying version: 1.9.2)
[DEBUG]     org.apache.avro:avro:jar:1.9.2:compile (selected for compile)
[DEBUG]       com.fasterxml.jackson.core:jackson-core:jar:2.10.2:compile (applying version: 2.10.0)
[DEBUG]       com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile (selected for compile)
[DEBUG]       com.fasterxml.jackson.core:jackson-databind:jar:2.10.2:compile (applying version: 2.10.0)
[DEBUG]       org.apache.commons:commons-compress:jar:1.19:compile (applying version: 1.21)
[DEBUG]       org.apache.commons:commons-compress:jar:1.21:test (setting artifactScope to: compile)
[DEBUG]       org.apache.commons:commons-compress:jar:1.21:compile (selected for compile)
[DEBUG]     org.apache.avro:avro-protobuf:jar:1.9.1:compile (selected for compile)
[DEBUG]       org.apache.avro:avro:jar:1.9.1:compile (applying version: 1.9.2)
[DEBUG]       com.fasterxml.jackson.core:jackson-core:jar:2.9.9:compile (applying version: 2.10.0)
[DEBUG]       com.fasterxml.jackson.core:jackson-databind:jar:2.9.9.3:compile (applying version: 2.10.0)
[DEBUG]     com.fasterxml.jackson.module:jackson-module-jsonSchema:jar:2.11.1:compile (selected for compile)
[DEBUG]       com.fasterxml.jackson.core:jackson-annotations:jar:2.11.1:compile (applying version: 2.10.0)
[DEBUG]       com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile (selected for compile)
[DEBUG]       com.fasterxml.jackson.core:jackson-core:jar:2.11.1:compile (applying version: 2.10.0)
[DEBUG]       com.fasterxml.jackson.core:jackson-databind:jar:2.11.1:compile (applying version: 2.10.0)
[DEBUG]       javax.validation:validation-api:jar:1.1.0.Final:compile (applying version: 2.0.1.Final)
[DEBUG]       javax.validation:validation-api:jar:2.0.1.Final:compile (selected for compile)
[DEBUG]     net.jcip:jcip-annotations:jar:1.0:compile (selected for compile)
[DEBUG]   org.apache.pulsar:pulsar-client-admin-original:jar:2.7.2:compile (selected for compile)
[DEBUG]     org.glassfish.jersey.core:jersey-client:jar:2.31:compile (applying version: 2.35)
[DEBUG]     org.glassfish.jersey.core:jersey-client:jar:2.35:compile (selected for compile)
[DEBUG]       jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile (selected for compile)
[DEBUG]       org.glassfish.jersey.core:jersey-common:jar:2.35:compile (selected for compile)
[DEBUG]         jakarta.annotation:jakarta.annotation-api:jar:1.3.5:compile (selected for compile)
[DEBUG]         org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile (selected for compile)
[DEBUG]         org.glassfish.hk2:osgi-resource-locator:jar:1.0.3:compile (selected for compile)
[DEBUG]       org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile (selected for compile)
[DEBUG]     org.glassfish.jersey.media:jersey-media-json-jackson:jar:2.31:compile (applying version: 2.35)
[DEBUG]     org.glassfish.jersey.media:jersey-media-json-jackson:jar:2.35:compile (selected for compile)
[DEBUG]       org.glassfish.jersey.ext:jersey-entity-filtering:jar:2.35:compile (selected for compile)
[DEBUG]       com.fasterxml.jackson.core:jackson-annotations:jar:2.12.2:compile (applying version: 2.10.0)
[DEBUG]       com.fasterxml.jackson.core:jackson-databind:jar:2.12.2:compile (applying version: 2.10.0)
[DEBUG]       com.fasterxml.jackson.module:jackson-module-jaxb-annotations:jar:2.12.2:compile (applying version: 2.10.0)
[DEBUG]       com.fasterxml.jackson.module:jackson-module-jaxb-annotations:jar:2.10.0:compile (selected for compile)
[DEBUG]         jakarta.xml.bind:jakarta.xml.bind-api:jar:2.3.2:compile (selected for compile)
[DEBUG]           jakarta.activation:jakarta.activation-api:jar:1.2.1:compile (selected for compile)
[DEBUG]         jakarta.activation:jakarta.activation-api:jar:1.2.1:compile (selected for compile)
[DEBUG]     org.glassfish.jersey.media:jersey-media-multipart:jar:2.31:compile (applying version: 2.35)
[DEBUG]     org.glassfish.jersey.media:jersey-media-multipart:jar:2.35:compile (selected for compile)
[DEBUG]       org.jvnet.mimepull:mimepull:jar:1.9.13:compile (selected for compile)
[DEBUG]     com.fasterxml.jackson.jaxrs:jackson-jaxrs-json-provider:jar:2.11.1:compile (applying version: 2.10.0)
[DEBUG]     com.fasterxml.jackson.jaxrs:jackson-jaxrs-json-provider:jar:2.10.0:compile (selected for compile)
[DEBUG]       com.fasterxml.jackson.jaxrs:jackson-jaxrs-base:jar:2.10.0:compile (selected for compile)
[DEBUG]     org.glassfish.jersey.inject:jersey-hk2:jar:2.31:compile (applying version: 2.35)
[DEBUG]     org.glassfish.jersey.inject:jersey-hk2:jar:2.35:compile (selected for compile)
[DEBUG]       org.glassfish.hk2:hk2-locator:jar:2.6.1:compile (selected for compile)
[DEBUG]         org.glassfish.hk2.external:aopalliance-repackaged:jar:2.6.1:compile (selected for compile)
[DEBUG]         org.glassfish.hk2:hk2-api:jar:2.6.1:compile (selected for compile)
[DEBUG]           org.glassfish.hk2:hk2-utils:jar:2.6.1:compile (selected for compile)
[DEBUG]         org.glassfish.hk2:hk2-utils:jar:2.6.1:compile (selected for compile)
[DEBUG]       org.javassist:javassist:jar:3.25.0-GA:compile (applying version: 3.19.0-GA)
[DEBUG]       org.javassist:javassist:jar:3.19.0-GA:compile (selected for compile)
[DEBUG]     javax.xml.bind:jaxb-api:jar:2.3.1:compile (applying version: 2.3.0)
[DEBUG]     javax.xml.bind:jaxb-api:jar:2.3.0:compile (selected for compile)
[DEBUG]     com.sun.activation:javax.activation:jar:1.2.0:runtime (selected for runtime)
[DEBUG]     org.slf4j:jul-to-slf4j:jar:1.7.25:compile (selected for compile)
[DEBUG]     com.google.guava:guava:jar:30.1-jre:compile (applying version: 20.0)
[DEBUG]     com.google.guava:guava:jar:20.0:compile (selected for compile)
[DEBUG]     com.google.code.gson:gson:jar:2.8.6:compile (applying version: 2.2.4)
[DEBUG]   javax.servlet:javax.servlet-api:jar:3.1.0:compile (selected for compile)
[DEBUG]   javax.ws.rs:javax.ws.rs-api:jar:2.1:compile (selected for compile)
[DEBUG]   org.glassfish.jersey.containers:jersey-container-grizzly2-http:jar:2.35:compile (selected for compile)
[DEBUG]     org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile (selected for compile)
[DEBUG]     org.glassfish.grizzly:grizzly-http-server:jar:2.4.4:compile (selected for compile)
[DEBUG]       org.glassfish.grizzly:grizzly-http:jar:2.4.4:compile (selected for compile)
[DEBUG]         org.glassfish.grizzly:grizzly-framework:jar:2.4.4:compile (selected for compile)
[DEBUG]     org.glassfish.jersey.core:jersey-common:jar:2.35:compile (selected for compile)
[DEBUG]       jakarta.annotation:jakarta.annotation-api:jar:1.3.5:compile (selected for compile)
[DEBUG]       org.glassfish.hk2:osgi-resource-locator:jar:1.0.3:compile (selected for compile)
[DEBUG]     org.glassfish.jersey.core:jersey-server:jar:2.35:compile (selected for compile)
[DEBUG]       jakarta.validation:jakarta.validation-api:jar:2.0.2:compile (selected for compile)
[DEBUG]     jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile (selected for compile)
[DEBUG]   org.glassfish.jersey.core:jersey-server:jar:2.35:compile (selected for compile)
[DEBUG]     jakarta.annotation:jakarta.annotation-api:jar:1.3.5:compile (selected for compile)
[DEBUG]     jakarta.validation:jakarta.validation-api:jar:2.0.2:compile (selected for compile)
[DEBUG]   org.glassfish.jersey.containers:jersey-container-servlet-core:jar:2.35:compile (selected for compile)
[DEBUG]   io.netty:netty-resolver:jar:4.1.74.Final:compile (selected for compile)
[DEBUG]     io.netty:netty-common:jar:4.1.74.Final:compile (selected for compile)
[DEBUG]   io.prometheus:simpleclient_common:jar:0.8.1:compile (selected for compile)
[DEBUG]     io.prometheus:simpleclient:jar:0.8.1:compile (selected for compile)
[DEBUG]   com.google.api.grpc:proto-google-common-protos:jar:1.12.0:compile (selected for compile)
[DEBUG]     com.google.protobuf:protobuf-java:jar:3.5.1:compile (applying version: 3.19.2)
[DEBUG]     com.google.protobuf:protobuf-java:jar:3.19.2:compile (selected for compile)
[DEBUG]   io.grpc:grpc-context:jar:1.14.0:compile (selected for compile)
[DEBUG]   commons-codec:commons-codec:jar:1.11:compile (selected for compile)
[DEBUG]   com.google.errorprone:error_prone_annotations:jar:2.3.4:compile (selected for compile)
[DEBUG]   io.prometheus:simpleclient:jar:0.8.1:compile (selected for compile)
[DEBUG]   org.eclipse.jetty:jetty-servlet:jar:9.4.45.v20220203:compile (selected for compile)
[DEBUG]     org.eclipse.jetty:jetty-security:jar:9.4.45.v20220203:compile (selected for compile)
[DEBUG]     org.eclipse.jetty:jetty-util-ajax:jar:9.4.45.v20220203:compile (selected for compile)
[DEBUG]   com.squareup.okio:okio:jar:1.6.0:compile (selected for compile)
[DEBUG]   io.prometheus:simpleclient_hotspot:jar:0.8.1:compile (selected for compile)
[DEBUG]   io.swagger:swagger-annotations:jar:1.5.21:compile (selected for compile)
[DEBUG]   io.grpc:grpc-protobuf-lite:jar:1.19.0:compile (selected for compile)
[DEBUG]     io.grpc:grpc-core:jar:1.19.0:compile (selected for compile)
[DEBUG]       com.google.code.gson:gson:jar:2.7:compile (applying version: 2.2.4)
[DEBUG]       com.google.code.findbugs:jsr305:jar:3.0.2:compile (applying version: 3.0.0)
[DEBUG]       com.google.code.findbugs:jsr305:jar:3.0.0:compile (selected for compile)
[DEBUG]       org.codehaus.mojo:animal-sniffer-annotations:jar:1.17:compile (selected for compile)
[DEBUG]       com.google.guava:guava:jar:26.0-android:compile (applying version: 20.0)
[DEBUG]       io.opencensus:opencensus-api:jar:0.19.2:compile (selected for compile)
[DEBUG]       io.opencensus:opencensus-contrib-grpc-metrics:jar:0.19.2:compile (selected for compile)
[DEBUG]     com.google.protobuf:protobuf-lite:jar:3.0.1:compile (selected for compile)
[DEBUG]     com.google.guava:guava:jar:26.0-android:compile (applying version: 20.0)
[DEBUG]   org.apache.commons:commons-collections4:jar:4.1:compile (selected for compile)
[DEBUG]   javax.annotation:javax.annotation-api:jar:1.2:compile (selected for compile)
[DEBUG]   org.codehaus.mojo:animal-sniffer-annotations:jar:1.17:compile (selected for compile)
[DEBUG]   com.github.ben-manes.caffeine:caffeine:jar:2.6.2:compile (selected for compile)
[DEBUG]   io.netty:netty-codec-socks:jar:4.1.74.Final:compile (selected for compile)
[DEBUG]     io.netty:netty-buffer:jar:4.1.74.Final:compile (selected for compile)
[DEBUG]     io.netty:netty-transport:jar:4.1.74.Final:compile (selected for compile)
[DEBUG]     io.netty:netty-codec:jar:4.1.74.Final:compile (selected for compile)
[DEBUG]   org.bouncycastle:bcpkix-jdk15to18:jar:1.68:compile (selected for compile)
[DEBUG]     org.bouncycastle:bcprov-jdk15to18:jar:1.68:compile (selected for compile)
[DEBUG]   org.bouncycastle:bcprov-ext-jdk15to18:jar:1.68:compile (selected for compile)
[DEBUG]   org.bouncycastle:bcprov-jdk15to18:jar:1.68:compile (selected for compile)
[DEBUG]   org.apache.pinot:pinot-spi:jar:0.11.0-SNAPSHOT:compile (selected for compile)
[DEBUG]     commons-configuration:commons-configuration:jar:1.10:compile (selected for compile)
[DEBUG]     commons-io:commons-io:jar:2.11.0:compile (selected for compile)
[DEBUG]     commons-lang:commons-lang:jar:2.6:compile (selected for compile)
[DEBUG]     commons-logging:commons-logging:jar:1.2:compile (selected for compile)
[DEBUG]     commons-collections:commons-collections:jar:3.2.2:compile (selected for compile)
[DEBUG]     com.google.code.findbugs:jsr305:jar:3.0.0:compile (selected for compile)
[DEBUG]     org.apache.logging.log4j:log4j-slf4j-impl:jar:2.17.1:compile (selected for compile)
[DEBUG]       org.apache.logging.log4j:log4j-api:jar:2.17.1:compile (selected for compile)
[DEBUG]       org.apache.logging.log4j:log4j-core:jar:2.17.1:runtime (selected for runtime)
[DEBUG]     com.lmax:disruptor:jar:3.3.4:compile (selected for compile)
[DEBUG]     org.apache.logging.log4j:log4j-1.2-api:jar:2.17.1:compile (selected for compile)
[DEBUG]     joda-time:joda-time:jar:2.10.5:compile (selected for compile)
[DEBUG]     com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile (selected for compile)
[DEBUG]     org.yaml:snakeyaml:jar:1.30:compile (selected for compile)
[DEBUG]     com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile (selected for compile)
[DEBUG]     org.codehaus.groovy:groovy-all:jar:2.4.21:compile (selected for compile)
[DEBUG]     org.reflections:reflections:jar:0.9.9:compile (selected for compile)
[DEBUG]       com.google.guava:guava:jar:15.0:compile (applying version: 20.0)
[DEBUG]       org.javassist:javassist:jar:3.18.2-GA:compile (applying version: 3.19.0-GA)
[DEBUG]       com.google.code.findbugs:annotations:jar:2.0.1:compile (selected for compile)
[DEBUG]   org.testng:testng:jar:6.11:test (selected for test)
[DEBUG]     com.beust:jcommander:jar:1.64:test (selected for test)
[DEBUG]     org.yaml:snakeyaml:jar:1.17:test (applying version: 1.30)
[DEBUG] Building project for net.jcip:jcip-annotations:jar:1.0:compile
[DEBUG] Adding project with groupId [net.jcip]
[DEBUG] Building project for org.jvnet.mimepull:mimepull:jar:1.9.13:compile
[DEBUG] Adding project with groupId [org.jvnet.mimepull]
[DEBUG] Building project for org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[DEBUG] Adding project with groupId [org.glassfish.hk2.external]
[DEBUG] Building project for org.glassfish.hk2:hk2-locator:jar:2.6.1:compile
[DEBUG] Adding project with groupId [org.glassfish.hk2]
[DEBUG] Building project for io.netty:netty-codec:jar:4.1.74.Final:compile
[DEBUG] Adding project with groupId [io.netty]
[DEBUG] Building project for org.glassfish.hk2:hk2-utils:jar:2.6.1:compile
[DEBUG] Adding project with groupId [org.glassfish.hk2]
[DEBUG] Building project for org.glassfish.grizzly:grizzly-http:jar:2.4.4:compile
[DEBUG] Adding project with groupId [org.glassfish.grizzly]
[DEBUG] Building project for org.glassfish.jersey.media:jersey-media-json-jackson:jar:2.35:compile
[DEBUG] Adding project with groupId [org.glassfish.jersey.media]
[DEBUG] Building project for com.squareup.okio:okio:jar:1.6.0:compile
[DEBUG] Adding project with groupId [com.squareup.okio]
[DEBUG] Building project for com.fasterxml.jackson.core:jackson-annotations:jar:2.10.0:compile
[DEBUG] Adding project with groupId [com.fasterxml.jackson.core]
[DEBUG] Building project for io.grpc:grpc-context:jar:1.14.0:compile
[DEBUG] Adding project with groupId [io.grpc]
[DEBUG] Building project for org.bouncycastle:bcpkix-jdk15to18:jar:1.68:compile
[DEBUG] Adding project with groupId [org.bouncycastle]
[DEBUG] Building project for io.netty:netty-resolver:jar:4.1.74.Final:compile
[DEBUG] Adding project with groupId [io.netty]
[DEBUG] Building project for com.google.code.findbugs:jsr305:jar:3.0.0:compile
[DEBUG] Adding project with groupId [com.google.code.findbugs]
[DEBUG] Building project for org.codehaus.mojo:animal-sniffer-annotations:jar:1.17:compile
[DEBUG] Adding project with groupId [org.codehaus.mojo]
[DEBUG] Building project for com.fasterxml.jackson.core:jackson-core:jar:2.10.0:compile
[DEBUG] Adding project with groupId [com.fasterxml.jackson.core]
[DEBUG] Building project for io.netty:netty-codec-haproxy:jar:4.1.74.Final:compile
[DEBUG] Adding project with groupId [io.netty]
[DEBUG] Building project for jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile
[DEBUG] Adding project with groupId [jakarta.ws.rs]
[DEBUG] Building project for org.apache.pulsar:bouncy-castle-bc:jar:pkg:2.7.2:compile
[DEBUG] Adding project with groupId [org.apache.pulsar]
[DEBUG] Building project for org.glassfish.hk2.external:aopalliance-repackaged:jar:2.6.1:compile
[DEBUG] Adding project with groupId [org.glassfish.hk2.external]
[DEBUG] Building project for javax.xml.bind:jaxb-api:jar:2.3.0:compile
[DEBUG] Adding project with groupId [javax.xml.bind]
[DEBUG] Building project for io.netty:netty-buffer:jar:4.1.74.Final:compile
[DEBUG] Adding project with groupId [io.netty]
[DEBUG] Building project for org.glassfish.jersey.core:jersey-server:jar:2.35:compile
[DEBUG] Adding project with groupId [org.glassfish.jersey.core]
[DEBUG] Building project for com.fasterxml.jackson.module:jackson-module-jaxb-annotations:jar:2.10.0:compile
[DEBUG] Adding project with groupId [com.fasterxml.jackson.module]
[DEBUG] Building project for org.apache.commons:commons-lang3:jar:3.5:compile
[DEBUG] Adding project with groupId [org.apache.commons]
[DEBUG] Building project for com.google.guava:guava:jar:20.0:compile
[DEBUG] Adding project with groupId [com.google.guava]
[DEBUG] Building project for org.glassfish.jersey.containers:jersey-container-grizzly2-http:jar:2.35:compile
[DEBUG] Adding project with groupId [org.glassfish.jersey.containers]
[DEBUG] Building project for org.apache.logging.log4j:log4j-core:jar:2.17.1:runtime
[DEBUG] Adding project with groupId [org.apache.logging.log4j]
[DEBUG] Building project for commons-logging:commons-logging:jar:1.2:compile
[DEBUG] Adding project with groupId [commons-logging]
[DEBUG] Building project for io.netty:netty-codec-http:jar:4.1.74.Final:compile
[DEBUG] Adding project with groupId [io.netty]
[DEBUG] Building project for org.glassfish.jersey.inject:jersey-hk2:jar:2.35:compile
[DEBUG] Adding project with groupId [org.glassfish.jersey.inject]
[DEBUG] Building project for org.bouncycastle:bcprov-jdk15to18:jar:1.68:compile
[DEBUG] Adding project with groupId [org.bouncycastle]
[DEBUG] Building project for org.glassfish.grizzly:grizzly-http-server:jar:2.4.4:compile
[DEBUG] Adding project with groupId [org.glassfish.grizzly]
[DEBUG] Building project for io.netty:netty-tcnative-classes:jar:2.0.48.Final:compile
[DEBUG] Adding project with groupId [io.netty]
[DEBUG] Building project for io.netty:netty-codec-dns:jar:4.1.74.Final:compile
[DEBUG] Adding project with groupId [io.netty]
[DEBUG] Building project for commons-lang:commons-lang:jar:2.6:compile
[DEBUG] Adding project with groupId [commons-lang]
[DEBUG] Building project for commons-io:commons-io:jar:2.11.0:compile
[DEBUG] Adding project with groupId [commons-io]
[DEBUG] Building project for joda-time:joda-time:jar:2.10.5:compile
[DEBUG] Adding project with groupId [joda-time]
[DEBUG] Building project for com.yahoo.datasketches:sketches-core:jar:0.8.3:compile
[DEBUG] Adding project with groupId [com.yahoo.datasketches]
[DEBUG] Building project for io.netty:netty-codec-socks:jar:4.1.74.Final:compile
[DEBUG] Adding project with groupId [io.netty]
[DEBUG] Building project for org.apache.commons:commons-collections4:jar:4.1:compile
[DEBUG] Adding project with groupId [org.apache.commons]
[DEBUG] Building project for io.grpc:grpc-protobuf-lite:jar:1.19.0:compile
[DEBUG] Adding project with groupId [io.grpc]
[DEBUG] Building project for com.google.protobuf:protobuf-java:jar:3.19.2:compile
[DEBUG] Adding project with groupId [com.google.protobuf]
[DEBUG] Building project for com.google.protobuf:protobuf-java-util:jar:3.11.4:compile
[DEBUG] Adding project with groupId [com.google.protobuf]
[DEBUG] Building project for org.eclipse.jetty:jetty-servlet:jar:9.4.45.v20220203:compile
[DEBUG] Adding project with groupId [org.eclipse.jetty]
[DEBUG] Building project for javax.servlet:javax.servlet-api:jar:3.1.0:compile
[DEBUG] Adding project with groupId [javax.servlet]
[DEBUG] Building project for jakarta.validation:jakarta.validation-api:jar:2.0.2:compile
[DEBUG] Adding project with groupId [jakarta.validation]
[DEBUG] Building project for io.netty:netty-tcnative-boringssl-static:jar:2.0.48.Final:compile
[DEBUG] Adding project with groupId [io.netty]
[DEBUG] Building project for org.apache.avro:avro:jar:1.9.2:compile
[DEBUG] Adding project with groupId [org.apache.avro]
[DEBUG] Building project for org.eclipse.jetty:jetty-security:jar:9.4.45.v20220203:compile
[DEBUG] Adding project with groupId [org.eclipse.jetty]
[DEBUG] Building project for org.glassfish.grizzly:grizzly-framework:jar:2.4.4:compile
[DEBUG] Adding project with groupId [org.glassfish.grizzly]
[DEBUG] Building project for io.prometheus:simpleclient_hotspot:jar:0.8.1:compile
[DEBUG] Adding project with groupId [io.prometheus]
[DEBUG] Building project for org.slf4j:jul-to-slf4j:jar:1.7.25:compile
[DEBUG] Adding project with groupId [org.slf4j]
[DEBUG] Building project for org.glassfish.jersey.containers:jersey-container-servlet-core:jar:2.35:compile
[DEBUG] Adding project with groupId [org.glassfish.jersey.containers]
[DEBUG] Building project for io.prometheus:simpleclient_common:jar:0.8.1:compile
[DEBUG] Adding project with groupId [io.prometheus]
[DEBUG] Building project for org.javassist:javassist:jar:3.19.0-GA:compile
[DEBUG] Adding project with groupId [org.javassist]
[DEBUG] Building project for io.prometheus:simpleclient:jar:0.8.1:compile
[DEBUG] Adding project with groupId [io.prometheus]
[DEBUG] Building project for org.apache.logging.log4j:log4j-slf4j-impl:jar:2.17.1:compile
[DEBUG] Adding project with groupId [org.apache.logging.log4j]
[DEBUG] Building project for com.google.code.findbugs:annotations:jar:2.0.1:compile
[DEBUG] Adding project with groupId [com.google.code.findbugs]
[DEBUG] Building project for org.apache.pulsar:pulsar-common:jar:2.7.2:compile
[DEBUG] Adding project with groupId [org.apache.pulsar]
[DEBUG] Building project for com.fasterxml.jackson.module:jackson-module-jsonSchema:jar:2.11.1:compile
[DEBUG] Adding project with groupId [com.fasterxml.jackson.module]
[DEBUG] Building project for com.google.api.grpc:proto-google-common-protos:jar:1.12.0:compile
[DEBUG] Adding project with groupId [com.google.api.grpc]
[DEBUG] Building project for org.eclipse.jetty:jetty-util-ajax:jar:9.4.45.v20220203:compile
[DEBUG] Adding project with groupId [org.eclipse.jetty]
[DEBUG] Building project for io.netty:netty-transport-classes-epoll:jar:4.1.74.Final:compile
[DEBUG] Adding project with groupId [io.netty]
[DEBUG] Building project for io.netty:netty-handler:jar:4.1.74.Final:compile
[DEBUG] Adding project with groupId [io.netty]
[DEBUG] Building project for javax.ws.rs:javax.ws.rs-api:jar:2.1:compile
[DEBUG] Adding project with groupId [javax.ws.rs]
[DEBUG] Building project for org.apache.logging.log4j:log4j-1.2-api:jar:2.17.1:compile
[DEBUG] Adding project with groupId [org.apache.logging.log4j]
[DEBUG] Building project for org.reactivestreams:reactive-streams:jar:1.0.3:compile
[DEBUG] Adding project with groupId [org.reactivestreams]
[DEBUG] Building project for org.eclipse.jetty:jetty-util:jar:9.4.45.v20220203:compile
[DEBUG] Adding project with groupId [org.eclipse.jetty]
[DEBUG] Building project for org.eclipse.jetty:jetty-io:jar:9.4.45.v20220203:compile
[DEBUG] Adding project with groupId [org.eclipse.jetty]
[DEBUG] Building project for javax.validation:validation-api:jar:2.0.1.Final:compile
[DEBUG] Adding project with groupId [javax.validation]
[DEBUG] Building project for org.apache.pulsar:protobuf-shaded:jar:2.1.0-incubating:compile
[DEBUG] Adding project with groupId [org.apache.pulsar]
[DEBUG] Building project for org.glassfish.hk2:hk2-api:jar:2.6.1:compile
[DEBUG] Adding project with groupId [org.glassfish.hk2]
[DEBUG] Building project for io.grpc:grpc-core:jar:1.19.0:compile
[DEBUG] Adding project with groupId [io.grpc]
[DEBUG] Building project for org.eclipse.jetty:jetty-http:jar:9.4.45.v20220203:compile
[DEBUG] Adding project with groupId [org.eclipse.jetty]
[DEBUG] Building project for jakarta.annotation:jakarta.annotation-api:jar:1.3.5:compile
[DEBUG] Adding project with groupId [jakarta.annotation]
[DEBUG] Building project for com.typesafe.netty:netty-reactive-streams:jar:2.0.4:compile
[DEBUG] Adding project with groupId [com.typesafe.netty]
[DEBUG] Building project for org.glassfish.hk2:osgi-resource-locator:jar:1.0.3:compile
[DEBUG] Adding project with groupId [org.glassfish.hk2]
[DEBUG] Building project for org.glassfish.jersey.core:jersey-common:jar:2.35:compile
[DEBUG] Adding project with groupId [org.glassfish.jersey.core]
[DEBUG] Building project for org.apache.bookkeeper:bookkeeper-common-allocator:jar:4.12.0:compile
[DEBUG] Adding project with groupId [org.apache.bookkeeper]
[DEBUG] Building project for com.github.ben-manes.caffeine:caffeine:jar:2.6.2:compile
[DEBUG] Adding project with groupId [com.github.ben-manes.caffeine]
[DEBUG] Building project for org.eclipse.jetty:jetty-server:jar:9.4.45.v20220203:compile
[DEBUG] Adding project with groupId [org.eclipse.jetty]
[DEBUG] Building project for io.swagger:swagger-annotations:jar:1.5.21:compile
[DEBUG] Adding project with groupId [io.swagger]
[DEBUG] Building project for com.sun.activation:javax.activation:jar:1.2.0:runtime
[DEBUG] Adding project with groupId [com.sun.activation]
[DEBUG] Building project for com.fasterxml.jackson.jaxrs:jackson-jaxrs-base:jar:2.10.0:compile
[DEBUG] Adding project with groupId [com.fasterxml.jackson.jaxrs]
[DEBUG] Building project for org.apache.pulsar:pulsar-client-admin-original:jar:2.7.2:compile
[DEBUG] Adding project with groupId [org.apache.pulsar]
[DEBUG] Building project for org.glassfish.jersey.media:jersey-media-multipart:jar:2.35:compile
[DEBUG] Adding project with groupId [org.glassfish.jersey.media]
[DEBUG] Building project for jakarta.activation:jakarta.activation-api:jar:1.2.1:compile
[DEBUG] Adding project with groupId [jakarta.activation]
[DEBUG] Building project for org.glassfish.jersey.core:jersey-client:jar:2.35:compile
[DEBUG] Adding project with groupId [org.glassfish.jersey.core]
[DEBUG] Building project for com.fasterxml.jackson.core:jackson-databind:jar:2.10.0:compile
[DEBUG] Adding project with groupId [com.fasterxml.jackson.core]
[DEBUG] Building project for io.netty:netty-resolver-dns:jar:4.1.74.Final:compile
[DEBUG] Adding project with groupId [io.netty]
[DEBUG] Building project for com.yahoo.datasketches:memory:jar:0.8.3:compile
[DEBUG] Adding project with groupId [com.yahoo.datasketches]
[DEBUG] Building project for commons-codec:commons-codec:jar:1.11:compile
[DEBUG] Adding project with groupId [commons-codec]
[DEBUG] Building project for io.opencensus:opencensus-api:jar:0.19.2:compile
[DEBUG] Adding project with groupId [io.opencensus]
[DEBUG] Building project for org.apache.pinot:pinot-spi:jar:0.11.0-SNAPSHOT:compile
[DEBUG] Adding project with groupId [org.apache.pinot]
[DEBUG] Building project for com.google.code.gson:gson:jar:2.2.4:compile
[DEBUG] Adding project with groupId [com.google.code.gson]
[DEBUG] Building project for com.sun.activation:jakarta.activation:jar:1.2.2:compile
[DEBUG] Adding project with groupId [com.sun.activation]
[DEBUG] Building project for org.asynchttpclient:async-http-client:jar:2.12.3:compile
[DEBUG] Adding project with groupId [org.asynchttpclient]
[DEBUG] Building project for org.apache.commons:commons-compress:jar:1.21:compile
[DEBUG] Adding project with groupId [org.apache.commons]
[DEBUG] Building project for commons-configuration:commons-configuration:jar:1.10:compile
[DEBUG] Adding project with groupId [commons-configuration]
[DEBUG] Building project for io.netty:netty-transport-native-epoll:jar:linux-x86_64:4.1.74.Final:compile
[DEBUG] Adding project with groupId [io.netty]
[DEBUG] Building project for org.codehaus.groovy:groovy-all:jar:2.4.21:compile
[DEBUG] Adding project with groupId [org.codehaus.groovy]
[DEBUG] Building project for org.apache.pulsar:pulsar-client-original:jar:2.7.2:compile
[DEBUG] Adding project with groupId [org.apache.pulsar]
[DEBUG] Building project for com.google.errorprone:error_prone_annotations:jar:2.3.4:compile
[DEBUG] Adding project with groupId [com.google.errorprone]
[DEBUG] Building project for org.asynchttpclient:async-http-client-netty-utils:jar:2.12.3:compile
[DEBUG] Adding project with groupId [org.asynchttpclient]
[DEBUG] Building project for org.apache.avro:avro-protobuf:jar:1.9.1:compile
[DEBUG] Adding project with groupId [org.apache.avro]
[DEBUG] Building project for jakarta.xml.bind:jakarta.xml.bind-api:jar:2.3.2:compile
[DEBUG] Adding project with groupId [jakarta.xml.bind]
[DEBUG] Building project for org.apache.logging.log4j:log4j-api:jar:2.17.1:compile
[DEBUG] Adding project with groupId [org.apache.logging.log4j]
[DEBUG] Building project for javax.annotation:javax.annotation-api:jar:1.2:compile
[DEBUG] Adding project with groupId [javax.annotation]
[DEBUG] Building project for com.lmax:disruptor:jar:3.3.4:compile
[DEBUG] Adding project with groupId [com.lmax]
[DEBUG] Building project for org.apache.pulsar:pulsar-client-api:jar:2.7.2:compile
[DEBUG] Adding project with groupId [org.apache.pulsar]
[DEBUG] Building project for com.fasterxml.jackson.jaxrs:jackson-jaxrs-json-provider:jar:2.10.0:compile
[DEBUG] Adding project with groupId [com.fasterxml.jackson.jaxrs]
[DEBUG] Building project for io.airlift:aircompressor:jar:0.16:compile
[DEBUG] Adding project with groupId [io.airlift]
[DEBUG] Building project for org.yaml:snakeyaml:jar:1.30:compile
[DEBUG] Adding project with groupId [org.yaml]
[DEBUG] Building project for commons-collections:commons-collections:jar:3.2.2:compile
[DEBUG] Adding project with groupId [commons-collections]
[DEBUG] Building project for org.apache.pulsar:pulsar-transaction-common:jar:2.7.2:compile
[DEBUG] Adding project with groupId [org.apache.pulsar]
[DEBUG] Building project for org.slf4j:slf4j-api:jar:1.7.25:compile
[DEBUG] Adding project with groupId [org.slf4j]
[DEBUG] Building project for com.google.protobuf:protobuf-lite:jar:3.0.1:compile
[DEBUG] Adding project with groupId [com.google.protobuf]
[DEBUG] Building project for com.fasterxml.jackson.dataformat:jackson-dataformat-yaml:jar:2.10.0:compile
[DEBUG] Adding project with groupId [com.fasterxml.jackson.dataformat]
[DEBUG] Building project for org.reflections:reflections:jar:0.9.9:compile
[DEBUG] Adding project with groupId [org.reflections]
[DEBUG] Building project for org.bouncycastle:bcprov-ext-jdk15to18:jar:1.68:compile
[DEBUG] Adding project with groupId [org.bouncycastle]
[DEBUG] Building project for io.netty:netty-transport:jar:4.1.74.Final:compile
[DEBUG] Adding project with groupId [io.netty]
[DEBUG] Building project for io.netty:netty-common:jar:4.1.74.Final:compile
[DEBUG] Adding project with groupId [io.netty]
[DEBUG] Building project for org.glassfish.jersey.ext:jersey-entity-filtering:jar:2.35:compile
[DEBUG] Adding project with groupId [org.glassfish.jersey.ext]
[DEBUG] Building project for org.apache.bookkeeper:circe-checksum:jar:4.12.0:compile
[DEBUG] Adding project with groupId [org.apache.bookkeeper]
[DEBUG] Building project for io.opencensus:opencensus-contrib-grpc-metrics:jar:0.19.2:compile
[DEBUG] Adding project with groupId [io.opencensus]
[DEBUG] File /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/maven-shared-archive-resources/META-INF/DEPENDENCIES contents differs
[DEBUG] Writing /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/maven-shared-archive-resources/META-INF/DEPENDENCIES
[INFO] 
[INFO] --- maven-resources-plugin:2.6:resources (default-resources) @ pinot-pulsar ---
[DEBUG] Dependency collection stats {ConflictMarker.analyzeTime=813292, ConflictMarker.markTime=110375, ConflictMarker.nodeCount=77, ConflictIdSorter.graphTime=261083, ConflictIdSorter.topsortTime=157292, ConflictIdSorter.conflictIdCount=26, ConflictIdSorter.conflictIdCycleCount=0, ConflictResolver.totalTime=2026583, ConflictResolver.conflictItemCount=74, DefaultDependencyCollector.collectTime=32348042, DefaultDependencyCollector.transformTime=3529250}
[DEBUG] org.apache.maven.plugins:maven-resources-plugin:jar:2.6
[DEBUG]    org.apache.maven:maven-plugin-api:jar:2.0.6:compile
[DEBUG]    org.apache.maven:maven-project:jar:2.0.6:compile
[DEBUG]       org.apache.maven:maven-profile:jar:2.0.6:compile
[DEBUG]       org.apache.maven:maven-artifact-manager:jar:2.0.6:compile
[DEBUG]       org.apache.maven:maven-plugin-registry:jar:2.0.6:compile
[DEBUG]    org.apache.maven:maven-core:jar:2.0.6:compile
[DEBUG]       org.apache.maven:maven-plugin-parameter-documenter:jar:2.0.6:compile
[DEBUG]       org.apache.maven.reporting:maven-reporting-api:jar:2.0.6:compile
[DEBUG]          org.apache.maven.doxia:doxia-sink-api:jar:1.0-alpha-7:compile
[DEBUG]       org.apache.maven:maven-repository-metadata:jar:2.0.6:compile
[DEBUG]       org.apache.maven:maven-error-diagnostics:jar:2.0.6:compile
[DEBUG]       commons-cli:commons-cli:jar:1.0:compile
[DEBUG]       org.apache.maven:maven-plugin-descriptor:jar:2.0.6:compile
[DEBUG]       org.codehaus.plexus:plexus-interactivity-api:jar:1.0-alpha-4:compile
[DEBUG]       classworlds:classworlds:jar:1.1:compile
[DEBUG]    org.apache.maven:maven-artifact:jar:2.0.6:compile
[DEBUG]    org.apache.maven:maven-settings:jar:2.0.6:compile
[DEBUG]    org.apache.maven:maven-model:jar:2.0.6:compile
[DEBUG]    org.apache.maven:maven-monitor:jar:2.0.6:compile
[DEBUG]    org.codehaus.plexus:plexus-container-default:jar:1.0-alpha-9-stable-1:compile
[DEBUG]       junit:junit:jar:3.8.1:compile
[DEBUG]    org.codehaus.plexus:plexus-utils:jar:2.0.5:compile
[DEBUG]    org.apache.maven.shared:maven-filtering:jar:1.1:compile
[DEBUG]       org.sonatype.plexus:plexus-build-api:jar:0.0.4:compile
[DEBUG]    org.codehaus.plexus:plexus-interpolation:jar:1.13:compile
[DEBUG] Created new class realm plugin>org.apache.maven.plugins:maven-resources-plugin:2.6
[DEBUG] Importing foreign packages into class realm plugin>org.apache.maven.plugins:maven-resources-plugin:2.6
[DEBUG]   Imported:  < project>org.apache.pinot:pinot-pulsar:0.11.0-SNAPSHOT
[DEBUG] Populating class realm plugin>org.apache.maven.plugins:maven-resources-plugin:2.6
[DEBUG]   Included: org.apache.maven.plugins:maven-resources-plugin:jar:2.6
[DEBUG]   Included: org.apache.maven.reporting:maven-reporting-api:jar:2.0.6
[DEBUG]   Included: org.apache.maven.doxia:doxia-sink-api:jar:1.0-alpha-7
[DEBUG]   Included: commons-cli:commons-cli:jar:1.0
[DEBUG]   Included: org.codehaus.plexus:plexus-interactivity-api:jar:1.0-alpha-4
[DEBUG]   Included: junit:junit:jar:3.8.1
[DEBUG]   Included: org.codehaus.plexus:plexus-utils:jar:2.0.5
[DEBUG]   Included: org.apache.maven.shared:maven-filtering:jar:1.1
[DEBUG]   Included: org.sonatype.plexus:plexus-build-api:jar:0.0.4
[DEBUG]   Included: org.codehaus.plexus:plexus-interpolation:jar:1.13
[DEBUG] Configuring mojo org.apache.maven.plugins:maven-resources-plugin:2.6:resources from plugin realm ClassRealm[plugin>org.apache.maven.plugins:maven-resources-plugin:2.6, parent: jdk.internal.loader.ClassLoaders$AppClassLoader@2c13da15]
[DEBUG] Configuring mojo 'org.apache.maven.plugins:maven-resources-plugin:2.6:resources' with basic configurator -->
[DEBUG]   (f) buildFilters = []
[DEBUG]   (f) encoding = UTF-8
[DEBUG]   (f) escapeWindowsPaths = true
[DEBUG]   (s) includeEmptyDirs = false
[DEBUG]   (s) outputDirectory = /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/classes
[DEBUG]   (s) overwrite = false
[DEBUG]   (f) project = MavenProject: org.apache.pinot:pinot-pulsar:0.11.0-SNAPSHOT @ /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/pom.xml
[DEBUG]   (s) resources = [Resource {targetPath: null, filtering: false, FileSet {directory: /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/src/main/resources, PatternSet [includes: {}, excludes: {}]}}, Resource {targetPath: null, filtering: false, FileSet {directory: /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/maven-shared-archive-resources, PatternSet [includes: {}, excludes: {}]}}, Resource {targetPath: null, filtering: false, FileSet {directory: /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/maven-shared-archive-resources, PatternSet [includes: {}, excludes: {}]}}]
[DEBUG]   (f) session = org.apache.maven.execution.MavenSession@53d6e959
[DEBUG]   (f) supportMultiLineFiltering = false
[DEBUG]   (f) useBuildFilters = true
[DEBUG]   (s) useDefaultDelimiters = true
[DEBUG] -- end configuration --
[DEBUG] properties used {java.specification.version=11, java.vendor.url=https://openjdk.java.net/, log4j.version=2.17.1, build.profile.id=dev, sun.boot.library.path=/Library/Java/JavaVirtualMachines/jdk-11.0.13.jdk/Contents/Home/lib, sun.java.command=org.codehaus.classworlds.Launcher -Didea.version=2022.1 clean install package -DskipTests -Pbin-dist -X -P apple-silicon,other-jdk-maven-compiler-plugin, jdk.debug=release, maven.version=3.8.1, kafka.version=2.0, SKIP_INTEGRATION_TESTS=true, java.specification.name=Java Platform API Specification, java.vm.specification.vendor=Oracle Corporation, env.HOMEBREW_REPOSITORY=/opt/homebrew, env.MANPATH=/opt/homebrew/share/man::, java.runtime.version=11.0.13+10-LTS-370, env.LSCOLORS=Gxfxcxdxbxegedabagacad, surefire.version=2.22.0, env.__CFBundleIdentifier=com.jetbrains.intellij.ce, h3.version=3.7.2, java.vendor.version=18.9, java.io.tmpdir=/var/folders/p1/5_dg90653gd_gj7vzjlzqqf80000gn/T/, java.version=11.0.13, java.vm.specification.name=Java Virtual Machine Specification, java.library.path=/Users/.../Library/Java/Extensions:/Library/Java/Extensions:/Network/Library/Java/Extensions:/System/Library/Java/Extensions:/usr/lib/java:., java.vendor=Oracle Corporation, jetty-server.version=9.4.45.v20220203, checkstyle.violation.severity=warning, async-http-client.version=2.12.3, lz4-java.version=1.8.0, user.timezone=, java.vm.specification.version=11, distMgmtSnapshotsName=Apache Development Snapshot Repository, maven.compiler.source=1.7, user.home=/Users/..., env.HOMEBREW_CELLAR=/opt/homebrew/Cellar, gpg.useagent=true, jsonpath.version=2.7.0, env.HOMEBREW_PREFIX=/opt/homebrew, os.version=11.3, os.detected.name=osx, lucene.version=8.2.0, java.vm.name=Java HotSpot(TM) 64-Bit Server VM, grpc-context.version=1.14.0, commons-net.version=3.1, os.arch=x86_64, argLine=-javaagent:/Users/.../.m2/repository/org/jacoco/org.jacoco.agent/0.8.6/org.jacoco.agent-0.8.6-runtime.jar=destfile=/Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/jacoco.exec,includes=org/apache/pinot/**/* -Xms4g -Xmx4g, awt.toolkit=sun.lwawt.macosx.LWCToolkit, distMgmtSnapshotsUrl=https://repository.apache.org/content/repositories/snapshots, hk2.version=2.6.1, commons-codec.version=1.11, caffeine.version=2.6.2, os.detected.classifier=osx-x86_64, java.vm.compressedOopsMode=Zero based, phase.prop=package, pulsar.version=2.7.2, jdk.version=11, env.LOGNAME=..., env.__CF_USER_TEXT_ENCODING=0x1F5:0x19:0x34, calcite.version=1.29.0, env.SSH_AUTH_SOCK=/private/tmp/com.apple.launchd.zhU6lvNoNZ/Listeners, sun.os.patch.level=unknown, maven.compiler.target=1.7, env.TMPDIR=/var/folders/p1/5_dg90653gd_gj7vzjlzqqf80000gn/T/, socksNonProxyHosts=local|*.local|169.254/16|*.169.254/16, zkclient.version=0.7, gopherProxySet=false, env.PAGER=less, sourceReleaseAssemblyDescriptor=source-release, maven.conf=/Applications/IntelliJ IDEA CE.app/Contents/plugins/maven/lib/maven3/conf, avro.version=1.9.2, sun.java.launcher=SUN_STANDARD, user.country=CN, bouncycastle.version=1.68, netty.version=4.1.74.Final, grpc-protobuf-lite.version=1.19.0, java.runtime.name=Java(TM) SE Runtime Environment, dropwizard-metrics.version=4.2.2, swagger-annotations.version=1.5.21, skip.integration.tests=true, sun.cpu.isalist=, jackson.version=2.10.0, sun.arch.data.model=64, java.specification.vendor=Oracle Corporation, java.version.date=2021-10-19, java.home=/Library/Java/JavaVirtualMachines/jdk-11.0.13.jdk/Contents/Home, codehaus-annotations.version=1.17, okio.version=1.6.0, jmh.version=1.26, user.script=Hans, jersey-container-grizzly2-http.version=2.35, sun.management.compiler=HotSpot 64-Bit Tiered Compilers, simpleclient_common.version=0.8.1, env.PATH=/opt/homebrew/bin:/opt/homebrew/sbin:/usr/local/bin:/usr/bin:/bin:/usr/sbin:/sbin, javax.ws.rs-api.version=2.1, file.encoding=UTF-8, assembly.tarLongFileMode=posix, timestamp=1656386998585, parquet.version=1.11.1, java.awt.printerjob=sun.lwawt.macosx.CPrinterJob, jts.version=1.16.1, classworlds.conf=/Applications/IntelliJ IDEA CE.app/Contents/plugins/maven/lib/maven3/bin/m2.conf, checkstyle.fail.on.violation=true, sun.io.unicode.encoding=UnicodeBig, os.detected.arch=x86_64, zookeeper.version=3.5.8, env.COMMAND_MODE=unix2003, skip.unit.tests=false, buildNumber=7dce7cb1e0f149429778c955d372aac018725aca, commons-logging.version=1.2, protobuf.version=3.19.2, grpc-proto.version=1.12.0, os.name=Mac OS X, http.nonProxyHosts=local|*.local|169.254/16|*.169.254/16, env.ZSH=/Users/.../.oh-my-zsh, java.awt.graphicsenv=sun.awt.CGraphicsEnvironment, grizzly.version=2.4.4, quartz.version=2.3.2, path.separator=:, env.SHELL=/bin/zsh, swagger.version=1.5.16, maven.ext.class.path=/Applications/IntelliJ IDEA CE.app/Contents/plugins/maven/lib/maven-event-listener.jar, maven.multiModuleProjectDirectory=/Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar, java.vm.info=mixed mode, env.USER=..., java.class.version=55.0, helix.version=0.9.8, javax.annotation-api.version=1.2, sun.jnu.encoding=UTF-8, organization.logo=https://www.apache.org/images/asf_logo_wide.gif, reactivestreams.version=1.0.3, maven.build.version=Apache Maven 3.8.1 (05c21c65bdfed0f71a2f2ada8b84da59348c4c5d), maven.home=/Applications/IntelliJ IDEA CE.app/Contents/plugins/maven/lib/maven3, env.JAVA_MAIN_CLASS_29651=org.codehaus.classworlds.Launcher, audienceannotations.version=0.13.0, file.separator=/, env.LESS=-R, line.separator=
, jersey.version=2.35, user.name=..., env.XPC_FLAGS=0x0, grpc.version=1.41.0, pinot.root=/Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/../../.., idea.version=2022.1, project.reporting.outputEncoding=UTF-8, env.INFOPATH=/opt/homebrew/share/info:, env.OLDPWD=/, env.PWD=/Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar, env.LC_CTYPE=zh_CN.UTF-8, java.class.path=/Applications/IntelliJ IDEA CE.app/Contents/plugins/maven/lib/maven3/boot/plexus-classworlds.license:/Applications/IntelliJ IDEA CE.app/Contents/plugins/maven/lib/maven3/boot/plexus-classworlds-2.6.0.jar, reflections.version=0.9.9, env.HOME=/Users/..., java.vm.vendor=Oracle Corporation, hadoop.version=2.10.1, zstd-jni.version=1.4.9-5, commons-collections.version=4.1, sun.cpu.endian=little, user.language=zh, commons-lang.version=2.6, env.XPC_SERVICE_NAME=application.com.jetbrains.intellij.ce.12689015.12690906, ftp.nonProxyHosts=local|*.local|169.254/16|*.169.254/16, project.build.sourceEncoding=UTF-8, skipTests=true, plugin.type=pinot-stream-ingestion, java.vendor.url.bug=https://bugreport.java.com/bugreport/, user.dir=/Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar, antlr.version=4.6, snappy-java.version=1.1.8.2, scmBranch=master, javax.servlet-api.version=3.1.0, java.vm.version=11.0.13+10-LTS-370, arguments=}
[INFO] Using 'UTF-8' encoding to copy filtered resources.
[DEBUG] resource with targetPath null
directory /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/src/main/resources
excludes []
includes []
[INFO] skip non existing resourceDirectory /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/src/main/resources
[DEBUG] resource with targetPath null
directory /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/maven-shared-archive-resources
excludes []
includes []
[DEBUG] ignoreDelta true
[INFO] Copying 3 resources
[DEBUG] file LICENSE has a filtered file extension
[DEBUG] copy /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/maven-shared-archive-resources/META-INF/LICENSE to /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/classes/META-INF/LICENSE
[DEBUG] file DEPENDENCIES has a filtered file extension
[DEBUG] copy /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/maven-shared-archive-resources/META-INF/DEPENDENCIES to /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/classes/META-INF/DEPENDENCIES
[DEBUG] file NOTICE has a filtered file extension
[DEBUG] copy /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/maven-shared-archive-resources/META-INF/NOTICE to /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/classes/META-INF/NOTICE
[DEBUG] resource with targetPath null
directory /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/maven-shared-archive-resources
excludes []
includes []
[DEBUG] ignoreDelta true
[INFO] Copying 3 resources
[DEBUG] file LICENSE has a filtered file extension
[DEBUG] copy /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/maven-shared-archive-resources/META-INF/LICENSE to /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/classes/META-INF/LICENSE
[DEBUG] file DEPENDENCIES has a filtered file extension
[DEBUG] copy /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/maven-shared-archive-resources/META-INF/DEPENDENCIES to /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/classes/META-INF/DEPENDENCIES
[DEBUG] file NOTICE has a filtered file extension
[DEBUG] copy /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/maven-shared-archive-resources/META-INF/NOTICE to /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/classes/META-INF/NOTICE
[DEBUG] no use filter components
[INFO] 
[INFO] --- maven-compiler-plugin:3.8.0:compile (default-compile) @ pinot-pulsar ---
[DEBUG] Dependency collection stats {ConflictMarker.analyzeTime=837291, ConflictMarker.markTime=146584, ConflictMarker.nodeCount=118, ConflictIdSorter.graphTime=353792, ConflictIdSorter.topsortTime=183417, ConflictIdSorter.conflictIdCount=45, ConflictIdSorter.conflictIdCycleCount=0, ConflictResolver.totalTime=6332667, ConflictResolver.conflictItemCount=72, DefaultDependencyCollector.collectTime=111553042, DefaultDependencyCollector.transformTime=8020833}
[DEBUG] org.apache.maven.plugins:maven-compiler-plugin:jar:3.8.0
[DEBUG]    org.apache.maven:maven-plugin-api:jar:3.0:compile
[DEBUG]       org.apache.maven:maven-model:jar:3.0:compile
[DEBUG]       org.sonatype.sisu:sisu-inject-plexus:jar:1.4.2:compile
[DEBUG]          org.sonatype.sisu:sisu-inject-bean:jar:1.4.2:compile
[DEBUG]             org.sonatype.sisu:sisu-guice:jar:noaop:2.1.7:compile
[DEBUG]    org.apache.maven:maven-artifact:jar:3.0:compile
[DEBUG]       org.codehaus.plexus:plexus-utils:jar:2.0.4:compile
[DEBUG]    org.apache.maven:maven-core:jar:3.0:compile
[DEBUG]       org.apache.maven:maven-settings:jar:3.0:compile
[DEBUG]       org.apache.maven:maven-settings-builder:jar:3.0:compile
[DEBUG]       org.apache.maven:maven-repository-metadata:jar:3.0:compile
[DEBUG]       org.apache.maven:maven-model-builder:jar:3.0:compile
[DEBUG]       org.apache.maven:maven-aether-provider:jar:3.0:runtime
[DEBUG]       org.sonatype.aether:aether-impl:jar:1.7:compile
[DEBUG]          org.sonatype.aether:aether-spi:jar:1.7:compile
[DEBUG]       org.sonatype.aether:aether-api:jar:1.7:compile
[DEBUG]       org.sonatype.aether:aether-util:jar:1.7:compile
[DEBUG]       org.codehaus.plexus:plexus-interpolation:jar:1.14:compile
[DEBUG]       org.codehaus.plexus:plexus-classworlds:jar:2.2.3:compile
[DEBUG]       org.codehaus.plexus:plexus-component-annotations:jar:1.7.1:compile (version managed from default)
[DEBUG]       org.sonatype.plexus:plexus-sec-dispatcher:jar:1.3:compile
[DEBUG]          org.sonatype.plexus:plexus-cipher:jar:1.4:compile
[DEBUG]    org.apache.maven.shared:maven-shared-utils:jar:3.2.1:compile
[DEBUG]       commons-io:commons-io:jar:2.5:compile
[DEBUG]    org.apache.maven.shared:maven-shared-incremental:jar:1.1:compile
[DEBUG]    org.codehaus.plexus:plexus-java:jar:0.9.10:compile
[DEBUG]       org.ow2.asm:asm:jar:6.2:compile
[DEBUG]       com.thoughtworks.qdox:qdox:jar:2.0-M9:compile (version managed from default)
[DEBUG]    org.codehaus.plexus:plexus-compiler-api:jar:2.8.4:compile
[DEBUG]    org.codehaus.plexus:plexus-compiler-manager:jar:2.8.4:compile
[DEBUG]    org.codehaus.plexus:plexus-compiler-javac:jar:2.8.4:runtime
[DEBUG] Created new class realm plugin>org.apache.maven.plugins:maven-compiler-plugin:3.8.0
[DEBUG] Importing foreign packages into class realm plugin>org.apache.maven.plugins:maven-compiler-plugin:3.8.0
[DEBUG]   Imported:  < project>org.apache.pinot:pinot-pulsar:0.11.0-SNAPSHOT
[DEBUG] Populating class realm plugin>org.apache.maven.plugins:maven-compiler-plugin:3.8.0
[DEBUG]   Included: org.apache.maven.plugins:maven-compiler-plugin:jar:3.8.0
[DEBUG]   Included: org.sonatype.sisu:sisu-inject-bean:jar:1.4.2
[DEBUG]   Included: org.sonatype.sisu:sisu-guice:jar:noaop:2.1.7
[DEBUG]   Included: org.codehaus.plexus:plexus-utils:jar:2.0.4
[DEBUG]   Included: org.sonatype.aether:aether-util:jar:1.7
[DEBUG]   Included: org.codehaus.plexus:plexus-interpolation:jar:1.14
[DEBUG]   Included: org.codehaus.plexus:plexus-component-annotations:jar:1.7.1
[DEBUG]   Included: org.sonatype.plexus:plexus-sec-dispatcher:jar:1.3
[DEBUG]   Included: org.sonatype.plexus:plexus-cipher:jar:1.4
[DEBUG]   Included: org.apache.maven.shared:maven-shared-utils:jar:3.2.1
[DEBUG]   Included: commons-io:commons-io:jar:2.5
[DEBUG]   Included: org.apache.maven.shared:maven-shared-incremental:jar:1.1
[DEBUG]   Included: org.codehaus.plexus:plexus-java:jar:0.9.10
[DEBUG]   Included: org.ow2.asm:asm:jar:6.2
[DEBUG]   Included: com.thoughtworks.qdox:qdox:jar:2.0-M9
[DEBUG]   Included: org.codehaus.plexus:plexus-compiler-api:jar:2.8.4
[DEBUG]   Included: org.codehaus.plexus:plexus-compiler-manager:jar:2.8.4
[DEBUG]   Included: org.codehaus.plexus:plexus-compiler-javac:jar:2.8.4
[DEBUG] Configuring mojo org.apache.maven.plugins:maven-compiler-plugin:3.8.0:compile from plugin realm ClassRealm[plugin>org.apache.maven.plugins:maven-compiler-plugin:3.8.0, parent: jdk.internal.loader.ClassLoaders$AppClassLoader@2c13da15]
[DEBUG] Configuring mojo 'org.apache.maven.plugins:maven-compiler-plugin:3.8.0:compile' with basic configurator -->
[DEBUG]   (f) basedir = /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar
[DEBUG]   (f) buildDirectory = /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target
[DEBUG]   (f) compilePath = [/Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/classes, /Users/.../.m2/repository/org/eclipse/jetty/jetty-server/9.4.45.v20220203/jetty-server-9.4.45.v20220203.jar, /Users/.../.m2/repository/org/eclipse/jetty/jetty-http/9.4.45.v20220203/jetty-http-9.4.45.v20220203.jar, /Users/.../.m2/repository/org/eclipse/jetty/jetty-util/9.4.45.v20220203/jetty-util-9.4.45.v20220203.jar, /Users/.../.m2/repository/org/eclipse/jetty/jetty-io/9.4.45.v20220203/jetty-io-9.4.45.v20220203.jar, /Users/.../.m2/repository/org/apache/commons/commons-compress/1.21/commons-compress-1.21.jar, /Users/.../.m2/repository/org/apache/pulsar/pulsar-client-original/2.7.2/pulsar-client-original-2.7.2.jar, /Users/.../.m2/repository/org/apache/pulsar/pulsar-client-api/2.7.2/pulsar-client-api-2.7.2.jar, /Users/.../.m2/repository/org/apache/pulsar/pulsar-common/2.7.2/pulsar-common-2.7.2.jar, /Users/.../.m2/repository/org/apache/pulsar/protobuf-shaded/2.1.0-incubating/protobuf-shaded-2.1.0-incubating.jar, /Users/.../.m2/repository/io/netty/netty-handler/4.1.74.Final/netty-handler-4.1.74.Final.jar, /Users/.../.m2/repository/io/netty/netty-tcnative-classes/2.0.48.Final/netty-tcnative-classes-2.0.48.Final.jar, /Users/.../.m2/repository/io/netty/netty-transport-native-epoll/4.1.74.Final/netty-transport-native-epoll-4.1.74.Final-linux-x86_64.jar, /Users/.../.m2/repository/io/netty/netty-transport-classes-epoll/4.1.74.Final/netty-transport-classes-epoll-4.1.74.Final.jar, /Users/.../.m2/repository/org/apache/bookkeeper/bookkeeper-common-allocator/4.12.0/bookkeeper-common-allocator-4.12.0.jar, /Users/.../.m2/repository/io/airlift/aircompressor/0.16/aircompressor-0.16.jar, /Users/.../.m2/repository/org/apache/bookkeeper/circe-checksum/4.12.0/circe-checksum-4.12.0.jar, /Users/.../.m2/repository/io/netty/netty-tcnative-boringssl-static/2.0.48.Final/netty-tcnative-boringssl-static-2.0.48.Final.jar, /Users/.../.m2/repository/io/netty/netty-codec-haproxy/4.1.74.Final/netty-codec-haproxy-4.1.74.Final.jar, /Users/.../.m2/repository/com/fasterxml/jackson/dataformat/jackson-dataformat-yaml/2.10.0/jackson-dataformat-yaml-2.10.0.jar, /Users/.../.m2/repository/org/apache/pulsar/pulsar-transaction-common/2.7.2/pulsar-transaction-common-2.7.2.jar, /Users/.../.m2/repository/com/google/protobuf/protobuf-java-util/3.11.4/protobuf-java-util-3.11.4.jar, /Users/.../.m2/repository/org/apache/pulsar/bouncy-castle-bc/2.7.2/bouncy-castle-bc-2.7.2-pkg.jar, /Users/.../.m2/repository/io/netty/netty-codec-http/4.1.74.Final/netty-codec-http-4.1.74.Final.jar, /Users/.../.m2/repository/io/netty/netty-resolver-dns/4.1.74.Final/netty-resolver-dns-4.1.74.Final.jar, /Users/.../.m2/repository/io/netty/netty-codec-dns/4.1.74.Final/netty-codec-dns-4.1.74.Final.jar, /Users/.../.m2/repository/org/apache/commons/commons-lang3/3.5/commons-lang3-3.5.jar, /Users/.../.m2/repository/org/asynchttpclient/async-http-client/2.12.3/async-http-client-2.12.3.jar, /Users/.../.m2/repository/org/asynchttpclient/async-http-client-netty-utils/2.12.3/async-http-client-netty-utils-2.12.3.jar, /Users/.../.m2/repository/org/reactivestreams/reactive-streams/1.0.3/reactive-streams-1.0.3.jar, /Users/.../.m2/repository/com/typesafe/netty/netty-reactive-streams/2.0.4/netty-reactive-streams-2.0.4.jar, /Users/.../.m2/repository/com/sun/activation/jakarta.activation/1.2.2/jakarta.activation-1.2.2.jar, /Users/.../.m2/repository/org/slf4j/slf4j-api/1.7.25/slf4j-api-1.7.25.jar, /Users/.../.m2/repository/com/yahoo/datasketches/sketches-core/0.8.3/sketches-core-0.8.3.jar, /Users/.../.m2/repository/com/yahoo/datasketches/memory/0.8.3/memory-0.8.3.jar, /Users/.../.m2/repository/com/google/code/gson/gson/2.2.4/gson-2.2.4.jar, /Users/.../.m2/repository/org/apache/avro/avro/1.9.2/avro-1.9.2.jar, /Users/.../.m2/repository/com/fasterxml/jackson/core/jackson-core/2.10.0/jackson-core-2.10.0.jar, /Users/.../.m2/repository/org/apache/avro/avro-protobuf/1.9.1/avro-protobuf-1.9.1.jar, /Users/.../.m2/repository/com/fasterxml/jackson/module/jackson-module-jsonSchema/2.11.1/jackson-module-jsonSchema-2.11.1.jar, /Users/.../.m2/repository/javax/validation/validation-api/2.0.1.Final/validation-api-2.0.1.Final.jar, /Users/.../.m2/repository/net/jcip/jcip-annotations/1.0/jcip-annotations-1.0.jar, /Users/.../.m2/repository/org/apache/pulsar/pulsar-client-admin-original/2.7.2/pulsar-client-admin-original-2.7.2.jar, /Users/.../.m2/repository/org/glassfish/jersey/core/jersey-client/2.35/jersey-client-2.35.jar, /Users/.../.m2/repository/org/glassfish/jersey/media/jersey-media-json-jackson/2.35/jersey-media-json-jackson-2.35.jar, /Users/.../.m2/repository/org/glassfish/jersey/ext/jersey-entity-filtering/2.35/jersey-entity-filtering-2.35.jar, /Users/.../.m2/repository/com/fasterxml/jackson/module/jackson-module-jaxb-annotations/2.10.0/jackson-module-jaxb-annotations-2.10.0.jar, /Users/.../.m2/repository/jakarta/xml/bind/jakarta.xml.bind-api/2.3.2/jakarta.xml.bind-api-2.3.2.jar, /Users/.../.m2/repository/jakarta/activation/jakarta.activation-api/1.2.1/jakarta.activation-api-1.2.1.jar, /Users/.../.m2/repository/org/glassfish/jersey/media/jersey-media-multipart/2.35/jersey-media-multipart-2.35.jar, /Users/.../.m2/repository/org/jvnet/mimepull/mimepull/1.9.13/mimepull-1.9.13.jar, /Users/.../.m2/repository/com/fasterxml/jackson/jaxrs/jackson-jaxrs-json-provider/2.10.0/jackson-jaxrs-json-provider-2.10.0.jar, /Users/.../.m2/repository/com/fasterxml/jackson/jaxrs/jackson-jaxrs-base/2.10.0/jackson-jaxrs-base-2.10.0.jar, /Users/.../.m2/repository/org/glassfish/jersey/inject/jersey-hk2/2.35/jersey-hk2-2.35.jar, /Users/.../.m2/repository/org/glassfish/hk2/hk2-locator/2.6.1/hk2-locator-2.6.1.jar, /Users/.../.m2/repository/org/glassfish/hk2/external/aopalliance-repackaged/2.6.1/aopalliance-repackaged-2.6.1.jar, /Users/.../.m2/repository/org/glassfish/hk2/hk2-api/2.6.1/hk2-api-2.6.1.jar, /Users/.../.m2/repository/org/glassfish/hk2/hk2-utils/2.6.1/hk2-utils-2.6.1.jar, /Users/.../.m2/repository/org/javassist/javassist/3.19.0-GA/javassist-3.19.0-GA.jar, /Users/.../.m2/repository/javax/xml/bind/jaxb-api/2.3.0/jaxb-api-2.3.0.jar, /Users/.../.m2/repository/org/slf4j/jul-to-slf4j/1.7.25/jul-to-slf4j-1.7.25.jar, /Users/.../.m2/repository/com/google/guava/guava/20.0/guava-20.0.jar, /Users/.../.m2/repository/javax/servlet/javax.servlet-api/3.1.0/javax.servlet-api-3.1.0.jar, /Users/.../.m2/repository/javax/ws/rs/javax.ws.rs-api/2.1/javax.ws.rs-api-2.1.jar, /Users/.../.m2/repository/org/glassfish/jersey/containers/jersey-container-grizzly2-http/2.35/jersey-container-grizzly2-http-2.35.jar, /Users/.../.m2/repository/org/glassfish/hk2/external/jakarta.inject/2.6.1/jakarta.inject-2.6.1.jar, /Users/.../.m2/repository/org/glassfish/grizzly/grizzly-http-server/2.4.4/grizzly-http-server-2.4.4.jar, /Users/.../.m2/repository/org/glassfish/grizzly/grizzly-http/2.4.4/grizzly-http-2.4.4.jar, /Users/.../.m2/repository/org/glassfish/grizzly/grizzly-framework/2.4.4/grizzly-framework-2.4.4.jar, /Users/.../.m2/repository/org/glassfish/jersey/core/jersey-common/2.35/jersey-common-2.35.jar, /Users/.../.m2/repository/org/glassfish/hk2/osgi-resource-locator/1.0.3/osgi-resource-locator-1.0.3.jar, /Users/.../.m2/repository/jakarta/ws/rs/jakarta.ws.rs-api/2.1.6/jakarta.ws.rs-api-2.1.6.jar, /Users/.../.m2/repository/org/glassfish/jersey/core/jersey-server/2.35/jersey-server-2.35.jar, /Users/.../.m2/repository/jakarta/annotation/jakarta.annotation-api/1.3.5/jakarta.annotation-api-1.3.5.jar, /Users/.../.m2/repository/jakarta/validation/jakarta.validation-api/2.0.2/jakarta.validation-api-2.0.2.jar, /Users/.../.m2/repository/org/glassfish/jersey/containers/jersey-container-servlet-core/2.35/jersey-container-servlet-core-2.35.jar, /Users/.../.m2/repository/io/netty/netty-resolver/4.1.74.Final/netty-resolver-4.1.74.Final.jar, /Users/.../.m2/repository/io/netty/netty-common/4.1.74.Final/netty-common-4.1.74.Final.jar, /Users/.../.m2/repository/io/prometheus/simpleclient_common/0.8.1/simpleclient_common-0.8.1.jar, /Users/.../.m2/repository/com/google/api/grpc/proto-google-common-protos/1.12.0/proto-google-common-protos-1.12.0.jar, /Users/.../.m2/repository/com/google/protobuf/protobuf-java/3.19.2/protobuf-java-3.19.2.jar, /Users/.../.m2/repository/io/grpc/grpc-context/1.14.0/grpc-context-1.14.0.jar, /Users/.../.m2/repository/commons-codec/commons-codec/1.11/commons-codec-1.11.jar, /Users/.../.m2/repository/com/google/errorprone/error_prone_annotations/2.3.4/error_prone_annotations-2.3.4.jar, /Users/.../.m2/repository/io/prometheus/simpleclient/0.8.1/simpleclient-0.8.1.jar, /Users/.../.m2/repository/org/eclipse/jetty/jetty-servlet/9.4.45.v20220203/jetty-servlet-9.4.45.v20220203.jar, /Users/.../.m2/repository/org/eclipse/jetty/jetty-security/9.4.45.v20220203/jetty-security-9.4.45.v20220203.jar, /Users/.../.m2/repository/org/eclipse/jetty/jetty-util-ajax/9.4.45.v20220203/jetty-util-ajax-9.4.45.v20220203.jar, /Users/.../.m2/repository/com/squareup/okio/okio/1.6.0/okio-1.6.0.jar, /Users/.../.m2/repository/io/prometheus/simpleclient_hotspot/0.8.1/simpleclient_hotspot-0.8.1.jar, /Users/.../.m2/repository/io/swagger/swagger-annotations/1.5.21/swagger-annotations-1.5.21.jar, /Users/.../.m2/repository/io/grpc/grpc-protobuf-lite/1.19.0/grpc-protobuf-lite-1.19.0.jar, /Users/.../.m2/repository/io/grpc/grpc-core/1.19.0/grpc-core-1.19.0.jar, /Users/.../.m2/repository/io/opencensus/opencensus-api/0.19.2/opencensus-api-0.19.2.jar, /Users/.../.m2/repository/io/opencensus/opencensus-contrib-grpc-metrics/0.19.2/opencensus-contrib-grpc-metrics-0.19.2.jar, /Users/.../.m2/repository/com/google/protobuf/protobuf-lite/3.0.1/protobuf-lite-3.0.1.jar, /Users/.../.m2/repository/org/apache/commons/commons-collections4/4.1/commons-collections4-4.1.jar, /Users/.../.m2/repository/javax/annotation/javax.annotation-api/1.2/javax.annotation-api-1.2.jar, /Users/.../.m2/repository/org/codehaus/mojo/animal-sniffer-annotations/1.17/animal-sniffer-annotations-1.17.jar, /Users/.../.m2/repository/com/github/ben-manes/caffeine/caffeine/2.6.2/caffeine-2.6.2.jar, /Users/.../.m2/repository/io/netty/netty-codec-socks/4.1.74.Final/netty-codec-socks-4.1.74.Final.jar, /Users/.../.m2/repository/io/netty/netty-buffer/4.1.74.Final/netty-buffer-4.1.74.Final.jar, /Users/.../.m2/repository/io/netty/netty-transport/4.1.74.Final/netty-transport-4.1.74.Final.jar, /Users/.../.m2/repository/io/netty/netty-codec/4.1.74.Final/netty-codec-4.1.74.Final.jar, /Users/.../.m2/repository/org/bouncycastle/bcpkix-jdk15to18/1.68/bcpkix-jdk15to18-1.68.jar, /Users/.../.m2/repository/org/bouncycastle/bcprov-ext-jdk15to18/1.68/bcprov-ext-jdk15to18-1.68.jar, /Users/.../.m2/repository/org/bouncycastle/bcprov-jdk15to18/1.68/bcprov-jdk15to18-1.68.jar, /Users/.../.m2/repository/org/apache/pinot/pinot-spi/0.11.0-SNAPSHOT/pinot-spi-0.11.0-SNAPSHOT.jar, /Users/.../.m2/repository/commons-configuration/commons-configuration/1.10/commons-configuration-1.10.jar, /Users/.../.m2/repository/commons-io/commons-io/2.11.0/commons-io-2.11.0.jar, /Users/.../.m2/repository/commons-lang/commons-lang/2.6/commons-lang-2.6.jar, /Users/.../.m2/repository/commons-logging/commons-logging/1.2/commons-logging-1.2.jar, /Users/.../.m2/repository/commons-collections/commons-collections/3.2.2/commons-collections-3.2.2.jar, /Users/.../.m2/repository/com/google/code/findbugs/jsr305/3.0.0/jsr305-3.0.0.jar, /Users/.../.m2/repository/org/apache/logging/log4j/log4j-slf4j-impl/2.17.1/log4j-slf4j-impl-2.17.1.jar, /Users/.../.m2/repository/org/apache/logging/log4j/log4j-api/2.17.1/log4j-api-2.17.1.jar, /Users/.../.m2/repository/com/lmax/disruptor/3.3.4/disruptor-3.3.4.jar, /Users/.../.m2/repository/org/apache/logging/log4j/log4j-1.2-api/2.17.1/log4j-1.2-api-2.17.1.jar, /Users/.../.m2/repository/joda-time/joda-time/2.10.5/joda-time-2.10.5.jar, /Users/.../.m2/repository/com/fasterxml/jackson/core/jackson-annotations/2.10.0/jackson-annotations-2.10.0.jar, /Users/.../.m2/repository/org/yaml/snakeyaml/1.30/snakeyaml-1.30.jar, /Users/.../.m2/repository/com/fasterxml/jackson/core/jackson-databind/2.10.0/jackson-databind-2.10.0.jar, /Users/.../.m2/repository/org/codehaus/groovy/groovy-all/2.4.21/groovy-all-2.4.21.jar, /Users/.../.m2/repository/org/reflections/reflections/0.9.9/reflections-0.9.9.jar, /Users/.../.m2/repository/com/google/code/findbugs/annotations/2.0.1/annotations-2.0.1.jar]
[DEBUG]   (f) compileSourceRoots = [/Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/src/main/java]
[DEBUG]   (f) compilerId = javac
[DEBUG]   (f) debug = true
[DEBUG]   (f) encoding = UTF-8
[DEBUG]   (f) failOnError = true
[DEBUG]   (f) failOnWarning = false
[DEBUG]   (f) forceJavacCompilerUse = false
[DEBUG]   (f) fork = true
[DEBUG]   (f) generatedSourcesDirectory = /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/generated-sources/annotations
[DEBUG]   (f) mojoExecution = org.apache.maven.plugins:maven-compiler-plugin:3.8.0:compile {execution: default-compile}
[DEBUG]   (f) optimize = false
[DEBUG]   (f) outputDirectory = /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/classes
[DEBUG]   (f) parameters = false
[DEBUG]   (f) project = MavenProject: org.apache.pinot:pinot-pulsar:0.11.0-SNAPSHOT @ /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/pom.xml
[DEBUG]   (f) projectArtifact = org.apache.pinot:pinot-pulsar:jar:0.11.0-SNAPSHOT
[DEBUG]   (s) release = 11
[DEBUG]   (f) session = org.apache.maven.execution.MavenSession@53d6e959
[DEBUG]   (f) showDeprecation = false
[DEBUG]   (f) showWarnings = false
[DEBUG]   (f) skipMultiThreadWarning = false
[DEBUG]   (f) source = 11
[DEBUG]   (f) staleMillis = 0
[DEBUG]   (s) target = 11
[DEBUG]   (f) useIncrementalCompilation = true
[DEBUG]   (f) verbose = false
[DEBUG] -- end configuration --
[DEBUG] Using compiler 'javac'.
[DEBUG] Adding /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/generated-sources/annotations to compile source roots:
  /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/src/main/java
[DEBUG] New compile source roots:
  /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/src/main/java
  /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/generated-sources/annotations
[DEBUG] CompilerReuseStrategy: reuseCreated
[DEBUG] useIncrementalCompilation enabled
[DEBUG] Stale source detected: /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/src/main/java/org/apache/pinot/plugin/stream/pulsar/PulsarConsumerFactory.java
[DEBUG] Stale source detected: /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/src/main/java/org/apache/pinot/plugin/stream/pulsar/PulsarStreamMetadataProvider.java
[DEBUG] Stale source detected: /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/src/main/java/org/apache/pinot/plugin/stream/pulsar/PulsarStreamLevelConsumerManager.java
[DEBUG] Stale source detected: /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/src/main/java/org/apache/pinot/plugin/stream/pulsar/PulsarPartitionLevelConsumer.java
[DEBUG] Stale source detected: /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/src/main/java/org/apache/pinot/plugin/stream/pulsar/PulsarConfig.java
[DEBUG] Stale source detected: /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/src/main/java/org/apache/pinot/plugin/stream/pulsar/PulsarStreamLevelConsumer.java
[DEBUG] Stale source detected: /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/src/main/java/org/apache/pinot/plugin/stream/pulsar/PulsarMessageBatch.java
[DEBUG] Stale source detected: /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/src/main/java/org/apache/pinot/plugin/stream/pulsar/MessageIdStreamOffset.java
[DEBUG] Stale source detected: /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/src/main/java/org/apache/pinot/plugin/stream/pulsar/PulsarUtils.java
[DEBUG] Stale source detected: /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/src/main/java/org/apache/pinot/plugin/stream/pulsar/PulsarPartitionLevelConnectionHandler.java
[DEBUG] Stale source detected: /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/src/main/java/org/apache/pinot/plugin/stream/pulsar/MessageIdStreamOffsetFactory.java
[INFO] Changes detected - recompiling the module!
[DEBUG] Classpath:
[DEBUG]  /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/classes
[DEBUG]  /Users/.../.m2/repository/org/eclipse/jetty/jetty-server/9.4.45.v20220203/jetty-server-9.4.45.v20220203.jar
[DEBUG]  /Users/.../.m2/repository/org/eclipse/jetty/jetty-http/9.4.45.v20220203/jetty-http-9.4.45.v20220203.jar
[DEBUG]  /Users/.../.m2/repository/org/eclipse/jetty/jetty-util/9.4.45.v20220203/jetty-util-9.4.45.v20220203.jar
[DEBUG]  /Users/.../.m2/repository/org/eclipse/jetty/jetty-io/9.4.45.v20220203/jetty-io-9.4.45.v20220203.jar
[DEBUG]  /Users/.../.m2/repository/org/apache/commons/commons-compress/1.21/commons-compress-1.21.jar
[DEBUG]  /Users/.../.m2/repository/org/apache/pulsar/pulsar-client-original/2.7.2/pulsar-client-original-2.7.2.jar
[DEBUG]  /Users/.../.m2/repository/org/apache/pulsar/pulsar-client-api/2.7.2/pulsar-client-api-2.7.2.jar
[DEBUG]  /Users/.../.m2/repository/org/apache/pulsar/pulsar-common/2.7.2/pulsar-common-2.7.2.jar
[DEBUG]  /Users/.../.m2/repository/org/apache/pulsar/protobuf-shaded/2.1.0-incubating/protobuf-shaded-2.1.0-incubating.jar
[DEBUG]  /Users/.../.m2/repository/io/netty/netty-handler/4.1.74.Final/netty-handler-4.1.74.Final.jar
[DEBUG]  /Users/.../.m2/repository/io/netty/netty-tcnative-classes/2.0.48.Final/netty-tcnative-classes-2.0.48.Final.jar
[DEBUG]  /Users/.../.m2/repository/io/netty/netty-transport-native-epoll/4.1.74.Final/netty-transport-native-epoll-4.1.74.Final-linux-x86_64.jar
[DEBUG]  /Users/.../.m2/repository/io/netty/netty-transport-classes-epoll/4.1.74.Final/netty-transport-classes-epoll-4.1.74.Final.jar
[DEBUG]  /Users/.../.m2/repository/org/apache/bookkeeper/bookkeeper-common-allocator/4.12.0/bookkeeper-common-allocator-4.12.0.jar
[DEBUG]  /Users/.../.m2/repository/io/airlift/aircompressor/0.16/aircompressor-0.16.jar
[DEBUG]  /Users/.../.m2/repository/org/apache/bookkeeper/circe-checksum/4.12.0/circe-checksum-4.12.0.jar
[DEBUG]  /Users/.../.m2/repository/io/netty/netty-tcnative-boringssl-static/2.0.48.Final/netty-tcnative-boringssl-static-2.0.48.Final.jar
[DEBUG]  /Users/.../.m2/repository/io/netty/netty-codec-haproxy/4.1.74.Final/netty-codec-haproxy-4.1.74.Final.jar
[DEBUG]  /Users/.../.m2/repository/com/fasterxml/jackson/dataformat/jackson-dataformat-yaml/2.10.0/jackson-dataformat-yaml-2.10.0.jar
[DEBUG]  /Users/.../.m2/repository/org/apache/pulsar/pulsar-transaction-common/2.7.2/pulsar-transaction-common-2.7.2.jar
[DEBUG]  /Users/.../.m2/repository/com/google/protobuf/protobuf-java-util/3.11.4/protobuf-java-util-3.11.4.jar
[DEBUG]  /Users/.../.m2/repository/org/apache/pulsar/bouncy-castle-bc/2.7.2/bouncy-castle-bc-2.7.2-pkg.jar
[DEBUG]  /Users/.../.m2/repository/io/netty/netty-codec-http/4.1.74.Final/netty-codec-http-4.1.74.Final.jar
[DEBUG]  /Users/.../.m2/repository/io/netty/netty-resolver-dns/4.1.74.Final/netty-resolver-dns-4.1.74.Final.jar
[DEBUG]  /Users/.../.m2/repository/io/netty/netty-codec-dns/4.1.74.Final/netty-codec-dns-4.1.74.Final.jar
[DEBUG]  /Users/.../.m2/repository/org/apache/commons/commons-lang3/3.5/commons-lang3-3.5.jar
[DEBUG]  /Users/.../.m2/repository/org/asynchttpclient/async-http-client/2.12.3/async-http-client-2.12.3.jar
[DEBUG]  /Users/.../.m2/repository/org/asynchttpclient/async-http-client-netty-utils/2.12.3/async-http-client-netty-utils-2.12.3.jar
[DEBUG]  /Users/.../.m2/repository/org/reactivestreams/reactive-streams/1.0.3/reactive-streams-1.0.3.jar
[DEBUG]  /Users/.../.m2/repository/com/typesafe/netty/netty-reactive-streams/2.0.4/netty-reactive-streams-2.0.4.jar
[DEBUG]  /Users/.../.m2/repository/com/sun/activation/jakarta.activation/1.2.2/jakarta.activation-1.2.2.jar
[DEBUG]  /Users/.../.m2/repository/org/slf4j/slf4j-api/1.7.25/slf4j-api-1.7.25.jar
[DEBUG]  /Users/.../.m2/repository/com/yahoo/datasketches/sketches-core/0.8.3/sketches-core-0.8.3.jar
[DEBUG]  /Users/.../.m2/repository/com/yahoo/datasketches/memory/0.8.3/memory-0.8.3.jar
[DEBUG]  /Users/.../.m2/repository/com/google/code/gson/gson/2.2.4/gson-2.2.4.jar
[DEBUG]  /Users/.../.m2/repository/org/apache/avro/avro/1.9.2/avro-1.9.2.jar
[DEBUG]  /Users/.../.m2/repository/com/fasterxml/jackson/core/jackson-core/2.10.0/jackson-core-2.10.0.jar
[DEBUG]  /Users/.../.m2/repository/org/apache/avro/avro-protobuf/1.9.1/avro-protobuf-1.9.1.jar
[DEBUG]  /Users/.../.m2/repository/com/fasterxml/jackson/module/jackson-module-jsonSchema/2.11.1/jackson-module-jsonSchema-2.11.1.jar
[DEBUG]  /Users/.../.m2/repository/javax/validation/validation-api/2.0.1.Final/validation-api-2.0.1.Final.jar
[DEBUG]  /Users/.../.m2/repository/net/jcip/jcip-annotations/1.0/jcip-annotations-1.0.jar
[DEBUG]  /Users/.../.m2/repository/org/apache/pulsar/pulsar-client-admin-original/2.7.2/pulsar-client-admin-original-2.7.2.jar
[DEBUG]  /Users/.../.m2/repository/org/glassfish/jersey/core/jersey-client/2.35/jersey-client-2.35.jar
[DEBUG]  /Users/.../.m2/repository/org/glassfish/jersey/media/jersey-media-json-jackson/2.35/jersey-media-json-jackson-2.35.jar
[DEBUG]  /Users/.../.m2/repository/org/glassfish/jersey/ext/jersey-entity-filtering/2.35/jersey-entity-filtering-2.35.jar
[DEBUG]  /Users/.../.m2/repository/com/fasterxml/jackson/module/jackson-module-jaxb-annotations/2.10.0/jackson-module-jaxb-annotations-2.10.0.jar
[DEBUG]  /Users/.../.m2/repository/jakarta/xml/bind/jakarta.xml.bind-api/2.3.2/jakarta.xml.bind-api-2.3.2.jar
[DEBUG]  /Users/.../.m2/repository/jakarta/activation/jakarta.activation-api/1.2.1/jakarta.activation-api-1.2.1.jar
[DEBUG]  /Users/.../.m2/repository/org/glassfish/jersey/media/jersey-media-multipart/2.35/jersey-media-multipart-2.35.jar
[DEBUG]  /Users/.../.m2/repository/org/jvnet/mimepull/mimepull/1.9.13/mimepull-1.9.13.jar
[DEBUG]  /Users/.../.m2/repository/com/fasterxml/jackson/jaxrs/jackson-jaxrs-json-provider/2.10.0/jackson-jaxrs-json-provider-2.10.0.jar
[DEBUG]  /Users/.../.m2/repository/com/fasterxml/jackson/jaxrs/jackson-jaxrs-base/2.10.0/jackson-jaxrs-base-2.10.0.jar
[DEBUG]  /Users/.../.m2/repository/org/glassfish/jersey/inject/jersey-hk2/2.35/jersey-hk2-2.35.jar
[DEBUG]  /Users/.../.m2/repository/org/glassfish/hk2/hk2-locator/2.6.1/hk2-locator-2.6.1.jar
[DEBUG]  /Users/.../.m2/repository/org/glassfish/hk2/external/aopalliance-repackaged/2.6.1/aopalliance-repackaged-2.6.1.jar
[DEBUG]  /Users/.../.m2/repository/org/glassfish/hk2/hk2-api/2.6.1/hk2-api-2.6.1.jar
[DEBUG]  /Users/.../.m2/repository/org/glassfish/hk2/hk2-utils/2.6.1/hk2-utils-2.6.1.jar
[DEBUG]  /Users/.../.m2/repository/org/javassist/javassist/3.19.0-GA/javassist-3.19.0-GA.jar
[DEBUG]  /Users/.../.m2/repository/javax/xml/bind/jaxb-api/2.3.0/jaxb-api-2.3.0.jar
[DEBUG]  /Users/.../.m2/repository/org/slf4j/jul-to-slf4j/1.7.25/jul-to-slf4j-1.7.25.jar
[DEBUG]  /Users/.../.m2/repository/com/google/guava/guava/20.0/guava-20.0.jar
[DEBUG]  /Users/.../.m2/repository/javax/servlet/javax.servlet-api/3.1.0/javax.servlet-api-3.1.0.jar
[DEBUG]  /Users/.../.m2/repository/javax/ws/rs/javax.ws.rs-api/2.1/javax.ws.rs-api-2.1.jar
[DEBUG]  /Users/.../.m2/repository/org/glassfish/jersey/containers/jersey-container-grizzly2-http/2.35/jersey-container-grizzly2-http-2.35.jar
[DEBUG]  /Users/.../.m2/repository/org/glassfish/hk2/external/jakarta.inject/2.6.1/jakarta.inject-2.6.1.jar
[DEBUG]  /Users/.../.m2/repository/org/glassfish/grizzly/grizzly-http-server/2.4.4/grizzly-http-server-2.4.4.jar
[DEBUG]  /Users/.../.m2/repository/org/glassfish/grizzly/grizzly-http/2.4.4/grizzly-http-2.4.4.jar
[DEBUG]  /Users/.../.m2/repository/org/glassfish/grizzly/grizzly-framework/2.4.4/grizzly-framework-2.4.4.jar
[DEBUG]  /Users/.../.m2/repository/org/glassfish/jersey/core/jersey-common/2.35/jersey-common-2.35.jar
[DEBUG]  /Users/.../.m2/repository/org/glassfish/hk2/osgi-resource-locator/1.0.3/osgi-resource-locator-1.0.3.jar
[DEBUG]  /Users/.../.m2/repository/jakarta/ws/rs/jakarta.ws.rs-api/2.1.6/jakarta.ws.rs-api-2.1.6.jar
[DEBUG]  /Users/.../.m2/repository/org/glassfish/jersey/core/jersey-server/2.35/jersey-server-2.35.jar
[DEBUG]  /Users/.../.m2/repository/jakarta/annotation/jakarta.annotation-api/1.3.5/jakarta.annotation-api-1.3.5.jar
[DEBUG]  /Users/.../.m2/repository/jakarta/validation/jakarta.validation-api/2.0.2/jakarta.validation-api-2.0.2.jar
[DEBUG]  /Users/.../.m2/repository/org/glassfish/jersey/containers/jersey-container-servlet-core/2.35/jersey-container-servlet-core-2.35.jar
[DEBUG]  /Users/.../.m2/repository/io/netty/netty-resolver/4.1.74.Final/netty-resolver-4.1.74.Final.jar
[DEBUG]  /Users/.../.m2/repository/io/netty/netty-common/4.1.74.Final/netty-common-4.1.74.Final.jar
[DEBUG]  /Users/.../.m2/repository/io/prometheus/simpleclient_common/0.8.1/simpleclient_common-0.8.1.jar
[DEBUG]  /Users/.../.m2/repository/com/google/api/grpc/proto-google-common-protos/1.12.0/proto-google-common-protos-1.12.0.jar
[DEBUG]  /Users/.../.m2/repository/com/google/protobuf/protobuf-java/3.19.2/protobuf-java-3.19.2.jar
[DEBUG]  /Users/.../.m2/repository/io/grpc/grpc-context/1.14.0/grpc-context-1.14.0.jar
[DEBUG]  /Users/.../.m2/repository/commons-codec/commons-codec/1.11/commons-codec-1.11.jar
[DEBUG]  /Users/.../.m2/repository/com/google/errorprone/error_prone_annotations/2.3.4/error_prone_annotations-2.3.4.jar
[DEBUG]  /Users/.../.m2/repository/io/prometheus/simpleclient/0.8.1/simpleclient-0.8.1.jar
[DEBUG]  /Users/.../.m2/repository/org/eclipse/jetty/jetty-servlet/9.4.45.v20220203/jetty-servlet-9.4.45.v20220203.jar
[DEBUG]  /Users/.../.m2/repository/org/eclipse/jetty/jetty-security/9.4.45.v20220203/jetty-security-9.4.45.v20220203.jar
[DEBUG]  /Users/.../.m2/repository/org/eclipse/jetty/jetty-util-ajax/9.4.45.v20220203/jetty-util-ajax-9.4.45.v20220203.jar
[DEBUG]  /Users/.../.m2/repository/com/squareup/okio/okio/1.6.0/okio-1.6.0.jar
[DEBUG]  /Users/.../.m2/repository/io/prometheus/simpleclient_hotspot/0.8.1/simpleclient_hotspot-0.8.1.jar
[DEBUG]  /Users/.../.m2/repository/io/swagger/swagger-annotations/1.5.21/swagger-annotations-1.5.21.jar
[DEBUG]  /Users/.../.m2/repository/io/grpc/grpc-protobuf-lite/1.19.0/grpc-protobuf-lite-1.19.0.jar
[DEBUG]  /Users/.../.m2/repository/io/grpc/grpc-core/1.19.0/grpc-core-1.19.0.jar
[DEBUG]  /Users/.../.m2/repository/io/opencensus/opencensus-api/0.19.2/opencensus-api-0.19.2.jar
[DEBUG]  /Users/.../.m2/repository/io/opencensus/opencensus-contrib-grpc-metrics/0.19.2/opencensus-contrib-grpc-metrics-0.19.2.jar
[DEBUG]  /Users/.../.m2/repository/com/google/protobuf/protobuf-lite/3.0.1/protobuf-lite-3.0.1.jar
[DEBUG]  /Users/.../.m2/repository/org/apache/commons/commons-collections4/4.1/commons-collections4-4.1.jar
[DEBUG]  /Users/.../.m2/repository/javax/annotation/javax.annotation-api/1.2/javax.annotation-api-1.2.jar
[DEBUG]  /Users/.../.m2/repository/org/codehaus/mojo/animal-sniffer-annotations/1.17/animal-sniffer-annotations-1.17.jar
[DEBUG]  /Users/.../.m2/repository/com/github/ben-manes/caffeine/caffeine/2.6.2/caffeine-2.6.2.jar
[DEBUG]  /Users/.../.m2/repository/io/netty/netty-codec-socks/4.1.74.Final/netty-codec-socks-4.1.74.Final.jar
[DEBUG]  /Users/.../.m2/repository/io/netty/netty-buffer/4.1.74.Final/netty-buffer-4.1.74.Final.jar
[DEBUG]  /Users/.../.m2/repository/io/netty/netty-transport/4.1.74.Final/netty-transport-4.1.74.Final.jar
[DEBUG]  /Users/.../.m2/repository/io/netty/netty-codec/4.1.74.Final/netty-codec-4.1.74.Final.jar
[DEBUG]  /Users/.../.m2/repository/org/bouncycastle/bcpkix-jdk15to18/1.68/bcpkix-jdk15to18-1.68.jar
[DEBUG]  /Users/.../.m2/repository/org/bouncycastle/bcprov-ext-jdk15to18/1.68/bcprov-ext-jdk15to18-1.68.jar
[DEBUG]  /Users/.../.m2/repository/org/bouncycastle/bcprov-jdk15to18/1.68/bcprov-jdk15to18-1.68.jar
[DEBUG]  /Users/.../.m2/repository/org/apache/pinot/pinot-spi/0.11.0-SNAPSHOT/pinot-spi-0.11.0-SNAPSHOT.jar
[DEBUG]  /Users/.../.m2/repository/commons-configuration/commons-configuration/1.10/commons-configuration-1.10.jar
[DEBUG]  /Users/.../.m2/repository/commons-io/commons-io/2.11.0/commons-io-2.11.0.jar
[DEBUG]  /Users/.../.m2/repository/commons-lang/commons-lang/2.6/commons-lang-2.6.jar
[DEBUG]  /Users/.../.m2/repository/commons-logging/commons-logging/1.2/commons-logging-1.2.jar
[DEBUG]  /Users/.../.m2/repository/commons-collections/commons-collections/3.2.2/commons-collections-3.2.2.jar
[DEBUG]  /Users/.../.m2/repository/com/google/code/findbugs/jsr305/3.0.0/jsr305-3.0.0.jar
[DEBUG]  /Users/.../.m2/repository/org/apache/logging/log4j/log4j-slf4j-impl/2.17.1/log4j-slf4j-impl-2.17.1.jar
[DEBUG]  /Users/.../.m2/repository/org/apache/logging/log4j/log4j-api/2.17.1/log4j-api-2.17.1.jar
[DEBUG]  /Users/.../.m2/repository/com/lmax/disruptor/3.3.4/disruptor-3.3.4.jar
[DEBUG]  /Users/.../.m2/repository/org/apache/logging/log4j/log4j-1.2-api/2.17.1/log4j-1.2-api-2.17.1.jar
[DEBUG]  /Users/.../.m2/repository/joda-time/joda-time/2.10.5/joda-time-2.10.5.jar
[DEBUG]  /Users/.../.m2/repository/com/fasterxml/jackson/core/jackson-annotations/2.10.0/jackson-annotations-2.10.0.jar
[DEBUG]  /Users/.../.m2/repository/org/yaml/snakeyaml/1.30/snakeyaml-1.30.jar
[DEBUG]  /Users/.../.m2/repository/com/fasterxml/jackson/core/jackson-databind/2.10.0/jackson-databind-2.10.0.jar
[DEBUG]  /Users/.../.m2/repository/org/codehaus/groovy/groovy-all/2.4.21/groovy-all-2.4.21.jar
[DEBUG]  /Users/.../.m2/repository/org/reflections/reflections/0.9.9/reflections-0.9.9.jar
[DEBUG]  /Users/.../.m2/repository/com/google/code/findbugs/annotations/2.0.1/annotations-2.0.1.jar
[DEBUG] Source roots:
[DEBUG]  /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/src/main/java
[DEBUG]  /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/generated-sources/annotations
[DEBUG] Command line options:
[DEBUG] -d /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/classes -classpath /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/classes:/Users/.../.m2/repository/org/eclipse/jetty/jetty-server/9.4.45.v20220203/jetty-server-9.4.45.v20220203.jar:/Users/.../.m2/repository/org/eclipse/jetty/jetty-http/9.4.45.v20220203/jetty-http-9.4.45.v20220203.jar:/Users/.../.m2/repository/org/eclipse/jetty/jetty-util/9.4.45.v20220203/jetty-util-9.4.45.v20220203.jar:/Users/.../.m2/repository/org/eclipse/jetty/jetty-io/9.4.45.v20220203/jetty-io-9.4.45.v20220203.jar:/Users/.../.m2/repository/org/apache/commons/commons-compress/1.21/commons-compress-1.21.jar:/Users/.../.m2/repository/org/apache/pulsar/pulsar-client-original/2.7.2/pulsar-client-original-2.7.2.jar:/Users/.../.m2/repository/org/apache/pulsar/pulsar-client-api/2.7.2/pulsar-client-api-2.7.2.jar:/Users/.../.m2/repository/org/apache/pulsar/pulsar-common/2.7.2/pulsar-common-2.7.2.jar:/Users/.../.m2/repository/org/apache/pulsar/protobuf-shaded/2.1.0-incubating/protobuf-shaded-2.1.0-incubating.jar:/Users/.../.m2/repository/io/netty/netty-handler/4.1.74.Final/netty-handler-4.1.74.Final.jar:/Users/.../.m2/repository/io/netty/netty-tcnative-classes/2.0.48.Final/netty-tcnative-classes-2.0.48.Final.jar:/Users/.../.m2/repository/io/netty/netty-transport-native-epoll/4.1.74.Final/netty-transport-native-epoll-4.1.74.Final-linux-x86_64.jar:/Users/.../.m2/repository/io/netty/netty-transport-classes-epoll/4.1.74.Final/netty-transport-classes-epoll-4.1.74.Final.jar:/Users/.../.m2/repository/org/apache/bookkeeper/bookkeeper-common-allocator/4.12.0/bookkeeper-common-allocator-4.12.0.jar:/Users/.../.m2/repository/io/airlift/aircompressor/0.16/aircompressor-0.16.jar:/Users/.../.m2/repository/org/apache/bookkeeper/circe-checksum/4.12.0/circe-checksum-4.12.0.jar:/Users/.../.m2/repository/io/netty/netty-tcnative-boringssl-static/2.0.48.Final/netty-tcnative-boringssl-static-2.0.48.Final.jar:/Users/.../.m2/repository/io/netty/netty-codec-haproxy/4.1.74.Final/netty-codec-haproxy-4.1.74.Final.jar:/Users/.../.m2/repository/com/fasterxml/jackson/dataformat/jackson-dataformat-yaml/2.10.0/jackson-dataformat-yaml-2.10.0.jar:/Users/.../.m2/repository/org/apache/pulsar/pulsar-transaction-common/2.7.2/pulsar-transaction-common-2.7.2.jar:/Users/.../.m2/repository/com/google/protobuf/protobuf-java-util/3.11.4/protobuf-java-util-3.11.4.jar:/Users/.../.m2/repository/org/apache/pulsar/bouncy-castle-bc/2.7.2/bouncy-castle-bc-2.7.2-pkg.jar:/Users/.../.m2/repository/io/netty/netty-codec-http/4.1.74.Final/netty-codec-http-4.1.74.Final.jar:/Users/.../.m2/repository/io/netty/netty-resolver-dns/4.1.74.Final/netty-resolver-dns-4.1.74.Final.jar:/Users/.../.m2/repository/io/netty/netty-codec-dns/4.1.74.Final/netty-codec-dns-4.1.74.Final.jar:/Users/.../.m2/repository/org/apache/commons/commons-lang3/3.5/commons-lang3-3.5.jar:/Users/.../.m2/repository/org/asynchttpclient/async-http-client/2.12.3/async-http-client-2.12.3.jar:/Users/.../.m2/repository/org/asynchttpclient/async-http-client-netty-utils/2.12.3/async-http-client-netty-utils-2.12.3.jar:/Users/.../.m2/repository/org/reactivestreams/reactive-streams/1.0.3/reactive-streams-1.0.3.jar:/Users/.../.m2/repository/com/typesafe/netty/netty-reactive-streams/2.0.4/netty-reactive-streams-2.0.4.jar:/Users/.../.m2/repository/com/sun/activation/jakarta.activation/1.2.2/jakarta.activation-1.2.2.jar:/Users/.../.m2/repository/org/slf4j/slf4j-api/1.7.25/slf4j-api-1.7.25.jar:/Users/.../.m2/repository/com/yahoo/datasketches/sketches-core/0.8.3/sketches-core-0.8.3.jar:/Users/.../.m2/repository/com/yahoo/datasketches/memory/0.8.3/memory-0.8.3.jar:/Users/.../.m2/repository/com/google/code/gson/gson/2.2.4/gson-2.2.4.jar:/Users/.../.m2/repository/org/apache/avro/avro/1.9.2/avro-1.9.2.jar:/Users/.../.m2/repository/com/fasterxml/jackson/core/jackson-core/2.10.0/jackson-core-2.10.0.jar:/Users/.../.m2/repository/org/apache/avro/avro-protobuf/1.9.1/avro-protobuf-1.9.1.jar:/Users/.../.m2/repository/com/fasterxml/jackson/module/jackson-module-jsonSchema/2.11.1/jackson-module-jsonSchema-2.11.1.jar:/Users/.../.m2/repository/javax/validation/validation-api/2.0.1.Final/validation-api-2.0.1.Final.jar:/Users/.../.m2/repository/net/jcip/jcip-annotations/1.0/jcip-annotations-1.0.jar:/Users/.../.m2/repository/org/apache/pulsar/pulsar-client-admin-original/2.7.2/pulsar-client-admin-original-2.7.2.jar:/Users/.../.m2/repository/org/glassfish/jersey/core/jersey-client/2.35/jersey-client-2.35.jar:/Users/.../.m2/repository/org/glassfish/jersey/media/jersey-media-json-jackson/2.35/jersey-media-json-jackson-2.35.jar:/Users/.../.m2/repository/org/glassfish/jersey/ext/jersey-entity-filtering/2.35/jersey-entity-filtering-2.35.jar:/Users/.../.m2/repository/com/fasterxml/jackson/module/jackson-module-jaxb-annotations/2.10.0/jackson-module-jaxb-annotations-2.10.0.jar:/Users/.../.m2/repository/jakarta/xml/bind/jakarta.xml.bind-api/2.3.2/jakarta.xml.bind-api-2.3.2.jar:/Users/.../.m2/repository/jakarta/activation/jakarta.activation-api/1.2.1/jakarta.activation-api-1.2.1.jar:/Users/.../.m2/repository/org/glassfish/jersey/media/jersey-media-multipart/2.35/jersey-media-multipart-2.35.jar:/Users/.../.m2/repository/org/jvnet/mimepull/mimepull/1.9.13/mimepull-1.9.13.jar:/Users/.../.m2/repository/com/fasterxml/jackson/jaxrs/jackson-jaxrs-json-provider/2.10.0/jackson-jaxrs-json-provider-2.10.0.jar:/Users/.../.m2/repository/com/fasterxml/jackson/jaxrs/jackson-jaxrs-base/2.10.0/jackson-jaxrs-base-2.10.0.jar:/Users/.../.m2/repository/org/glassfish/jersey/inject/jersey-hk2/2.35/jersey-hk2-2.35.jar:/Users/.../.m2/repository/org/glassfish/hk2/hk2-locator/2.6.1/hk2-locator-2.6.1.jar:/Users/.../.m2/repository/org/glassfish/hk2/external/aopalliance-repackaged/2.6.1/aopalliance-repackaged-2.6.1.jar:/Users/.../.m2/repository/org/glassfish/hk2/hk2-api/2.6.1/hk2-api-2.6.1.jar:/Users/.../.m2/repository/org/glassfish/hk2/hk2-utils/2.6.1/hk2-utils-2.6.1.jar:/Users/.../.m2/repository/org/javassist/javassist/3.19.0-GA/javassist-3.19.0-GA.jar:/Users/.../.m2/repository/javax/xml/bind/jaxb-api/2.3.0/jaxb-api-2.3.0.jar:/Users/.../.m2/repository/org/slf4j/jul-to-slf4j/1.7.25/jul-to-slf4j-1.7.25.jar:/Users/.../.m2/repository/com/google/guava/guava/20.0/guava-20.0.jar:/Users/.../.m2/repository/javax/servlet/javax.servlet-api/3.1.0/javax.servlet-api-3.1.0.jar:/Users/.../.m2/repository/javax/ws/rs/javax.ws.rs-api/2.1/javax.ws.rs-api-2.1.jar:/Users/.../.m2/repository/org/glassfish/jersey/containers/jersey-container-grizzly2-http/2.35/jersey-container-grizzly2-http-2.35.jar:/Users/.../.m2/repository/org/glassfish/hk2/external/jakarta.inject/2.6.1/jakarta.inject-2.6.1.jar:/Users/.../.m2/repository/org/glassfish/grizzly/grizzly-http-server/2.4.4/grizzly-http-server-2.4.4.jar:/Users/.../.m2/repository/org/glassfish/grizzly/grizzly-http/2.4.4/grizzly-http-2.4.4.jar:/Users/.../.m2/repository/org/glassfish/grizzly/grizzly-framework/2.4.4/grizzly-framework-2.4.4.jar:/Users/.../.m2/repository/org/glassfish/jersey/core/jersey-common/2.35/jersey-common-2.35.jar:/Users/.../.m2/repository/org/glassfish/hk2/osgi-resource-locator/1.0.3/osgi-resource-locator-1.0.3.jar:/Users/.../.m2/repository/jakarta/ws/rs/jakarta.ws.rs-api/2.1.6/jakarta.ws.rs-api-2.1.6.jar:/Users/.../.m2/repository/org/glassfish/jersey/core/jersey-server/2.35/jersey-server-2.35.jar:/Users/.../.m2/repository/jakarta/annotation/jakarta.annotation-api/1.3.5/jakarta.annotation-api-1.3.5.jar:/Users/.../.m2/repository/jakarta/validation/jakarta.validation-api/2.0.2/jakarta.validation-api-2.0.2.jar:/Users/.../.m2/repository/org/glassfish/jersey/containers/jersey-container-servlet-core/2.35/jersey-container-servlet-core-2.35.jar:/Users/.../.m2/repository/io/netty/netty-resolver/4.1.74.Final/netty-resolver-4.1.74.Final.jar:/Users/.../.m2/repository/io/netty/netty-common/4.1.74.Final/netty-common-4.1.74.Final.jar:/Users/.../.m2/repository/io/prometheus/simpleclient_common/0.8.1/simpleclient_common-0.8.1.jar:/Users/.../.m2/repository/com/google/api/grpc/proto-google-common-protos/1.12.0/proto-google-common-protos-1.12.0.jar:/Users/.../.m2/repository/com/google/protobuf/protobuf-java/3.19.2/protobuf-java-3.19.2.jar:/Users/.../.m2/repository/io/grpc/grpc-context/1.14.0/grpc-context-1.14.0.jar:/Users/.../.m2/repository/commons-codec/commons-codec/1.11/commons-codec-1.11.jar:/Users/.../.m2/repository/com/google/errorprone/error_prone_annotations/2.3.4/error_prone_annotations-2.3.4.jar:/Users/.../.m2/repository/io/prometheus/simpleclient/0.8.1/simpleclient-0.8.1.jar:/Users/.../.m2/repository/org/eclipse/jetty/jetty-servlet/9.4.45.v20220203/jetty-servlet-9.4.45.v20220203.jar:/Users/.../.m2/repository/org/eclipse/jetty/jetty-security/9.4.45.v20220203/jetty-security-9.4.45.v20220203.jar:/Users/.../.m2/repository/org/eclipse/jetty/jetty-util-ajax/9.4.45.v20220203/jetty-util-ajax-9.4.45.v20220203.jar:/Users/.../.m2/repository/com/squareup/okio/okio/1.6.0/okio-1.6.0.jar:/Users/.../.m2/repository/io/prometheus/simpleclient_hotspot/0.8.1/simpleclient_hotspot-0.8.1.jar:/Users/.../.m2/repository/io/swagger/swagger-annotations/1.5.21/swagger-annotations-1.5.21.jar:/Users/.../.m2/repository/io/grpc/grpc-protobuf-lite/1.19.0/grpc-protobuf-lite-1.19.0.jar:/Users/.../.m2/repository/io/grpc/grpc-core/1.19.0/grpc-core-1.19.0.jar:/Users/.../.m2/repository/io/opencensus/opencensus-api/0.19.2/opencensus-api-0.19.2.jar:/Users/.../.m2/repository/io/opencensus/opencensus-contrib-grpc-metrics/0.19.2/opencensus-contrib-grpc-metrics-0.19.2.jar:/Users/.../.m2/repository/com/google/protobuf/protobuf-lite/3.0.1/protobuf-lite-3.0.1.jar:/Users/.../.m2/repository/org/apache/commons/commons-collections4/4.1/commons-collections4-4.1.jar:/Users/.../.m2/repository/javax/annotation/javax.annotation-api/1.2/javax.annotation-api-1.2.jar:/Users/.../.m2/repository/org/codehaus/mojo/animal-sniffer-annotations/1.17/animal-sniffer-annotations-1.17.jar:/Users/.../.m2/repository/com/github/ben-manes/caffeine/caffeine/2.6.2/caffeine-2.6.2.jar:/Users/.../.m2/repository/io/netty/netty-codec-socks/4.1.74.Final/netty-codec-socks-4.1.74.Final.jar:/Users/.../.m2/repository/io/netty/netty-buffer/4.1.74.Final/netty-buffer-4.1.74.Final.jar:/Users/.../.m2/repository/io/netty/netty-transport/4.1.74.Final/netty-transport-4.1.74.Final.jar:/Users/.../.m2/repository/io/netty/netty-codec/4.1.74.Final/netty-codec-4.1.74.Final.jar:/Users/.../.m2/repository/org/bouncycastle/bcpkix-jdk15to18/1.68/bcpkix-jdk15to18-1.68.jar:/Users/.../.m2/repository/org/bouncycastle/bcprov-ext-jdk15to18/1.68/bcprov-ext-jdk15to18-1.68.jar:/Users/.../.m2/repository/org/bouncycastle/bcprov-jdk15to18/1.68/bcprov-jdk15to18-1.68.jar:/Users/.../.m2/repository/org/apache/pinot/pinot-spi/0.11.0-SNAPSHOT/pinot-spi-0.11.0-SNAPSHOT.jar:/Users/.../.m2/repository/commons-configuration/commons-configuration/1.10/commons-configuration-1.10.jar:/Users/.../.m2/repository/commons-io/commons-io/2.11.0/commons-io-2.11.0.jar:/Users/.../.m2/repository/commons-lang/commons-lang/2.6/commons-lang-2.6.jar:/Users/.../.m2/repository/commons-logging/commons-logging/1.2/commons-logging-1.2.jar:/Users/.../.m2/repository/commons-collections/commons-collections/3.2.2/commons-collections-3.2.2.jar:/Users/.../.m2/repository/com/google/code/findbugs/jsr305/3.0.0/jsr305-3.0.0.jar:/Users/.../.m2/repository/org/apache/logging/log4j/log4j-slf4j-impl/2.17.1/log4j-slf4j-impl-2.17.1.jar:/Users/.../.m2/repository/org/apache/logging/log4j/log4j-api/2.17.1/log4j-api-2.17.1.jar:/Users/.../.m2/repository/com/lmax/disruptor/3.3.4/disruptor-3.3.4.jar:/Users/.../.m2/repository/org/apache/logging/log4j/log4j-1.2-api/2.17.1/log4j-1.2-api-2.17.1.jar:/Users/.../.m2/repository/joda-time/joda-time/2.10.5/joda-time-2.10.5.jar:/Users/.../.m2/repository/com/fasterxml/jackson/core/jackson-annotations/2.10.0/jackson-annotations-2.10.0.jar:/Users/.../.m2/repository/org/yaml/snakeyaml/1.30/snakeyaml-1.30.jar:/Users/.../.m2/repository/com/fasterxml/jackson/core/jackson-databind/2.10.0/jackson-databind-2.10.0.jar:/Users/.../.m2/repository/org/codehaus/groovy/groovy-all/2.4.21/groovy-all-2.4.21.jar:/Users/.../.m2/repository/org/reflections/reflections/0.9.9/reflections-0.9.9.jar:/Users/.../.m2/repository/com/google/code/findbugs/annotations/2.0.1/annotations-2.0.1.jar: -sourcepath /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/src/main/java:/Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/generated-sources/annotations: /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/src/main/java/org/apache/pinot/plugin/stream/pulsar/PulsarPartitionLevelConsumer.java /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/src/main/java/org/apache/pinot/plugin/stream/pulsar/PulsarConsumerFactory.java /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/src/main/java/org/apache/pinot/plugin/stream/pulsar/PulsarStreamMetadataProvider.java /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/src/main/java/org/apache/pinot/plugin/stream/pulsar/PulsarStreamLevelConsumerManager.java /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/src/main/java/org/apache/pinot/plugin/stream/pulsar/PulsarMessageBatch.java /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/src/main/java/org/apache/pinot/plugin/stream/pulsar/PulsarConfig.java /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/src/main/java/org/apache/pinot/plugin/stream/pulsar/PulsarStreamLevelConsumer.java /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/src/main/java/org/apache/pinot/plugin/stream/pulsar/PulsarUtils.java /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/src/main/java/org/apache/pinot/plugin/stream/pulsar/MessageIdStreamOffset.java /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/src/main/java/org/apache/pinot/plugin/stream/pulsar/MessageIdStreamOffsetFactory.java /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/src/main/java/org/apache/pinot/plugin/stream/pulsar/PulsarPartitionLevelConnectionHandler.java -s /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/generated-sources/annotations -g -nowarn --release 11 -encoding UTF-8
[DEBUG] incrementalBuildHelper#beforeRebuildExecution
[INFO] Compiling 11 source files to /Users/.../Downloads/pinot-0.11.0/pinot-plugins/pinot-stream-ingestion/pinot-pulsar/target/classes
[DEBUG] incrementalBuildHelper#afterRebuildExecution
[INFO] ------------------------------------------------------------------------
[INFO] BUILD FAILURE
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  14.325 s
[INFO] Finished at: 2022-06-28T11:30:06+08:00
[INFO] ------------------------------------------------------------------------
[WARNING] The requested profile "bin-dist" could not be activated because it does not exist.
[ERROR] Failed to execute goal org.apache.maven.plugins:maven-compiler-plugin:3.8.0:compile (default-compile) on project pinot-pulsar: Compilation failure -> [Help 1]
org.apache.maven.lifecycle.LifecycleExecutionException: Failed to execute goal org.apache.maven.plugins:maven-compiler-plugin:3.8.0:compile (default-compile) on project pinot-pulsar: Compilation failure
    at org.apache.maven.lifecycle.internal.MojoExecutor.execute (MojoExecutor.java:215)
    at org.apache.maven.lifecycle.internal.MojoExecutor.execute (MojoExecutor.java:156)
    at org.apache.maven.lifecycle.internal.MojoExecutor.execute (MojoExecutor.java:148)
    at org.apache.maven.lifecycle.internal.LifecycleModuleBuilder.buildProject (LifecycleModuleBuilder.java:117)
    at org.apache.maven.lifecycle.internal.LifecycleModuleBuilder.buildProject (LifecycleModuleBuilder.java:81)
    at org.apache.maven.lifecycle.internal.builder.singlethreaded.SingleThreadedBuilder.build (SingleThreadedBuilder.java:56)
    at org.apache.maven.lifecycle.internal.LifecycleStarter.execute (LifecycleStarter.java:128)
    at org.apache.maven.DefaultMaven.doExecute (DefaultMaven.java:305)
    at org.apache.maven.DefaultMaven.doExecute (DefaultMaven.java:192)
    at org.apache.maven.DefaultMaven.execute (DefaultMaven.java:105)
    at org.apache.maven.cli.MavenCli.execute (MavenCli.java:957)
    at org.apache.maven.cli.MavenCli.doMain (MavenCli.java:289)
    at org.apache.maven.cli.MavenCli.main (MavenCli.java:193)
    at jdk.internal.reflect.NativeMethodAccessorImpl.invoke0 (Native Method)
    at jdk.internal.reflect.NativeMethodAccessorImpl.invoke (NativeMethodAccessorImpl.java:62)
    at jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke (DelegatingMethodAccessorImpl.java:43)
    at java.lang.reflect.Method.invoke (Method.java:566)
    at org.codehaus.plexus.classworlds.launcher.Launcher.launchEnhanced (Launcher.java:282)
    at org.codehaus.plexus.classworlds.launcher.Launcher.launch (Launcher.java:225)
    at org.codehaus.plexus.classworlds.launcher.Launcher.mainWithExitCode (Launcher.java:406)
    at org.codehaus.plexus.classworlds.launcher.Launcher.main (Launcher.java:347)
    at org.codehaus.classworlds.Launcher.main (Launcher.java:47)
Caused by: org.apache.maven.plugin.compiler.CompilationFailureException: Compilation failure
    at org.apache.maven.plugin.compiler.AbstractCompilerMojo.execute (AbstractCompilerMojo.java:1219)
    at org.apache.maven.plugin.compiler.CompilerMojo.execute (CompilerMojo.java:188)
    at org.apache.maven.plugin.DefaultBuildPluginManager.executeMojo (DefaultBuildPluginManager.java:137)
    at org.apache.maven.lifecycle.internal.MojoExecutor.execute (MojoExecutor.java:210)
    at org.apache.maven.lifecycle.internal.MojoExecutor.execute (MojoExecutor.java:156)
    at org.apache.maven.lifecycle.internal.MojoExecutor.execute (MojoExecutor.java:148)
    at org.apache.maven.lifecycle.internal.LifecycleModuleBuilder.buildProject (LifecycleModuleBuilder.java:117)
    at org.apache.maven.lifecycle.internal.LifecycleModuleBuilder.buildProject (LifecycleModuleBuilder.java:81)
    at org.apache.maven.lifecycle.internal.builder.singlethreaded.SingleThreadedBuilder.build (SingleThreadedBuilder.java:56)
    at org.apache.maven.lifecycle.internal.LifecycleStarter.execute (LifecycleStarter.java:128)
    at org.apache.maven.DefaultMaven.doExecute (DefaultMaven.java:305)
    at org.apache.maven.DefaultMaven.doExecute (DefaultMaven.java:192)
    at org.apache.maven.DefaultMaven.execute (DefaultMaven.java:105)
    at org.apache.maven.cli.MavenCli.execute (MavenCli.java:957)
    at org.apache.maven.cli.MavenCli.doMain (MavenCli.java:289)
    at org.apache.maven.cli.MavenCli.main (MavenCli.java:193)
    at jdk.internal.reflect.NativeMethodAccessorImpl.invoke0 (Native Method)
    at jdk.internal.reflect.NativeMethodAccessorImpl.invoke (NativeMethodAccessorImpl.java:62)
    at jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke (DelegatingMethodAccessorImpl.java:43)
    at java.lang.reflect.Method.invoke (Method.java:566)
    at org.codehaus.plexus.classworlds.launcher.Launcher.launchEnhanced (Launcher.java:282)
    at org.codehaus.plexus.classworlds.launcher.Launcher.launch (Launcher.java:225)
    at org.codehaus.plexus.classworlds.launcher.Launcher.mainWithExitCode (Launcher.java:406)
    at org.codehaus.plexus.classworlds.launcher.Launcher.main (Launcher.java:347)
    at org.codehaus.classworlds.Launcher.main (Launcher.java:47)
[ERROR] 
[ERROR] 
[ERROR] For more information about the errors and possible solutions, please read the following articles:
[ERROR] [Help 1] http://cwiki.apache.org/confluence/display/MAVEN/MojoFailureException

Process finished with exit code 1
```
