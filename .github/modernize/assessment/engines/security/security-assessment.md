# Security Assessment Report

**Generated:** 2026-06-22T06:51:31.0000000Z

## Summary

| Metric | Count |
|--------|-------|
| Total Findings | 176 |
| CVE Vulnerabilities | 170 |
| CWE Vulnerabilities | 6 |
| Total Rules Assessed | 59 |
| Rules Passed | 53 |

### By Severity

| Severity | Count |
|----------|-------|
| mandatory | 170 |
| optional | 3 |
| potential | 3 |

## CVE Findings (Dependency Vulnerabilities)

### CVE-2025-52999: jackson-core can throw a StackoverflowError when processing deeply nested data
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2025-52999](https://github.com/advisories/GHSA-h46c-h94j-95f3): jackson-core can throw a StackoverflowError when processing deeply nested data

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-core:2.9.6
    Vulnerable range: < 2.15.0

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-core to 2.15.0 or later

### CVE-2023-6378: logback serialization vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2023-6378](https://github.com/advisories/GHSA-vmq6-5m68-f53m): logback serialization vulnerability

Severity: HIGH

Affected dependencies:
  - ch.qos.logback:logback-classic:1.2.3
    Vulnerable range: >= 1.4.0, < 1.4.12
  - ch.qos.logback:logback-core:1.2.3
    Vulnerable range: >= 1.4.0, < 1.4.12
  - ch.qos.logback:logback-classic:1.2.3
    Vulnerable range: >= 1.3.0, < 1.3.12
  - ch.qos.logback:logback-core:1.2.3
    Vulnerable range: >= 1.3.0, < 1.3.12
  - ch.qos.logback:logback-core:1.2.3
    Vulnerable range: < 1.2.13
  - ch.qos.logback:logback-classic:1.2.3
    Vulnerable range: < 1.2.13

Recommended fix:
  - Upgrade ch.qos.logback:logback-classic to 1.4.12 or later
  - Upgrade ch.qos.logback:logback-core to 1.4.12 or later
  - Upgrade ch.qos.logback:logback-classic to 1.3.12 or later
  - Upgrade ch.qos.logback:logback-core to 1.3.12 or later
  - Upgrade ch.qos.logback:logback-core to 1.2.13 or later
  - Upgrade ch.qos.logback:logback-classic to 1.2.13 or later

### CVE-2022-42003: Uncontrolled Resource Consumption in Jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2022-42003](https://github.com/advisories/GHSA-jjjh-jjxp-wpff): Uncontrolled Resource Consumption in Jackson-databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.4.0-rc1, < 2.12.7.1
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.13.0, < 2.13.4.2

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.12.7.1 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.13.4.2 or later

### CVE-2022-42004: Uncontrolled Resource Consumption in FasterXML jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2022-42004](https://github.com/advisories/GHSA-rgv9-q543-rqg4): Uncontrolled Resource Consumption in FasterXML jackson-databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.13.0, < 2.13.4
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.4.0-rc1, < 2.12.7.1

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.13.4 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.12.7.1 or later

### CVE-2020-10650: jackson-databind vulnerable to unsafe deserialization
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-10650](https://github.com/advisories/GHSA-rpr3-cw39-3pxh): jackson-databind vulnerable to unsafe deserialization

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: <= 2.9.10.3

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.4 or later

### CVE-2022-25647: Deserialization of Untrusted Data in Gson
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2022-25647](https://github.com/advisories/GHSA-4jrv-ppp4-jm57): Deserialization of Untrusted Data in Gson

Severity: HIGH

Affected dependencies:
  - com.google.code.gson:gson:2.8.5
    Vulnerable range: < 2.8.9

Recommended fix:
  - Upgrade com.google.code.gson:gson to 2.8.9 or later

### CVE-2020-36518: Deeply nested json in jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-36518](https://github.com/advisories/GHSA-57j2-w4cx-62h2): Deeply nested json in jackson-databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.13.0, <= 2.13.2.0
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: <= 2.12.6.0

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.13.2.1 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.12.6.1 or later

### CVE-2020-36189: Unsafe Deserialization in jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-36189](https://github.com/advisories/GHSA-vfqx-33qm-g869): Unsafe Deserialization in jackson-databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.7.0, < 2.9.10.8
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: < 2.6.7.5

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.8 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.6.7.5 or later

### CVE-2020-36187: Unsafe Deserialization in jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-36187](https://github.com/advisories/GHSA-r695-7vr9-jgc2): Unsafe Deserialization in jackson-databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.0.0, < 2.9.10.8

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.8 or later

### CVE-2020-36188: Unsafe Deserialization in jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-36188](https://github.com/advisories/GHSA-f9xh-2qgp-cq57): Unsafe Deserialization in jackson-databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.7.0, < 2.9.10.8
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.0.0, < 2.6.7.5

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.8 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.6.7.5 or later

### CVE-2020-36183: Unsafe Deserialization in jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-36183](https://github.com/advisories/GHSA-9m6f-7xcq-8vf8): Unsafe Deserialization in jackson-databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.7.00, < 2.9.10.8
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.0.0, < 2.6.7.5

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.8 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.6.7.5 or later

### CVE-2020-36184: Unsafe Deserialization in jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-36184](https://github.com/advisories/GHSA-m6x4-97wx-4q27): Unsafe Deserialization in jackson-databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.0.0, < 2.9.10.8

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.8 or later

### CVE-2020-36180: Unsafe Deserialization in jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-36180](https://github.com/advisories/GHSA-8c4j-34r4-xr8g): Unsafe Deserialization in jackson-databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.7.0, < 2.9.10.8
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.0.0, < 2.6.7.5

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.8 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.6.7.5 or later

### CVE-2020-36181: Unsafe Deserialization in jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-36181](https://github.com/advisories/GHSA-cvm9-fjm9-3572): Unsafe Deserialization in jackson-databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.7.0, < 2.9.10.8
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.0.0, < 2.6.7.5

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.8 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.6.7.5 or later

### CVE-2020-36185: Unsafe Deserialization in jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-36185](https://github.com/advisories/GHSA-8w26-6f25-cm9x): Unsafe Deserialization in jackson-databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.0.0, < 2.9.10.8

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.8 or later

### CVE-2020-36179: Unsafe Deserialization in jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-36179](https://github.com/advisories/GHSA-9gph-22xh-8x98): Unsafe Deserialization in jackson-databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.7.0, < 2.9.10.8
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.0.0, < 2.6.7.5

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.8 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.6.7.5 or later

### CVE-2020-36182: Unsafe Deserialization in jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-36182](https://github.com/advisories/GHSA-89qr-369f-5m5x): Unsafe Deserialization in jackson-databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.7.0, < 2.9.10.8
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.0.0, < 2.6.7.5

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.8 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.6.7.5 or later

### CVE-2020-24750: Unsafe Deserialization in jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-24750](https://github.com/advisories/GHSA-qjw2-hr98-qgfh): Unsafe Deserialization in jackson-databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.0, <= 2.6.7.4
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.7.0, <= 2.9.10.5

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.6.7.5 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.6 or later

### CVE-2020-35728: Serialization gadget exploit in jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-35728](https://github.com/advisories/GHSA-5r5r-6hpj-8gg9): Serialization gadget exploit in jackson-databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.0.0, <= 2.9.10.7

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.8 or later

### CVE-2020-35491: Serialization gadgets exploit in jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-35491](https://github.com/advisories/GHSA-r3gr-cxrf-hg25): Serialization gadgets exploit in jackson-databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.0.0, <= 2.9.10.7

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.8 or later

### CVE-2020-35490: Serialization gadgets exploit in jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-35490](https://github.com/advisories/GHSA-wh8g-3j2c-rqj5): Serialization gadgets exploit in jackson-databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.0.0, <= 2.9.10.7

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.8 or later

### CVE-2020-24616: Code Injection in jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-24616](https://github.com/advisories/GHSA-h3cw-g4mq-c5x2): Code Injection in jackson-databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.0.0, <= 2.9.10.5

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.6 or later

### CVE-2020-36186: Unsafe Deserialization in jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-36186](https://github.com/advisories/GHSA-v585-23hc-c647): Unsafe Deserialization in jackson-databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.0.0, < 2.9.10.8

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.8 or later

### CVE-2020-25649: XML External Entity (XXE) Injection in Jackson Databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-25649](https://github.com/advisories/GHSA-288c-cq4h-88gq): XML External Entity (XXE) Injection in Jackson Databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.7.0.0, <= 2.9.10.6
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.10.0.0, <= 2.10.5.0
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.6.0, <= 2.6.7.3

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.7 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.10.5.1 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.6.7.4 or later

### CVE-2021-20190: Deserialization of untrusted data in jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2021-20190](https://github.com/advisories/GHSA-5949-rw7g-wx7w): Deserialization of untrusted data in jackson-databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.7.0, < 2.9.10.7
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: < 2.6.7.5

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.7 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.6.7.5 or later

### CVE-2020-14061: Deserialization of untrusted data in Jackson Databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-14061](https://github.com/advisories/GHSA-c2q3-4qrh-fm48): Deserialization of untrusted data in Jackson Databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.9.0, <= 2.9.10.4

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.5 or later

### CVE-2020-14062: Deserialization of untrusted data in Jackson Databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-14062](https://github.com/advisories/GHSA-c265-37vj-cwcc): Deserialization of untrusted data in Jackson Databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.9.0, <= 2.9.10.4

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.5 or later

### CVE-2020-14060: Deserialization of untrusted data in Jackson Databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-14060](https://github.com/advisories/GHSA-j823-4qch-3rgm): Deserialization of untrusted data in Jackson Databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.9.0, <= 2.9.10.4

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.5 or later

### CVE-2020-14195: Deserialization of untrusted data in Jackson Databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-14195](https://github.com/advisories/GHSA-mc6h-4qgp-37qh): Deserialization of untrusted data in Jackson Databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.9.0, <= 2.9.10.4

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.5 or later

### CVE-2019-17267: Improper Input Validation in jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2019-17267](https://github.com/advisories/GHSA-f3j5-rmmp-3fc5): Improper Input Validation in jackson-databind

Severity: CRITICAL

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.9.0, < 2.9.10
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: < 2.8.11.5

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.8.11.5 or later

### CVE-2020-11112: jackson-databind mishandles the interaction between serialization gadgets and typing
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-11112](https://github.com/advisories/GHSA-58pp-9c76-5625): jackson-databind mishandles the interaction between serialization gadgets and typing

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.9.0, <= 2.9.10.3

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.4 or later

### CVE-2020-9547: jackson-databind mishandles the interaction between serialization gadgets and typing
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-9547](https://github.com/advisories/GHSA-q93h-jc49-78gg): jackson-databind mishandles the interaction between serialization gadgets and typing

Severity: CRITICAL

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.9.0, < 2.9.10.4
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.8.0, < 2.8.11.6
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.0.0, < 2.7.9.7

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.4 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.8.11.6 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.7.9.7 or later

### CVE-2019-14893: Polymorphic deserialization of malicious object in jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2019-14893](https://github.com/advisories/GHSA-qmqc-x3r4-6v39): Polymorphic deserialization of malicious object in jackson-databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.9.0, < 2.9.10

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10 or later

### CVE-2020-10673: jackson-databind mishandles the interaction between serialization gadgets and typing
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-10673](https://github.com/advisories/GHSA-fqwf-pjwf-7vqv): jackson-databind mishandles the interaction between serialization gadgets and typing

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.7.0, < 2.9.10.4
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.0.0, < 2.6.7.4

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.4 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.6.7.4 or later

### CVE-2020-9548: jackson-databind mishandles the interaction between serialization gadgets and typing
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-9548](https://github.com/advisories/GHSA-p43x-xfjf-5jhr): jackson-databind mishandles the interaction between serialization gadgets and typing

Severity: CRITICAL

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.9.0, < 2.9.10.4
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.8.0, < 2.8.11.6
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.0.0, < 2.7.9.7

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.4 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.8.11.6 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.7.9.7 or later

### CVE-2019-14892: Polymorphic deserialization of malicious object in jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2019-14892](https://github.com/advisories/GHSA-cf6r-3wgc-h863): Polymorphic deserialization of malicious object in jackson-databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: <= 2.6.7.2
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.9.0, < 2.9.10
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.7.0, <= 2.8.11.4

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.6.7.3 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.8.11.5 or later

### CVE-2020-10968: jackson-databind mishandles the interaction between serialization gadgets and typing
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-10968](https://github.com/advisories/GHSA-rf6r-2c4q-2vwg): jackson-databind mishandles the interaction between serialization gadgets and typing

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.9.0, <= 2.9.10.3

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.4 or later

### CVE-2020-11111: jackson-databind mishandles the interaction between serialization gadgets and typing
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-11111](https://github.com/advisories/GHSA-v3xw-c963-f5hc): jackson-databind mishandles the interaction between serialization gadgets and typing

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.9.0, <= 2.9.10.3

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.4 or later

### CVE-2020-11113: jackson-databind mishandles the interaction between serialization gadgets and typing
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-11113](https://github.com/advisories/GHSA-9vvp-fxw6-jcxr): jackson-databind mishandles the interaction between serialization gadgets and typing

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.9.0, <= 2.9.10.3

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.4 or later

### CVE-2020-11619: jackson-databind mishandles the interaction between serialization gadgets and typing
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-11619](https://github.com/advisories/GHSA-27xj-rqx5-2255): jackson-databind mishandles the interaction between serialization gadgets and typing

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.9.0, <= 2.9.10.3

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.4 or later

### CVE-2020-10969: jackson-databind mishandles the interaction between serialization gadgets and typing
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-10969](https://github.com/advisories/GHSA-758m-v56v-grj4): jackson-databind mishandles the interaction between serialization gadgets and typing

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.9.0, <= 2.9.10.3

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.4 or later

### CVE-2020-9546: jackson-databind mishandles the interaction between serialization gadgets and typing
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-9546](https://github.com/advisories/GHSA-5p34-5m6p-p58g): jackson-databind mishandles the interaction between serialization gadgets and typing

Severity: CRITICAL

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.9.0, <= 2.9.10.3

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.4 or later

### CVE-2020-11620: jackson-databind mishandles the interaction between serialization gadgets and typing
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-11620](https://github.com/advisories/GHSA-h4rc-386g-6m85): jackson-databind mishandles the interaction between serialization gadgets and typing

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.9.0, <= 2.9.10.3

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.4 or later

### CVE-2020-10672: jackson-databind mishandles the interaction between serialization gadgets and typing
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-10672](https://github.com/advisories/GHSA-95cm-88f5-f2c7): jackson-databind mishandles the interaction between serialization gadgets and typing

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.9.0, <= 2.9.10.3

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.4 or later

### CVE-2020-8840: Deserialization of Untrusted Data in jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-8840](https://github.com/advisories/GHSA-4w82-r329-3q67): Deserialization of Untrusted Data in jackson-databind

Severity: CRITICAL

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.7.0, <= 2.7.9.6
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.8.0, <= 2.8.11.4
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.9.0, <= 2.9.10.2
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.0.0, <= 2.6.7.3

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.7.9.7 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.8.11.5 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.3 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.6.7.4 or later

### CVE-2019-20330: Deserialization of Untrusted Data in jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2019-20330](https://github.com/advisories/GHSA-gww7-p5w4-wrfv): Deserialization of Untrusted Data in jackson-databind

Severity: CRITICAL

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.7.0, <= 2.7.9.6
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.8.0, <= 2.8.11.4
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.9.0, <= 2.9.10.1
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.0.0, <= 2.6.7.3

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.7.9.7 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.8.11.5 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.2 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.6.7.4 or later

### CVE-2019-17531: jackson-databind polymorphic typing issue
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2019-17531](https://github.com/advisories/GHSA-gjmw-vf9h-g25v): jackson-databind polymorphic typing issue

Severity: CRITICAL

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.9.0, < 2.9.10.1
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.7.0, < 2.8.11.5
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: < 2.6.7.3

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.1 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.8.11.5 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.6.7.3 or later

### CVE-2019-16943: jackson-databind polymorphic typing issue
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2019-16943](https://github.com/advisories/GHSA-fmmc-742q-jg75): jackson-databind polymorphic typing issue

Severity: CRITICAL

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.9.0, < 2.9.10.1
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.7.0, < 2.8.11.5
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: < 2.6.7.3

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.1 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.8.11.5 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.6.7.3 or later

### CVE-2019-16942: Polymorphic Typing in FasterXML jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2019-16942](https://github.com/advisories/GHSA-mx7p-6679-8g3q): Polymorphic Typing in FasterXML jackson-databind

Severity: CRITICAL

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.9.0, < 2.9.10.1
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.0.0, < 2.6.7.3
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.7.0, < 2.8.11.5

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.1 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.6.7.3 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.8.11.5 or later

### CVE-2019-16335: Polymorphic Typing issue in FasterXML jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2019-16335](https://github.com/advisories/GHSA-85cw-hj65-qqv9): Polymorphic Typing issue in FasterXML jackson-databind

Severity: CRITICAL

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.9.0, < 2.9.10
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.7.0, < 2.8.11.5
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: < 2.6.7.3

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.8.11.5 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.6.7.3 or later

### CVE-2019-14540: Polymorphic Typing issue in FasterXML jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2019-14540](https://github.com/advisories/GHSA-h822-r4r5-v8jg): Polymorphic Typing issue in FasterXML jackson-databind

Severity: CRITICAL

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.9.0, < 2.9.10
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.7.0, < 2.8.11.5
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: < 2.6.7.3

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.8.11.5 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.6.7.3 or later

### CVE-2019-14439: Deserialization of untrusted data in FasterXML jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2019-14439](https://github.com/advisories/GHSA-gwp4-hfv6-p7hw): Deserialization of untrusted data in FasterXML jackson-databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.9.0, < 2.9.9.2
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.7.0, < 2.7.9.6
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: < 2.6.7.3
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.8.0, < 2.8.11.4

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.9.2 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.7.9.6 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.6.7.3 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.8.11.4 or later

### CVE-2019-14379: Deserialization of untrusted data in FasterXML jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2019-14379](https://github.com/advisories/GHSA-6fpp-rgj9-8rwc): Deserialization of untrusted data in FasterXML jackson-databind

Severity: CRITICAL

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.9.0, < 2.9.9.2
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.8.0, < 2.8.11.4
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: < 2.7.9.6

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.9.2 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.8.11.4 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.7.9.6 or later

### CVE-2019-12086: Information exposure in FasterXML jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2019-12086](https://github.com/advisories/GHSA-5ww9-j83m-q7qx): Information exposure in FasterXML jackson-databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.9.0, < 2.9.9
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.8.0, < 2.8.11.4
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.7.0, < 2.7.9.6
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.0.0, < 2.6.7.3

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.9 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.8.11.4 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.7.9.6 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.6.7.3 or later

### CVE-2018-14719: Arbitrary Code Execution in jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2018-14719](https://github.com/advisories/GHSA-4gq5-ch57-c2mg): Arbitrary Code Execution in jackson-databind

Severity: CRITICAL

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.9.0, < 2.9.7
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.8.0, <= 2.8.11.2
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.0.0, <= 2.7.9.4

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.7 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.8.11.3 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.7.9.5 or later

### CVE-2018-14720: XML External Entity Reference (XXE) in jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2018-14720](https://github.com/advisories/GHSA-x2w5-5m2g-7h5m): XML External Entity Reference (XXE) in jackson-databind

Severity: CRITICAL

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.9.0, < 2.9.7
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.8.0, <= 2.8.11.2
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.7.0, <= 2.7.9.2

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.7 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.8.11.3 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.7.9.5 or later

### CVE-2018-14721: Server-Side Request Forgery (SSRF) in jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2018-14721](https://github.com/advisories/GHSA-9mxf-g3x6-wv74): Server-Side Request Forgery (SSRF) in jackson-databind

Severity: CRITICAL

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.9.0, < 2.9.7
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.8.0, <= 2.8.11.2
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.7.0, <= 2.7.9.4

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.7 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.8.11.3 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.7.9.5 or later

### CVE-2018-19362: com.fasterxml.jackson.core:jackson-databind vulnerable to Deserialization of Untrusted Data
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2018-19362](https://github.com/advisories/GHSA-c8hm-7hpq-7jhg): com.fasterxml.jackson.core:jackson-databind vulnerable to Deserialization of Untrusted Data

Severity: CRITICAL

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.9.0, < 2.9.8
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.8.0, <= 2.8.11.2
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.7.0, <= 2.7.9.4
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.0.0, < 2.6.7.3

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.8 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.8.11.3 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.7.9.5 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.6.7.3 or later

### CVE-2018-19361: Deserialization of Untrusted Data in jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2018-19361](https://github.com/advisories/GHSA-mx9v-gmh4-mgqw): Deserialization of Untrusted Data in jackson-databind

Severity: CRITICAL

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.9.0, < 2.9.8
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.7.0, <= 2.7.9.4
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.8.0, <= 2.8.11.2

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.8 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.7.9.5 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.8.11.3 or later

### CVE-2018-19360: Deserialization of Untrusted Data in jackson-databind due to polymorphic deserialization
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2018-19360](https://github.com/advisories/GHSA-f9hv-mg5h-xcw9): Deserialization of Untrusted Data in jackson-databind due to polymorphic deserialization

Severity: CRITICAL

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.9.0, < 2.9.8
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.8.0, <= 2.8.11.2
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.7.0, <= 2.7.9.4

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.8 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.8.11.3 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.7.9.5 or later

### CVE-2018-14718: Arbitrary Code Execution in jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2018-14718](https://github.com/advisories/GHSA-645p-88qh-w398): Arbitrary Code Execution in jackson-databind

Severity: CRITICAL

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.9.0, < 2.9.7
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.8.0, <= 2.8.11.2
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.7.0, <= 2.7.9.4
  - com.fasterxml.jackson.core:jackson-databind:2.9.6
    Vulnerable range: >= 2.0.0, < 2.6.7.3

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.7 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.8.11.3 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.7.9.5 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.6.7.3 or later

### CVE-2024-47072: XStream is vulnerable to a Denial of Service attack due to stack overflow from a manipulated binary input stream
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2024-47072](https://github.com/advisories/GHSA-hfq9-hggm-c56q): XStream is vulnerable to a Denial of Service attack due to stack overflow from a manipulated binary input stream

Severity: HIGH

Affected dependencies:
  - com.thoughtworks.xstream:xstream:1.4.10
    Vulnerable range: < 1.4.21

Recommended fix:
  - Upgrade com.thoughtworks.xstream:xstream to 1.4.21 or later

### CVE-2022-40151: XStream can cause a Denial of Service by injecting deeply nested objects raising a stack overflow
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2022-40151](https://github.com/advisories/GHSA-f8cc-g7j8-xxpm): XStream can cause a Denial of Service by injecting deeply nested objects raising a stack overflow

Severity: HIGH

Affected dependencies:
  - com.thoughtworks.xstream:xstream:1.4.10
    Vulnerable range: < 1.4.20

Recommended fix:
  - Upgrade com.thoughtworks.xstream:xstream to 1.4.20 or later

### CVE-2022-41966: XStream can cause Denial of Service via stack overflow
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2022-41966](https://github.com/advisories/GHSA-j563-grx4-pjpv): XStream can cause Denial of Service via stack overflow

Severity: HIGH

Affected dependencies:
  - com.thoughtworks.xstream:xstream:1.4.10
    Vulnerable range: < 1.4.20

Recommended fix:
  - Upgrade com.thoughtworks.xstream:xstream to 1.4.20 or later

### CVE-2021-43859: Denial of Service by injecting highly recursive collections or maps in XStream
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2021-43859](https://github.com/advisories/GHSA-rmr5-cpv2-vgjf): Denial of Service by injecting highly recursive collections or maps in XStream

Severity: HIGH

Affected dependencies:
  - com.thoughtworks.xstream:xstream:1.4.10
    Vulnerable range: < 1.4.19

Recommended fix:
  - Upgrade com.thoughtworks.xstream:xstream to 1.4.19 or later

### CVE-2021-39139: XStream is vulnerable to an Arbitrary Code Execution attack
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2021-39139](https://github.com/advisories/GHSA-64xx-cq4q-mf44): XStream is vulnerable to an Arbitrary Code Execution attack

Severity: HIGH

Affected dependencies:
  - com.thoughtworks.xstream:xstream:1.4.10
    Vulnerable range: < 1.4.18

Recommended fix:
  - Upgrade com.thoughtworks.xstream:xstream to 1.4.18 or later

### CVE-2021-39141: XStream is vulnerable to an Arbitrary Code Execution attack
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2021-39141](https://github.com/advisories/GHSA-g5w6-mrj7-75h2): XStream is vulnerable to an Arbitrary Code Execution attack

Severity: HIGH

Affected dependencies:
  - com.thoughtworks.xstream:xstream:1.4.10
    Vulnerable range: < 1.4.18

Recommended fix:
  - Upgrade com.thoughtworks.xstream:xstream to 1.4.18 or later

### CVE-2021-39144: XStream is vulnerable to a Remote Command Execution attack
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2021-39144](https://github.com/advisories/GHSA-j9h8-phrw-h4fh): XStream is vulnerable to a Remote Command Execution attack

Severity: HIGH

Affected dependencies:
  - com.thoughtworks.xstream:xstream:1.4.10
    Vulnerable range: < 1.4.18

Recommended fix:
  - Upgrade com.thoughtworks.xstream:xstream to 1.4.18 or later

### CVE-2021-39145: XStream is vulnerable to an Arbitrary Code Execution attack
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2021-39145](https://github.com/advisories/GHSA-8jrj-525p-826v): XStream is vulnerable to an Arbitrary Code Execution attack

Severity: HIGH

Affected dependencies:
  - com.thoughtworks.xstream:xstream:1.4.10
    Vulnerable range: < 1.4.18

Recommended fix:
  - Upgrade com.thoughtworks.xstream:xstream to 1.4.18 or later

### CVE-2021-39146: XStream is vulnerable to an Arbitrary Code Execution attack
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2021-39146](https://github.com/advisories/GHSA-p8pq-r894-fm8f): XStream is vulnerable to an Arbitrary Code Execution attack

Severity: HIGH

Affected dependencies:
  - com.thoughtworks.xstream:xstream:1.4.10
    Vulnerable range: < 1.4.18

Recommended fix:
  - Upgrade com.thoughtworks.xstream:xstream to 1.4.18 or later

### CVE-2021-39147: XStream is vulnerable to an Arbitrary Code Execution attack
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2021-39147](https://github.com/advisories/GHSA-h7v4-7xg3-hxcc): XStream is vulnerable to an Arbitrary Code Execution attack

Severity: HIGH

Affected dependencies:
  - com.thoughtworks.xstream:xstream:1.4.10
    Vulnerable range: < 1.4.18

Recommended fix:
  - Upgrade com.thoughtworks.xstream:xstream to 1.4.18 or later

### CVE-2021-39148: XStream is vulnerable to an Arbitrary Code Execution attack
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2021-39148](https://github.com/advisories/GHSA-qrx8-8545-4wg2): XStream is vulnerable to an Arbitrary Code Execution attack

Severity: HIGH

Affected dependencies:
  - com.thoughtworks.xstream:xstream:1.4.10
    Vulnerable range: < 1.4.18

Recommended fix:
  - Upgrade com.thoughtworks.xstream:xstream to 1.4.18 or later

### CVE-2021-39149: XStream is vulnerable to an Arbitrary Code Execution attack
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2021-39149](https://github.com/advisories/GHSA-3ccq-5vw3-2p6x): XStream is vulnerable to an Arbitrary Code Execution attack

Severity: HIGH

Affected dependencies:
  - com.thoughtworks.xstream:xstream:1.4.10
    Vulnerable range: < 1.4.18

Recommended fix:
  - Upgrade com.thoughtworks.xstream:xstream to 1.4.18 or later

### CVE-2021-39150: A Server-Side Forgery Request can be activated unmarshalling with XStream to access data streams from an arbitrary URL referencing a resource in an intranet or the local host
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2021-39150](https://github.com/advisories/GHSA-cxfm-5m4g-x7xp): A Server-Side Forgery Request can be activated unmarshalling with XStream to access data streams from an arbitrary URL referencing a resource in an intranet or the local host

Severity: HIGH

Affected dependencies:
  - com.thoughtworks.xstream:xstream:1.4.10
    Vulnerable range: < 1.4.18

Recommended fix:
  - Upgrade com.thoughtworks.xstream:xstream to 1.4.18 or later

### CVE-2021-39151: XStream is vulnerable to an Arbitrary Code Execution attack
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2021-39151](https://github.com/advisories/GHSA-hph2-m3g5-xxv4): XStream is vulnerable to an Arbitrary Code Execution attack

Severity: HIGH

Affected dependencies:
  - com.thoughtworks.xstream:xstream:1.4.10
    Vulnerable range: < 1.4.18

Recommended fix:
  - Upgrade com.thoughtworks.xstream:xstream to 1.4.18 or later

### CVE-2021-39152: A Server-Side Forgery Request can be activated unmarshalling with XStream to access data streams from an arbitrary URL referencing a resource in an intranet or the local host
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2021-39152](https://github.com/advisories/GHSA-xw4p-crpj-vjx2): A Server-Side Forgery Request can be activated unmarshalling with XStream to access data streams from an arbitrary URL referencing a resource in an intranet or the local host

Severity: HIGH

Affected dependencies:
  - com.thoughtworks.xstream:xstream:1.4.10
    Vulnerable range: < 1.4.18

Recommended fix:
  - Upgrade com.thoughtworks.xstream:xstream to 1.4.18 or later

### CVE-2021-39153: XStream is vulnerable to an Arbitrary Code Execution attack
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2021-39153](https://github.com/advisories/GHSA-2q8x-2p7f-574v): XStream is vulnerable to an Arbitrary Code Execution attack

Severity: HIGH

Affected dependencies:
  - com.thoughtworks.xstream:xstream:1.4.10
    Vulnerable range: < 1.4.18

Recommended fix:
  - Upgrade com.thoughtworks.xstream:xstream to 1.4.18 or later

### CVE-2021-39154: XStream is vulnerable to an Arbitrary Code Execution attack
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2021-39154](https://github.com/advisories/GHSA-6w62-hx7r-mw68): XStream is vulnerable to an Arbitrary Code Execution attack

Severity: HIGH

Affected dependencies:
  - com.thoughtworks.xstream:xstream:1.4.10
    Vulnerable range: < 1.4.18

Recommended fix:
  - Upgrade com.thoughtworks.xstream:xstream to 1.4.18 or later

### CVE-2021-29505: XStream is vulnerable to a Remote Command Execution attack
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2021-29505](https://github.com/advisories/GHSA-7chv-rrw6-w6fc): XStream is vulnerable to a Remote Command Execution attack

Severity: HIGH

Affected dependencies:
  - com.thoughtworks.xstream:xstream:1.4.10
    Vulnerable range: < 1.4.17

Recommended fix:
  - Upgrade com.thoughtworks.xstream:xstream to 1.4.17 or later

### CVE-2021-21341: XStream can cause a Denial of Service.
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2021-21341](https://github.com/advisories/GHSA-2p3x-qw9c-25hh): XStream can cause a Denial of Service.

Severity: HIGH

Affected dependencies:
  - com.thoughtworks.xstream:xstream:1.4.10
    Vulnerable range: < 1.4.16

Recommended fix:
  - Upgrade com.thoughtworks.xstream:xstream to 1.4.16 or later

### CVE-2020-26217: XStream can be used for Remote Code Execution
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-26217](https://github.com/advisories/GHSA-mw36-7c6c-q4q2): XStream can be used for Remote Code Execution

Severity: HIGH

Affected dependencies:
  - com.thoughtworks.xstream:xstream:1.4.10
    Vulnerable range: <= 1.4.13

Recommended fix:
  - Upgrade com.thoughtworks.xstream:xstream to 1.4.14-java7 or later

### CVE-2019-10173: Deserialization of Untrusted Data and Code Injection in xstream
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2019-10173](https://github.com/advisories/GHSA-hf23-9pf7-388p): Deserialization of Untrusted Data and Code Injection in xstream

Severity: CRITICAL

Affected dependencies:
  - com.thoughtworks.xstream:xstream:1.4.10
    Vulnerable range: = 1.4.10

Recommended fix:
  - Upgrade com.thoughtworks.xstream:xstream to 1.4.11 or later

### CVE-2013-7285: Command Injection in Xstream
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2013-7285](https://github.com/advisories/GHSA-f554-x222-wgf7): Command Injection in Xstream

Severity: CRITICAL

Affected dependencies:
  - com.thoughtworks.xstream:xstream:1.4.10
    Vulnerable range: < 1.4.7
  - com.thoughtworks.xstream:xstream:1.4.10
    Vulnerable range: = 1.4.10

Recommended fix:
  - Upgrade com.thoughtworks.xstream:xstream to 1.4.7 or later
  - Upgrade com.thoughtworks.xstream:xstream to 1.4.11 or later

### CVE-2026-50010: Netty: Wrapping plain trust manager silently disables hostname verification
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2026-50010](https://github.com/advisories/GHSA-c653-97m9-rcg9): Netty: Wrapping plain trust manager silently disables hostname verification

Severity: HIGH

Affected dependencies:
  - io.netty:netty-handler:4.1.25.Final
    Vulnerable range: >= 4.2.0.Final, < 4.2.15.Final
  - io.netty:netty-handler:4.1.25.Final
    Vulnerable range: <= 4.1.134.Final

Recommended fix:
  - Upgrade io.netty:netty-handler to 4.2.15.Final or later
  - Upgrade io.netty:netty-handler to 4.1.135.Final or later

### CVE-2026-45416: Netty: SNI handler pre-allocates up to 16 MiB from nine attacker bytes
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2026-45416](https://github.com/advisories/GHSA-x4gw-5cx5-pgmh): Netty: SNI handler pre-allocates up to 16 MiB from nine attacker bytes

Severity: HIGH

Affected dependencies:
  - io.netty:netty-handler:4.1.25.Final
    Vulnerable range: >= 4.2.0.Final, <= 4.2.14.Final
  - io.netty:netty-handler:4.1.25.Final
    Vulnerable range: <= 4.1.134.Final

Recommended fix:
  - Upgrade io.netty:netty-handler to 4.2.15.Final or later
  - Upgrade io.netty:netty-handler to 4.1.135.Final or later

### CVE-2026-44249: Netty has an IPv6 Subnet Filter Bypass via Incorrect Comparator Masking
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2026-44249](https://github.com/advisories/GHSA-3qp7-7mw8-wx86): Netty has an IPv6 Subnet Filter Bypass via Incorrect Comparator Masking

Severity: HIGH

Affected dependencies:
  - io.netty:netty-handler:4.1.25.Final
    Vulnerable range: >= 4.2.0.Final, <= 4.2.14.Final
  - io.netty:netty-handler:4.1.25.Final
    Vulnerable range: <= 4.1.134.Final

Recommended fix:
  - Upgrade io.netty:netty-handler to 4.2.15.Final or later
  - Upgrade io.netty:netty-handler to 4.1.135.Final or later

### CVE-2026-42587: Netty: HttpContentDecompressor maxAllocation bypass when Content-Encoding set to br/zstd/snappy leads to decompression bomb DoS
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2026-42587](https://github.com/advisories/GHSA-f6hv-jmp6-3vwv): Netty: HttpContentDecompressor maxAllocation bypass when Content-Encoding set to br/zstd/snappy leads to decompression bomb DoS

Severity: HIGH

Affected dependencies:
  - io.netty:netty-codec-http:4.1.25.Final
    Vulnerable range: >= 4.2.0.Alpha1, <= 4.2.12.Final
  - io.netty:netty-codec-http:4.1.25.Final
    Vulnerable range: <= 4.1.132.Final

Recommended fix:
  - Upgrade io.netty:netty-codec-http to 4.2.13.Final or later
  - Upgrade io.netty:netty-codec-http to 4.1.133.Final or later

### CVE-2026-42584: Netty has HttpClientCodec response desynchronization
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2026-42584](https://github.com/advisories/GHSA-57rv-r2g8-2cj3): Netty has HttpClientCodec response desynchronization

Severity: HIGH

Affected dependencies:
  - io.netty:netty-codec-http:4.1.25.Final
    Vulnerable range: >= 4.2.0.Alpha1, <= 4.2.12.Final
  - io.netty:netty-codec-http:4.1.25.Final
    Vulnerable range: <= 4.1.132.Final

Recommended fix:
  - Upgrade io.netty:netty-codec-http to 4.2.13.Final or later
  - Upgrade io.netty:netty-codec-http to 4.1.133.Final or later

### CVE-2026-42583: Netty Lz4FrameDecoder is vulnerable to resource exhaustion 
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2026-42583](https://github.com/advisories/GHSA-mj4r-2hfc-f8p6): Netty Lz4FrameDecoder is vulnerable to resource exhaustion 

Severity: HIGH

Affected dependencies:
  - io.netty:netty-codec:4.1.25.Final
    Vulnerable range: <= 4.1.132.Final

Recommended fix:
  - Upgrade io.netty:netty-codec to 4.1.133.Final or later

### CVE-2026-33870: Netty: HTTP Request Smuggling via Chunked Extension Quoted-String Parsing
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2026-33870](https://github.com/advisories/GHSA-pwqr-wmgm-9rr8): Netty: HTTP Request Smuggling via Chunked Extension Quoted-String Parsing

Severity: HIGH

Affected dependencies:
  - io.netty:netty-codec-http:4.1.25.Final
    Vulnerable range: < 4.1.132.Final
  - io.netty:netty-codec-http:4.1.25.Final
    Vulnerable range: >= 4.2.0.Alpha1, < 4.2.10.Final

Recommended fix:
  - Upgrade io.netty:netty-codec-http to 4.1.132.Final or later
  - Upgrade io.netty:netty-codec-http to 4.2.10.Final or later

### CVE-2024-47554: Apache Commons IO: Possible denial of service attack on untrusted input to XmlStreamReader
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2024-47554](https://github.com/advisories/GHSA-78wr-2p64-hpwj): Apache Commons IO: Possible denial of service attack on untrusted input to XmlStreamReader

Severity: HIGH

Affected dependencies:
  - commons-io:commons-io:2.4
    Vulnerable range: >= 2.0, < 2.14.0

Recommended fix:
  - Upgrade commons-io:commons-io to 2.14.0 or later

### CVE-2021-37137:  SnappyFrameDecoder doesn't restrict chunk length any may buffer skippable chunks in an unnecessary way
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2021-37137](https://github.com/advisories/GHSA-9vjp-v76f-g363):  SnappyFrameDecoder doesn't restrict chunk length any may buffer skippable chunks in an unnecessary way

Severity: HIGH

Affected dependencies:
  - io.netty:netty-codec:4.1.25.Final
    Vulnerable range: >= 4.0.0, < 4.1.68.Final

Recommended fix:
  - Upgrade io.netty:netty-codec to 4.1.68.Final or later

### CVE-2021-37136: Bzip2Decoder doesn't allow setting size restrictions for decompressed data
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2021-37136](https://github.com/advisories/GHSA-grg4-wf29-r9vv): Bzip2Decoder doesn't allow setting size restrictions for decompressed data

Severity: HIGH

Affected dependencies:
  - io.netty:netty-codec:4.1.25.Final
    Vulnerable range: < 4.1.68.Final

Recommended fix:
  - Upgrade io.netty:netty-codec to 4.1.68.Final or later

### CVE-2020-11612: Denial of Service in Netty
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-11612](https://github.com/advisories/GHSA-mm9x-g8pc-w292): Denial of Service in Netty

Severity: HIGH

Affected dependencies:
  - io.netty:netty-handler:4.1.25.Final
    Vulnerable range: >= 4.1.0, < 4.1.46

Recommended fix:
  - Upgrade io.netty:netty-handler to 4.1.46 or later

### CVE-2019-20444: HTTP Request Smuggling in Netty
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2019-20444](https://github.com/advisories/GHSA-cqqj-4p63-rrmm): HTTP Request Smuggling in Netty

Severity: CRITICAL

Affected dependencies:
  - io.netty:netty-codec-http:4.1.25.Final
    Vulnerable range: < 4.1.44

Recommended fix:
  - Upgrade io.netty:netty-codec-http to 4.1.44 or later

### CVE-2023-1370: json-smart Uncontrolled Recursion vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2023-1370](https://github.com/advisories/GHSA-493p-pfq6-5258): json-smart Uncontrolled Recursion vulnerability

Severity: HIGH

Affected dependencies:
  - net.minidev:json-smart:2.3
    Vulnerable range: < 2.4.9

Recommended fix:
  - Upgrade net.minidev:json-smart to 2.4.9 or later

### CVE-2026-41284: Apache Tomcat: Unbounded read in WebDAV LOCK and  PROPFIND handling
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2026-41284](https://github.com/advisories/GHSA-gx5v-xp9w-j4cg): Apache Tomcat: Unbounded read in WebDAV LOCK and  PROPFIND handling

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: < 9.0.118
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 10.1.0-M1, < 10.1.55
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 11.0.0-M1, < 11.0.22

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.118 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.1.55 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.22 or later

### CVE-2026-43512: Apache Tomcat - Digest authenticator will authenticate any unknown user
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2026-43512](https://github.com/advisories/GHSA-h6fc-48rj-7qqh): Apache Tomcat - Digest authenticator will authenticate any unknown user

Severity: CRITICAL

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: < 9.0.118
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 10.1.0-M1, < 10.1.55
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 11.0.0-M1, < 11.0.22

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.118 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.1.55 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.22 or later

### CVE-2026-43513: Apache Tomcat: LockOutRealm treats user names as case-sensitive
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2026-43513](https://github.com/advisories/GHSA-5mp6-jrq3-r938): Apache Tomcat: LockOutRealm treats user names as case-sensitive

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: < 9.0.118
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 10.1.0-M1, < 10.1.55
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 11.0.0-M1, < 11.0.22

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.118 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.1.55 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.22 or later

### CVE-2026-43515: Apache Tomcat - Security constraints not correctly applied
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2026-43515](https://github.com/advisories/GHSA-5m62-pw8w-7w9f): Apache Tomcat - Security constraints not correctly applied

Severity: CRITICAL

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: < 9.0.118
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 10.1.0-M1, < 10.1.55
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 11.0.0-M1, < 11.0.22

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.118 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.1.55 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.22 or later

### CVE-2026-41293: Apache Tomcat - HTTP/2 request headers not validated
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2026-41293](https://github.com/advisories/GHSA-r29c-68gh-xp6x): Apache Tomcat - HTTP/2 request headers not validated

Severity: CRITICAL

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: < 9.0.118
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 10.1.0-M1, < 10.1.55
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 11.0.0-M1, < 11.0.22

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.118 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.1.55 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.22 or later

### CVE-2026-42498: Apache Tomcat - WebSocket authentication header exposure
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2026-42498](https://github.com/advisories/GHSA-fv25-8xcx-gqjc): Apache Tomcat - WebSocket authentication header exposure

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: < 9.0.118
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 10.1.0-M1, < 10.1.55
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 11.0.0-M1, < 11.0.22

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.118 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.1.55 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.22 or later

### CVE-2026-24880: Apache Tomcat has an HTTP Request/Response Smuggling vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2026-24880](https://github.com/advisories/GHSA-563x-q5rq-57qp): Apache Tomcat has an HTTP Request/Response Smuggling vulnerability

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 7.0.0, < 9.0.116
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 10.1.0-M1, < 10.1.52
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 11.0.0-M1, <= 11.0.18

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.116 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.1.52 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.20 or later

### CVE-2026-24400: AssertJ has XML External Entity (XXE) vulnerability when parsing untrusted XML via isXmlEqualTo assertion
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2026-24400](https://github.com/advisories/GHSA-rqfh-9r24-8c9r): AssertJ has XML External Entity (XXE) vulnerability when parsing untrusted XML via isXmlEqualTo assertion

Severity: HIGH

Affected dependencies:
  - org.assertj:assertj-core:3.9.1
    Vulnerable range: >= 1.4.0, <= 3.27.6

Recommended fix:
  - Upgrade org.assertj:assertj-core to 3.27.7 or later

### CVE-2025-55752: Apache Tomcat Vulnerable to Relative Path Traversal
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2025-55752](https://github.com/advisories/GHSA-wmwf-9ccg-fff5): Apache Tomcat Vulnerable to Relative Path Traversal

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 11.0.0-M1, < 11.0.11
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 10.1.0-M1, < 10.1.45
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 9.0.0-M11, < 9.0.109
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 8.5.6, <= 8.5.100

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.11 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.1.45 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.109 or later

### CVE-2025-53506: Apache Tomcat Coyote vulnerable to Denial of Service via excessive HTTP/2 streams
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2025-53506](https://github.com/advisories/GHSA-25xr-qj8w-c4vf): Apache Tomcat Coyote vulnerable to Denial of Service via excessive HTTP/2 streams

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 8.5.0, <= 8.5.100
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 9.0.0.M1, < 9.0.107
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 10.1.0-M1, < 10.1.43
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 11.0.0-M1, < 11.0.9

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.107 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.1.43 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.9 or later

### CVE-2025-52520: Apache Tomcat Catalina is vulnerable to DoS attack through bypassing of size limits
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2025-52520](https://github.com/advisories/GHSA-wr62-c79q-cv37): Apache Tomcat Catalina is vulnerable to DoS attack through bypassing of size limits

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 11.0.0-M1, < 11.0.9
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 10.1.0-M1, < 10.1.43
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 9.0.0.M1, < 9.0.107
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 8.5.0, <= 8.5.100

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.9 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.1.43 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.107 or later

### CVE-2025-48988: Apache Tomcat - DoS in multipart upload
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2025-48988](https://github.com/advisories/GHSA-h3gc-qfqq-6h8f): Apache Tomcat - DoS in multipart upload

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 11.0.0-M1, <= 11.0.7
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 10.1.0-M1, <= 10.1.41
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 9.0.0.M1, <= 9.0.105
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 8.5.0, <= 8.5.100

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.8 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.1.42 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.106 or later

### CVE-2025-24813: Apache Tomcat: Potential RCE and/or information disclosure and/or information corruption with partial PUT
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2025-24813](https://github.com/advisories/GHSA-83qj-6fr2-vhqg): Apache Tomcat: Potential RCE and/or information disclosure and/or information corruption with partial PUT

Severity: CRITICAL

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 11.0.0-M1, < 11.0.3
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 10.1.0-M1, < 10.1.35
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 9.0.0.M1, < 9.0.99
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 8.5.0, <= 8.5.100

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.3 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.1.35 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.99 or later

### CVE-2024-50379: Apache Tomcat Time-of-check Time-of-use (TOCTOU) Race Condition vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2024-50379](https://github.com/advisories/GHSA-5j33-cvvr-w245): Apache Tomcat Time-of-check Time-of-use (TOCTOU) Race Condition vulnerability

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 11.0.0-M1, < 11.0.2
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 10.1.0-M1, < 10.1.34
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 9.0.0.M1, < 9.0.98
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 8.5.0, <= 8.5.100

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.2 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.1.34 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.98 or later

### CVE-2024-34750: Apache Tomcat - Denial of Service
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2024-34750](https://github.com/advisories/GHSA-wm9w-rjj3-j356): Apache Tomcat - Denial of Service

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 11.0.0-M1, < 11.0.0-M21
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 10.1.0-M1, < 10.1.25
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 9.0.0-M1, < 9.0.90
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 8.5.0, <= 8.5.100

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.0-M21 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.1.25 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.90 or later

### CVE-2023-46589: Apache Tomcat Improper Input Validation vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2023-46589](https://github.com/advisories/GHSA-fccv-jmmp-qg76): Apache Tomcat Improper Input Validation vulnerability

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 11.0.0-M1, < 11.0.0-M11
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 10.1.0-M1, < 10.1.16
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 9.0.0-M1, < 9.0.83
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 8.5.0, < 8.5.96

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.0-M11 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.1.16 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.83 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 8.5.96 or later

### CVE-2023-4759: Arbitrary File Overwrite in Eclipse JGit 
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2023-4759](https://github.com/advisories/GHSA-3p86-9955-h393): Arbitrary File Overwrite in Eclipse JGit 

Severity: HIGH

Affected dependencies:
  - org.eclipse.jgit:org.eclipse.jgit:4.11.0.201803080745-r
    Vulnerable range: >= 6.0.0.202111291000-r, <= 6.6.0.202305301015-r
  - org.eclipse.jgit:org.eclipse.jgit:4.11.0.201803080745-r
    Vulnerable range: < 5.13.3.202401111512-r

Recommended fix:
  - Upgrade org.eclipse.jgit:org.eclipse.jgit to 6.6.1.202309021850-r or later
  - Upgrade org.eclipse.jgit:org.eclipse.jgit to 5.13.3.202401111512-r or later

### CVE-2023-1436: Jettison vulnerable to infinite recursion
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2023-1436](https://github.com/advisories/GHSA-q6g2-g7f3-rr83): Jettison vulnerable to infinite recursion

Severity: HIGH

Affected dependencies:
  - org.codehaus.jettison:jettison:1.3.7
    Vulnerable range: < 1.5.4

Recommended fix:
  - Upgrade org.codehaus.jettison:jettison to 1.5.4 or later

### CVE-2022-45693: Jettison Out-of-bounds Write vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2022-45693](https://github.com/advisories/GHSA-grr4-wv38-f68w): Jettison Out-of-bounds Write vulnerability

Severity: HIGH

Affected dependencies:
  - org.codehaus.jettison:jettison:1.3.7
    Vulnerable range: < 1.5.2

Recommended fix:
  - Upgrade org.codehaus.jettison:jettison to 1.5.2 or later

### CVE-2022-45685: Jettison Out-of-bounds Write vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2022-45685](https://github.com/advisories/GHSA-7rf3-mqpx-h7xg): Jettison Out-of-bounds Write vulnerability

Severity: HIGH

Affected dependencies:
  - org.codehaus.jettison:jettison:1.3.7
    Vulnerable range: < 1.5.2

Recommended fix:
  - Upgrade org.codehaus.jettison:jettison to 1.5.2 or later

### CVE-2022-42252: Apache Tomcat may reject request containing invalid Content-Length header
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2022-42252](https://github.com/advisories/GHSA-p22x-g9px-3945): Apache Tomcat may reject request containing invalid Content-Length header

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 8.5.0, < 8.5.83
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 9.0.0-M1, < 9.0.68
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 10.0.0-M1, < 10.0.27
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 10.1.0-M1, < 10.1.1

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 8.5.83 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.68 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.0.27 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.1.1 or later

### CVE-2022-40150: Jettison memory exhaustion
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2022-40150](https://github.com/advisories/GHSA-x27m-9w8j-5vcw): Jettison memory exhaustion

Severity: HIGH

Affected dependencies:
  - org.codehaus.jettison:jettison:1.3.7
    Vulnerable range: < 1.5.2

Recommended fix:
  - Upgrade org.codehaus.jettison:jettison to 1.5.2 or later

### CVE-2019-10202: Deserialization of Untrusted Data in org.codehaus.jackson:jackson-mapper-asl
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2019-10202](https://github.com/advisories/GHSA-c27h-mcmw-48hv): Deserialization of Untrusted Data in org.codehaus.jackson:jackson-mapper-asl

Severity: CRITICAL

Affected dependencies:
  - org.codehaus.jackson:jackson-mapper-asl:1.9.2
    Vulnerable range: <= 1.9.13

### CVE-2020-11996: Uncontrolled Resource Consumption in Apache Tomcat
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-11996](https://github.com/advisories/GHSA-53hp-jpwq-2jgq): Uncontrolled Resource Consumption in Apache Tomcat

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 10.0.0-M1, <= 10.0.0-M4
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 9.0.0.M1, < 9.0.35
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 8.5.0, < 8.5.55

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.0.0-M5 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.35 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 8.5.55 or later

### CVE-2020-13935: Infinite Loop in Apache Tomcat
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-13935](https://github.com/advisories/GHSA-m7jv-hq7h-mq7c): Infinite Loop in Apache Tomcat

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-websocket:8.5.31
    Vulnerable range: >= 7.0.27, < 7.0.105
  - org.apache.tomcat.embed:tomcat-embed-websocket:8.5.31
    Vulnerable range: >= 8.5.0, < 8.5.57
  - org.apache.tomcat.embed:tomcat-embed-websocket:8.5.31
    Vulnerable range: >= 9.0.0.M1, < 9.0.37
  - org.apache.tomcat.embed:tomcat-embed-websocket:8.5.31
    Vulnerable range: >= 10.0.0-M1, < 10.0.0-M7

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-websocket to 7.0.105 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-websocket to 8.5.57 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-websocket to 9.0.37 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-websocket to 10.0.0-M7 or later

### CVE-2021-36090: Improper Handling of Length Parameter Inconsistency in Compress
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2021-36090](https://github.com/advisories/GHSA-mc84-pj99-q6hh): Improper Handling of Length Parameter Inconsistency in Compress

Severity: HIGH

Affected dependencies:
  - org.apache.commons:commons-compress:1.10
    Vulnerable range: < 1.21

Recommended fix:
  - Upgrade org.apache.commons:commons-compress to 1.21 or later

### CVE-2021-35517: Improper Handling of Length Parameter Inconsistency in Compress
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2021-35517](https://github.com/advisories/GHSA-xqfj-vm6h-2x34): Improper Handling of Length Parameter Inconsistency in Compress

Severity: HIGH

Affected dependencies:
  - org.apache.commons:commons-compress:1.10
    Vulnerable range: < 1.21

Recommended fix:
  - Upgrade org.apache.commons:commons-compress to 1.21 or later

### CVE-2021-35516: Improper Handling of Length Parameter Inconsistency in Compress
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2021-35516](https://github.com/advisories/GHSA-crv7-7245-f45f): Improper Handling of Length Parameter Inconsistency in Compress

Severity: HIGH

Affected dependencies:
  - org.apache.commons:commons-compress:1.10
    Vulnerable range: < 1.21

Recommended fix:
  - Upgrade org.apache.commons:commons-compress to 1.21 or later

### CVE-2021-35515: Excessive Iteration in Compress
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2021-35515](https://github.com/advisories/GHSA-7hfm-57qf-j43q): Excessive Iteration in Compress

Severity: HIGH

Affected dependencies:
  - org.apache.commons:commons-compress:1.10
    Vulnerable range: < 1.21

Recommended fix:
  - Upgrade org.apache.commons:commons-compress to 1.21 or later

### CVE-2021-25122: Exposure of Sensitive Information to an Unauthorized Actor in Apache Tomcat
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2021-25122](https://github.com/advisories/GHSA-j39c-c8hj-x4j3): Exposure of Sensitive Information to an Unauthorized Actor in Apache Tomcat

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 8.5.0, < 8.5.63
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 10.0.0-M1, < 10.0.2
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 9.0.0-M1, < 9.0.43

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 8.5.63 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.0.2 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.43 or later

### CVE-2021-25329: Potential remote code execution in Apache Tomcat
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2021-25329](https://github.com/advisories/GHSA-jgwr-3qm3-26f3): Potential remote code execution in Apache Tomcat

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 10.0.0-M1, < 10.0.2
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 9.0.0, < 9.0.41
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 8.0.0, < 8.5.61
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 7.0.0, < 7.0.107

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.0.2 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.41 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 8.5.61 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 7.0.108 or later

### CVE-2020-1938: Improper Privilege Management in Tomcat
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-1938](https://github.com/advisories/GHSA-c9hw-wf7x-jp9j): Improper Privilege Management in Tomcat

Severity: CRITICAL

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 9.0.0, < 9.0.31
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 8.0.0, < 8.5.51
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 7.0.0, < 7.0.100

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.31 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 8.5.51 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 7.0.100 or later

### CVE-2019-0199: Apache Tomcat Denial of Service vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2019-0199](https://github.com/advisories/GHSA-qcxh-w3j9-58qr): Apache Tomcat Denial of Service vulnerability

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 9.0.0, < 9.0.16
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 8.0.0, < 8.5.38

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.16 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 8.5.38 or later

### CVE-2020-9484: Potential remote code execution in Apache Tomcat
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-9484](https://github.com/advisories/GHSA-344f-f5vg-2jfj): Potential remote code execution in Apache Tomcat

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 10.0.0-M1, <= 10.0.0-M4
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 9.0.0, < 9.0.35
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 8.0.0, < 8.5.55
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 7.0.0, < 7.0.104

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.0.0-M5 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.35 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 8.5.55 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 7.0.104 or later

### CVE-2019-10172: Improper Restriction of XML External Entity Reference in jackson-mapper-asl
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2019-10172](https://github.com/advisories/GHSA-r6j9-8759-g62w): Improper Restriction of XML External Entity Reference in jackson-mapper-asl

Severity: HIGH

Affected dependencies:
  - org.codehaus.jackson:jackson-mapper-asl:1.9.2
    Vulnerable range: <= 1.9.13

### CVE-2019-12418: Insufficiently Protected Credentials in Apache Tomcat
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2019-12418](https://github.com/advisories/GHSA-hh3j-x4mc-g48r): Insufficiently Protected Credentials in Apache Tomcat

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: < 7.0.98
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 8.0.0, < 8.5.48
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 9.0.0, < 9.0.29

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 7.0.99 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 8.5.49 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.29 or later

### CVE-2019-17563: In Apache Tomcat, when using FORM authentication there was a narrow window where an attacker could perform a session fixation attack
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2019-17563](https://github.com/advisories/GHSA-9xcj-c8cr-8c3c): In Apache Tomcat, when using FORM authentication there was a narrow window where an attacker could perform a session fixation attack

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: < 7.0.99
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 8.0.0, < 8.5.50
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 9.0.0, < 9.0.30

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 7.0.99 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 8.5.50 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.30 or later

### CVE-2019-10072: Improper Locking in Apache Tomcat
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2019-10072](https://github.com/advisories/GHSA-q4hg-rmq2-52q9): Improper Locking in Apache Tomcat

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 9.0.0.M1, < 9.0.20
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 8.5.0, < 8.5.41

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.20 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 8.5.41 or later

### CVE-2019-0232: Apache Tomcat OS Command Injection vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2019-0232](https://github.com/advisories/GHSA-8vmx-qmch-mpqg): Apache Tomcat OS Command Injection vulnerability

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 8.0.0, < 8.5.40
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 7.0.0, < 7.0.94
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 9.0.0.M1, < 9.0.17

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 8.5.40 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 7.0.94 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.17 or later

### CVE-2018-8034: The host name verification missing in Apache Tomcat
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2018-8034](https://github.com/advisories/GHSA-46j3-r4pj-4835): The host name verification missing in Apache Tomcat

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 9.0.0, <= 9.0.9
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 8.5.0, < 8.5.32
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 8.0.0, < 8.0.53
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 7.0.35, <= 7.0.88

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.10 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 8.5.32 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 8.0.53 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 7.0.90 or later

### CVE-2018-8014: The defaults settings for the CORS filter provided in Apache Tomcat are insecure and enable 'supportsCredentials' for all origins
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2018-8014](https://github.com/advisories/GHSA-r4x2-3cq5-hqvp): The defaults settings for the CORS filter provided in Apache Tomcat are insecure and enable 'supportsCredentials' for all origins

Severity: CRITICAL

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 8.5.0, < 8.5.32
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 7.0.41, < 7.0.88
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 9.0.0.M1, <= 9.0.8
  - org.apache.tomcat.embed:tomcat-embed-core:8.5.31
    Vulnerable range: >= 8.0.0RC1, < 8.0.53

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 8.5.32 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 7.0.88 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.9 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 8.0.53 or later

### CVE-2018-1000180: Bouncy Castle has a flaw in the Low-level interface to RSA key pair generator
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2018-1000180](https://github.com/advisories/GHSA-xqj7-j8j5-f2xr): Bouncy Castle has a flaw in the Low-level interface to RSA key pair generator

Severity: HIGH

Affected dependencies:
  - org.bouncycastle:bcprov-jdk15on:1.56
    Vulnerable range: < 1.60

Recommended fix:
  - Upgrade org.bouncycastle:bcprov-jdk15on to 1.60 or later

### CVE-2026-22733: Spring Boot has an Authentication Bypass under Actuator CloudFoundry endpoints
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** notification-service/pom.xml:53, account-service/pom.xml:53, statistics-service/pom.xml:53

[CVE-2026-22733](https://github.com/advisories/GHSA-mgvc-8q2h-5pgc): Spring Boot has an Authentication Bypass under Actuator CloudFoundry endpoints

Severity: HIGH

Affected dependencies:
  - org.springframework.boot:spring-boot-starter-actuator:2.0.3.RELEASE (declared at notification-service/pom.xml:53)
    Vulnerable range: >= 4.0.0-M1, < 4.0.4
  - org.springframework.boot:spring-boot-starter-actuator:2.0.3.RELEASE (declared at notification-service/pom.xml:53)
    Vulnerable range: >= 3.5.0, < 3.5.12
  - org.springframework.boot:spring-boot-starter-actuator:2.0.3.RELEASE (declared at notification-service/pom.xml:53)
    Vulnerable range: >= 3.4.0, <= 3.4.13
  - org.springframework.boot:spring-boot-starter-actuator:2.0.3.RELEASE (declared at notification-service/pom.xml:53)
    Vulnerable range: >= 3.0.0, <= 3.3.13
  - org.springframework.boot:spring-boot-starter-actuator:2.0.3.RELEASE (declared at notification-service/pom.xml:53)
    Vulnerable range: <= 2.7.18

Recommended fix:
  - Upgrade org.springframework.boot:spring-boot-starter-actuator to 4.0.4 or later
  - Upgrade org.springframework.boot:spring-boot-starter-actuator to 3.5.12 or later

### CVE-2023-20883: Spring Boot Welcome Page Denial of Service
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2023-20883](https://github.com/advisories/GHSA-xf96-w227-r7c4): Spring Boot Welcome Page Denial of Service

Severity: HIGH

Affected dependencies:
  - org.springframework.boot:spring-boot-autoconfigure:2.0.3.RELEASE
    Vulnerable range: >= 3.0.0, < 3.0.7
  - org.springframework.boot:spring-boot-autoconfigure:2.0.3.RELEASE
    Vulnerable range: >= 2.7.0, < 2.7.12
  - org.springframework.boot:spring-boot-autoconfigure:2.0.3.RELEASE
    Vulnerable range: >= 2.6.0, < 2.6.15
  - org.springframework.boot:spring-boot-autoconfigure:2.0.3.RELEASE
    Vulnerable range: < 2.5.15

Recommended fix:
  - Upgrade org.springframework.boot:spring-boot-autoconfigure to 3.0.7 or later
  - Upgrade org.springframework.boot:spring-boot-autoconfigure to 2.7.12 or later
  - Upgrade org.springframework.boot:spring-boot-autoconfigure to 2.6.15 or later
  - Upgrade org.springframework.boot:spring-boot-autoconfigure to 2.5.15 or later

### CVE-2023-20873: Spring Boot Security Bypass with Wildcard Pattern Matching on Cloud Foundry
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2023-20873](https://github.com/advisories/GHSA-g5h3-w546-pj7f): Spring Boot Security Bypass with Wildcard Pattern Matching on Cloud Foundry

Severity: CRITICAL

Affected dependencies:
  - org.springframework.boot:spring-boot-actuator-autoconfigure:2.0.3.RELEASE
    Vulnerable range: >= 3.0.0, < 3.0.6
  - org.springframework.boot:spring-boot-actuator-autoconfigure:2.0.3.RELEASE
    Vulnerable range: >= 2.7.0, < 2.7.11
  - org.springframework.boot:spring-boot-actuator-autoconfigure:2.0.3.RELEASE
    Vulnerable range: >= 2.6.0, < 2.6.15
  - org.springframework.boot:spring-boot-actuator-autoconfigure:2.0.3.RELEASE
    Vulnerable range: < 2.5.15

Recommended fix:
  - Upgrade org.springframework.boot:spring-boot-actuator-autoconfigure to 3.0.6 or later
  - Upgrade org.springframework.boot:spring-boot-actuator-autoconfigure to 2.7.11 or later
  - Upgrade org.springframework.boot:spring-boot-actuator-autoconfigure to 2.6.15 or later
  - Upgrade org.springframework.boot:spring-boot-actuator-autoconfigure to 2.5.15 or later

### CVE-2026-40982: Spring Cloud Config vulnerable to Path Traversal
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** config/pom.xml:22

[CVE-2026-40982](https://github.com/advisories/GHSA-6g23-24mc-hx6x): Spring Cloud Config vulnerable to Path Traversal

Severity: CRITICAL

Affected dependencies:
  - org.springframework.cloud:spring-cloud-config-server:2.0.0.RELEASE (declared at config/pom.xml:22)
    Vulnerable range: >= 4.1.0, <= 4.1.9
  - org.springframework.cloud:spring-cloud-config-server:2.0.0.RELEASE (declared at config/pom.xml:22)
    Vulnerable range: >= 4.2.0, <= 4.2.6
  - org.springframework.cloud:spring-cloud-config-server:2.0.0.RELEASE (declared at config/pom.xml:22)
    Vulnerable range: >= 4.3.0, <= 4.3.2
  - org.springframework.cloud:spring-cloud-config-server:2.0.0.RELEASE (declared at config/pom.xml:22)
    Vulnerable range: >= 5.0.0, <= 5.0.2
  - org.springframework.cloud:spring-cloud-config-server:2.0.0.RELEASE (declared at config/pom.xml:22)
    Vulnerable range: <= 3.1.13

Recommended fix:
  - Upgrade org.springframework.cloud:spring-cloud-config-server to 4.3.3 or later
  - Upgrade org.springframework.cloud:spring-cloud-config-server to 5.0.3 or later

### CVE-2026-40973: Spring Boot accepts predictable temp directory without ownership verification
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml:13, notification-service/pom.xml:25, account-service/pom.xml:25, turbine-stream-service/pom.xml:39, registry/pom.xml:29, config/pom.xml:26, monitoring/pom.xml:29, statistics-service/pom.xml:21, auth-service/pom.xml:21, gateway/pom.xml:41

[CVE-2026-40973](https://github.com/advisories/GHSA-wwpq-f5c3-7hvx): Spring Boot accepts predictable temp directory without ownership verification

Severity: HIGH

Affected dependencies:
  - org.springframework.boot:spring-boot:2.0.3.RELEASE (declared at pom.xml:13)
    Vulnerable range: >= 4.0.0, < 4.0.6
  - org.springframework.boot:spring-boot:2.0.3.RELEASE (declared at pom.xml:13)
    Vulnerable range: >= 3.5.0, < 3.5.14
  - org.springframework.boot:spring-boot:2.0.3.RELEASE (declared at pom.xml:13)
    Vulnerable range: >= 3.4.0, <= 3.4.15
  - org.springframework.boot:spring-boot:2.0.3.RELEASE (declared at pom.xml:13)
    Vulnerable range: >= 3.3.0, <= 3.3.18
  - org.springframework.boot:spring-boot:2.0.3.RELEASE (declared at pom.xml:13)
    Vulnerable range: <= 2.7.32

Recommended fix:
  - Upgrade org.springframework.boot:spring-boot to 4.0.6 or later
  - Upgrade org.springframework.boot:spring-boot to 3.5.14 or later

### CVE-2026-22739: Spring Cloud Config Server: Path Traversal via Profile Parameter Allows Arbitrary File Access
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** config/pom.xml:22

[CVE-2026-22739](https://github.com/advisories/GHSA-3qwq-q9vm-5j42): Spring Cloud Config Server: Path Traversal via Profile Parameter Allows Arbitrary File Access

Severity: HIGH

Affected dependencies:
  - org.springframework.cloud:spring-cloud-config-server:2.0.0.RELEASE (declared at config/pom.xml:22)
    Vulnerable range: >= 4.3.0, < 4.3.2
  - org.springframework.cloud:spring-cloud-config-server:2.0.0.RELEASE (declared at config/pom.xml:22)
    Vulnerable range: >= 5.0.0-M1, < 5.0.2
  - org.springframework.cloud:spring-cloud-config-server:2.0.0.RELEASE (declared at config/pom.xml:22)
    Vulnerable range: >= 4.2.0, <= 4.2.4
  - org.springframework.cloud:spring-cloud-config-server:2.0.0.RELEASE (declared at config/pom.xml:22)
    Vulnerable range: >= 4.0.0, <= 4.1.7
  - org.springframework.cloud:spring-cloud-config-server:2.0.0.RELEASE (declared at config/pom.xml:22)
    Vulnerable range: <= 3.1.10

Recommended fix:
  - Upgrade org.springframework.cloud:spring-cloud-config-server to 4.3.2 or later
  - Upgrade org.springframework.cloud:spring-cloud-config-server to 5.0.2 or later

### CVE-2025-22235: Spring Boot EndpointRequest.to() creates wrong matcher if actuator endpoint is not exposed
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml:13, notification-service/pom.xml:25, account-service/pom.xml:25, turbine-stream-service/pom.xml:39, registry/pom.xml:29, config/pom.xml:26, monitoring/pom.xml:29, statistics-service/pom.xml:21, auth-service/pom.xml:21, gateway/pom.xml:41

[CVE-2025-22235](https://github.com/advisories/GHSA-rc42-6c7j-7h5r): Spring Boot EndpointRequest.to() creates wrong matcher if actuator endpoint is not exposed

Severity: HIGH

Affected dependencies:
  - org.springframework.boot:spring-boot:2.0.3.RELEASE (declared at pom.xml:13)
    Vulnerable range: <= 2.7.24.2
  - org.springframework.boot:spring-boot:2.0.3.RELEASE (declared at pom.xml:13)
    Vulnerable range: >= 3.1.0, <= 3.1.15.2
  - org.springframework.boot:spring-boot:2.0.3.RELEASE (declared at pom.xml:13)
    Vulnerable range: >= 3.2.0, <= 3.2.13.2
  - org.springframework.boot:spring-boot:2.0.3.RELEASE (declared at pom.xml:13)
    Vulnerable range: >= 3.3.0, <= 3.3.10
  - org.springframework.boot:spring-boot:2.0.3.RELEASE (declared at pom.xml:13)
    Vulnerable range: >= 3.4.0, <= 3.4.4

Recommended fix:
  - Upgrade org.springframework.boot:spring-boot to 3.3.11 or later
  - Upgrade org.springframework.boot:spring-boot to 3.4.5 or later

### CVE-2022-27772: Temporary Directory Hijacking to Local Privilege Escalation Vulnerability in org.springframework.boot:spring-boot
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml:13, notification-service/pom.xml:25, account-service/pom.xml:25, turbine-stream-service/pom.xml:39, registry/pom.xml:29, config/pom.xml:26, monitoring/pom.xml:29, statistics-service/pom.xml:21, auth-service/pom.xml:21, gateway/pom.xml:41

[CVE-2022-27772](https://github.com/advisories/GHSA-cm59-pr5q-cw85): Temporary Directory Hijacking to Local Privilege Escalation Vulnerability in org.springframework.boot:spring-boot

Severity: HIGH

Affected dependencies:
  - org.springframework.boot:spring-boot:2.0.3.RELEASE (declared at pom.xml:13)
    Vulnerable range: <= 2.2.10.RELEASE

Recommended fix:
  - Upgrade org.springframework.boot:spring-boot to 2.2.11.RELEASE or later

### CVE-2022-22965: Remote Code Execution in Spring Framework
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** notification-service/pom.xml:33, account-service/pom.xml:33, statistics-service/pom.xml:33, auth-service/pom.xml:37

[CVE-2022-22965](https://github.com/advisories/GHSA-36p3-wjmg-h94x): Remote Code Execution in Spring Framework

Severity: CRITICAL

Affected dependencies:
  - org.springframework:spring-beans:5.0.7.RELEASE
    Vulnerable range: >= 5.3.0, < 5.3.18
  - org.springframework:spring-webmvc:5.0.7.RELEASE
    Vulnerable range: >= 5.3.0, < 5.3.18
  - org.springframework.boot:spring-boot-starter-web:2.0.3.RELEASE (declared at notification-service/pom.xml:33)
    Vulnerable range: < 2.5.12
  - org.springframework.boot:spring-boot-starter-web:2.0.3.RELEASE (declared at notification-service/pom.xml:33)
    Vulnerable range: >= 2.6.0, < 2.6.6
  - org.springframework:spring-webflux:5.0.7.RELEASE
    Vulnerable range: >= 5.3.0, < 5.3.18
  - org.springframework.boot:spring-boot-starter-webflux:2.0.3.RELEASE
    Vulnerable range: < 2.5.12
  - org.springframework.boot:spring-boot-starter-webflux:2.0.3.RELEASE
    Vulnerable range: >= 2.6.0, < 2.6.6
  - org.springframework:spring-beans:5.0.7.RELEASE
    Vulnerable range: < 5.2.20.RELEASE
  - org.springframework:spring-webmvc:5.0.7.RELEASE
    Vulnerable range: < 5.2.20.RELEASE
  - org.springframework:spring-webflux:5.0.7.RELEASE
    Vulnerable range: < 5.2.20.RELEASE

Recommended fix:
  - Upgrade org.springframework:spring-beans to 5.3.18 or later
  - Upgrade org.springframework:spring-webmvc to 5.3.18 or later
  - Upgrade org.springframework.boot:spring-boot-starter-web to 2.5.12 or later
  - Upgrade org.springframework.boot:spring-boot-starter-web to 2.6.6 or later
  - Upgrade org.springframework:spring-webflux to 5.3.18 or later
  - Upgrade org.springframework.boot:spring-boot-starter-webflux to 2.5.12 or later
  - Upgrade org.springframework.boot:spring-boot-starter-webflux to 2.6.6 or later
  - Upgrade org.springframework:spring-beans to 5.2.20.RELEASE or later
  - Upgrade org.springframework:spring-webmvc to 5.2.20.RELEASE or later
  - Upgrade org.springframework:spring-webflux to 5.2.20.RELEASE or later

### CVE-2021-22053: Code injection in spring-cloud-netflix-hystrix-dashboard
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2021-22053](https://github.com/advisories/GHSA-gx3f-hq7p-8fxv): Code injection in spring-cloud-netflix-hystrix-dashboard

Severity: HIGH

Affected dependencies:
  - org.springframework.cloud:spring-cloud-netflix-hystrix-dashboard:2.0.0.RELEASE
    Vulnerable range: <= 2.2.9.RELEASE

Recommended fix:
  - Upgrade org.springframework.cloud:spring-cloud-netflix-hystrix-dashboard to 2.2.10.RELEASE or later

### CVE-2026-22732: Spring Security HTTP Headers Are not Written Under Some Conditions
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2026-22732](https://github.com/advisories/GHSA-mf92-479x-3373): Spring Security HTTP Headers Are not Written Under Some Conditions

Severity: CRITICAL

Affected dependencies:
  - org.springframework.security:spring-security-web:5.0.6.RELEASE
    Vulnerable range: <= 5.7.14
  - org.springframework.security:spring-security-web:5.0.6.RELEASE
    Vulnerable range: >= 5.8.0, <= 5.8.16
  - org.springframework.security:spring-security-web:5.0.6.RELEASE
    Vulnerable range: >= 6.0.0, <= 6.3.10
  - org.springframework.security:spring-security-web:5.0.6.RELEASE
    Vulnerable range: >= 6.4.0, <= 6.4.13
  - org.springframework.security:spring-security-web:5.0.6.RELEASE
    Vulnerable range: >= 6.5.0, < 6.5.9
  - org.springframework.security:spring-security-web:5.0.6.RELEASE
    Vulnerable range: >= 7.0.0, < 7.0.4

Recommended fix:
  - Upgrade org.springframework.security:spring-security-web to 6.5.9 or later
  - Upgrade org.springframework.security:spring-security-web to 7.0.4 or later

### CVE-2025-22228: Spring Security Does Not Enforce Password Length
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2025-22228](https://github.com/advisories/GHSA-mg83-c7gq-rv5c): Spring Security Does Not Enforce Password Length

Severity: HIGH

Affected dependencies:
  - org.springframework.security:spring-security-crypto:5.0.6.RELEASE
    Vulnerable range: >= 6.3.0, < 6.3.8
  - org.springframework.security:spring-security-crypto:5.0.6.RELEASE
    Vulnerable range: >= 6.4.0, < 6.4.4
  - org.springframework.security:spring-security-crypto:5.0.6.RELEASE
    Vulnerable range: >= 6.2.0, <= 6.2.9
  - org.springframework.security:spring-security-crypto:5.0.6.RELEASE
    Vulnerable range: >= 6.1.0, <= 6.1.13
  - org.springframework.security:spring-security-crypto:5.0.6.RELEASE
    Vulnerable range: >= 6.0.0, <= 6.0.15
  - org.springframework.security:spring-security-crypto:5.0.6.RELEASE
    Vulnerable range: >= 5.8.0, <= 5.8.17
  - org.springframework.security:spring-security-crypto:5.0.6.RELEASE
    Vulnerable range: <= 5.7.15

Recommended fix:
  - Upgrade org.springframework.security:spring-security-crypto to 6.3.8 or later
  - Upgrade org.springframework.security:spring-security-crypto to 6.4.4 or later
  - Upgrade org.springframework.security:spring-security-crypto to 6.2.10 or later
  - Upgrade org.springframework.security:spring-security-crypto to 6.1.14 or later
  - Upgrade org.springframework.security:spring-security-crypto to 6.0.16 or later
  - Upgrade org.springframework.security:spring-security-crypto to 5.8.18 or later
  - Upgrade org.springframework.security:spring-security-crypto to 5.7.16 or later

### CVE-2024-38821: Spring Security vulnerable to Authorization Bypass of Static Resources in WebFlux Applications
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2024-38821](https://github.com/advisories/GHSA-c4q5-6c82-3qpw): Spring Security vulnerable to Authorization Bypass of Static Resources in WebFlux Applications

Severity: CRITICAL

Affected dependencies:
  - org.springframework.security:spring-security-web:5.0.6.RELEASE
    Vulnerable range: < 5.7.13
  - org.springframework.security:spring-security-web:5.0.6.RELEASE
    Vulnerable range: >= 5.8.0, < 5.8.15
  - org.springframework.security:spring-security-web:5.0.6.RELEASE
    Vulnerable range: >= 6.2.0, < 6.2.7
  - org.springframework.security:spring-security-web:5.0.6.RELEASE
    Vulnerable range: >= 6.0.0, < 6.0.13
  - org.springframework.security:spring-security-web:5.0.6.RELEASE
    Vulnerable range: >= 6.1.0, < 6.1.11
  - org.springframework.security:spring-security-web:5.0.6.RELEASE
    Vulnerable range: >= 6.3.0, < 6.3.4

Recommended fix:
  - Upgrade org.springframework.security:spring-security-web to 5.7.13 or later
  - Upgrade org.springframework.security:spring-security-web to 5.8.15 or later
  - Upgrade org.springframework.security:spring-security-web to 6.2.7 or later
  - Upgrade org.springframework.security:spring-security-web to 6.0.13 or later
  - Upgrade org.springframework.security:spring-security-web to 6.1.11 or later
  - Upgrade org.springframework.security:spring-security-web to 6.3.4 or later

### CVE-2024-22257: Erroneous authentication pass in Spring Security
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2024-22257](https://github.com/advisories/GHSA-f3jh-qvm4-mg39): Erroneous authentication pass in Spring Security

Severity: HIGH

Affected dependencies:
  - org.springframework.security:spring-security-core:5.0.6.RELEASE
    Vulnerable range: < 5.7.12
  - org.springframework.security:spring-security-core:5.0.6.RELEASE
    Vulnerable range: >= 5.8.0, < 5.8.11
  - org.springframework.security:spring-security-core:5.0.6.RELEASE
    Vulnerable range: >= 6.0.0, < 6.1.8
  - org.springframework.security:spring-security-core:5.0.6.RELEASE
    Vulnerable range: >= 6.2.0, < 6.2.3

Recommended fix:
  - Upgrade org.springframework.security:spring-security-core to 5.7.12 or later
  - Upgrade org.springframework.security:spring-security-core to 5.8.11 or later
  - Upgrade org.springframework.security:spring-security-core to 6.1.8 or later
  - Upgrade org.springframework.security:spring-security-core to 6.2.3 or later

### CVE-2022-22980: SpEL Injection in Spring Data MongoDB
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2022-22980](https://github.com/advisories/GHSA-w24x-87mr-4r23): SpEL Injection in Spring Data MongoDB

Severity: CRITICAL

Affected dependencies:
  - org.springframework.data:spring-data-mongodb:2.0.8.RELEASE
    Vulnerable range: = 3.4.0
  - org.springframework.data:spring-data-mongodb:2.0.8.RELEASE
    Vulnerable range: < 3.3.5

Recommended fix:
  - Upgrade org.springframework.data:spring-data-mongodb to 3.4.1 or later
  - Upgrade org.springframework.data:spring-data-mongodb to 3.3.5 or later

### CVE-2022-22978: Authorization bypass in Spring Security
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2022-22978](https://github.com/advisories/GHSA-hh32-7344-cg2f): Authorization bypass in Spring Security

Severity: CRITICAL

Affected dependencies:
  - org.springframework.security:spring-security-core:5.0.6.RELEASE
    Vulnerable range: >= 5.6.0, < 5.6.4
  - org.springframework.security:spring-security-core:5.0.6.RELEASE
    Vulnerable range: >= 5.5.0, < 5.5.7
  - org.springframework.security:spring-security-core:5.0.6.RELEASE
    Vulnerable range: < 5.4.11
  - org.springframework.security:spring-security-web:5.0.6.RELEASE
    Vulnerable range: >= 5.5.0, < 5.5.7
  - org.springframework.security:spring-security-web:5.0.6.RELEASE
    Vulnerable range: >= 5.6.0, < 5.6.4
  - org.springframework.security:spring-security-web:5.0.6.RELEASE
    Vulnerable range: < 5.4.11

Recommended fix:
  - Upgrade org.springframework.security:spring-security-core to 5.6.4 or later
  - Upgrade org.springframework.security:spring-security-core to 5.5.7 or later
  - Upgrade org.springframework.security:spring-security-core to 5.4.11 or later
  - Upgrade org.springframework.security:spring-security-web to 5.5.7 or later
  - Upgrade org.springframework.security:spring-security-web to 5.6.4 or later
  - Upgrade org.springframework.security:spring-security-web to 5.4.11 or later

### CVE-2021-22112: Privilege escalation in spring security
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2021-22112](https://github.com/advisories/GHSA-gq28-h5vg-8prx): Privilege escalation in spring security

Severity: HIGH

Affected dependencies:
  - org.springframework.security:spring-security-web:5.0.6.RELEASE
    Vulnerable range: < 5.2.9
  - org.springframework.security:spring-security-web:5.0.6.RELEASE
    Vulnerable range: >= 5.4.0, < 5.4.4
  - org.springframework.security:spring-security-web:5.0.6.RELEASE
    Vulnerable range: >= 5.3.0, < 5.3.8

Recommended fix:
  - Upgrade org.springframework.security:spring-security-web to 5.2.9 or later
  - Upgrade org.springframework.security:spring-security-web to 5.4.4 or later
  - Upgrade org.springframework.security:spring-security-web to 5.3.8 or later

### CVE-2018-15758: Authorization bypass in org.springframework.security.oauth:spring-security-oauth2
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2018-15758](https://github.com/advisories/GHSA-h8w4-qv99-f7vj): Authorization bypass in org.springframework.security.oauth:spring-security-oauth2

Severity: HIGH

Affected dependencies:
  - org.springframework.security.oauth:spring-security-oauth2:2.2.1.RELEASE
    Vulnerable range: >= 2.0.0, < 2.0.16
  - org.springframework.security.oauth:spring-security-oauth2:2.2.1.RELEASE
    Vulnerable range: >= 2.1.0, < 2.1.3
  - org.springframework.security.oauth:spring-security-oauth2:2.2.1.RELEASE
    Vulnerable range: >= 2.2.0, < 2.2.3.RELEASE
  - org.springframework.security.oauth:spring-security-oauth2:2.2.1.RELEASE
    Vulnerable range: >= 2.3.0, < 2.3.4.RELEASE

Recommended fix:
  - Upgrade org.springframework.security.oauth:spring-security-oauth2 to 2.0.16 or later
  - Upgrade org.springframework.security.oauth:spring-security-oauth2 to 2.1.3 or later
  - Upgrade org.springframework.security.oauth:spring-security-oauth2 to 2.2.3.RELEASE or later
  - Upgrade org.springframework.security.oauth:spring-security-oauth2 to 2.3.4.RELEASE or later

### CVE-2018-1260: Spring Security OAuth vulnerable to remote code execution (RCE)
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2018-1260](https://github.com/advisories/GHSA-rrpm-pj7p-7j9q): Spring Security OAuth vulnerable to remote code execution (RCE)

Severity: CRITICAL

Affected dependencies:
  - org.springframework.security.oauth:spring-security-oauth2:2.2.1.RELEASE
    Vulnerable range: >= 2.3.0, < 2.3.3
  - org.springframework.security.oauth:spring-security-oauth2:2.2.1.RELEASE
    Vulnerable range: >= 2.2.0, < 2.2.2
  - org.springframework.security.oauth:spring-security-oauth2:2.2.1.RELEASE
    Vulnerable range: >= 2.1.0, < 2.1.2
  - org.springframework.security.oauth:spring-security-oauth2:2.2.1.RELEASE
    Vulnerable range: >= 2.0.0, < 2.0.15
  - org.springframework.security.oauth:spring-security-oauth2:2.2.1.RELEASE
    Vulnerable range: >= 1.0.0, <= 1.0.5

Recommended fix:
  - Upgrade org.springframework.security.oauth:spring-security-oauth2 to 2.3.3 or later
  - Upgrade org.springframework.security.oauth:spring-security-oauth2 to 2.2.2 or later
  - Upgrade org.springframework.security.oauth:spring-security-oauth2 to 2.1.2 or later
  - Upgrade org.springframework.security.oauth:spring-security-oauth2 to 2.0.15 or later

### CVE-2024-38819: Spring Framework Path Traversal vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2024-38819](https://github.com/advisories/GHSA-g5vr-rgqm-vf78): Spring Framework Path Traversal vulnerability

Severity: HIGH

Affected dependencies:
  - org.springframework:spring-webflux:5.0.7.RELEASE
    Vulnerable range: >= 6.1.0, < 6.1.14
  - org.springframework:spring-webmvc:5.0.7.RELEASE
    Vulnerable range: >= 6.1.0, < 6.1.14
  - org.springframework:spring-webflux:5.0.7.RELEASE
    Vulnerable range: <= 5.3.39
  - org.springframework:spring-webmvc:5.0.7.RELEASE
    Vulnerable range: <= 5.3.39
  - org.springframework:spring-webflux:5.0.7.RELEASE
    Vulnerable range: >= 6.0.0, <= 6.0.23
  - org.springframework:spring-webmvc:5.0.7.RELEASE
    Vulnerable range: >= 6.0.0, <= 6.0.23

Recommended fix:
  - Upgrade org.springframework:spring-webflux to 6.1.14 or later
  - Upgrade org.springframework:spring-webmvc to 6.1.14 or later

### CVE-2024-22262: Spring Framework URL Parsing with Host Validation
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2024-22262](https://github.com/advisories/GHSA-2wrp-6fg6-hmc5): Spring Framework URL Parsing with Host Validation

Severity: HIGH

Affected dependencies:
  - org.springframework:spring-web:5.0.7.RELEASE
    Vulnerable range: < 5.3.34
  - org.springframework:spring-web:5.0.7.RELEASE
    Vulnerable range: >= 6.0.0, < 6.0.19
  - org.springframework:spring-web:5.0.7.RELEASE
    Vulnerable range: >= 6.1.0, < 6.1.6

Recommended fix:
  - Upgrade org.springframework:spring-web to 5.3.34 or later
  - Upgrade org.springframework:spring-web to 6.0.19 or later
  - Upgrade org.springframework:spring-web to 6.1.6 or later

### CVE-2024-22259: Spring Framework URL Parsing with Host Validation Vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2024-22259](https://github.com/advisories/GHSA-hgjh-9rj2-g67j): Spring Framework URL Parsing with Host Validation Vulnerability

Severity: HIGH

Affected dependencies:
  - org.springframework:spring-web:5.0.7.RELEASE
    Vulnerable range: >= 6.1.0, < 6.1.5
  - org.springframework:spring-web:5.0.7.RELEASE
    Vulnerable range: >= 6.0.0, < 6.0.18
  - org.springframework:spring-web:5.0.7.RELEASE
    Vulnerable range: < 5.3.33

Recommended fix:
  - Upgrade org.springframework:spring-web to 6.1.5 or later
  - Upgrade org.springframework:spring-web to 6.0.18 or later
  - Upgrade org.springframework:spring-web to 5.3.33 or later

### CVE-2024-22243: Spring Web vulnerable to Open Redirect or Server Side Request Forgery
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2024-22243](https://github.com/advisories/GHSA-ccgv-vj62-xf9h): Spring Web vulnerable to Open Redirect or Server Side Request Forgery

Severity: HIGH

Affected dependencies:
  - org.springframework:spring-web:5.0.7.RELEASE
    Vulnerable range: >= 6.1.0, < 6.1.4
  - org.springframework:spring-web:5.0.7.RELEASE
    Vulnerable range: >= 6.0.0, < 6.0.17
  - org.springframework:spring-web:5.0.7.RELEASE
    Vulnerable range: >= 5.3.0, < 5.3.32
  - org.springframework:spring-web:5.0.7.RELEASE
    Vulnerable range: <= 5.2.25.RELEASE

Recommended fix:
  - Upgrade org.springframework:spring-web to 6.1.4 or later
  - Upgrade org.springframework:spring-web to 6.0.17 or later
  - Upgrade org.springframework:spring-web to 5.3.32 or later

### CVE-2023-20863: Spring Framework vulnerable to denial of service
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2023-20863](https://github.com/advisories/GHSA-wxqc-pxw9-g2p8): Spring Framework vulnerable to denial of service

Severity: HIGH

Affected dependencies:
  - org.springframework:spring-expression:5.0.7.RELEASE
    Vulnerable range: >= 6.0.0, < 6.0.8
  - org.springframework:spring-expression:5.0.7.RELEASE
    Vulnerable range: >= 5.3.0, < 5.3.27
  - org.springframework:spring-expression:5.0.7.RELEASE
    Vulnerable range: < 5.2.24.RELEASE

Recommended fix:
  - Upgrade org.springframework:spring-expression to 6.0.8 or later
  - Upgrade org.springframework:spring-expression to 5.3.27 or later
  - Upgrade org.springframework:spring-expression to 5.2.24.RELEASE or later

### CVE-2022-1471: SnakeYaml Constructor Deserialization Remote Code Execution
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2022-1471](https://github.com/advisories/GHSA-mjmj-j48q-9wg2): SnakeYaml Constructor Deserialization Remote Code Execution

Severity: HIGH

Affected dependencies:
  - org.yaml:snakeyaml:1.19
    Vulnerable range: <= 1.33

Recommended fix:
  - Upgrade org.yaml:snakeyaml to 2.0 or later

### CVE-2022-25857: Uncontrolled Resource Consumption in snakeyaml
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2022-25857](https://github.com/advisories/GHSA-3mc7-4q67-w48m): Uncontrolled Resource Consumption in snakeyaml

Severity: HIGH

Affected dependencies:
  - org.yaml:snakeyaml:1.19
    Vulnerable range: < 1.31

Recommended fix:
  - Upgrade org.yaml:snakeyaml to 1.31 or later

### CVE-2016-1000027: Pivotal Spring Framework contains unsafe Java deserialization methods
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2016-1000027](https://github.com/advisories/GHSA-4wrc-f8pq-fpqp): Pivotal Spring Framework contains unsafe Java deserialization methods

Severity: CRITICAL

Affected dependencies:
  - org.springframework:spring-web:5.0.7.RELEASE
    Vulnerable range: < 6.0.0

Recommended fix:
  - Upgrade org.springframework:spring-web to 6.0.0 or later

### CVE-2022-22970: Denial of service in Spring Framework
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2022-22970](https://github.com/advisories/GHSA-hh26-6xwr-ggv7): Denial of service in Spring Framework

Severity: HIGH

Affected dependencies:
  - org.springframework:spring-beans:5.0.7.RELEASE
    Vulnerable range: <= 5.2.21.RELEASE
  - org.springframework:spring-beans:5.0.7.RELEASE
    Vulnerable range: >= 5.3.0, < 5.3.20

Recommended fix:
  - Upgrade org.springframework:spring-beans to 5.2.22.RELEASE or later
  - Upgrade org.springframework:spring-beans to 5.3.20 or later

### CVE-2022-22968: Improper handling of case sensitivity in Spring Framework
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2022-22968](https://github.com/advisories/GHSA-g5mm-vmx4-3rg7): Improper handling of case sensitivity in Spring Framework

Severity: HIGH

Affected dependencies:
  - org.springframework:spring-context:5.0.7.RELEASE
    Vulnerable range: >= 5.3.0, < 5.3.19
  - org.springframework:spring-context:5.0.7.RELEASE
    Vulnerable range: < 5.2.21.RELEASE

Recommended fix:
  - Upgrade org.springframework:spring-context to 5.3.19 or later
  - Upgrade org.springframework:spring-context to 5.2.21.RELEASE or later

### CVE-2017-18640: SnakeYAML Entity Expansion during load operation
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2017-18640](https://github.com/advisories/GHSA-rvwf-54qp-4r6v): SnakeYAML Entity Expansion during load operation

Severity: HIGH

Affected dependencies:
  - org.yaml:snakeyaml:1.19
    Vulnerable range: < 1.26

Recommended fix:
  - Upgrade org.yaml:snakeyaml to 1.26 or later

### CVE-2018-15756: Denial of Service in Spring Framework
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2018-15756](https://github.com/advisories/GHSA-ffvq-7w96-97p7): Denial of Service in Spring Framework

Severity: HIGH

Affected dependencies:
  - org.springframework:spring-core:5.0.7.RELEASE
    Vulnerable range: >= 5.1.0.RELEASE, < 5.1.1.RELEASE
  - org.springframework:spring-core:5.0.7.RELEASE
    Vulnerable range: >= 5.0.0.RELEASE, < 5.0.10.RELEASE
  - org.springframework:spring-core:5.0.7.RELEASE
    Vulnerable range: >= 4.2.0.RELEASE, < 4.3.20.RELEASE

Recommended fix:
  - Upgrade org.springframework:spring-core to 5.1.1.RELEASE or later
  - Upgrade org.springframework:spring-core to 5.0.10.RELEASE or later
  - Upgrade org.springframework:spring-core to 4.3.20.RELEASE or later

### CVE-2020-5398: RFD attack via Content-Disposition header sourced from request input by Spring MVC or Spring WebFlux Application
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-5398](https://github.com/advisories/GHSA-8wx2-9q48-vm9r): RFD attack via Content-Disposition header sourced from request input by Spring MVC or Spring WebFlux Application

Severity: HIGH

Affected dependencies:
  - org.springframework:spring-webmvc:5.0.7.RELEASE
    Vulnerable range: >= 5.2.0.RELEASE, < 5.2.3.RELEASE
  - org.springframework:spring-webmvc:5.0.7.RELEASE
    Vulnerable range: >= 5.1.0.RELEASE, < 5.1.13.RELEASE
  - org.springframework:spring-webmvc:5.0.7.RELEASE
    Vulnerable range: >= 5.0.0.RELEASE, < 5.0.16.RELEASE
  - org.springframework:spring-webflux:5.0.7.RELEASE
    Vulnerable range: >= 5.2.0.RELEASE, < 5.2.3.RELEASE
  - org.springframework:spring-webflux:5.0.7.RELEASE
    Vulnerable range: >= 5.1.0.RELEASE, < 5.1.13.RELEASE
  - org.springframework:spring-webflux:5.0.7.RELEASE
    Vulnerable range: >= 5.0.0.RELEASE, < 5.0.16.RELEASE

Recommended fix:
  - Upgrade org.springframework:spring-webmvc to 5.2.3.RELEASE or later
  - Upgrade org.springframework:spring-webmvc to 5.1.13.RELEASE or later
  - Upgrade org.springframework:spring-webmvc to 5.0.16.RELEASE or later
  - Upgrade org.springframework:spring-webflux to 5.2.3.RELEASE or later
  - Upgrade org.springframework:spring-webflux to 5.1.13.RELEASE or later
  - Upgrade org.springframework:spring-webflux to 5.0.16.RELEASE or later

## CWE Findings (Code-Level Vulnerabilities)

### CWE-477: Use of Obsolete Function
- **Category:** Code Quality
- **Severity:** optional
- **Story Points:** 1
- **Files:** notification-service/src/main/java/com/piggymetrics/notification/service/RecipientServiceImpl.java, notification-service/src/main/java/com/piggymetrics/notification/repository/RecipientRepository.java, account-service/src/main/java/com/piggymetrics/account/service/AccountServiceImpl.java

Multiple uses of the deprecated java.util.Date API and deprecated Date methods: (1) RecipientServiceImpl.java lines 39 and 70 call 'new Date()' which is deprecated in favour of java.time.Instant/LocalDateTime; (2) RecipientRepository.java lines 16 and 20 embed a MongoDB $where JavaScript expression calling deprecated 'Date.getDate()'; (3) AccountServiceImpl.java lines 62 and 85 call 'new Date()'. These deprecated APIs should be replaced with the modern java.time API.

### CWE-567: Unsynchronized Access to Shared Data in a Multithreaded Context
- **Category:** Concurrency & Synchronization
- **Severity:** potential
- **Story Points:** 5
- **Files:** statistics-service/src/main/java/com/piggymetrics/statistics/service/ExchangeRatesServiceImpl.java

ExchangeRatesServiceImpl is a Spring @Service singleton with a non-volatile, non-synchronized instance field 'container' (line 23). The getCurrentRates() method performs an unsynchronized check-then-act sequence (lines 34-37): it reads container, checks if null or stale, then updates it — all without synchronization. In a multithreaded environment with concurrent HTTP requests, multiple threads can simultaneously observe container as null, trigger redundant API calls, or read a partially updated container reference, leading to race conditions and unpredictable data.

### CWE-820: Missing Synchronization
- **Category:** Concurrency & Synchronization
- **Severity:** potential
- **Story Points:** 8
- **Files:** statistics-service/src/main/java/com/piggymetrics/statistics/service/ExchangeRatesServiceImpl.java

The 'container' field in ExchangeRatesServiceImpl (line 23) is a shared mutable instance variable of a singleton Spring service, accessed and mutated in getCurrentRates() (lines 34-37) without any synchronization mechanism (no synchronized block, volatile keyword, or atomic reference). This constitutes missing synchronization on a shared resource that is read and written by multiple concurrent threads handling incoming HTTP requests.

### CWE-259: Use of Hard-coded Password
- **Category:** Credentials & Secrets
- **Severity:** optional
- **Story Points:** 5
- **Files:** config/src/main/resources/shared/notification-service.yml

The notification-service configuration file contains a hard-coded SMTP mail password: 'spring.mail.password: dev-password'. This plain-text password for the outbound mail connection is committed directly in the source repository and used without substitution at runtime.

### CWE-778: Insufficient Logging
- **Category:** Credentials & Secrets
- **Severity:** potential
- **Story Points:** 3
- **Files:** auth-service/src/main/java/com/piggymetrics/auth/service/UserServiceImpl.java

The UserServiceImpl class (auth-service) only logs successful user creation events (line 35: 'new user has been created'). Security-critical events such as authentication failures, access-denied attempts, and duplicate registration attempts are not logged. The IllegalArgumentException thrown on duplicate usernames (line 28) is not caught and logged as a security event, leaving no audit trail for potential enumeration or brute-force attacks.

### CWE-798: Use of Hard-coded Credentials
- **Category:** Credentials & Secrets
- **Severity:** optional
- **Story Points:** 5
- **Files:** config/src/main/resources/shared/notification-service.yml

The notification-service shared configuration contains hard-coded SMTP credentials: 'spring.mail.username: dev-user' and 'spring.mail.password: dev-password'. Both the username and password for outbound email communication are committed as plain text in the source repository, exposing them to anyone with repository access.
