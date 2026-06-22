# piggymetrics

## Summary

| Metric | Value |
|--------|-------|
| Total Issues | 185 |
| Mandatory Blockers | 175 |
| Potential Issues | 5 |

## Component Information

| Property | Value |
|----------|-------|
| Language | Java, Dockerfile |
| Frameworks | Spring Boot, Spring Cloud, Spring |
| Build tools | Maven |
| JDK version | 1.8 |

## Cloud Readiness Issues

| Issue Name | Criticality | Story Points | Occurrences |
|------------|-------------|--------------|-------------|
| Use of unsecured network protocols or URI libraries | Mandatory | 3 | [14](#Use_of_unsecured_network_protocols_or_URI_libraries) |
| CRA: Default or well-known password detected | Mandatory | 3 | [8](#CRA_Default_or_well-known_password_detected) |
| CRA: Hard-coded password in Java source code | Mandatory | 8 | [6](#CRA_Hard-coded_password_in_Java_source_code) |
| CRA: Use of weak password hashing (plain MD5/SHA for passwords) | Mandatory | 8 | [2](#CRA_Use_of_weak_password_hashing_plain_MD5_SHA_for_passwords) |
| MongoDB connection found in configuration file | Potential | 5 | [16](#MongoDB_connection_found_in_configuration_file) |
| Password found in configuration file | Potential | 3 | [10](#Password_found_in_configuration_file) |
| Avoid using hardcoded URLs (HTTP protocol) in source code | Optional | 3 | [17](#Avoid_using_hardcoded_URLs_HTTP_protocol_in_source_code) |
| Spring AMQP dependency found | Optional | 5 | [4](#Spring_AMQP_dependency_found) |

### Issue Details

<details id="Use_of_unsecured_network_protocols_or_URI_libraries">
<summary><b>Use of unsecured network protocols or URI libraries</b> — affected files</summary>

- `account-service/src/main/resources/bootstrap.yml (line 6)`
- `config/src/main/resources/shared/application.yml (line 18)`
- `config/src/main/resources/shared/application.yml (line 23)`
- `config/src/main/resources/shared/gateway.yml (line 22)`
- `config/src/main/resources/shared/notification-service.yml (line 6)`
- `config/src/main/resources/shared/statistics-service.yml (line 6)`
- `gateway/src/main/resources/bootstrap.yml (line 6)`
- `monitoring/src/main/resources/bootstrap.yml (line 6)`
- `auth-service/src/main/resources/bootstrap.yml (line 6)`
- `notification-service/src/main/resources/bootstrap.yml (line 6)`
- `registry/src/main/resources/bootstrap.yml (line 6)`
- `statistics-service/src/main/resources/bootstrap.yml (line 6)`
- `turbine-stream-service/src/main/resources/bootstrap.yml (line 6)`
- `config/src/main/resources/shared/account-service.yml (line 6)`

</details>

<details id="CRA_Default_or_well-known_password_detected">
<summary><b>CRA: Default or well-known password detected</b> — affected files</summary>

- `account-service/src/main/java/com/piggymetrics/account/domain/User.java (line 30)`
- `auth-service/src/main/java/com/piggymetrics/auth/domain/User.java (line 38)`
- `notification-service/src/test/resources/application.yml (line 23)`
- `account-service/src/test/java/com/piggymetrics/account/controller/AccountControllerTest.java (line 129)`
- `auth-service/src/test/java/com/piggymetrics/auth/controller/UserControllerTest.java (line 49)`
- `auth-service/src/test/java/com/piggymetrics/auth/repository/UserRepositoryTest.java (line 30)`
- `auth-service/src/test/java/com/piggymetrics/auth/service/UserServiceTest.java (line 33)`
- `auth-service/src/test/java/com/piggymetrics/auth/service/UserServiceTest.java (line 44)`

</details>

<details id="CRA_Hard-coded_password_in_Java_source_code">
<summary><b>CRA: Hard-coded password in Java source code</b> — affected files</summary>

- `account-service/src/test/java/com/piggymetrics/account/controller/AccountControllerTest.java (line 129)`
- `auth-service/src/test/java/com/piggymetrics/auth/controller/UserControllerTest.java (line 49)`
- `auth-service/src/test/java/com/piggymetrics/auth/controller/UserControllerTest.java (line 62)`
- `auth-service/src/test/java/com/piggymetrics/auth/repository/UserRepositoryTest.java (line 30)`
- `auth-service/src/test/java/com/piggymetrics/auth/service/UserServiceTest.java (line 33)`
- `auth-service/src/test/java/com/piggymetrics/auth/service/UserServiceTest.java (line 44)`

</details>

<details id="CRA_Use_of_weak_password_hashing_plain_MD5_SHA_for_passwords">
<summary><b>CRA: Use of weak password hashing (plain MD5/SHA for passwords)</b> — affected files</summary>

- `auth-service/src/main/java/com/piggymetrics/auth/config/OAuth2AuthorizationConfig.java (line 26)`
- `auth-service/src/main/java/com/piggymetrics/auth/config/OAuth2AuthorizationConfig.java (line 79)`

</details>

<details id="MongoDB_connection_found_in_configuration_file">
<summary><b>MongoDB connection found in configuration file</b> — affected files</summary>

- `docker-compose.dev.yml (line 23)`
- `docker-compose.dev.yml (line 33)`
- `docker-compose.dev.yml (line 43)`
- `docker-compose.dev.yml (line 53)`
- `account-service/src/test/resources/application.yml (line 3)`
- `auth-service/src/test/resources/application.yml (line 3)`
- `config/src/main/resources/shared/account-service.yml (line 12)`
- `config/src/main/resources/shared/auth-service.yml (line 3)`
- `config/src/main/resources/shared/notification-service.yml (line 30)`
- `config/src/main/resources/shared/statistics-service.yml (line 12)`
- `notification-service/src/test/resources/application.yml (line 16)`
- `docker-compose.yml (line 70)`
- `docker-compose.yml (line 95)`
- `docker-compose.yml (line 121)`
- `docker-compose.yml (line 146)`
- `statistics-service/src/test/resources/application.yml (line 11)`

</details>

<details id="Password_found_in_configuration_file">
<summary><b>Password found in configuration file</b> — affected files</summary>

- `account-service/src/main/resources/bootstrap.yml (line 8)`
- `auth-service/src/main/resources/bootstrap.yml (line 8)`
- `config/src/main/resources/application.yml (line 11)`
- `gateway/src/main/resources/bootstrap.yml (line 8)`
- `monitoring/src/main/resources/bootstrap.yml (line 8)`
- `notification-service/src/main/resources/bootstrap.yml (line 8)`
- `notification-service/src/test/resources/application.yml (line 23)`
- `registry/src/main/resources/bootstrap.yml (line 8)`
- `statistics-service/src/main/resources/bootstrap.yml (line 8)`
- `turbine-stream-service/src/main/resources/bootstrap.yml (line 8)`

</details>

<details id="Avoid_using_hardcoded_URLs_HTTP_protocol_in_source_code">
<summary><b>Avoid using hardcoded URLs (HTTP protocol) in source code</b> — affected files</summary>

- `.travis.yml (line 18)`
- `account-service/src/main/resources/bootstrap.yml (line 6)`
- `auth-service/src/main/resources/bootstrap.yml (line 6)`
- `config/src/main/resources/shared/account-service.yml (line 6)`
- `config/src/main/resources/shared/application.yml (line 18)`
- `config/src/main/resources/shared/application.yml (line 23)`
- `config/src/main/resources/shared/gateway.yml (line 22)`
- `config/src/main/resources/shared/notification-service.yml (line 6)`
- `config/src/main/resources/shared/statistics-service.yml (line 6)`
- `config/src/main/resources/shared/statistics-service.yml (line 25)`
- `gateway/src/main/resources/bootstrap.yml (line 6)`
- `monitoring/src/main/resources/bootstrap.yml (line 6)`
- `notification-service/src/main/resources/bootstrap.yml (line 6)`
- `registry/src/main/resources/bootstrap.yml (line 6)`
- `statistics-service/src/main/resources/bootstrap.yml (line 6)`
- `statistics-service/src/test/resources/application.yml (line 16)`
- `turbine-stream-service/src/main/resources/bootstrap.yml (line 6)`

</details>

<details id="Spring_AMQP_dependency_found">
<summary><b>Spring AMQP dependency found</b> — affected files</summary>

- `notification-service/pom.xml (line 57)`
- `statistics-service/pom.xml (line 57)`
- `account-service/pom.xml (line 57)`

</details>

## Upgrade Issues

| Issue Name | Criticality | Story Points | Occurrences |
|------------|-------------|--------------|-------------|
| Java Version Has Reached the End of Support | Mandatory | 8 | [1](#Java_Version_Has_Reached_the_End_of_Support) |

### Issue Details

<details id="Java_Version_Has_Reached_the_End_of_Support">
<summary><b>Java Version Has Reached the End of Support</b> — affected files</summary>

- `pom.xml (line 21)`

</details>

## Security Issues

> **Note:** These issues were generated by AI and may contain inaccuracies or incomplete information. Please review carefully.

| Issue Name | Criticality | Story Points | Files |
|------------|-------------|--------------|-------|
| CVE-2025-52999: jackson-core can throw a StackoverflowError when processing deeply nested data | Mandatory | 1 | 0 |
| CVE-2023-6378: logback serialization vulnerability | Mandatory | 1 | 0 |
| CVE-2022-42003: Uncontrolled Resource Consumption in Jackson-databind | Mandatory | 1 | 0 |
| CVE-2022-42004: Uncontrolled Resource Consumption in FasterXML jackson-databind | Mandatory | 1 | 0 |
| CVE-2020-10650: jackson-databind vulnerable to unsafe deserialization | Mandatory | 1 | 0 |
| CVE-2022-25647: Deserialization of Untrusted Data in Gson | Mandatory | 1 | 0 |
| CVE-2020-36518: Deeply nested json in jackson-databind | Mandatory | 1 | 0 |
| CVE-2020-36189: Unsafe Deserialization in jackson-databind | Mandatory | 1 | 0 |
| CVE-2020-36187: Unsafe Deserialization in jackson-databind | Mandatory | 1 | 0 |
| CVE-2020-36188: Unsafe Deserialization in jackson-databind | Mandatory | 1 | 0 |
| CVE-2020-36183: Unsafe Deserialization in jackson-databind | Mandatory | 1 | 0 |
| CVE-2020-36184: Unsafe Deserialization in jackson-databind | Mandatory | 1 | 0 |
| CVE-2020-36180: Unsafe Deserialization in jackson-databind | Mandatory | 1 | 0 |
| CVE-2020-36181: Unsafe Deserialization in jackson-databind | Mandatory | 1 | 0 |
| CVE-2020-36185: Unsafe Deserialization in jackson-databind | Mandatory | 1 | 0 |
| CVE-2020-36179: Unsafe Deserialization in jackson-databind | Mandatory | 1 | 0 |
| CVE-2020-36182: Unsafe Deserialization in jackson-databind | Mandatory | 1 | 0 |
| CVE-2020-24750: Unsafe Deserialization in jackson-databind | Mandatory | 1 | 0 |
| CVE-2020-35728: Serialization gadget exploit in jackson-databind | Mandatory | 1 | 0 |
| CVE-2020-35491: Serialization gadgets exploit in jackson-databind | Mandatory | 1 | 0 |
| CVE-2020-35490: Serialization gadgets exploit in jackson-databind | Mandatory | 1 | 0 |
| CVE-2020-24616: Code Injection in jackson-databind | Mandatory | 1 | 0 |
| CVE-2020-36186: Unsafe Deserialization in jackson-databind | Mandatory | 1 | 0 |
| CVE-2020-25649: XML External Entity (XXE) Injection in Jackson Databind | Mandatory | 1 | 0 |
| CVE-2021-20190: Deserialization of untrusted data in jackson-databind | Mandatory | 1 | 0 |
| CVE-2020-14061: Deserialization of untrusted data in Jackson Databind | Mandatory | 1 | 0 |
| CVE-2020-14062: Deserialization of untrusted data in Jackson Databind | Mandatory | 1 | 0 |
| CVE-2020-14060: Deserialization of untrusted data in Jackson Databind | Mandatory | 1 | 0 |
| CVE-2020-14195: Deserialization of untrusted data in Jackson Databind | Mandatory | 1 | 0 |
| CVE-2019-17267: Improper Input Validation in jackson-databind | Mandatory | 1 | 0 |
| CVE-2020-11112: jackson-databind mishandles the interaction between serialization gadgets and typing | Mandatory | 1 | 0 |
| CVE-2020-9547: jackson-databind mishandles the interaction between serialization gadgets and typing | Mandatory | 1 | 0 |
| CVE-2019-14893: Polymorphic deserialization of malicious object in jackson-databind | Mandatory | 1 | 0 |
| CVE-2020-10673: jackson-databind mishandles the interaction between serialization gadgets and typing | Mandatory | 1 | 0 |
| CVE-2020-9548: jackson-databind mishandles the interaction between serialization gadgets and typing | Mandatory | 1 | 0 |
| CVE-2019-14892: Polymorphic deserialization of malicious object in jackson-databind | Mandatory | 1 | 0 |
| CVE-2020-10968: jackson-databind mishandles the interaction between serialization gadgets and typing | Mandatory | 1 | 0 |
| CVE-2020-11111: jackson-databind mishandles the interaction between serialization gadgets and typing | Mandatory | 1 | 0 |
| CVE-2020-11113: jackson-databind mishandles the interaction between serialization gadgets and typing | Mandatory | 1 | 0 |
| CVE-2020-11619: jackson-databind mishandles the interaction between serialization gadgets and typing | Mandatory | 1 | 0 |
| CVE-2020-10969: jackson-databind mishandles the interaction between serialization gadgets and typing | Mandatory | 1 | 0 |
| CVE-2020-9546: jackson-databind mishandles the interaction between serialization gadgets and typing | Mandatory | 1 | 0 |
| CVE-2020-11620: jackson-databind mishandles the interaction between serialization gadgets and typing | Mandatory | 1 | 0 |
| CVE-2020-10672: jackson-databind mishandles the interaction between serialization gadgets and typing | Mandatory | 1 | 0 |
| CVE-2020-8840: Deserialization of Untrusted Data in jackson-databind | Mandatory | 1 | 0 |
| CVE-2019-20330: Deserialization of Untrusted Data in jackson-databind | Mandatory | 1 | 0 |
| CVE-2019-17531: jackson-databind polymorphic typing issue | Mandatory | 1 | 0 |
| CVE-2019-16943: jackson-databind polymorphic typing issue | Mandatory | 1 | 0 |
| CVE-2019-16942: Polymorphic Typing in FasterXML jackson-databind | Mandatory | 1 | 0 |
| CVE-2019-16335: Polymorphic Typing issue in FasterXML jackson-databind | Mandatory | 1 | 0 |
| CVE-2019-14540: Polymorphic Typing issue in FasterXML jackson-databind | Mandatory | 1 | 0 |
| CVE-2019-14439: Deserialization of untrusted data in FasterXML jackson-databind | Mandatory | 1 | 0 |
| CVE-2019-14379: Deserialization of untrusted data in FasterXML jackson-databind | Mandatory | 1 | 0 |
| CVE-2019-12086: Information exposure in FasterXML jackson-databind | Mandatory | 1 | 0 |
| CVE-2018-14719: Arbitrary Code Execution in jackson-databind | Mandatory | 1 | 0 |
| CVE-2018-14720: XML External Entity Reference (XXE) in jackson-databind | Mandatory | 1 | 0 |
| CVE-2018-14721: Server-Side Request Forgery (SSRF) in jackson-databind | Mandatory | 1 | 0 |
| CVE-2018-19362: com.fasterxml.jackson.core:jackson-databind vulnerable to Deserialization of Untrusted Data | Mandatory | 1 | 0 |
| CVE-2018-19361: Deserialization of Untrusted Data in jackson-databind | Mandatory | 1 | 0 |
| CVE-2018-19360: Deserialization of Untrusted Data in jackson-databind due to polymorphic deserialization | Mandatory | 1 | 0 |
| CVE-2018-14718: Arbitrary Code Execution in jackson-databind | Mandatory | 1 | 0 |
| CVE-2024-47072: XStream is vulnerable to a Denial of Service attack due to stack overflow from a manipulated binary input stream | Mandatory | 1 | 0 |
| CVE-2022-40151: XStream can cause a Denial of Service by injecting deeply nested objects raising a stack overflow | Mandatory | 1 | 0 |
| CVE-2022-41966: XStream can cause Denial of Service via stack overflow | Mandatory | 1 | 0 |
| CVE-2021-43859: Denial of Service by injecting highly recursive collections or maps in XStream | Mandatory | 1 | 0 |
| CVE-2021-39139: XStream is vulnerable to an Arbitrary Code Execution attack | Mandatory | 1 | 0 |
| CVE-2021-39141: XStream is vulnerable to an Arbitrary Code Execution attack | Mandatory | 1 | 0 |
| CVE-2021-39144: XStream is vulnerable to a Remote Command Execution attack | Mandatory | 1 | 0 |
| CVE-2021-39145: XStream is vulnerable to an Arbitrary Code Execution attack | Mandatory | 1 | 0 |
| CVE-2021-39146: XStream is vulnerable to an Arbitrary Code Execution attack | Mandatory | 1 | 0 |
| CVE-2021-39147: XStream is vulnerable to an Arbitrary Code Execution attack | Mandatory | 1 | 0 |
| CVE-2021-39148: XStream is vulnerable to an Arbitrary Code Execution attack | Mandatory | 1 | 0 |
| CVE-2021-39149: XStream is vulnerable to an Arbitrary Code Execution attack | Mandatory | 1 | 0 |
| CVE-2021-39150: A Server-Side Forgery Request can be activated unmarshalling with XStream to access data streams from an arbitrary URL referencing a resource in an intranet or the local host | Mandatory | 1 | 0 |
| CVE-2021-39151: XStream is vulnerable to an Arbitrary Code Execution attack | Mandatory | 1 | 0 |
| CVE-2021-39152: A Server-Side Forgery Request can be activated unmarshalling with XStream to access data streams from an arbitrary URL referencing a resource in an intranet or the local host | Mandatory | 1 | 0 |
| CVE-2021-39153: XStream is vulnerable to an Arbitrary Code Execution attack | Mandatory | 1 | 0 |
| CVE-2021-39154: XStream is vulnerable to an Arbitrary Code Execution attack | Mandatory | 1 | 0 |
| CVE-2021-29505: XStream is vulnerable to a Remote Command Execution attack | Mandatory | 1 | 0 |
| CVE-2021-21341: XStream can cause a Denial of Service. | Mandatory | 1 | 0 |
| CVE-2020-26217: XStream can be used for Remote Code Execution | Mandatory | 1 | 0 |
| CVE-2019-10173: Deserialization of Untrusted Data and Code Injection in xstream | Mandatory | 1 | 0 |
| CVE-2013-7285: Command Injection in Xstream | Mandatory | 1 | 0 |
| CVE-2026-50010: Netty: Wrapping plain trust manager silently disables hostname verification | Mandatory | 1 | 0 |
| CVE-2026-45416: Netty: SNI handler pre-allocates up to 16 MiB from nine attacker bytes | Mandatory | 1 | 0 |
| CVE-2026-44249: Netty has an IPv6 Subnet Filter Bypass via Incorrect Comparator Masking | Mandatory | 1 | 0 |
| CVE-2026-42587: Netty: HttpContentDecompressor maxAllocation bypass when Content-Encoding set to br/zstd/snappy leads to decompression bomb DoS | Mandatory | 1 | 0 |
| CVE-2026-42584: Netty has HttpClientCodec response desynchronization | Mandatory | 1 | 0 |
| CVE-2026-42583: Netty Lz4FrameDecoder is vulnerable to resource exhaustion  | Mandatory | 1 | 0 |
| CVE-2026-33870: Netty: HTTP Request Smuggling via Chunked Extension Quoted-String Parsing | Mandatory | 1 | 0 |
| CVE-2024-47554: Apache Commons IO: Possible denial of service attack on untrusted input to XmlStreamReader | Mandatory | 1 | 0 |
| CVE-2021-37137:  SnappyFrameDecoder doesn't restrict chunk length any may buffer skippable chunks in an unnecessary way | Mandatory | 1 | 0 |
| CVE-2021-37136: Bzip2Decoder doesn't allow setting size restrictions for decompressed data | Mandatory | 1 | 0 |
| CVE-2020-11612: Denial of Service in Netty | Mandatory | 1 | 0 |
| CVE-2019-20444: HTTP Request Smuggling in Netty | Mandatory | 1 | 0 |
| CVE-2023-1370: json-smart Uncontrolled Recursion vulnerability | Mandatory | 1 | 0 |
| CVE-2026-41284: Apache Tomcat: Unbounded read in WebDAV LOCK and  PROPFIND handling | Mandatory | 1 | 0 |
| CVE-2026-43512: Apache Tomcat - Digest authenticator will authenticate any unknown user | Mandatory | 1 | 0 |
| CVE-2026-43513: Apache Tomcat: LockOutRealm treats user names as case-sensitive | Mandatory | 1 | 0 |
| CVE-2026-43515: Apache Tomcat - Security constraints not correctly applied | Mandatory | 1 | 0 |
| CVE-2026-41293: Apache Tomcat - HTTP/2 request headers not validated | Mandatory | 1 | 0 |
| CVE-2026-42498: Apache Tomcat - WebSocket authentication header exposure | Mandatory | 1 | 0 |
| CVE-2026-24880: Apache Tomcat has an HTTP Request/Response Smuggling vulnerability | Mandatory | 1 | 0 |
| CVE-2026-24400: AssertJ has XML External Entity (XXE) vulnerability when parsing untrusted XML via isXmlEqualTo assertion | Mandatory | 1 | 0 |
| CVE-2025-55752: Apache Tomcat Vulnerable to Relative Path Traversal | Mandatory | 1 | 0 |
| CVE-2025-53506: Apache Tomcat Coyote vulnerable to Denial of Service via excessive HTTP/2 streams | Mandatory | 1 | 0 |
| CVE-2025-52520: Apache Tomcat Catalina is vulnerable to DoS attack through bypassing of size limits | Mandatory | 1 | 0 |
| CVE-2025-48988: Apache Tomcat - DoS in multipart upload | Mandatory | 1 | 0 |
| CVE-2025-24813: Apache Tomcat: Potential RCE and/or information disclosure and/or information corruption with partial PUT | Mandatory | 1 | 0 |
| CVE-2024-50379: Apache Tomcat Time-of-check Time-of-use (TOCTOU) Race Condition vulnerability | Mandatory | 1 | 0 |
| CVE-2024-34750: Apache Tomcat - Denial of Service | Mandatory | 1 | 0 |
| CVE-2023-46589: Apache Tomcat Improper Input Validation vulnerability | Mandatory | 1 | 0 |
| CVE-2023-4759: Arbitrary File Overwrite in Eclipse JGit  | Mandatory | 1 | 0 |
| CVE-2023-1436: Jettison vulnerable to infinite recursion | Mandatory | 1 | 0 |
| CVE-2022-45693: Jettison Out-of-bounds Write vulnerability | Mandatory | 1 | 0 |
| CVE-2022-45685: Jettison Out-of-bounds Write vulnerability | Mandatory | 1 | 0 |
| CVE-2022-42252: Apache Tomcat may reject request containing invalid Content-Length header | Mandatory | 1 | 0 |
| CVE-2022-40150: Jettison memory exhaustion | Mandatory | 1 | 0 |
| CVE-2019-10202: Deserialization of Untrusted Data in org.codehaus.jackson:jackson-mapper-asl | Mandatory | 1 | 0 |
| CVE-2020-11996: Uncontrolled Resource Consumption in Apache Tomcat | Mandatory | 1 | 0 |
| CVE-2020-13935: Infinite Loop in Apache Tomcat | Mandatory | 1 | 0 |
| CVE-2021-36090: Improper Handling of Length Parameter Inconsistency in Compress | Mandatory | 1 | 0 |
| CVE-2021-35517: Improper Handling of Length Parameter Inconsistency in Compress | Mandatory | 1 | 0 |
| CVE-2021-35516: Improper Handling of Length Parameter Inconsistency in Compress | Mandatory | 1 | 0 |
| CVE-2021-35515: Excessive Iteration in Compress | Mandatory | 1 | 0 |
| CVE-2021-25122: Exposure of Sensitive Information to an Unauthorized Actor in Apache Tomcat | Mandatory | 1 | 0 |
| CVE-2021-25329: Potential remote code execution in Apache Tomcat | Mandatory | 1 | 0 |
| CVE-2020-1938: Improper Privilege Management in Tomcat | Mandatory | 1 | 0 |
| CVE-2019-0199: Apache Tomcat Denial of Service vulnerability | Mandatory | 1 | 0 |
| CVE-2020-9484: Potential remote code execution in Apache Tomcat | Mandatory | 1 | 0 |
| CVE-2019-10172: Improper Restriction of XML External Entity Reference in jackson-mapper-asl | Mandatory | 1 | 0 |
| CVE-2019-12418: Insufficiently Protected Credentials in Apache Tomcat | Mandatory | 1 | 0 |
| CVE-2019-17563: In Apache Tomcat, when using FORM authentication there was a narrow window where an attacker could perform a session fixation attack | Mandatory | 1 | 0 |
| CVE-2019-10072: Improper Locking in Apache Tomcat | Mandatory | 1 | 0 |
| CVE-2019-0232: Apache Tomcat OS Command Injection vulnerability | Mandatory | 1 | 0 |
| CVE-2018-8034: The host name verification missing in Apache Tomcat | Mandatory | 1 | 0 |
| CVE-2018-8014: The defaults settings for the CORS filter provided in Apache Tomcat are insecure and enable 'supportsCredentials' for all origins | Mandatory | 1 | 0 |
| CVE-2018-1000180: Bouncy Castle has a flaw in the Low-level interface to RSA key pair generator | Mandatory | 1 | 0 |
| CVE-2026-22733: Spring Boot has an Authentication Bypass under Actuator CloudFoundry endpoints | Mandatory | 1 | [3](#CVE-2026-22733_Spring_Boot_has_an_Authentication_Bypass_under_Actuator_CloudFoundry_endpoints) |
| CVE-2023-20883: Spring Boot Welcome Page Denial of Service | Mandatory | 1 | 0 |
| CVE-2023-20873: Spring Boot Security Bypass with Wildcard Pattern Matching on Cloud Foundry | Mandatory | 1 | 0 |
| CVE-2026-40982: Spring Cloud Config vulnerable to Path Traversal | Mandatory | 1 | [1](#CVE-2026-40982_Spring_Cloud_Config_vulnerable_to_Path_Traversal) |
| CVE-2026-40973: Spring Boot accepts predictable temp directory without ownership verification | Mandatory | 1 | [10](#CVE-2026-40973_Spring_Boot_accepts_predictable_temp_directory_without_ownership_verification) |
| CVE-2026-22739: Spring Cloud Config Server: Path Traversal via Profile Parameter Allows Arbitrary File Access | Mandatory | 1 | [1](#CVE-2026-22739_Spring_Cloud_Config_Server_Path_Traversal_via_Profile_Parameter_Allows_Arbitrary_File_Access) |
| CVE-2025-22235: Spring Boot EndpointRequest.to() creates wrong matcher if actuator endpoint is not exposed | Mandatory | 1 | [10](#CVE-2025-22235_Spring_Boot_EndpointRequest_to_creates_wrong_matcher_if_actuator_endpoint_is_not_exposed) |
| CVE-2022-27772: Temporary Directory Hijacking to Local Privilege Escalation Vulnerability in org.springframework.boot:spring-boot | Mandatory | 1 | [10](#CVE-2022-27772_Temporary_Directory_Hijacking_to_Local_Privilege_Escalation_Vulnerability_in_org_springframework_boot_spring-boot) |
| CVE-2022-22965: Remote Code Execution in Spring Framework | Mandatory | 1 | [4](#CVE-2022-22965_Remote_Code_Execution_in_Spring_Framework) |
| CVE-2021-22053: Code injection in spring-cloud-netflix-hystrix-dashboard | Mandatory | 1 | 0 |
| CVE-2026-22732: Spring Security HTTP Headers Are not Written Under Some Conditions | Mandatory | 1 | 0 |
| CVE-2025-22228: Spring Security Does Not Enforce Password Length | Mandatory | 1 | 0 |
| CVE-2024-38821: Spring Security vulnerable to Authorization Bypass of Static Resources in WebFlux Applications | Mandatory | 1 | 0 |
| CVE-2024-22257: Erroneous authentication pass in Spring Security | Mandatory | 1 | 0 |
| CVE-2022-22980: SpEL Injection in Spring Data MongoDB | Mandatory | 1 | 0 |
| CVE-2022-22978: Authorization bypass in Spring Security | Mandatory | 1 | 0 |
| CVE-2021-22112: Privilege escalation in spring security | Mandatory | 1 | 0 |
| CVE-2018-15758: Authorization bypass in org.springframework.security.oauth:spring-security-oauth2 | Mandatory | 1 | 0 |
| CVE-2018-1260: Spring Security OAuth vulnerable to remote code execution (RCE) | Mandatory | 1 | 0 |
| CVE-2024-38819: Spring Framework Path Traversal vulnerability | Mandatory | 1 | 0 |
| CVE-2024-22262: Spring Framework URL Parsing with Host Validation | Mandatory | 1 | 0 |
| CVE-2024-22259: Spring Framework URL Parsing with Host Validation Vulnerability | Mandatory | 1 | 0 |
| CVE-2024-22243: Spring Web vulnerable to Open Redirect or Server Side Request Forgery | Mandatory | 1 | 0 |
| CVE-2023-20863: Spring Framework vulnerable to denial of service | Mandatory | 1 | 0 |
| CVE-2022-1471: SnakeYaml Constructor Deserialization Remote Code Execution | Mandatory | 1 | 0 |
| CVE-2022-25857: Uncontrolled Resource Consumption in snakeyaml | Mandatory | 1 | 0 |
| CVE-2016-1000027: Pivotal Spring Framework contains unsafe Java deserialization methods | Mandatory | 1 | 0 |
| CVE-2022-22970: Denial of service in Spring Framework | Mandatory | 1 | 0 |
| CVE-2022-22968: Improper handling of case sensitivity in Spring Framework | Mandatory | 1 | 0 |
| CVE-2017-18640: SnakeYAML Entity Expansion during load operation | Mandatory | 1 | 0 |
| CVE-2018-15756: Denial of Service in Spring Framework | Mandatory | 1 | 0 |
| CVE-2020-5398: RFD attack via Content-Disposition header sourced from request input by Spring MVC or Spring WebFlux Application | Mandatory | 1 | 0 |
| CWE-820: Missing Synchronization | Potential | 8 | [1](#CWE-820_Missing_Synchronization) |
| CWE-567: Unsynchronized Access to Shared Data in a Multithreaded Context | Potential | 5 | [1](#CWE-567_Unsynchronized_Access_to_Shared_Data_in_a_Multithreaded_Context) |
| CWE-778: Insufficient Logging | Potential | 3 | [1](#CWE-778_Insufficient_Logging) |
| CWE-259: Use of Hard-coded Password | Optional | 5 | [1](#CWE-259_Use_of_Hard-coded_Password) |
| CWE-798: Use of Hard-coded Credentials | Optional | 5 | [1](#CWE-798_Use_of_Hard-coded_Credentials) |
| CWE-477: Use of Obsolete Function | Optional | 1 | [3](#CWE-477_Use_of_Obsolete_Function) |

### Security Issue Details

<details id="CVE-2026-22733_Spring_Boot_has_an_Authentication_Bypass_under_Actuator_CloudFoundry_endpoints">
<summary><b>CVE-2026-22733: Spring Boot has an Authentication Bypass under Actuator CloudFoundry endpoints</b> — affected files</summary>

- `notification-service/pom.xml:53`
- `account-service/pom.xml:53`
- `statistics-service/pom.xml:53`

</details>

<details id="CVE-2026-40982_Spring_Cloud_Config_vulnerable_to_Path_Traversal">
<summary><b>CVE-2026-40982: Spring Cloud Config vulnerable to Path Traversal</b> — affected files</summary>

- `config/pom.xml:22`

</details>

<details id="CVE-2026-40973_Spring_Boot_accepts_predictable_temp_directory_without_ownership_verification">
<summary><b>CVE-2026-40973: Spring Boot accepts predictable temp directory without ownership verification</b> — affected files</summary>

- `pom.xml:13`
- `notification-service/pom.xml:25`
- `account-service/pom.xml:25`
- `turbine-stream-service/pom.xml:39`
- `registry/pom.xml:29`
- `config/pom.xml:26`
- `monitoring/pom.xml:29`
- `statistics-service/pom.xml:21`
- `auth-service/pom.xml:21`
- `gateway/pom.xml:41`

</details>

<details id="CVE-2026-22739_Spring_Cloud_Config_Server_Path_Traversal_via_Profile_Parameter_Allows_Arbitrary_File_Access">
<summary><b>CVE-2026-22739: Spring Cloud Config Server: Path Traversal via Profile Parameter Allows Arbitrary File Access</b> — affected files</summary>

- `config/pom.xml:22`

</details>

<details id="CVE-2025-22235_Spring_Boot_EndpointRequest_to_creates_wrong_matcher_if_actuator_endpoint_is_not_exposed">
<summary><b>CVE-2025-22235: Spring Boot EndpointRequest.to() creates wrong matcher if actuator endpoint is not exposed</b> — affected files</summary>

- `pom.xml:13`
- `notification-service/pom.xml:25`
- `account-service/pom.xml:25`
- `turbine-stream-service/pom.xml:39`
- `registry/pom.xml:29`
- `config/pom.xml:26`
- `monitoring/pom.xml:29`
- `statistics-service/pom.xml:21`
- `auth-service/pom.xml:21`
- `gateway/pom.xml:41`

</details>

<details id="CVE-2022-27772_Temporary_Directory_Hijacking_to_Local_Privilege_Escalation_Vulnerability_in_org_springframework_boot_spring-boot">
<summary><b>CVE-2022-27772: Temporary Directory Hijacking to Local Privilege Escalation Vulnerability in org.springframework.boot:spring-boot</b> — affected files</summary>

- `pom.xml:13`
- `notification-service/pom.xml:25`
- `account-service/pom.xml:25`
- `turbine-stream-service/pom.xml:39`
- `registry/pom.xml:29`
- `config/pom.xml:26`
- `monitoring/pom.xml:29`
- `statistics-service/pom.xml:21`
- `auth-service/pom.xml:21`
- `gateway/pom.xml:41`

</details>

<details id="CVE-2022-22965_Remote_Code_Execution_in_Spring_Framework">
<summary><b>CVE-2022-22965: Remote Code Execution in Spring Framework</b> — affected files</summary>

- `notification-service/pom.xml:33`
- `account-service/pom.xml:33`
- `statistics-service/pom.xml:33`
- `auth-service/pom.xml:37`

</details>

<details id="CWE-820_Missing_Synchronization">
<summary><b>CWE-820: Missing Synchronization</b> — affected files</summary>

- `statistics-service/src/main/java/com/piggymetrics/statistics/service/ExchangeRatesServiceImpl.java`

</details>

<details id="CWE-567_Unsynchronized_Access_to_Shared_Data_in_a_Multithreaded_Context">
<summary><b>CWE-567: Unsynchronized Access to Shared Data in a Multithreaded Context</b> — affected files</summary>

- `statistics-service/src/main/java/com/piggymetrics/statistics/service/ExchangeRatesServiceImpl.java`

</details>

<details id="CWE-778_Insufficient_Logging">
<summary><b>CWE-778: Insufficient Logging</b> — affected files</summary>

- `auth-service/src/main/java/com/piggymetrics/auth/service/UserServiceImpl.java`

</details>

<details id="CWE-259_Use_of_Hard-coded_Password">
<summary><b>CWE-259: Use of Hard-coded Password</b> — affected files</summary>

- `config/src/main/resources/shared/notification-service.yml`

</details>

<details id="CWE-798_Use_of_Hard-coded_Credentials">
<summary><b>CWE-798: Use of Hard-coded Credentials</b> — affected files</summary>

- `config/src/main/resources/shared/notification-service.yml`

</details>

<details id="CWE-477_Use_of_Obsolete_Function">
<summary><b>CWE-477: Use of Obsolete Function</b> — affected files</summary>

- `notification-service/src/main/java/com/piggymetrics/notification/service/RecipientServiceImpl.java`
- `notification-service/src/main/java/com/piggymetrics/notification/repository/RecipientRepository.java`
- `account-service/src/main/java/com/piggymetrics/account/service/AccountServiceImpl.java`

</details>

---

## Codebase Insights

> **Note:** These documents are generated by AI and may contain inaccuracies or incomplete information. Please review carefully.

> **Codebase Insights aren't available yet.**
>
> These documents are generated when assessment runs with **Full analysis** coverage. Re-run the assessment and set `analysisCoverage: full` to enable them.

[Share feedback](https://aka.ms/ghcp-appmod/feedback)
