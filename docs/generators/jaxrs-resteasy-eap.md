---
title: Config Options for jaxrs-resteasy-eap
sidebar_label: jaxrs-resteasy-eap
---

| Option | Description | Values | Default |
| ------ | ----------- | ------ | ------- |
|sortParamsByRequiredFlag|Sort method arguments to place required parameters before optional parameters.| |true|
|sortModelPropertiesByRequiredFlag|Sort model properties to place required parameters before optional parameters.| |true|
|ensureUniqueParams|Whether to ensure parameter names are unique in an operation (rename parameters that are not).| |true|
|allowUnicodeIdentifiers|boolean, toggles whether unicode identifiers are allowed in names or not, default is false| |false|
|prependFormOrBodyParameters|Add form or body parameters to the beginning of the parameter list.| |false|
|modelPackage|package for generated models| |org.openapitools.model|
|apiPackage|package for generated api classes| |org.openapitools.api|
|invokerPackage|root package for generated code| |org.openapitools.api|
|groupId|groupId in generated pom.xml| |org.openapitools|
|artifactId|artifactId in generated pom.xml. This also becomes part of the generated library's filename| |openapi-jaxrs-resteasy-eap-server|
|artifactVersion|artifact version in generated pom.xml. This also becomes part of the generated library's filename| |1.0.0|
|artifactUrl|artifact URL in generated pom.xml| |https://github.com/openapitools/openapi-generator|
|artifactDescription|artifact description in generated pom.xml| |OpenAPI Java|
|scmConnection|SCM connection in generated pom.xml| |scm:git:git@github.com:openapitools/openapi-generator.git|
|scmDeveloperConnection|SCM developer connection in generated pom.xml| |scm:git:git@github.com:openapitools/openapi-generator.git|
|scmUrl|SCM URL in generated pom.xml| |https://github.com/openapitools/openapi-generator|
|developerName|developer name in generated pom.xml| |OpenAPI-Generator Contributors|
|developerEmail|developer email in generated pom.xml| |team@openapitools.org|
|developerOrganization|developer organization in generated pom.xml| |OpenAPITools.org|
|developerOrganizationUrl|developer organization URL in generated pom.xml| |http://openapitools.org|
|licenseName|The name of the license| |Unlicense|
|licenseUrl|The URL of the license| |http://unlicense.org|
|sourceFolder|source folder for generated code| |src/main/java|
|serializableModel|boolean - toggle &quot;implements Serializable&quot; for generated models| |false|
|bigDecimalAsString|Treat BigDecimal values as Strings to avoid precision loss.| |false|
|fullJavaUtil|whether to use fully qualified name for classes under java.util. This option only works for Java API client| |false|
|hideGenerationTimestamp|Hides the generation timestamp when files are generated.| |false|
|withXml|whether to include support for application/xml content type and include XML annotations in the model (works with libraries that provide support for JSON and XML)| |false|
|dateLibrary|Option. Date library to use|<dl><dt>**joda**</dt><dd>Joda (for legacy app only)</dd><dt>**legacy**</dt><dd>Legacy java.util.Date (if you really have a good reason not to use threetenbp</dd><dt>**java8-localdatetime**</dt><dd>Java 8 using LocalDateTime (for legacy app only)</dd><dt>**java8**</dt><dd>Java 8 native JSR310 (preferred for jdk 1.8+) - note: this also sets &quot;java8&quot; to true</dd><dt>**threetenbp**</dt><dd>Backport of JSR310 (preferred for jdk &lt; 1.8)</dd><dl>|legacy|
|java8|Option. Use Java8 classes instead of third party equivalents|<dl><dt>**true**</dt><dd>Use Java 8 classes such as Base64</dd><dt>**false**</dt><dd>Various third party libraries as needed</dd><dl>|false|
|disableHtmlEscaping|Disable HTML escaping of JSON strings when using gson (needed to avoid problems with byte[] fields)| |false|
|booleanGetterPrefix|Set booleanGetterPrefix| |get|
|additionalModelTypeAnnotations|Additional annotations for model type(class level annotations)| |null|
|parentGroupId|parent groupId in generated pom N.B. parentGroupId, parentArtifactId and parentVersion must all be specified for any of them to take effect| |null|
|parentArtifactId|parent artifactId in generated pom N.B. parentGroupId, parentArtifactId and parentVersion must all be specified for any of them to take effect| |null|
|parentVersion|parent version in generated pom N.B. parentGroupId, parentArtifactId and parentVersion must all be specified for any of them to take effect| |null|
|snapshotVersion|Uses a SNAPSHOT version.|<dl><dt>**true**</dt><dd>Use a SnapShot Version</dd><dt>**false**</dt><dd>Use a Release Version</dd><dl>|null|
|implFolder|folder for generated implementation code| |src/main/java|
|title|a title describing the application| |OpenAPI Server|
|useBeanValidation|Use BeanValidation API annotations| |true|
|serverPort|The port on which the server should be started| |8080|
|useBeanValidation|Use BeanValidation API annotations| |true|
|generateJbossDeploymentDescriptor|Generate Jboss Deployment Descriptor| |true|
|useSwaggerFeature|Use dynamic Swagger generator| |false|

## IMPORT MAPPING

| Type/Alias | Imports |
| ---------- | ------- |
|LocalDateTime|org.joda.time.*|
|Set|java.util.*|
|LocalTime|org.joda.time.*|
|HashMap|java.util.HashMap|
|ArrayList|java.util.ArrayList|
|URI|java.net.URI|
|Timestamp|java.sql.Timestamp|
|LocalDate|org.joda.time.*|
|BigDecimal|java.math.BigDecimal|
|Date|java.util.Date|
|DateTime|org.joda.time.*|
|Array|java.util.List|
|List|java.util.*|
|UUID|java.util.UUID|
|File|java.io.File|
|Map|java.util.Map|


## INSTANTIATION TYPES

| Type/Alias | Instantiated By |
| ---------- | --------------- |
|array|ArrayList|
|map|HashMap|


## LANGUAGE PRIMITIVES

<ul data-columns="2" style="list-style-type: disc;-webkit-columns:2;-moz-columns:2;columns:2;-moz-column-fill:auto;column-fill:auto"><li>Integer</li>
<li>byte[]</li>
<li>Float</li>
<li>boolean</li>
<li>Long</li>
<li>Object</li>
<li>String</li>
<li>Boolean</li>
<li>Double</li>
</ul>

## RESERVED WORDS

<ul data-columns="2" style="list-style-type: disc;-webkit-columns:2;-moz-columns:2;columns:2;-moz-column-fill:auto;column-fill:auto"><li>localvaraccepts</li>
<li>synchronized</li>
<li>do</li>
<li>float</li>
<li>while</li>
<li>localvarpath</li>
<li>protected</li>
<li>continue</li>
<li>else</li>
<li>apiclient</li>
<li>localvarqueryparams</li>
<li>catch</li>
<li>if</li>
<li>case</li>
<li>new</li>
<li>package</li>
<li>static</li>
<li>void</li>
<li>localvaraccept</li>
<li>double</li>
<li>byte</li>
<li>finally</li>
<li>this</li>
<li>strictfp</li>
<li>throws</li>
<li>enum</li>
<li>extends</li>
<li>null</li>
<li>transient</li>
<li>apiexception</li>
<li>final</li>
<li>try</li>
<li>object</li>
<li>localvarcontenttypes</li>
<li>implements</li>
<li>private</li>
<li>import</li>
<li>const</li>
<li>configuration</li>
<li>for</li>
<li>apiresponse</li>
<li>interface</li>
<li>long</li>
<li>switch</li>
<li>default</li>
<li>goto</li>
<li>public</li>
<li>localvarheaderparams</li>
<li>native</li>
<li>localvarcontenttype</li>
<li>assert</li>
<li>stringutil</li>
<li>class</li>
<li>localvarcollectionqueryparams</li>
<li>localvarcookieparams</li>
<li>localreturntype</li>
<li>localvarformparams</li>
<li>break</li>
<li>volatile</li>
<li>localvarauthnames</li>
<li>abstract</li>
<li>int</li>
<li>instanceof</li>
<li>super</li>
<li>boolean</li>
<li>throw</li>
<li>localvarpostbody</li>
<li>char</li>
<li>short</li>
<li>return</li>
</ul>
